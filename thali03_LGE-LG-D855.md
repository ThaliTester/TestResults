#### Test 5546736337bcedb_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1459): called onTimeUpdated()
I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,D/AndroidRuntime( 7291): 
D/AndroidRuntime( 7291): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7291): CheckJNI is OFF
D/AndroidRuntime( 7291): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1953): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{7f18301 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{7f18301 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  335): DFP En is all cleared set to be enabled
I/ActivityManager( 1040): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7306 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7291): Shutting down VM
V/ActivityManager( 1040): Display changed displayId=0
D/DSDPConnection( 1859): Display #0 changed.
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{1a70400c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{a971d55 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7306): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7306): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7306): Loading: webviewchromium
I/LibraryLoader( 7306): Time to load native libraries: 3 ms (timestamps 6401-6404)
I/LibraryLoader( 7306): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7306): Binding Chromium to main looper Looper (main, tid 1) {2eeb468e}
,I/LibraryLoader( 7306): Expected native library version number "",actual native library version number ""
I/chromium( 7306): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7306): Initializing chromium process, renderers=0
W/art     ( 7306): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  320): registerClient() client 0xb54f4cc0, uid 10311
,W/chromium( 7306): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7306): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 7306): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3768df83:true
I/Adreno-EGL( 7306): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7306): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7306): Build Date: 12/12/14 금
I/Adreno-EGL( 7306): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7306): Remote Branch: 
I/Adreno-EGL( 7306): Local Patches: 
I/Adreno-EGL( 7306): Reconstruct Branch: 
,W/chromium( 7306): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7306): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7306): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7306): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7306): CordovaWebView is running on device made by: LGE
,W/art     ( 7306): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7306): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7306): Render dirty regions requested: true
I/OpenGLRenderer( 7306): Initialized EGL, version 1.4
D/OpenGLRenderer( 7306): Enabling debug mode 0
D/Atlas   ( 7306): Validating map...
,D/SplitWindow( 1040): check instance of lgWin Window{64dd865 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@e83ccf0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 7306): LgDataFeature() Constructor: none
D/LgDataFeature( 7306): LgDataFeature() Constructor Done, null
,I/Timeline( 7306): Timeline: Activity_idle id: android.os.BinderProxy@32fc6f3e time:286775
,I/ActivityManager( 1040): Displayed com.test.thalitest/.MainActivity: +573ms (total +668ms)
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{b8545a6 u0 com.test.thalitest/.MainActivity t4} time:286802
,I/chromium( 7306): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7306): 
,D/JsMessageQueue( 7306): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7306): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7306): 
,D/jxcore_app_log( 7306): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434872448
D/JX-Cordova( 7306): jxcore cordova android initializing
E/GBMv2   (  335): DFP En is all cleared set to be enabled
E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7306): Initializing JXcore engine
W/jxcore-log( 7306): JXcore engine is ready
W/jxcore-log( 7306): Starting JXcore engine
W/.test.thalitest( 7306): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8340]" dev="sockfs" ino=8340 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7306): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7306): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9938]" dev="sockfs" ino=9938 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7306): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7306): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[35177]" dev="sockfs" ino=35177 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7306): Background sticky concurrent mark sweep GC freed 124652(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.419ms total 245.116ms
W/jxcore-log( 7306): Platform android
W/jxcore-log( 7306): 
W/jxcore-log( 7306): Process ARCH arm
W/jxcore-log( 7306): 
,I/jxcore-log( 7306): JXcore Cordova bridge is ready!
I/jxcore-log( 7306): 
W/jxcore-log( 7306): JXcore engine is started
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=759829015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{184895e1 type 2 when 291324 android} when 291324
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=759829015 [*alarm*], flags=0x0
,I/BooksSync( 7184): Starting books sync
,D/BooksSync( 7184): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7184): null auth token
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
W/ApiaryClient( 7184): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7105825072275219131&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
,I/jxcore-log( 7306): Toggling radios to true
I/jxcore-log( 7306): 
,D/BluetoothAdapter( 7306): enable(): BT is already enabled..!
D/WifiService( 1040): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1040): setWifiEnabled: true pid=7306, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1040): setWifiEnabled: true pid=7306, uid=10311
,E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1040): disconnect pid=7306, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1040): reconnect pid=7306, uid=10311, packageName=com.test.thalitest
E/WifiNative: ( 1040): [291,664,468 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: DISCONNECT
I/jxcore-log( 7306): Radios toggled
I/jxcore-log( 7306): 
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7306): Received device characteristics:
I/jxcore-log( 7306): Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7306): Bluetooth name: G3-1
I/jxcore-log( 7306): Device name: LGE-LG-D855
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): Perf Test app loaded loaded
I/jxcore-log( 7306): 
I/wpa_supplicant( 2675): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1040): DISCONNECT: returned true
,D/Tethering( 1040): InitialState.processMessage what=4
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
I/jxcore-log( 7306): check test folder
I/jxcore-log( 7306): 
I/jxcore-log( 7306): found test : ./testFindPeers.js
I/jxcore-log( 7306): 
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1040): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7306): found test : ./testSendData.js
I/jxcore-log( 7306): 
,I/ActivityManager( 1040): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7421 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2124): Read error: ssl=0xaf4d3400: I/O error during system call, Connection timed out
,V/NativeCrypto( 2124): SSL shutdown failed: ssl=0xaf4d3400: I/O error during system call, Broken pipe
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): ignoring duplicate network state non-change
,D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 0
,D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1040):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1040): [291,778,625 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: RECONNECT
I/wpa_supplicant( 2675): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1040): hidePasspointNotification off =false
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1040): RECONNECT: returned true
E/WifiStateMachine( 1040):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=291796
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=291796
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
D/DSQN    ( 1040): stop dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=291820  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=291821  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1040): hidePasspointNotification off =false
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524292
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D,/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=291825  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1040): Removing idletimer
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=291829  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NET,WORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateDISCONNECTED
,D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7306): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7306): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DhcpStateMachine( 1040): StoppedState
,D/DhcpStateMachine( 1040): StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7421): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7421): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7421): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7421): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7421): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7421): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7447 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/PCSuite ( 7447): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7447): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7447): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7421): LgDataFeature() Constructor: none
,D/LgDataFeature( 7421): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
,I/ActivityManager( 1040): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7471 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1040): Killing 6733:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10004/pid_6733/cgroup.procs: No such file or directory
,W/ResourcesManager( 7471): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/QRemote ( 7471): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7184): errCount = 2: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.UnknownHostException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7105825072275219131&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
,D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/BooksSync( 7184): Soft error: 
E/BooksSync( 7184): Sync error
I/BooksSync( 7184): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 291324, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1040): Killing 6867:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,D/QRemote ( 7471): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7471): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 7471): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7471): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7471): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7471): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7471): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
W/libprocessgroup( 1040): failed to open /acct/uid_10008/pid_6867/cgroup.procs: No such file or directory
,D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7471): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 7471): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7447): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7447): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7447): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7471): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7471): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7447): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7447): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7447): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7471): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7447): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7447): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7447): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7471): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7471): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7471): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7471): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7471): LgDataFeature() Constructor: none
D/LgDataFeature( 7471): LgDataFeature() Constructor Done, null
,V/SoundPool( 7471): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7471): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7471): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7471): doLoad: loading sample sampleID=1
V/SoundPool( 7471): Start decode
V/MediaPlayer[Native]( 7471): decode(31, 10857164, 17813)
I/QRemote ( 7471): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
V/AwesomePlayer(  320): AwesomePlayer create()
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
,V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb1432200, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 7025): QS Service created
D/QRemote ( 7471): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7471): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7471): Create singleton instance
,I/UEI.SmartControl( 7025): Service initServices...
D/UEI.SmartControl( 7025): QS start get config
,V/LGParserOSAL(  320): supported mime: application/ogg
V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
,V/MediaPlayerService(  320): wait for prepare
V/AwesomePlayer(  320): onPrepareAsyncEvent() 
V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
,V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3470 on output port
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb1432200, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb1432200, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.,vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815984
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): notify(0xb1432200, 6, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab700000, 0xb17ba000, 4096)
V/MediaPlayerService(  320): wait for playback complete
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab701000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab702000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab703000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab704000, 0xb17ba000, 4096)
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab705000, 0xb17ba000, 4096)
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab706000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab707000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab708000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab709000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab70a000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab70b000, 0xb17ba000, 4096)
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8535
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab70c000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab70d000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab70e000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab70f000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab710000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab711000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab712000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab713000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab714000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab715000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab716000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab717000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab718000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab719000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab71a000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab71b000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab71c000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab71d000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab71e000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab71f000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab720000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab721000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab722000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab723000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab724000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab725000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab726000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab727000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab728000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab729000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab72a000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab72b000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab72c000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab72d000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab72e000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab72f000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab730000, 0xb17ba000, 4096)
V/AudioCache(  320): write(0xb17ba000, 4096)
V/AudioCache(  320): memcpy(0xab731000, 0xb17ba000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb17ba000, 280)
V/AudioCache(  320): memcpy(0xab732000, 0xb17ba000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  320): notify(0xb1432200, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): wait - success
V/AudioCache(  320): notify(0xb1432200, 7, 0, 0)
,V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): Pause Playback at 1068125
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb1432200, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/SoundPool( 7471): close(31)
V/SoundPool( 7471): pointer = 0x9ffbd000, size = 205080, sampleRate = 48000, numChannels = 2
,I/UEI.SmartControl( 7025): Supports setup maps: true
,D/UEI.SmartControl( 7025): QS start statue = true Error code = 0
I/UEI.SmartControl( 7025): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7025): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7025): ### init IR Blaster...
D/serial_port( 7025): Configuring serial port
E/UEI.SmartControl( 7025): UEIBLaster setting for 616
I/UEI.SmartControl( 7025): Setting serial record hearder size = 2
I/UEI.SmartControl( 7025): configuring settings for MAXQ616
I/UEI.SmartControl( 7025): Get version...
D/UEI.SmartControl( 7025): serial port data available: 21
,D/UEI.SmartControl( 7025): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 7025): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7025): QS saving settings...
D/UEI.SmartControl( 7025): IR Blaster version: 25672567
D/UEI.SmartControl( 7025): serial port data available: 4
,W/ContextImpl( 7025): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 7025): Services init done
D/UEI.SmartControl( 7025): QS Service init finished
D/UEI.SmartControl( 7025): QS Service version name: 2.1.91
D/UEI.SmartControl( 7025): QS Service version code: 201091
,D/UEI.SmartControl( 7025): Service requested: Control
I/UEI.SmartControl( 7025): Device manager: loading config....
I/QRemote ( 7471): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7025): ------ IControl API: 11
D/UEI.SmartControl( 7025): File observer start...
E/UEI.SmartControl( 7025): IR Port is disabled: false
D/UEI.SmartControl( 7025): Starting file observer...
I/UEI.SmartControl( 7025): Registering callback...
I/UEI.SmartControl( 7025): ------ IControl API: 19
I/UEI.SmartControl( 7025): Registering Services Ready callback...
,D/UEI.SmartControl( 7025): Internal service binding...
D/UEI.SmartControl( 7025): ----------- loading internal config...
E/UEI.SmartControl( 7025): Loading SETTINGS...
D/UEI.SmartControl( 7025): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7025): Notify AllClients services are ready: 0
,I/QRemote ( 7471): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7471): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7471): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7471): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7471): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7025): ------ IControl API: 8
D/UEI.SmartControl( 7025): -----service ready thread exits
D/QRemote ( 7471): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7471): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7471): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7471): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7471): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7471): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7471): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7471): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7471): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7471): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452264791835]
D/QRemote ( 7471): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1040): Killing 6889:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7471): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_6889/cgroup.procs: No such file or directory
V/QRemote ( 7471): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7471): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7471): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2675): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1040): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=293917  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=293948  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7471): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2675): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 2675): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2675): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=294028  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=294029  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATED
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1040): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiMonitor( 1040): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294040
E/WifiStateMachine( 1040):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294041
D/Tethering( 1040): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1040):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294052
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294052
E/WifiStateMachine( 1040):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294054
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=294055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=294084  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=294088  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=294091  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=294091
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=294092
D/WifiNative-wlan0( 1040): doString: [STATUS]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1040):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/WifiServiceExtension( 1040): setVHTCapabilityType  : false
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7421): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7421): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7421): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7421): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : errorList=[]
I/WifiServerServiceExt( 1040): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1040): setKeepAlivePacketInterval msec : 60
,D/UsbSettingsControl( 7421): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7421): [AUTORUN] onReceive() : TetherState Changed=wlan0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 7421): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1040): Got NetworkAgent Messenger
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/ConnectivityService( 1040): NetworkAgent connected
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/CommandListener(  316): Setting iface cfg
E/WifiStateMachine( 1040): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1040): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=294154  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=294154  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=294155  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=294160  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=294160  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=294161  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 0
D/WifiNative-wlan0( 1040): SET ps 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1040): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@72a0d4a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@72a0d4a target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up wlan0
D/DhcpStateMachine( 1040): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1040): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1040): SET ps 1: returned true
,E/WifiStateMachine( 1040):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1040): ignoring duplicate network state non-change
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1040): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1040): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1040): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1040): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/Netd    (  316): netlink response contains error (File exists)
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1040): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1040): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1040): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1040): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1040): currentScore = 0, newScore = 20
D/ConnectivityService( 1040):    accepting network in place of null
D/ConnectivityService( 1040): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1859): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1040): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1040): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1040): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1040): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1040): validation of new default Network = false
D/ConnectivityService( 1040): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1040): enableDataServiceNotify 
D/DSQN    ( 1040): start dsqn bin
D/LocSvc_java( 1040): Sending msg: 4 arg1:1 arg2:1
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unsp,ecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7561): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7561): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
,E/DSQN    ( 7561): DSQN ssw
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1040): [LG_RESTRICTED] checkMobilePolicy_type()
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7471): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7447): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7447): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7471): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7471): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7471): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7447): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7447): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
D/LGDataListener(  316): argv[0]=dsqncommand
D/LGDataListener(  316): argv[1]=wlan0
D/LGDataListener(  316): argv[2]=1
D/LGDataListener(  316): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1040): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1040): start to monitor internet connection
D/QRemote ( 7471): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7471): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7471): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7471): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7471): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 14:53:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452264792543], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452264792525]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Validated
D/ConnectivityService( 1040): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
,D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1040): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1040): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1040): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7567): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
W/dhcpcd  ( 7567): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7567): version 5.5.6 starting
E/dhcpcd  ( 7567): get_duid: m
D/dhcpcd  ( 7567): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7567): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7567): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7567): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7567): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7567): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7567): wlan0: sending REQUEST (xid 0x2c1d2703), next in 3.17 seconds
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3e8032ee type 2 when 294583 com.google.android.gms} when 294583
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/libc-netbsd(  316): res_queryN name = mtalk.google.com succeed
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5174): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5174): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6839): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GCM     ( 2124): Connected
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7597 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/jxcore-log( 7306): Connected to the server!
I/jxcore-log( 7306): 
D/GCM     ( 2124): Message class com.google.f.a.a.p
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/chromium( 7306): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
I/AppUp4:AppBoxCP( 7597): onCreate
,W/AppUp4:DB( 7597):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7597):  setFingerPrint start
I/AppUp4:DB( 7597):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7597):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7597):  SDK version = 21
I/AppUp4:DB( 7597):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7597): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7597): onReceive
,D/LgDataFeature( 7597): LgDataFeature() Constructor: none
,D/LgDataFeature( 7597): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7597): Context : android.app.ReceiverRestrictedContext@1ca972bc
D/AppUp4:CustFacade( 7597): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7597): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7597): begin check event
I/AppUp4:CustModeStarterReceiver( 7597): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7597): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7597): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7597): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7597): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 6912:com.android.contacts/u0a19 (adj 15): empty #17
,D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1040): failed to open /acct/uid_10019/pid_6912/cgroup.procs: No such file or directory
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3358): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3358): DownloadService onCreate
,D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4282): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3358): in removeSpuriousFiles
V/DownloadManager( 3358): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@1ed2d920 on behalf of 3358
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3358): DownloadService onStartCommand
V/DownloadManager( 3358): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4282): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3358): in trimDatabase
V/DownloadManager( 3358): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@e2b2b7f on behalf of 3358
V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@12dc674c on behalf of 3358
V/DownloadManager( 3358): processing inserted download 1
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4282): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4282): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4282): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3358): processing inserted download 4
V/DownloadManager( 3358): processing inserted download 7
V/DownloadManager( 3358): processing inserted download 8
,D/eas_req ( 6936): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3358): processing inserted download 9
V/DownloadManager( 3358): processing inserted download 10
V/DownloadManager( 3358): processing inserted download 16
V/DownloadManager( 3358): processing inserted download 17
V/DownloadManager( 3358): processing inserted download 18
,V/DownloadManager( 3358): processing inserted download 21
E/WifiStateMachine( 1040):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1040): identical MTU - not setting
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524295
I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7646 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3358): DownloadService onDestroy
,I/HubEmail( 6936): JNI_OnLoad()
I/HubEmail( 6936): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6936): registerNatives()
I/HubEmail( 6936): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6936): registerNativeMethods()
I/HubEmail( 6936): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6936): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3329): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3329): networkInfo.isConnected() = false
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7671 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7567): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7567): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7567): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7567): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7567): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7567): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7567): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7567): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7567): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7698 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6960:com.android.gallery3d/u0a27 (adj 15): empty #17
I/art     (  352): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 22.621ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.397ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 20.379ms
,W/libprocessgroup( 1040): failed to open /acct/uid_10027/pid_6960/cgroup.procs: No such file or directory
,D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7732 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6667:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DhcpStateMachine( 1040): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1040): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1040): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1040): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1040): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1040): RunningState
W/libprocessgroup( 1040): failed to open /acct/uid_10061/pid_6667/cgroup.procs: No such file or directory
,I/art     ( 7732): Almond Protected OAT
,V/FormManager( 7646): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7646): Alarm would be updated, because LastCheckTime has been updated.
,D/WeatherApplication( 7732): removeAccount
,D/WeatherApplication( 7732): Account.length = 0
I/ActivityManager( 1040): Killing 6981:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
E/WeatherApplication( 7732): OPERATOR:OPEN
D/WeatherAncestor( 7732): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:53:14
,D/Weather.Utils( 7732): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7732): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7732): 2 : This is isUpdating : false
D/WeatherAncestor( 7732): connectivity changed - connection : true
D/WeatherService( 7732): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7732): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7732): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7732): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7732): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7732): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:53:14
,I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7751 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 7065:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_7065/cgroup.procs: No such file or directory
,W/libprocessgroup( 1040): failed to open /acct/uid_10080/pid_6981/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7306): BLE is supported
I/jxcore-log( 7306): 
I/art     ( 1040): Explicit concurrent mark sweep GC freed 82580(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 3.762ms total 154.513ms
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7751): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/ContextImpl( 7751): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine( 1040):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7751): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7751): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7751): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7751): Loading: webviewchromium
I/LibraryLoader( 7751): Time to load native libraries: 5 ms (timestamps 7040-7045)
I/LibraryLoader( 7751): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7751): Binding Chromium to main looper Looper (main, tid 1) {153cf597}
I/LibraryLoader( 7751): Expected native library version number "",actual native library version number ""
,I/chromium( 7751): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7751): Initializing chromium process, renderers=0
W/art     ( 7751): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7751): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7751): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7751): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  320): registerClient() client 0xb57bb880, uid 10093
W/AudioManagerAndroid( 7751): Requires BLUETOOTH permission
I/Adreno-EGL( 7751): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7751): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7751): Build Date: 12/12/14 금
I/Adreno-EGL( 7751): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7751): Remote Branch: 
I/Adreno-EGL( 7751): Local Patches: 
I/Adreno-EGL( 7751): Reconstruct Branch: 
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 297218571818; DSPS: 9881101; Offset : -4343978424
,I/NSApplication( 7751): Starting up...
,V/WifiInternetCheck( 1040): Single check msg out of sync, ignoring.
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1040): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5174): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1040): Killing 7091:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_7091/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6839): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7597): onReceive
D/AppUp4:CustFacade( 7597): Context : android.app.ReceiverRestrictedContext@1ca972bc
D/AppUp4:CustFacade( 7597): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7597): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7597): begin check event
,I/AppUp4:CustModeStarterReceiver( 7597): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3358): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3358): DownloadService onCreate
D/LGDMClient( 4282): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/DownloadManager( 3358): in removeSpuriousFiles
V/DownloadManager( 3358): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@1c7e2caa on behalf of 3358
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3358): in trimDatabase
I/LGDMClient( 4282): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3358): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@8d1009b on behalf of 3358
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3358): DownloadService onStartCommand
,V/DownloadManager( 3358): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@2aea6976 on behalf of 3358
V/DownloadManager( 3358): processing inserted download 1
V/DownloadManager( 3358): processing inserted download 4
W/Settings( 6936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4282): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4282): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4282): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3329): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3329): networkInfo.isConnected() = false
V/DownloadManager( 3358): processing inserted download 7
V/DownloadManager( 3358): processing inserted download 8
V/DownloadManager( 3358): processing inserted download 9
V/DownloadManager( 3358): processing inserted download 10
V/DownloadManager( 3358): processing inserted download 16
,V/DownloadManager( 3358): processing inserted download 17
V/DownloadManager( 3358): processing inserted download 18
D/WeatherAncestor( 7732): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:53:15
D/Weather.Utils( 7732): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7732): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7732): 2 : This is isUpdating : false
D/WeatherAncestor( 7732): connectivity changed - connection : true
V/DownloadManager( 3358): processing inserted download 21
D/WeatherService( 7732): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17593d9a
D/ForecastDataCache( 7732): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7732): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7732): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7732): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7732): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:53:15
V/DownloadManager( 3358): DownloadService onDestroy
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
W/Kids    ( 2337): [AccountUtils] Account not ready
W/Kids    ( 2337): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2337): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2337): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2337): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2337): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7646): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7646): Alarm would be updated, because LastCheckTime has been updated.
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6839): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7597): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7597): onReceive
,D/AppUp4:CustFacade( 7597): Context : android.app.ReceiverRestrictedContext@1ca972bc
D/AppUp4:CustFacade( 7597): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7597): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7597): begin check event
I/AppUp4:CustModeStarterReceiver( 7597): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3358): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3358): DownloadService onCreate
I/LGDMClient( 4282): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3358): in removeSpuriousFiles
V/DownloadManager( 3358): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@1a1e53e4 on behalf of 3358
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3358): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3358): in trimDatabase
V/DownloadManager( 3358): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@22d1604d on behalf of 3358
V/DownloadManager( 3358): DownloadService onStartCommand
V/DownloadManager( 3358): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3358): created cursor android.database.sqlite.SQLiteCursor@d5eca50 on behalf of 3358
V/DownloadManager( 3358): processing inserted download 1
V/DownloadManager( 3358): processing inserted download 4
W/Settings( 6936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3358): processing inserted download 7
V/DownloadManager( 3358): processing inserted download 8
V/DownloadManager( 3358): processing inserted download 9
E/LGDMClient( 4282): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4282): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4282): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3358): processing inserted download 10
V/DownloadManager( 3358): processing inserted download 16
V/DownloadManager( 3358): processing inserted download 17
V/DownloadManager( 3358): processing inserted download 18
W/Settings( 6936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3358): processing inserted download 21
,I/LgeMiscReceiver( 3329): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3329): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3358): DownloadService onDestroy
I/LgeMiscReceiver( 3329): networkInfo.isConnected() = true
D/PhoneState( 3329): setPdpRejectCasuse : false
D/WeatherAncestor( 7732): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:53:15
,D/Weather.Utils( 7732): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7732): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7732): 2 : This is isUpdating : false
D/WeatherAncestor( 7732): connectivity changed - connection : true
D/WeatherService( 7732): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17593d9a
D/ForecastDataCache( 7732): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7732): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7732): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7732): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7732): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:53:15
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2337): [AccountUtils] Account not ready
W/Kids    ( 2337): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2337): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2337): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2337): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2337): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
,D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7646): There are no updated forms. The schedule will be deleted.
V/FormManager( 7646): Alarm would be updated, because LastCheckTime has been updated.
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
W/Kids    ( 2337): [AccountUtils] Account not ready
W/Kids    ( 2337): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2337): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2337): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2337): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2337): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2337): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2337): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = www.google.com succeed
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
D/UEI.SmartControl( 7025): Internal timer expired: 4
D/UEI.SmartControl( 7025): unbind internal service
,V/WifiInternetCheck( 1040): isHttpConnectionAvailable - We got a valid response : 204
,D/serial_port( 7025): close(fd = 24)
,I/UEI.SmartControl( 7025): Serial port is closed.
I/GAV4    ( 7751): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 317221350092; DSPS: 10536552; Offset : -4343977093
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{34805d0d type 2 when 321384 android} when 321384
,V/QRemote ( 7471): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 7471): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8535
E/WifiStateMachine( 1040):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 337223059200; DSPS: 11191968; Offset : -4343976969
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=759829015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=759829015 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 357224763462; DSPS: 11847384; Offset : -4343981770
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
,D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6401): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6401): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6401): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6401): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6401): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6401): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6401): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 6401): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 377226614965; DSPS: 12502805; Offset : -4343991736
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 397228567509; DSPS: 13158229; Offset : -4343992265
I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
I/jxcore-log( 7306): --- start :testFindPeers.js---
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): testFindPeers created [object Object]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): serverPort is 8876
I/jxcore-log( 7306): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7306): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3791): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): start: OK
I/io.jxcore.node.ConnectionHelper( 7306): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7306): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7306): createAdvertiseData: From: G3-1 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7306): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7306): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7306): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7306): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): start: Starting P2P device discovery...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7306): start: OK
I/jxcore-log( 7306): StartBroadcasting started ok
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7306): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7306): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7306): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/chromium( 7306): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 7306): 
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 417230907554; DSPS: 13813665; Offset : -4343971529
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/WifiServerServiceExt( 1040): No p2p device connected
,D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7306): 
,D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-10ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-13ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-13ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-13ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-15ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-15ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-15ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1040): InactiveState{ when=-19ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-19ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-19ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-21ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-21ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-21ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-22ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-22ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-22ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-23ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-23ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-23ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000101000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000101000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000101000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1040): InactiveState{ when=-13ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-13ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=12 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=12 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=55 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
I/[SystemUI]LGPowerUI( 1459): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1459): On Skip Timer : true
,D/LEDHandler( 1953): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1953): Battery Level Remaining: 100%
D/LEDHandler( 1953): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1459): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1459): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1040): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1459): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3791): Disconnected process message: 10, size: 0
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 437232638119; DSPS: 14469082; Offset : -4343980361
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000103000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000103000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000103000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7306): 
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7306): 
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7306): 
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7306): 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=74 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1040):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1040):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
,D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000103000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000103000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000103000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7306): 
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=77 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 a2:39:f7:6f:c9:5d 0 4 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 a2:39:f7:6f:c9:5d 0 4 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-SERV-DISC-REQ 2462 a2:39:f7:6f:c9:5d 0 4 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=82 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 457233347279; DSPS: 15124465; Offset : -4343973419
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
,D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=86 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=87 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10,-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7306): 
I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=89 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=93 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=-11ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=95 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device:, Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=96 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=97 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000105000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000105000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=99 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000105000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=100 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=102 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 477235272791; DSPS: 15779888; Offset : -4343970513
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-12ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 6 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ],
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=105 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=107 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=108 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=109 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=110 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=111 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=112 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
,D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=114 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg,2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-8ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
,D/LGWifiP2pService( 1040): InactiveState{ when=-14ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-14ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-14ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-14ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-15ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-15ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-16ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-17ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-17ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=117 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=118 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=119 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=120 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=121 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-8ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-8ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b,
,D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=122 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=123 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=124 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=125 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1040):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1040):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=126 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=127 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=128 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED ,
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=129 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=130 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 497236939555; DSPS: 16435303; Offset : -4343982112
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=131 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=132 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=133 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=134 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=135 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=136 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=137 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=139 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=140 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 A3-1] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Removed peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Removed peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerLost: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] removed
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] not available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":false}]
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): onPeerLost: [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] removed
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] not available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":false}]
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=141 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=142 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=143 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=144 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=146 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
,D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=147 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=148 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000107000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000107000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=149 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000107000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=150 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-15ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
,D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
I/jxcore-log( 7306): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"XT1072","peerAvailable":true}]
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 7306): 
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
,D/LGWifiP2pService( 1040): InactiveState{ when=-19ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-19ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/jxcore-log( 7306): timeout now
I/jxcore-log( 7306): 
I/jxcore-log( 7306): weAreDoneNow
I/jxcore-log( 7306): 
I/jxcore-log( 7306): done, now sending data to server
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 517238953661; DSPS: 17090729; Offset : -4343982062
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=152 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=153 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED ,
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=154 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=155 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=156 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=157 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=159 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=55 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=55 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=161 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139310 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b6037688
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=162 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=163 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 8 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=164 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027,
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=165 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=166 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=167 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=168 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01
I/jxcore-log( 7306): teardown
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): testFindPeers stopped
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 7306): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2675): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1953): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/LGWifiP2pService( 1040): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7306): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setState: NOT_STARTED
I/jxcore-log( 7306): StopBroadcasting went ok
I/jxcore-log( 7306): 
I/jxcore-log( 7306): --- start :testSendData.js---
I/jxcore-log( 7306): 
I/jxcore-log( 7306): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":18}bt-address length : 17
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): daya100000
I/jxcore-log( 7306): 
I/jxcore-log( 7306): check server
I/jxcore-log( 7306): 
I/jxcore-log( 7306): serverPort is 60102
I/jxcore-log( 7306): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7306): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): start: OK
I/io.jxcore.node.ConnectionHelper( 7306): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7306): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7306): createAdvertiseData: From: G3-1 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7306): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7306): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7306): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7306): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=170 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7306): start: OK
I/jxcore-log( 7306): StartBroadcasting started ok
I/jxcore-log( 7306): 
I/jxcore-log( 7306): [ { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 7306):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 7306):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 7306):   { address: '34:FC:EF:11:B1:66', tryCount: 0 },
I/jxcore-log( 7306):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 7306):   { address: 'B4:CE:F6:AB:A4:6A', tryCount: 0 },
I/jxcore-log( 7306):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 7306):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 7306):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 7306):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 7306):   { address: '34:FC:EF:9D:93:0B', tryCount: 0 },
I/jxcore-log( 7306):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 7306):   { address: '80:01:84:8A:B3:68', tryCount: 0 },
I/jxcore-log( 7306):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 7306):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 7306):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 7306):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 } ]
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): startWithNextDevice
I/jxcore-log( 7306): 
I/jxcore-log( 7306): do fake peer & start
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:57:11.022Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:57:11.023Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:57:11.023Z SendDataConnector.js: do connect now
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 7306): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): connect: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7306): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/jxcore-log( 7306): 2016-01-08T14:57:11.030Z SendDataTCPServer.js: TCP/IP server is bound to port: 60102
I/jxcore-log( 7306): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 866)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7306): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,I/io.jxcore.node.ConnectionHelper( 7306): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7306): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7306): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7306): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7306): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: RESTARTING
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2675): P2P-FIND-STOPPED 
D/WfdsMonitor( 1953): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=171 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7306): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7306): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: RESTARTING
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
I/chromium( 7306): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7306): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
W/LGMDMUISystemServiceAdapter( 7306): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3791): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3791): [BTUI] connectSocket FD=85 mFd=84
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=759829015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3c4d76b3 type 2 when 533079 android} when 533079
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=759829015 [*alarm*], flags=0x0
,I/BooksSync( 7184): Starting books sync
,D/BooksSync( 7184): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2124): Explicit concurrent mark sweep GC freed 47359(2MB) AllocSpace objects, 23(3MB) LOS objects, 51% free, 30MB/62MB, paused 2.522ms total 69.271ms
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
,D/libc-netbsd(  316): res_queryN name = www.googleapis.com succeed
,W/bt-btm  ( 3791): btm_acl_created hci_handle=2 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=2 link_role=1  transport=1
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24841
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: 34-fc-ef-11-ae-67
,W/bt-btif ( 3791): info:x10
D/        ( 3791): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3791): aclStateChangeCallback: Device is NULL
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/LGBluetoothServiceUtil( 3791): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0042,PSM: 1,our MTU present:1,our MTU:672
D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d70e91e:true
D/LGBluetoothFeatureConfig( 7421): isPrivacyLogsEnabled : true
,D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 1
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0042,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3791): process_service_search_attr_rsp
W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x0040
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 21
W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
,W/ApiaryClient( 7184): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1744712286080922291&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
D/        ( 3791): cod is 0, set as unclassified
,W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3791): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
I/ActivityManager( 1040): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7943 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7421): Create singleton instance
,D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3463bfcc:true
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=380699157, flags=0x3000001a, tag="LGBluetoothAlertSound", ws=null, historyTag=null, uid=1000, pid=7421
,I/PowerManagerService( 1040): Waking up from sleep (uid 1000)...
D/KnockOnPowerController( 1040): [updateScreenState] screen on = true
D/KnockOnPowerController( 1040): disable proximity sensor
I/SensorManager( 1040): removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.android.server.power.ProximitySensorListener.disable():117
I/sensors_hal_Ctx( 1040): activate: handle is 70, disable
V/sensors_hal_Ctx( 1040): activate sensors is 800000000000
D/sensors_hal_KnockOnProx( 1040): enable: handle=70
D/sensors_hal_KnockOnProx( 1040): enable: Disabling sensor handle=70
I/sensors_hal_SAM( 1040): sendCancel:sensor() Sending cancel to svc no:33
I/KnockOnPowerController( 1040): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
V/KeyguardServiceDelegate( 1040): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@93e792a)
V/SmartCoverServiceDelegate( 1040): onScreenTurnedOn()
D/SmartCoverViewMediator( 1405): onScreenTurnedOn, seq = 0
D/SmartCoverViewMediator( 1405): notifyScreenOnLocked
D/SmartCoverViewMediator( 1405): handleNotifyScreenOn
I/QuickCircle( 1405): onScreenTurnedOn
V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 0, txn Id 69
D/sensors_hal_KnockOnProx( 1040): processResp: Received SNS_SAM_KNOCK_DISABLE/CANCEL_RESP_V01
D/KeyguardViewMediator( 1459): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1459): notifyScreenOnLocked
D/KeyguardViewMediator( 1459): handleNotifyScreenOn
V/KeyguardStatusView( 1459): Enable transport text marquee
V/KeyguardServiceDelegate( 1040): **** SHOWN CALLED ****
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=30000 (505617 ms ago)
I/DisplayPowerController( 1040): Blocking screen on until initial contents have been drawn.
I/SensorManager( 1040): registerListenerImpl() [Sensor: Motion Accel, Rate: 66667, SensorEventListener: com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@30b81c5b] bycom.android.internal.policy.impl.WindowOrientationListener.enable():147
I/sensors_hal_Ctx( 1040): batch: handle:46 flags:0x0 period_ns 66667000, timeout 0
D/sensors_hal_SAM( 1040): batch:sensor(com.qti.sensor.motion_accel) handle:46 flags:0x0 period_ns:66667000 timeout:0
D/sensors_hal_SAM( 1040): batch:sensor(com.qti.sensor.motion_accel) handle:46 freq:1 report_rate:1 max:1.000000 min:0.000000
I/sensors_hal_Ctx( 1040): activate: handle is 46, enable
V/sensors_hal_Ctx( 1040): activate sensors is c00000000000
D/sensors_hal_LP2( 1040): enable: handle=46
I/sensors_hal_SAM( 1040): sendEnableReq:sensor(com.qti.sensor.motion_accel) Sending enable to svc no:49
D/sensors_hal_Util( 1040): waitForResponse: timeout=1000
I/Sensors (  496): sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
I/Sensors (  496): sns_sam_dep.c(465):Algo b76018ca Generating dependent req f54afd3e
E/LGBluetoothAuthorization( 7421): [BTUI] ### PAIR_REQUEST : isLockScreen (false)
V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 2, txn Id 0
D/sensors_hal_LP2( 1040): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_ENABLE_RESP_V01
W/ContextImpl( 7421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1289 android.content.ContextWrapper.startActivity:322 android.content.ContextWrapper.startActivity:322 com.android.settings.bluetooth.BluetoothPairingRequest.onReceive:96 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 7421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1301 android.app.ContextImpl.startActivity:1290 android.content.ContextWrapper.startActivity:322 android.content.ContextWrapper.startActivity:322 com.android.settings.bluetooth.BluetoothPairingRequest.onReceive:96 
I/Timeline( 7421): Timeline: Activity_launch_request id:com.android.settings time:535622
D/sensors_hal_LP2( 1040): enable: Received response: 0
,I/QCOM PowerHAL( 1040): Got set_interactive hint
D/SurfaceFlinger(  282): Set power mode=2, type=0 flinger=0xb6082000
D/qdhwcomposer(  282): hwc_blank: Unblanking display: 0
I/DisplayManagerService( 1040): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/ActivityManager( 1040): START u0 {act=android.bluetooth.device.action.PAIRING_REQUEST flg=0x10040000 cmp=com.android.settings/.bluetooth.BluetoothPairingDialog (has extras)} from uid 1000 on display 0
,D/QuickCircleViewManager( 1405): applyCoverState:0
D/DSDPConnection( 1859): Display #0 changed.
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{1205936a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
W/ResourcesManager( 1040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1040): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 1040): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 1040): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 1040): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1040): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33f30cb8:true
V/SplitWindowPolicy( 1953): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....bluetooth.BluetoothPairingDialog}
,D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{3aacaa91 #5 I=com.android.settings/.bluetooth.BluetoothPairingDialog U=0 sz=0} / mTaskToReturnTo = 0
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): VFP is [12]
,I/qdhwcomposer(  282): handle_blank_event: dpy:0 panel power state: 1
,I/rmt_storage(  308): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  308): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  308): wakelock acquired: 1, error no: 42
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/qdhwcomposer(  282): hwc_blank: Done unblanking display: 0
D/SurfaceControl( 1040): Excessive delay in setPowerMode(): 187ms
,I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  308): 
E/Diag_Lib(  896): [IMS_FATAL]| 3347 | 914 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/rmt_storage(  308): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/WindowManager( 1040): Screenshot max retries 4 of Token{75b6be7 ActivityRecord{b8545a6 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{64dd865 u0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=1
E/ActivityManager( 1040): Invalid thumbnail dimensions: 768x768
,V/ActivityManager( 1040): Display changed displayId=0
D/LNfcService( 1929): action : android.intent.action.USER_PRESENT
V/SplitWindowPolicy( 1953): receive broadcasted action: android.intent.action.USER_PRESENT, isFull? false, isPrevLock? false
,D/LIA_MrGDBLogger_AppUsageDetector( 3732): [dreamwood]ACTION_USER_PRESENT
D/LIA_MrGDBLogger_LoggerThread( 3732): [dreamwood]App Usage Logging
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{2fe750f8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,E/ActivityThread( 7943): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7943): No ProfileInfo entries
I/LG Account v2.2( 7943): isEnabled: false
I/Feature ( 7943): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7943): [Lifetracker]Country: EU
I/Feature ( 7943): [Lifetracker]Operator: OPEN
I/Feature ( 7943): [Lifetracker]Ranking support: false
I/Feature ( 7943): [Lifetracker]Comfort support: false
I/Feature ( 7943): [Lifetracker]Accessory: true
I/Feature ( 7943): [Lifetracker]Health device: true
I/Feature ( 7943): [Lifetracker]Extra Pedometer: false
I/Feature ( 7943): [Lifetracker]Blood glucose device: false
I/Feature ( 7943): [Lifetracker]Device Number: 3
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{37f939d1 co.....bluetooth.BluetoothPairingDialog}, taskId=5, activityType=0, bIsSplit=false
V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
D/sensors_hal_LP2( 1040): processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
D/sensors_hal_LP2( 1040): processInd: Samples_len=1 Items=1 max_reports_per_index=1
V/sensors_hal_LP2( 1040): processInd: X: -0.277435 Y: -0.275269 Z: 9.618179 
D/sensors_hal_Ctx( 1040): poll:polldata:1, sensor:46, type:499898101, x:-0.277435 y:-0.275269 z:9.618179
D/sensors_hal_Ctx( 1040): poll: count: 36
D/sensors_hal_Util( 1040): waitForResponse: timeout=0
E/WifiStateMachine( 1040):  ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
D/WifiServerServiceExt( 1040): sendKtScanInterval  mRtspPlay : false
E/WifiStateMachine( 1040):  L2ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 1040):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 1040):  ConnectedState !what:132097 0 0
E/WifiStateMachine( 1040):  L2ConnectedState !what:132097 0 0
E/WifiStateMachine( 1040):  ConnectModeState !what:132097 0 0
E/WifiStateMachine( 1040):  DriverStartedState !what:132097 0 0
I/WifiServerServiceExt( 1040): set CMD_KT_SCAN_INTERVAL
,E/WifiStateMachine( 1040):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
V/AudioFlinger(  320): setParameters(): io 0, keyvalue screen_state=on, calling pid 1040
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1040):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
D/WeatherAncestor( 7732): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:57:14
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine( 1040):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine( 1040):  ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
D/audio_hw_primary(  320): adev_set_parameters: enter: screen_state=on
V/voice   (  320): voice_set_parameters: enter: screen_state=on
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: exit
V/voice   (  320): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  320): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  320): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  320): platform_set_parameters: exit with code(0)
,V/lge_audio_loopback(  320): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  320): lge_set_dump_config: exit dump_config : 0
V/audio_hw_primary(  320): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  320): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
E/WifiStateMachine( 1040):  ConnectModeState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
E/WifiStateMachine( 1040):  DriverStartedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
D/sensors_hal_LP2( 1040): processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
D/sensors_hal_LP2( 1040): processInd: Samples_len=1 Items=1 max_reports_per_index=1
V/sensors_hal_LP2( 1040): processInd: X: -0.284927 Y: -0.266449 Z: 9.626572 
D/sensors_hal_Ctx( 1040): poll:polldata:1, sensor:46, type:499898101, x:-0.284927 y:-0.266449 z:9.626572
D/sensors_hal_Ctx( 1040): poll: count: 36
D/sensors_hal_Util( 1040): waitForResponse: timeout=0
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/Weather.Utils( 7732): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7732): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7732): 2 : This is isUpdating : false
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WeatherAncestor( 7732): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:57:14
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1459): onReceive = android.intent.action.SCREEN_ON
I/LEDService( 1953): getCurrentHighestLGLedRecord() start. size = 1
,D/qdlights( 1953): set_light_notifications: 3,0,0,0,3
D/qdlights( 1953): [pattern_id] = 0
D/qdlights( 1953): set_light_notifications: 0,0,0,0,3
V/UserPresentBroadcastReceiver( 1824): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/LEDService( 1953): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1953): set_light_notifications: 0,0,0,0,3
I/LEDService( 1953): updateLightsLocked : turn off led
D/qdlights( 1953): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1953): RESTART MSG
,D/SplitWindow( 1040): check instance of lgWin Window{19ab4e7e u0 SearchPanel}
I/Timeline( 7306): Timeline: Activity_idle id: android.os.BinderProxy@32fc6f3e time:536155
I/Cliptray Service( 1953): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1953): lockStatus = 0
,D/LNfcService( 1929): action : android.intent.action.SCREEN_ON
I/DisplayPowerController( 1040): Unblocked screen on after 542 ms
D/Ulp_jni ( 1040): JNI:system_update. Event-0
E/libEGL  ( 1040): call to OpenGL ES API with no current context (logged once per thread)
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/WifiStateMachine( 1040):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine( 1040):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
D/WifiNative-wlan0( 1040): doBoolean: BLACKLIST clear
D/WifiNative-wlan0( 1040): BLACKLIST clear: returned true
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
V/PhoneApp( 1859): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/InputDispatcher( 1040): Window went away: Window{2886cf44 u0 SearchPanel}
,I/[SystemUI]Clock( 1459): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1459): time changed, timezoneChanged : false
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): ACTION_SCREEN_ON
D/LIA_MrGDBLogger_AppUsageDetector( 3732): [dreamwood]ACTION_SCREEN_ON !!!
,D/LIA_MrGDBLogger_AppUsageDetector( 3732): [dreamwood]scheduledExecutorService is running
W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
D/AppCleanupService( 5138): android.intent.action.SCREEN_ON
W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 64627(3MB) AllocSpace objects, 5(720KB) LOS objects, 33% free, 44MB/66MB, paused 2.582ms total 258.398ms
D/ContextHelper( 7421): convertTheme. context->name=com.android.settings themeResourceId=34210251
E/BluetoothPairingDialog( 7421): onCreate mUserConfirmed : false
D/LGBluetoothFeatureConfig( 7421):  get() - isFeatureLoaded : false
,D/LocalBluetoothProfileManager( 7421): Adding local A2DP profile
D/BluetoothManagerService( 1040): Message: 30
,D/LocalBluetoothProfileManager( 7421): Adding local HEADSET profile
D/BluetoothManagerService( 1040): Message: 30
D/BluetoothManagerService( 1040): Message: 30
D/BluetoothManagerService( 1040): Message: 30
,D/LocalBluetoothProfileManager( 7421): Adding local MAP profile
D/BluetoothMap( 7421): Create BluetoothMap proxy object
D/BluetoothManagerService( 1040): Message: 30
D/BluetoothManagerService( 1040): Message: 30
D/LocalBluetoothProfileManager( 7421): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 7421): [BTUI] initUserBindClient
,W/ContextImpl( 7421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothPairingDialog( 7421): onCreate: mDeviceType: Phone mType :2 mDeviceType.length : 5
E/BluetoothPairingDialog( 7421): [BTUI] [3] PAIRING_VARIANT_PASSKEY_CONFIRMATION
I/PhoneWindow( 7421): [generateLayout] setColorNavigationBar => color=0x ff000001
,D/PhoneWindowEx( 7421): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 7421): [setNavigationBarColor2] color=0x fff5f5f5
,D/OpenGLRenderer( 7421): Render dirty regions requested: true
I/Adreno-EGL( 7421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7421): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7421): Build Date: 12/12/14 금
I/Adreno-EGL( 7421): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7421): Remote Branch: 
I/Adreno-EGL( 7421): Local Patches: 
I/Adreno-EGL( 7421): Reconstruct Branch: 
I/OpenGLRenderer( 7421): Initialized EGL, version 1.4
D/OpenGLRenderer( 7421): Enabling debug mode 0
,D/Atlas   ( 7421): Validating map...
D/SplitWindow( 1040): check instance of lgWin Window{3bd7d051 u0 com.android.settings/com.android.settings.bluetooth.BluetoothPairingDialog}
,D/BluetoothA2dp( 7421): Proxy object connected
D/A2dpProfile( 7421): Bluetooth service connected
,D/BluetoothHeadset( 7421): Proxy object connected
D/HeadsetProfile( 7421): Bluetooth service connected
D/BluetoothInputDevice( 7421): Proxy object connected
D/HidProfile( 7421): Bluetooth service connected
D/BluetoothPan( 7421): BluetoothPAN Proxy object connected
D/PanProfile( 7421): Bluetooth service connected
D/BluetoothMap( 7421): Proxy object connected
D/MapProfile( 7421): Bluetooth service connected
D/BluetoothMap( 7421): getConnectedDevices()
V/BluetoothMapService( 3791): getConnectedDevices()
,D/BluetoothPbap( 7421): Proxy object connected
D/PbapServerProfile( 7421): Bluetooth service connected
D/LGBluetoothUserBindClient( 7421): [BTUI] onServiceConnected
W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
W/ApiaryClient( 7184): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1744712286080922291&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
,I/Timeline( 7421): Timeline: Activity_idle id: android.os.BinderProxy@2bc5c2c6 time:536619
,I/ActivityManager( 1040): Displayed com.android.settings/.bluetooth.BluetoothPairingDialog: +633ms
I/Sensors (  496): sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
,I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{14a2fdf6 u0 com.android.settings/.bluetooth.BluetoothPairingDialog t5} time:536895
,E/GBMv2   (  335): DFP En is all cleared set to be enabled
,E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
W/bt-l2cap( 3791): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/bt-btm  ( 3791): btm_acl_created hci_handle=3 link_role=1  transport=1
W/bt-btm  ( 3791): btm_acl_created hci_handle=3 link_role=0  transport=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): Start timer timeout, starting now...
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=172 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-76-27
W/bt-btif ( 3791): info:x10
D/        ( 3791): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3791): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3791): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: 08eca9507627  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
,D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 2
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
W/ApiaryClient( 7184): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1744712286080922291&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:474756] from screen [on:0 period:566091198] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:566091203] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
D/ConnectivityService( 1040): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1040): Connected BT device : -1
I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 1
,D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15fee8a8:true
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]
I/BluetoothClassifier( 4616): Bluetooth Device Name: Thali Test (Galaxy A3)
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=173 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/BooksSync( 7184): Soft error: 
E/BooksSync( 7184): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1744712286080922291&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7184): Headers:
E/BooksSync( 7184): accept-encoding: [gzip]
E/BooksSync( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7184): gdata-version: 2
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7184): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7184): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7184): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7184): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7184): {
E/BooksSync( 7184):  "error": {
E/BooksSync( 7184):   "errors": [
E/BooksSync( 7184):    {
E/BooksSync( 7184):     "domain": "global",
E/BooksSync( 7184):     "reason": "required",
E/BooksSync( 7184):     "message": "Login Required",
E/BooksSync( 7184):     "locationType": "header",
E/BooksSync( 7184):     "location": "Authorization"
E/BooksSync( 7184):    }
E/BooksSync( 7184):   ],
E/BooksSync( 7184):   "code": 401,
E/BooksSync( 7184):   "message": "Login Required"
E/BooksSync( 7184):  }
E/BooksSync( 7184): }
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7184): 	... 8 more
,E/BooksSync( 7184): Sync error
E/BooksSync( 7184): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1744712286080922291&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7184): Headers:
E/BooksSync( 7184): accept-encoding: [gzip]
E/BooksSync( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7184): gdata-version: 2
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7184): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7184): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7184): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7184): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7184): {
E/BooksSync( 7184):  "error": {
E/BooksSync( 7184):   "errors": [
E/BooksSync( 7184):    {
E/BooksSync( 7184):     "domain": "global",
E/BooksSync( 7184):     "reason": "required",
E/BooksSync( 7184):     "message": "Login Required",
E/BooksSync( 7184):     "locationType": "header",
E/BooksSync( 7184):     "location": "Authorization"
E/BooksSync( 7184):    }
E/BooksSync( 7184):   ],
E/BooksSync( 7184):   "code": 401,
E/BooksSync( 7184):   "message": "Login Required"
E/BooksSync( 7184):  }
E/BooksSync( 7184): }
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7184): 	... 8 more
I/BooksSync( 7184): Finished books sync
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=174 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 8 device(s) discovered
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 533079, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=175 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1040):    returned b60376a0
,D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=176 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=177 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1040):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1040):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thal,iproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=178 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=156.0, 0.0, 0.0  rx=154.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:566094219] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=156.0, 0.0, 0.0  rx=154.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:566094223] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/btif_config_util( 3791): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=78.0, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:566097238] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=78.0, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566097241] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=380699157 [LGBluetoothAlertSound], flags=0x0
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=575630 (in 29994 ms)
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 7 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 7 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=179 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 7 120001060a436f72646f7661703270c00c000c01
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=39.0, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:566100254] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=39.0, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:566100260] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=180 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/[SystemUI]LGPowerUI( 1459): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1459): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1459): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=181 dispatchEvent: P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 7 120001070a436f72646f7661703270c00c000c01
I/[SystemUI]LGPowerUI( 1459): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1040): battery changed pluggedType: 2
D/LEDHandler( 1953): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1953): Battery Level Remaining: 100%
D/LEDHandler( 1953): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1459): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3791): Disconnected process message: 10, size: 0
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=182 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=19.5, 0.0, 0.0  rx=19.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:566103272] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=19.5, 0.0, 0.0  rx=19.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:566103276] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=183 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=184 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0],
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=-18ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-19ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=185 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=186 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p,2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-10ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-11ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-10ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=38 target=com.android.,internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=187 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1040):    returned b60376a0
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=188 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=189 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=190 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147477 obj=Device: A3-1,
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
,D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=-11ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-11ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-8ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-10ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=10.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:566106481] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=10.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566106484] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 557242394845; DSPS: 18401562; Offset : -4343989313
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:566109498] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566109501] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=575630 (in 16034 ms)
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=191 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:566112513] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566112516] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=192 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 7 120001080a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=193 dispatchEvent: P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 7 120001080a436f72646f7661703270c00c000c01
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=194 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=195 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{225c6fc1 type 2 when 563241 android} when 563241
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=196 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:566115528] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:566115535] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=197 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=198 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 8
,W/bt-rfcomm( 3791): PORT_StartCnf failed result:5
W/bt-btif ( 3791): invalid rfc slot id: 8
,E/bt-btif ( 3791): invalid rfc slot id: 8
I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 9 Address: 34:FC:EF:11:AE:67 newState: 0
D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3791): Failed to remove device: 34:FC:EF:11:AE:67
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
,W/LGMDMUISystemServiceAdapter( 7306): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothEventManager( 7421): Got bonding state changed for 34:FC:EF:11:AE:67, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(1) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
D/LGBluetoothUtils( 7421): [BTUI] == Not displaying any message for reason: 1
,I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=575630 (in 10031 ms)
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{d617c36 co.....bluetooth.BluetoothPairingDialog}, taskId=5, activityType=0, bIsSplit=false
D/BTIF_SOCK( 3791): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
V/ActivityManager( 1040): Display changed displayId=0
,D/DSDPConnection( 1859): Display #0 changed.
E/GBMv2   (  335): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
,D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{2e1e8737 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,I/Timeline( 7306): Timeline: Activity_idle id: android.os.BinderProxy@32fc6f3e time:565671
,I/ActivityManager( 1040): Killing 7121:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/LGBluetoothUtils( 7421): [BTUI] ****** showError(0) ******
D/LGBluetoothUtils( 7421): [BTUI] mForegroundActivity is null
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
,I/NotificationService( 1040): enqueueToast pkg=com.android.settings callback=android.app.ITransientNotification$Stub$Proxy@30807ff2 duration=0
W/libprocessgroup( 1040): failed to open /acct/uid_10005/pid_7121/cgroup.procs: No such file or directory
,D/NotificationService( 1040): Show pkg=com.android.settings callback=android.app.ITransientNotification$Stub$Proxy@30807ff2
D/LGBluetoothTutorialUtils( 7421): isBtTutorialShowing(), mCurrentBtSettings is null
,D/InputDispatcher( 1040): Window went away: Window{3bd7d051 u0 com.android.settings/com.android.settings.bluetooth.BluetoothPairingDialog EXITING}
,D/SplitWindow( 1040): check instance of lgWin Window{20ac24c0 u0 Toast}
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=150885881, flags=0x2000000a, tag="WindowManager", ws=WorkSource{1000}, historyTag=null, uid=1000, pid=1040
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
W/bt-btm  ( 3791): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=2
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btm  ( 3791): BTM: Local device role : 0x01
W/bt-btm  ( 3791): BTM: RemBdAddr: 34fcef11ae67
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 3791): l2c_link_hci_conn_req:current link_role= 0
,E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/LIA_MrGDBLogger_LoggerThread( 3732): [dreamwood]App Usage Logging
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=199 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:566118882] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566118885] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,E/GBMv2   (  335): DFP En is all cleared set to be enabled
,E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=200 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=201 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/NotificationService( 1040): Timeout pkg=com.android.settings callback=android.app.ITransientNotification$Stub$Proxy@30807ff2
D/InputDispatcher( 1040): Window went away: Window{20ac24c0 u0 Toast}
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
,D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1040):    returned b60376a0
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=202 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): VFP is [12]
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=575630 (in 7285 ms)
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=150885881 [WindowManager], flags=0x0
D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=598346 (in 29998 ms)
D/btif_config_util( 3791): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=203 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010b000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010b000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=204 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010b000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 XT1072] already in the list, will not add again
D/TaskPersister( 1040): removeObsoleteFile: deleting file=5_task_thumbnail.png
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=205 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=206 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=207 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
E/GBMv2   (  335): DFP En is all cleared set to be enabled
E/GBMv2   (  335): Set value is all cleared set the max
,I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:2997] from screen [on:0 period:566122196] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:566122200] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,W/bt-btm  ( 3791): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-btm  ( 3791): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-btif ( 3791): info:x10
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3791): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,D/WifiServerServiceExt( 1040): Connected BT device : 0
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 255
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btm  ( 3791): BTM: Local device role : 0x01
W/bt-btm  ( 3791): BTM: RemBdAddr: 34fcef11ae67
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 2
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]
I/BluetoothClassifier( 4616): Bluetooth Device Name: Thali Test (Galaxy A3)
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
,W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=0
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3791): btm_acl_created hci_handle=6 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=6 link_role=1  transport=1
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a218 rs_disc_pending=1
,W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btm  ( 3791): BTM: Local device role : 0x01
W/bt-btm  ( 3791): BTM: RemBdAddr: 08eca9507627
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x0044  Result: 0  Status: 0  BDA: 08eca9507627  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0042,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0042,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x0044
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3791): process_service_search_attr_rsp
W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x0043
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): Requested New Role: 0
E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:566125214] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566125217] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a218 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btm  ( 3791): BTM: Local device role : 0x01
W/bt-btm  ( 3791): BTM: RemBdAddr: 08eca9507627
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
,W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=0
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btm  ( 3791): btm_acl_created hci_handle=8 link_role=1  transport=1
W/bt-btm  ( 3791): btm_acl_created hci_handle=8 link_role=1  transport=1
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 0
D/WifiServerServiceExt( 1040): Connected BT device : -1
I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4616): Bluetooth Device Name: Thali Test (Galaxy A3)
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 19
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 3791): check_cod: remote_cod = 0x5a020c
W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3791): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for 34:FC:EF:11:AE:67, but we have no record of that device.
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3791): Failed to remove device: 34:FC:EF:11:AE:67
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
E/BluetoothEventManager( 7421): Got bonding state changed for 34:FC:EF:11:AE:67, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
W/LGBluetoothUtils( 7421): showUnbondMessage: Not displaying any message for reason: 0
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
,I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0048,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0048,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3791): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3791): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onSocketConnected: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67] (thread ID: 866)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 866)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesWritten: 63 bytes successfully written (thread ID: 868)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Outgoing connection initialized (*handshake* thread ID: 868)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Exiting thread (thread ID: 866)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Entering thread (ID: 868)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesRead: Read 66 bytes successfully (thread ID: 868)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Handshake succeeded with [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onHandshakeSucceeded: [34:FC:EF:11:AE:67 Nexus 5] (thread ID: 866)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Exiting thread (ID: 868)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 Nexus 5]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7306): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 7306): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7306): Entering thread (ID: 869)
D/io.jxcore.node.OutgoingSocketThread( 7306): Server socket local port: 56234
I/io.jxcore.node.OutgoingSocketThread( 7306): Now accepting connections...
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,I/io.jxcore.node.ConnectionHelper( 7306): onListeningForIncomingConnections: Outgoing connection is using port 56234 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 7306): 2016-01-08T14:57:53.715Z SendDataConnector.js: CLIENT connected to 56234, error: null
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:57:53.716Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7306): 
,I/io.jxcore.node.OutgoingSocketThread( 7306): Incoming data from address: /127.0.0.1, port: 56234
D/io.jxcore.node.OutgoingSocketThread( 7306): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7306): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7306): Exiting thread (ID: 869)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 871, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 870, name: Sender)
I/jxcore-log( 7306): 2016-01-08T14:57:53.741Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7306): 
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=208 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=209 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:566128230] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:566128230] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 7306): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7306): setAdvertiseMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7306): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7306): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7306): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7306): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7306): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=210 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,I/jxcore-log( 7306): 2016-01-08T14:57:55.284Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7306): 
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 577244323118; DSPS: 19056985; Offset : -4343983882
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62826
I/jxcore-log( 7306): 2016-01-08T14:57:55.458Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7306): 
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=211 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,I/jxcore-log( 7306): 2016-01-08T14:57:55.943Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7306): 
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,I/jxcore-log( 7306): 2016-01-08T14:57:56.031Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:32136
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22236
I/jxcore-log( 7306): 2016-01-08T14:57:56.208Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:56.250Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7306): 
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4416
,I/jxcore-log( 7306): 2016-01-08T14:57:56.505Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:56.537Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:56.749Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=212 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,I/jxcore-log( 7306): 2016-01-08T14:57:57.270Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:57.271Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7306): 
I/jxcore-log( 7306): oneRoundDownNow
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:57.275Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:57.276Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7306): 
D/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 7306): close
D/io.jxcore.node.OutgoingSocketThread( 7306): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 871
D/io.jxcore.node.OutgoingSocketThread( 7306): close: Stopping sending thread...
E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:566131240] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 870
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local input stream...
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:566131241] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 870, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7306): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 871, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 870, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 871, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:57:57.295,Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7306): 
I/jxcore-log( 7306): ---- round done--------
I/jxcore-log( 7306): 
I/jxcore-log( 7306): startWithNextDevice
I/jxcore-log( 7306): 
I/jxcore-log( 7306): do fake peer & start
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:57:57.297Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:57:57.297Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:57:57.297Z SendDataConnector.js: do connect now
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 7306): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): connect: [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 7306): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
W/bt-rfcomm( 3791): rfc_port_closed
W/bt-btif ( 3791): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 872)
W/LGMDMUISystemServiceAdapter( 7306): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3791): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f895c7873c51  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): Requested New Role: 0
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=213 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x0045
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18,
,E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
E/bt-btif ( 3791): Do not find the bg connection mask for the remote device
D/WifiServerServiceExt( 1040): Connected BT device : -2
,I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
D/btif_config_util( 3791): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4616): Bluetooth Device Name: Nexus 5
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=214 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1040):    returned b60376a0
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
,D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=215 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: f8-95-c7-87-3c-51
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010c000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010c000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=216 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010c000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=217 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=218 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/bt-btm  ( 3791): btm_acl_created hci_handle=10 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=10 link_role=1  transport=1
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 0
,W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=759829015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=759829015 [*alarm*], flags=0x0
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2993] from screen [on:0 period:566134614] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566134617] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=219 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: f8-95-c7-87-3c-51
W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24841
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=220 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=221 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=222 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1040):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1040):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pServi,ce( 1040):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-10ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139287 arg2=95 target=com.android.internal.util.StateMach,ine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
E/WifiServerServiceExt( 1040): No p2p device connected
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-12ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDe,viceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=223 dispatchEvent: P2P-SERV-DISC-REQ 2462 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec,
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: f8-95-c7-87-3c-51
,W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: f8-95-c7-87-3c-51
W/bt-btif ( 3791): info:x10
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3791): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3791): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3791): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 1
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=224 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 12
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3791): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=225 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 14
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:566137634] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566137637] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0049,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0049,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3791): process_service_search_attr_rsp
,W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x0046
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: f895c7873c51  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 21
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=226 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=227 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001060a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001060a436f72646f7661703270c00c000c01]
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=228 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 7 120001090a436f72646f7661703270c00c000c01
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3791): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:566140647] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:566140653] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3791): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3791): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
,W/LGBluetoothUtils( 7421): showUnbondMessage: Not displaying any message for reason: 0
,E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x004a,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x004a,PSM: 3,peer MTU present: 0,peer MTU: 1691
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onSocketConnected: [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51] (thread ID: 872)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 872)
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1 count:1
,W/bt-btif ( 3791): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3791): bta_dm_pm_ssr:2, lat:1200
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesWritten: 63 bytes successfully written (thread ID: 873)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Outgoing connection initialized (*handshake* thread ID: 873)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Exiting thread (thread ID: 872)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Entering thread (ID: 873)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesRead: Read 63 bytes successfully (thread ID: 873)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Handshake succeeded with [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onHandshakeSucceeded: [F8:95:C7:87:3C:51 G4-1] (thread ID: 872)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Exiting thread (ID: 873)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnected: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 G4-1]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7306): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 7306): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7306): Entering thread (ID: 874)
D/io.jxcore.node.OutgoingSocketThread( 7306): Server socket local port: 39783
I/io.jxcore.node.OutgoingSocketThread( 7306): Now accepting connections...
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=229 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 7306): onListeningForIncomingConnections: Outgoing connection is using port 39783 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 7306): 2016-01-08T14:58:07.390Z SendDataConnector.js: CLIENT connected to 39783, error: null
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:07.391Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7306): 
I/io.jxcore.node.OutgoingSocketThread( 7306): Incoming data from address: /127.0.0.1, port: 39783
D/io.jxcore.node.OutgoingSocketThread( 7306): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7306): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7306): Exiting thread (ID: 874)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 876, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:58:07.408Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7306): 
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 875, name: Sender)
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=230 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:566143664] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:566143669] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=231 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=598346 (in 6003 ms)
,D/btif_config_util( 3791): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=232 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1f0c1b4a type 2 when 593247 android} when 593247
,I/BooksSync( 7184): Starting books sync
,D/BooksSync( 7184): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
,W/ApiaryClient( 7184): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983179690699600576&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=233 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7306): 2016-01-08T14:58:12.256Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7306): 
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42210
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 44:80:eb:7b:5a:07 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 44:80:eb:7b:5a:07 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=234 dispatchEvent: P2P-SERV-DISC-REQ 2462 44:80:eb:7b:5a:07 0 7 120001070a436f72646f7661703270c00c000c01
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:566146683] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566146686] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/ThermalEngine(  329): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
,W/ApiaryClient( 7184): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983179690699600576&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
,I/jxcore-log( 7306): 2016-01-08T14:58:14.082Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=235 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
E/BooksAccountManager( 7184): Authentication error
E/BooksAccountManager( 7184): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7184): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7184): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7184): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7184): null auth token
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
,D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{1a1e53e4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ProcessCpuTracker( 1040): Skipping unknown process pid 8109
,W/ProcessCpuTracker( 1040): Skipping unknown process pid 8110
W/ProcessCpuTracker( 1040): Skipping unknown process pid 8112
W/ProcessCpuTracker( 1040): Skipping unknown process pid 8113
W/ProcessCpuTracker( 1040): Skipping unknown process pid 8114
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=236 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 597245917225; DSPS: 19712397; Offset : -4343976715
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1040):  ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:566149700] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState !CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566149703] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1040): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 2675): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5]
D/WifiMonitor( 1040): Event [P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=237 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: null
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 0
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 0
D/LGWifiP2pService( 1040):  status: 4
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: null
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 0
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 0
D/LGWifiP2pService( 1040):  status: 4
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( ,7306): Service request added successfully
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:20430
I/jxcore-log( 7306): 2016-01-08T14:58:15.953Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7306): 
,W/ApiaryClient( 7184): Error response from books API: {
W/ApiaryClient( 7184):  "error": {
W/ApiaryClient( 7184):   "errors": [
W/ApiaryClient( 7184):    {
W/ApiaryClient( 7184):     "domain": "global",
W/ApiaryClient( 7184):     "reason": "required",
W/ApiaryClient( 7184):     "message": "Login Required",
W/ApiaryClient( 7184):     "locationType": "header",
W/ApiaryClient( 7184):     "location": "Authorization"
W/ApiaryClient( 7184):    }
W/ApiaryClient( 7184):   ],
W/ApiaryClient( 7184):   "code": 401,
W/ApiaryClient( 7184):   "message": "Login Required"
W/ApiaryClient( 7184):  }
W/ApiaryClient( 7184): }
W/ApiaryClient( 7184): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983179690699600576&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7184): Headers:
W/ApiaryClient( 7184): accept-encoding: [gzip]
W/ApiaryClient( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7184): gdata-version: 2
,W/ActivityManager( 1040): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=598346 (in 4 ms)
,D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=598346 (1 ms ago)
,I/PowerManagerService( 1040): Going to sleep due to screen timeout (uid 1000)...
,D/KnockOnPowerController( 1040): [updateScreenState] screen on = false
D/KnockOnPowerController( 1040): disable proximity sensor
D/KnockOnPowerController( 1040): enable proximity sensor
I/SensorManager( 1040): registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@28b43198] bycom.android.server.power.ProximitySensorListener.enable():107
I/sensors_hal_Ctx( 1040): batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM( 1040): batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM( 1040): batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
I/sensors_hal_Ctx( 1040): activate: handle is 70, enable
V/sensors_hal_Ctx( 1040): activate sensors is c00000000000
D/sensors_hal_KnockOnProx( 1040): enable: handle=70
I/sensors_hal_SAM( 1040): sendEnableReq:sensor() Sending enable to svc no:33
D/sensors_hal_Util( 1040): waitForResponse: timeout=1000
V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 2, txn Id 0
D/sensors_hal_KnockOnProx( 1040): processResp: Received SNS_SAM_KNOCK_ENABLE_RESP_V01
D/sensors_hal_KnockOnProx( 1040): enable: Received response: 0
I/KnockOnPowerController( 1040): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=598346 (29 ms ago)
W/ContextImpl( 1040): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.power.PowerManagerServiceEx$3.run:1231 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/SensorManager( 1040): removeAllSensors() [Sensor: Motion Accel] bycom.android.internal.policy.impl.WindowOrientationListener.disable():166
I/sensors_hal_Ctx( 1040): activate: handle is 46, disable
V/sensors_hal_Ctx( 1040): activate sensors is 800000000000
D/sensors_hal_LP2( 1040): enable: handle=46
D/sensors_hal_LP2( 1040): enable: Disabling sensor handle=46
I/sensors_hal_SAM( 1040): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/KeyguardViewMediator( 1459): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1459): notifyScreenOffLocked
D/SmartCoverViewMediator( 1405): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1405): notifyScreenOffLocked
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{3bbc84a4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,D/KeyguardViewMediator( 1459): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1459): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1459): unregisterProximitySensor
D/StatusBarWindowView( 1459): onScreenTurnedOff why = 3
V/KeyguardStatusView( 1459): Disable transport text marquee
D/SmartCoverViewMediator( 1405): handleNotifyScreenOFF
I/QuickCircle( 1405): onScreenTurnedOff
D/LgeQuickCoverOverlayWindow( 1405): updateVisibility:hideSmartLighting
D/LgeQuickCoverOverlayWindow( 1405): updateVisibility:hideNotification
D/QuickCircleViewManager( 1405): applyCoverState:1
D/QuickCircleViewManager( 1405): getState: 0
D/QuickCircleViewManager( 1405): applyCoverState:LCD Off -> go to lock
D/QuickCircleViewManager( 1405): getState: 0
I/PowerManagerService( 1040): Sleeping (uid 1000)...
D/PowerManagerServiceEx( 1040): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=598346 (57 ms ago)
E/WifiStateMachine( 1040):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 1040):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 1040):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 1040):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
,V/AudioFlinger(  320): setParameters(): io 0, keyvalue screen_state=off, calling pid 1040
D/audio_hw_primary(  320): adev_set_parameters: enter: screen_state=off
V/voice   (  320): voice_set_parameters: enter: screen_state=off
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: exit
V/voice   (  320): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  320): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  320): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  320): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  320): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  320): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  320): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine( 1040):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 1040):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 1040):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
D/WifiController( 1040): CMD_SCREEN_OFF 
D/WifiController( 1040): shouldWifiStayAwake TRUE
E/WifiStateMachine( 1040):  ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,E/WifiStateMachine( 1040):  ConnectModeState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2( 1040): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/Sensors (  496): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM( 1040): SAMSensor_sensor1_cb: msg_type 2, Sn 33, msg Id 5, txn Id 0
D/sensors_hal_KnockOnProx( 1040): processInd: SNS_SAM_KNOCK_REPORT_IND_V01
D/sensors_hal_KnockOnProx( 1040): processInd: handle 70, count=1
I/sensors_hal_KnockOnProx( 1040): processInd : knock-on state changed - FAR
D/sensors_hal_Ctx( 1040): poll:polldata:1, sensor:70, type:499898103, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx( 1040): poll: count: 36
D/sensors_hal_Util( 1040): waitForResponse: timeout=0
D/KnockOnPowerController( 1040): proximity onSensorChanged : proximity = 1
I/KnockOnPowerController( 1040): current mode = 1  value = 1 1
I/KnockOnPowerController( 1040): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1459): onReceive = android.intent.action.SCREEN_OFF
,I/LEDService( 1953): getCurrentHighestLGLedRecord() start. size = 1
D/qdlights( 1953): set_light_notifications: 3,0,0,0,3
D/qdlights( 1953): [pattern_id] = 0
D/VolumeVibrator( 1953): clear
D/qdlights( 1953): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1953): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1929): action : android.intent.action.SCREEN_OFF
I/LEDService( 1953): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1953): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1953): updateLightsLocked : turn on led
,D/qdlights( 1953): set_light_notifications: 3,4,0,0,1
D/qdlights( 1953): [pattern_id] = 4
D/LEDHandler( 1953): RESTART MSG
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
,V/PhoneApp( 1859): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
I/[LGHome]EVENT( 2075): [Launcher.java:1836:onReceive()]Screen Off
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1040): ACTION_SCREEN_OFF
D/LIA_MrGDBLogger_AppUsageDetector( 3732): [dreamwood]ACTION_SCREEN_OFF !!!
D/LIA_MrGDBLogger_AppUsageDetector( 3732): [dreamwood]case 9 : com.test.thalitest
,D/LIA_MrGDBLogger_AppUsageDetector( 3732): [dreamwood]scheduledExecutorService is stopped
,D/LIA_MrGDBLogger_LoggerThread( 3732): [dreamwood]App Usage Logging
D/AppCleanupService( 5138): android.intent.action.SCREEN_OFF
D/AppCleanupService( 5138): AppUsageStatsSaveTask
E/LibSecureUISvc( 1976): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=238 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
,D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1040):    returned b60376a0
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=239 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
E/BooksSync( 7184): Soft error: 
E/BooksSync( 7184): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983179690699600576&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7184): Headers:
E/BooksSync( 7184): accept-encoding: [gzip]
E/BooksSync( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7184): gdata-version: 2
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7184): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7184): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7184): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7184): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7184): {
E/BooksSync( 7184):  "error": {
E/BooksSync( 7184):   "errors": [
E/BooksSync( 7184):    {
E/BooksSync( 7184):     "domain": "global",
E/BooksSync( 7184):     "reason": "required",
E/BooksSync( 7184):     "message": "Login Required",
E/BooksSync( 7184):     "locationType": "header",
E/BooksSync( 7184):     "location": "Authorization"
E/BooksSync( 7184):    }
E/BooksSync( 7184):   ],
E/BooksSync( 7184):   "code": 401,
E/BooksSync( 7184):   "message": "Login Required"
E/BooksSync( 7184):  }
E/BooksSync( 7184): }
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7184): 	... 8 more
,E/BooksSync( 7184): Sync error
E/BooksSync( 7184): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7184): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983179690699600576&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7184): Headers:
E/BooksSync( 7184): accept-encoding: [gzip]
E/BooksSync( 7184): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7184): gdata-version: 2
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7184): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7184): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7184): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7184): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7184): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7184): {
E/BooksSync( 7184):  "error": {
E/BooksSync( 7184):   "errors": [
E/BooksSync( 7184):    {
E/BooksSync( 7184):     "domain": "global",
E/BooksSync( 7184):     "reason": "required",
E/BooksSync( 7184):     "message": "Login Required",
E/BooksSync( 7184):     "locationType": "header",
E/BooksSync( 7184):     "location": "Authorization"
E/BooksSync( 7184):    }
E/BooksSync( 7184):   ],
E/BooksSync( 7184):   "code": 401,
E/BooksSync( 7184):   "message": "Login Required"
E/BooksSync( 7184):  }
E/BooksSync( 7184): }
E/BooksSync( 7184): 
E/BooksSync( 7184): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7184): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7184): 	... 8 more
I/BooksSync( 7184): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 572168, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/DisplayManagerService( 1040): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1040): Display changed displayId=0
D/SurfaceFlinger(  282): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  282): hwc_blank: Blanking display: 0
,D/DSDPConnection( 1859): Display #0 changed.
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=240 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8550
,I/jxcore-log( 7306): 2016-01-08T14:58:17.285Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7306): 
,I/qdhwcomposer(  282): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  282): hwc_blank: Done blanking display: 0
,D/SurfaceControl( 1040): Excessive delay in setPowerMode(): 278ms
I/QCOM PowerHAL( 1040): Got set_interactive hint
D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010d000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010d000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=241 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 5700010d000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
E/ThermalEngine(  329): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 578000000
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027],
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=242 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
I/Sensors (  496): sns_pwr.c(301):releasing wakelock
,W/bt-l2cap( 3791): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
,E/WifiStateMachine( 1040):  ConnectedState CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:566152714] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:566152717] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,W/bt-btm  ( 3791): btm_acl_created hci_handle=11 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=11 link_role=0  transport=1
W/bt-btif ( 3791): info:x10
W/bt-btm  ( 3791): BTM_SwitchRole BDA: f8-95-c7-87-3c-51
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3791): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
D/WifiServerServiceExt( 1040): Connected BT device : -1
,D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 2
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4616): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: f8-95-c7-87-3c-51
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a3e0 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 7306): 2016-01-08T14:58:20.134Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7306): 
,W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-76-27
,W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-76-27
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x0048  Result: 0  Status: 0  BDA: 08eca9507627  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x0048
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/jxcore-log( 7306): 2016-01-08T14:58:20.545Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7306): 
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3791): check_cod: remote_cod = 0x5a020c
W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
W/bt-l2cap( 3791): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 3791): btm_acl_created hci_handle=12 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=12 link_role=0  transport=1
,I/jxcore-log( 7306): 2016-01-08T14:58:21.140Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7306): 
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3791): Failed to remove device: 08:EC:A9:50:76:27
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
,W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
,W/LGBluetoothUtils( 7421): showUnbondMessage: Not displaying any message for reason: 0
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x0049  Result: 0  Status: 0  BDA: 08eca9507627  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0049,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0049,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
,W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3791): new conn_srvc id:26, app_id:255
W/bt-btif ( 3791): new conn_srvc id:26, app_id:255 count:2
W/bt-btif ( 3791): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3791): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Incoming connection initialized (thread ID: 877)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Entering thread (ID: 877)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): onBytesRead: Read 81 bytes successfully (thread ID: 877)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Got valid identity from [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): onBytesWritten: 63 bytes successfully written (thread ID: 877)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): removeThreadFromList: Removing thread with ID 877
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Handshake thread disposed (thread ID: 877)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onIncomingConnectionConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Exiting thread (ID: 877)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], created successfully
D/io.jxcore.node.ConnectionHelper( 7306): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 7306): Entering thread (ID: 878)
I/io.jxcore.node.IncomingSocketThread( 7306): Local host address: localhost/127.0.0.1, port: 60102
D/io.jxcore.node.IncomingSocketThread( 7306): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7306): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7306): Exiting thread (ID: 878)
,I/jxcore-log( 7306): 2016-01-08T14:58:21.469Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7306): 
,D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 879, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 880, name: Receiver)
D/KeyguardViewMediator( 1459): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2c87a24d type 2 when 603372 com.android.systemui} when 603372
,D/KeyguardUpdateMonitor( 1459): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1459): doKeyguard: not showing because lockscreen is off
I/jxcore-log( 7306): 2016-01-08T14:58:21.685Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7306): 
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
W/bt-btif ( 3791): info:x10
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3791): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3791): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3791): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 3
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
,W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=0
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 7306): 2016-01-08T14:58:22.222Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7306): 
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x004a  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x004a,Remote CID: 0x004c,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x004a,Remote CID: 0x004c,PSM: 1,peer MTU present: 0,peer MTU: 672
I/jxcore-log( 7306): 2016-01-08T14:58:22.678Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:22.698Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:22.699Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 7306): 
W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x004a
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/jxcore-log( 7306): 2016-01-08T14:58:22.743Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7306): 2016-01-08T14:58:22.823Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:22.853Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:22.870Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:22.948Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:22.960Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:22.965Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.026Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.050Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.078Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.129Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.147Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 7306): 
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3791): check_cod: remote_cod = 0x5a020c
,I/jxcore-log( 7306): 2016-01-08T14:58:23.188Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 7306): 
,W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
I/jxcore-log( 7306): 2016-01-08T14:58:23.201Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 7306): 
,W/BluetoothEventManager( 7421): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
I/jxcore-log( 7306): 2016-01-08T14:58:23.275Z SendDataTCPServer.js: TCP/IP server has received 17102 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.305Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.317Z SendDataTCPServer.js: TCP/IP server has received 19082 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.402Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.419Z SendDataTCPServer.js: TCP/IP server has received 21062 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:23.474Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.496Z SendDataTCPServer.js: TCP/IP server has received 23042 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.508Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 7306): 
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=243 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7306): 2016-01-08T14:58:23.575Z SendDataTCPServer.js: TCP/IP server has received 25022 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.591Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.603Z SendDataTCPServer.js: TCP/IP server has received 27002 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.619Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.644Z SendDataTCPServer.js: TCP/IP server has received 28982 bytes of data
I/jxcore-log( 7306): 
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3791): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3791): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/jxcore-log( 7306): 2016-01-08T14:58:23.722Z SendDataTCPServer.js: TCP/IP server has received 30962 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.734Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 7306): 
I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 7421): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
W/LGBluetoothUtils( 7421): showUnbondMessage: Not displaying any message for reason: 0
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
,I/jxcore-log( 7306): 2016-01-08T14:58:23.768Z SendDataTCPServer.js: TCP/IP server has received 32942 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.814Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:23.916Z SendDataTCPServer.js: TCP/IP server has received 34922 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=244 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=245 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7306): 2016-01-08T14:58:23.975Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 7306): 
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-10ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-10ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-10ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/jxcore-log( 7306): 2016-01-08T14:58:24.010Z SendDataTCPServer.js: TCP/IP server has received 38882 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.022Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.027Z SendDataTCPServer.js: TCP/IP server has received 40862 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.035Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.038Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7306): 
I/jxcore-log( 7306): oneRoundDownNow
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.038Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.038Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7306): 
D/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.IncomingSocketThread( 7306): close
D/io.jxcore.node.IncomingSocketThread( 7306): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 876
D/io.jxcore.node.IncomingSocketThread( 7306): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 875
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 875, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7306): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 876, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-btm  ( 3791): BTM_SwitchRole BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 875, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 876, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:58:24.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 7306): 
I/jxcore-log( 7306): ---- round done--------
I/jxcore-log( 7306): 
I/jxcore-log( 7306): startWithNextDevice
I/jxcore-log( 7306): 
I/jxcore-log( 7306): do fake peer & start
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.051Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.051Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.051Z SendDataConnector.js: do connect now
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): connect: [7C:F9:0E:37:96:AB A5-1]
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x004b  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Trying to start connecting to null in a,ddress 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 7306): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 881)
I/jxcore-log( 7306): 2016-01-08T14:58:24.067Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 7306): 
W/LGMDMUISystemServiceAdapter( 7306): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3791): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3791): [BTUI] connectSocket FD=86 mFd=85
I/jxcore-log( 7306): 2016-01-08T14:58:24.480Z SendDataTCPServer.js: TCP/IP server has received 42842 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.503Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 7306): 
,W/bt-rfcomm( 3791): rfc_port_closed
W/bt-btif ( 3791): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
I/jxcore-log( 7306): 2016-01-08T14:58:24.515Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.523Z SendDataTCPServer.js: TCP/IP server has received 46802 bytes of data
I/jxcore-log( 7306): 
,W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x0047
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=246 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
I/jxcore-log( 7306): 2016-01-08T14:58:24.690Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.708Z SendDataTCPServer.js: TCP/IP server has received 48782 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.712Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 7306): 
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
W/bt-btm  ( 3791): BTM: Local device role : 0x01
W/bt-btm  ( 3791): BTM: RemBdAddr: e0db1014e2c0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 7306): 2016-01-08T14:58:24.840Z SendDataTCPServer.js: TCP/IP server has received 50762 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.865Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.888Z SendDataTCPServer.js: TCP/IP server has received 52742 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7306): 2016-01-08T14:58:24.933Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:24.956Z SendDataTCPServer.js: TCP/IP server has received 54722 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:24.971Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.005Z SendDataTCPServer.js: TCP/IP server has received 56702 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.088Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.109Z SendDataTCPServer.js: TCP/IP server has received 58682 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.162Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.223Z SendDataTCPServer.js: TCP/IP server has received 60662 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.241Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.316Z SendDataTCPServer.js: TCP/IP server has received 62642 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:25.423Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=247 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7306): 2016-01-08T14:58:26.075Z SendDataTCPServer.js: TCP/IP server has received 64622 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.135Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.151Z SendDataTCPServer.js: TCP/IP server has received 66602 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:26.189Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.204Z SendDataTCPServer.js: TCP/IP server has received 68582 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.298Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.311Z SendDataTCPServer.js: TCP/IP server has received 70562 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.330Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.414Z SendDataTCPServer.js: TCP/IP server has received 72542 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.441Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.461Z SendDataTCPServer.js: TCP/IP server has received 74522 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.516Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.527Z SendDataTCPServer.js: TCP/IP server has received 76502 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.728Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.762Z SendDataTCPServer.js: TCP/IP server has received 78482 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.783Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=248 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7306): 2016-01-08T14:58:26.922Z SendDataTCPServer.js: TCP/IP server has received 80462 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.941Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:26.978Z SendDataTCPServer.js: TCP/IP server has received 82442 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.025Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7306): 2016-01-08T14:58:27.095Z SendDataTCPServer.js: TCP/IP server has received 84422 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.267Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.359Z SendDataTCPServer.js: TCP/IP server has received 86402 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.385Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.411Z SendDataTCPServer.js: TCP/IP server has received 88382 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.509Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.536Z SendDataTCPServer.js: TCP/IP server has received 90362 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.555Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.700Z SendDataTCPServer.js: TCP/IP server has received 92342 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.789Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:27.942Z SendDataTCPServer.js: TCP/IP server has received 94322 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=249 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7306): 2016-01-08T14:58:28.080Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:28.096Z SendDataTCPServer.js: TCP/IP server has received 96302 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:28.168Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 7306): 
,D/btif_config_util( 3791): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 7306): 2016-01-08T14:58:28.263Z SendDataTCPServer.js: TCP/IP server has received 98282 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:28.301Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7306): 2016-01-08T14:58:28.339Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7306): 
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x004b,Remote CID: 0x004d,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-btm  ( 3791): BTM_SwitchRole BDA: e0-db-10-14-e2-c0
,W/bt-btm  ( 3791): Requested New Role: 0
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3791): invalid rfc slot id: 7,
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 880, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7306): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 878
D/io.jxcore.node.IncomingSocketThread( 7306): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 880
D/io.jxcore.node.IncomingSocketThread( 7306): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 879
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 879, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7306): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 879, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 880, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:58:28.468Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7306): 
,E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1040): Connected BT device : -2
I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 2
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4616): Bluetooth Device Name: G4-1
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x004b,Remote CID: 0x004d,PSM: 3,peer MTU present: 0,peer MTU: 1691
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=250 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=251 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=252 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1040):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-5ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-12ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1040): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState add service request,
D/WifiP2pManager( 7306): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=253 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b60376a0
,D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1953): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=254 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=255 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1040):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 392
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0,
W/bt-btif ( 3791): new conn_srvc id:26, app_id:255
W/bt-btif ( 3791): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3791): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3791): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Incoming connection initialized (thread ID: 882)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Entering thread (ID: 882)
W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x0049
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 1
,W/bt-sdp  ( 3791): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3791): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3791): invalid rfc slot id: 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 881)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Maximum number of allowed retries (0) reached, giving up... (thread ID: 881)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 881)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): shutdownAndRemoveClientThread: Shutting down thread with ID 881
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Exiting thread (thread ID: 881)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB A5-1]
I/jxcore-log( 7306): 2016-01-08T14:58:34.020Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB A5-1] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:34.021Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB A5-1] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:34.023Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7306): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7306): setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): shutdown (thread ID: 881)
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=256 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): onBytesRead: Read 66 bytes successfully (thread ID: 882)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Got valid identity from [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): onBytesWritten: 63 bytes successfully written (thread ID: 882)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): removeThreadFromList: Removing thread with ID 882
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Handshake thread disposed (thread ID: 882)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Exiting thread (ID: 882)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnected: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 Note4-1]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 Note4-1], created successfully
D/io.jxcore.node.ConnectionHelper( 7306): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 7306): Entering thread (ID: 884)
I/io.jxcore.node.IncomingSocketThread( 7306): Local host address: localhost/127.0.0.1, port: 60102
D/io.jxcore.node.IncomingSocketThread( 7306): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7306): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7306): Exiting thread (ID: 884)
I/jxcore-log( 7306): 2016-01-08T14:58:34.803Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7306): 
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 886, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 885, name: Sender)
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 617247622530; DSPS: 20367813; Offset : -4343980055
,I/jxcore-log( 7306): 2016-01-08T14:58:35.989Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:35.993Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:36.007Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:36.075Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:36.141Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:36.165Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:36.177Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:36.234Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:36.243Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 7306): 
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a218 rs_disc_pending=0
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
I/jxcore-log( 7306): 2016-01-08T14:58:36.528Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 7306): 
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 3
E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1040): Connected BT device : -3
I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
I/jxcore-log( 7306): 2016-01-08T14:58:36.567Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 7306): 
,D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4616): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 7306): 2016-01-08T14:58:36.726Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.031Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.041Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.171Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.365Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.464Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.534Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.610Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.695Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.720Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.760Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.774Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:37.777Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.793Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:37.796Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:37.807Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.813Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.910Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.930Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.941Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:37.944Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:37.950Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:37.956Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:37.988Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.003Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.009Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.012Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.020Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.062Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.075Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.083Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.090Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.097Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.102Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.107Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.112Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.117Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.122Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.159Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.168Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.175Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.213Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.222Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.226Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.240Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.268Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.273Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.280Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.289Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.295Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.302Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.308Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.338Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.363Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.368Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.372Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.378Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.388Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:38.392Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.399Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.403Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.442Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:38.461Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7306): 
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
,E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a050 rs_disc_pending=0
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3791): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 886, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 7306): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 884
D/io.jxcore.node.IncomingSocketThread( 7306): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 886
D/io.jxcore.node.IncomingSocketThread( 7306): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 885
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 885, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7306): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7306): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 885, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 886, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:58:38.740Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7306): 
,W/bt-rfcomm( 3791): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x004b
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
W/bt-rfcomm( 3791): RFCOMM_DisconnectInd LCID:0x4b
I/jxcore-log( 7306): 2016-01-08T14:58:39.024Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:39.025Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=257 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1dc1c102 type 2 when 623275 android} when 623275
,I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=258 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1040): Connected BT device : -4
,I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4616): Bluetooth Device Name: Note4-1
,D/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
,I/jxcore-log( 7306): 2016-01-08T14:58:44.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:44.050Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:44.050Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:44.051Z SendDataConnector.js: do connect now
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): connect: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 7306): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 887)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7306): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/LGMDMUISystemServiceAdapter( 7306): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3791): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=14 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=14 link_role=1  transport=1
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: 7c-f9-0e-37-96-ab
,W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: 7c-f9-0e-37-96-ab
W/bt-btif ( 3791): info:x10
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3791): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3791): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3791): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x004d,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x004d,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3791): process_service_search_attr_rsp
W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x004d
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 21
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 1
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3791): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 7421): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3791): Failed to remove device: 7C:F9:0E:37:96:AB
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
I/BluetoothBondStateMachine( 3791): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x004e,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x004e,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
E/BluetoothEventManager( 7421): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
,W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3791): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3791): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onSocketConnected: [7C:F9:0E:37:96:AB A5-1] (thread ID: 887)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 887)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesWritten: 63 bytes successfully written (thread ID: 888)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Outgoing connection initialized (*handshake* thread ID: 888)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Exiting thread (thread ID: 887)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Entering thread (ID: 888)
W/LGBluetoothUtils( 7421): showUnbondMessage: Not displaying any message for reason: 0
E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesRead: Read 63 bytes successfully (thread ID: 888)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Handshake succeeded with [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onHandshakeSucceeded: [7C:F9:0E:37:96:AB A5-1] (thread ID: 887)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Exiting thread (ID: 888)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnected: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7306): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 7306): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7306): Entering thread (ID: 889)
D/io.jxcore.node.OutgoingSocketThread( 7306): Server socket local port: 41826
I/io.jxcore.node.OutgoingSocketThread( 7306): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7306): onListeningForIncomingConnections: Outgoing connection is using port 41826 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 7306): 2016-01-08T14:58:46.236Z SendDataConnector.js: CLIENT connected to 41826, error: null
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:46.237Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7306): 
I/io.jxcore.node.OutgoingSocketThread( 7306): Incoming data from address: /127.0.0.1, port: 41826
D/io.jxcore.node.OutgoingSocketThread( 7306): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7306): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7306): Exiting thread (ID: 889)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 891, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 890, name: Sender)
I/jxcore-log( 7306): 2016-01-08T14:58:46.268Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7306): 
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3dd9fa13 type 2 when 628567 com.google.android.gms} when 628567
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61848
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67342
,I/jxcore-log( 7306): 2016-01-08T14:58:47.461Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7306): 
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58148
,I/jxcore-log( 7306): 2016-01-08T14:58:47.503Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7306): 
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48248
,I/jxcore-log( 7306): 2016-01-08T14:58:47.591Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7306): 
W/ProcessCpuTracker( 1040): Skipping unknown process pid 8153
,W/ProcessCpuTracker( 1040): Skipping unknown process pid 8156
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38348
,I/jxcore-log( 7306): 2016-01-08T14:58:47.660Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7306): 
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28448
,I/jxcore-log( 7306): 2016-01-08T14:58:47.795Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7306): 
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18548
,I/jxcore-log( 7306): 2016-01-08T14:58:47.973Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7306): 
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7658
,I/jxcore-log( 7306): 2016-01-08T14:58:48.286Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:48.459Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:48.466Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:48.549Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:58:48.550Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7306): 
I/jxcore-log( 7306): oneRoundDownNow
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:48.552Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:48.552Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7306): 
D/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 7306): close
,D/io.jxcore.node.OutgoingSocketThread( 7306): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 891,
D/io.jxcore.node.OutgoingSocketThread( 7306): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 890
,D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 890, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7306): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 891, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 890, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 891, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:58:48.585Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7306): 
I/jxcore-log( 7306): ---- round done--------
I/jxcore-log( 7306): 
I/jxcore-log( 7306): startWithNextDevice
I/jxcore-log( 7306): 
I/jxcore-log( 7306): do fake peer & start
I/jxcore-log( 7306): 
I/jxcore-log( 7306): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:48.587Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:48.588Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:48.588Z SendDataConnector.js: do connect now
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 7306): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): connect: [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 7306): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 892)
,W/LGMDMUISystemServiceAdapter( 7306): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7306): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3791): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11b166  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a5a8 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-b1-66
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=16 link_role=1  transport=1
,W/bt-btm  ( 3791): btm_acl_created hci_handle=16 link_role=1  transport=1
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3791): btm_read_remote_version_complete: BDA: 34-fc-ef-11-b1-66
W/bt-btm  ( 3791): btm_read_remote_version_complete lmp_version 6 manufacturer 15 lmp_subversion 24841,
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3791): btm_process_remote_ext_features_page 0: BDA: 34-fc-ef-11-b1-66
,W/bt-btm  ( 3791): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3791): btm_process_remote_ext_features_page 1: BDA: 34-fc-ef-11-b1-66
,W/bt-btif ( 3791): info:x10
D/        ( 3791): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
W/bt-btm  ( 3791): BTM_SwitchRole BDA: 34-fc-ef-11-b1-66
W/bt-btm  ( 3791): Requested New Role: 0
W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
E/BluetoothRemoteDevices( 3791): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3791): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x004f,Remote CID: 0x004e,PSM: 1,our MTU present:1,our MTU:672
D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL connected => AclLinkCount = 2
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-b1-66
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a770 rs_disc_pending=1
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x004f,Remote CID: 0x004e,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-sdp  ( 3791): process_service_search_attr_rsp
,W/bt-l2cap( 3791): L2CA_DisconnectReq()  CID: 0x004f
,W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3791): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 34fcef11b166  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 21
,D/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 3791): check_cod: remote_cod = 0x5a020c
W/LGMDMUISystemServiceAdapter( 3791): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3791): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3791): Entering PendingCommandState State
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 7421): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 11
I/BluetoothBondStateMachine( 3791): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothRemoteDevices( 3791): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3791): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3791): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3791): StableState(): Entering Off State
W/BluetoothEventManager( 7421): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 7421): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
W/LGBluetoothUtils( 7421): showUnbondMessage: PROPERTY_PAIR_RETRY: 0
D/LGBluetoothUtils( 7421): [BTUI] [SET] service.btui.gap.pairByLocal : 0
W/LGBluetoothUtils( 7421): showUnbondMessage: Not displaying any message for reason: 0
,E/LGBluetoothEventManager( 7421): [BTUI] onReceive()... android.bluetooth.device.action.BOND_STATE_CHANGED: bondState = 10
D/LGBluetoothUtils( 7421): [BTUI] BOND_NONE == reason(0) [failed:1 / rejected:2 / canceled:3 / down:4 / timeout:6 / rem_canceled:8 / removed:9]
W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: 34fcef11b166  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
,W/bt-l2cap( 3791): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x004f,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x004f,PSM: 1,peer MTU present: 0,peer MTU: 256
W/bt-l2cap( 3791): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-l2cap( 3791): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3791): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3791): L2CA_ErtmConnectRsp()  CID: 0x0041  Result: 0  Status: 0  BDA: 34fcef11b166  p_ertm_info:0x00000000
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1
W/bt-btif ( 3791): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3791): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3791): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onSocketConnected: [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66] (thread ID: 892)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 892)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesWritten: 63 bytes successfully written (thread ID: 893)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Outgoing connection initialized (*handshake* thread ID: 893)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Exiting thread (thread ID: 892)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Entering thread (ID: 893)
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3791): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3791): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3791): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 1,peer MTU present: 0,peer MTU: 256
W/bt-rfcomm( 3791): rfc_port_closed
W/bt-btif ( 3791): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
I/jxcore-log( 7306): timeout now
I/jxcore-log( 7306): 
I/jxcore-log( 7306): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 7306): 
I/jxcore-log( 7306): sendReportNow
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): done, now sending data to server
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:51.063Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7306): 
D/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7306): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 7306): 2016-01-08T14:58:51.064Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 7306): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): onBytesRead: Read 66 bytes successfully (thread ID: 893)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7306): Handshake succeeded with [34:FC:EF:11:B1:66 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onHandshakeSucceeded: [34:FC:EF:11:B1:66 Nexus 5] (thread ID: 892)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7306): Exiting thread (ID: 893)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): onConnected: [34:FC:EF:11:B1:66 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing connection to peer [34:FC:EF:11:B1:66 Nexus 5]
D/io.jxcore.node.ConnectionHelper( 7306): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 7306): notifyPeerAvailability: Peer [34:FC:EF:11:B1:66 Nexus 5] is available
I/io.jxcore.node.ConnectionHelper( 7306): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:B1:66 Nexus 5], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7306): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 7306): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7306): Entering thread (ID: 894)
,D/io.jxcore.node.OutgoingSocketThread( 7306): Server socket local port: 41258
I/io.jxcore.node.OutgoingSocketThread( 7306): Now accepting connections...
W/bt-btm  ( 3791): btm_acl_role_changed: BDA: 34-fc-ef-11-b1-66
W/bt-btm  ( 3791): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3791): tBTM_SEC_DEV:0xa037a770 rs_disc_pending=0
W/bt-btif ( 3791): bta_dm_check_av:0
,W/bt-btif ( 3791): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 7306): onListeningForIncomingConnections: Outgoing connection is using port 41258 (peer ID: 34:FC:EF:11:B1:66)
,I/jxcore-log( 7306): 2016-01-08T14:58:51.410Z SendDataConnector.js: CLIENT connected to 41258, error: null
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:58:51.411Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7306): 
,W/bt-btm  ( 3791): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-l2cap( 3791): L2CA_DisconnectRsp()  CID: 0x0041
W/bt-l2cap( 3791): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/io.jxcore.node.OutgoingSocketThread( 7306): Incoming data from address: /127.0.0.1, port: 41258
,D/io.jxcore.node.OutgoingSocketThread( 7306): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7306): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7306): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7306): Exiting thread (ID: 894)
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 896, name: Receiver)
I/jxcore-log( 7306): 2016-01-08T14:58:51.446Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7306): 
D/io.jxcore.node.StreamCopyingThread( 7306): Entering thread (ID: 895, name: Sender)
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61130
,E/bt-btm  ( 3791): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3791): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1040): Connected BT device : -5
,I/BluetoothMapService( 3791): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3791): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3791): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3791): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3791): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3791): state: -2147483648
D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:49250
,D/LGBluetoothPowerSaveListener( 7421): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4616): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4616): Bluetooth Device Name: A5-1
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:37370
,D/btif_config_util( 3791): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:25490
,D/        ( 3791): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13610
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 637249294188; DSPS: 21023228; Offset : -4343986864
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: RESTARTING
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2675): P2P-FIND-STOPPED 
D/WfdsMonitor( 1953): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=259 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=759829015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=759829015 [*alarm*], flags=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): Start timer timeout, starting now...
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=260 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,I/wpa_supplicant( 2675): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=261 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=262 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1040):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1040):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 4488
D/LGWifiP2pService( 1040):  grpcapab: 0
D/LGWifiP2pService( 1040):  devcapab: 37
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-6ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-8ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-8ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-8ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
,D/LGWifiP2pService( 1040): InactiveState{ when=-7ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-7ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-7ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): restart: Restarting...
D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-12ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListCh,anged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service request
D/WifiP2pManager( 7306): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service request added successfully
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=263 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139310 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139310 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState discover services
D/WifiNative-p2p0( 1040): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1040):    returned b60376b8
,D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2675): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=264 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service discovery started successfully
I/wpa_supplicant( 2675): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WfdsMonitor( 1953): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WifiMonitor( 1040): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=265 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1040):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1040):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1040):  secondary type: null
D/LGWifiP2pService( 1040):  wps: 128
D/LGWifiP2pService( 1040):  grpcapab: 9
D/LGWifiP2pService( 1040):  devcapab: 4
D/LGWifiP2pService( 1040):  status: 3
D/LGWifiP2pService( 1040):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1953): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1040): No p2p device connected
D/LGWifiP2pService( 1040): InactiveState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1953): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010f000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010f000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=266 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010f000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7306): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7306): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7306): Powering the BLE discovery back up
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7306): setAdvertiseMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7306): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7306): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7306): setScanMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 7306): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7306): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7306): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/ActivityManager( 1040): Killing 6401:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10044/pid_6401/cgroup.procs: No such file or directory
,I/jxcore-log( 7306): 2016-01-08T14:59:12.530Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): 2016-01-08T14:59:12.531Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:59:12.533Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:59:12.533Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7306): 
I/jxcore-log( 7306): 2016-01-08T14:59:12.534Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 7306): 
,E/io.jxcore.node.StreamCopyingThread( 7306): Input stream got -1 on read (thread ID: 895, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 7306): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [34:FC:EF:11:B1:66 Nexus 5] disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:B1:66
I/io.jxcore.node.OutgoingSocketThread( 7306): close
D/io.jxcore.node.OutgoingSocketThread( 7306): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 896
D/io.jxcore.node.OutgoingSocketThread( 7306): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7306): doStop: Thread ID: 895
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7306): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7306): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7306): Either failed to read from the output stream or write to the input stream (thread ID: 896, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7306): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7306): onDisconnected: Outgoing connection, peer [34:FC:EF:11:B1:66 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
E/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 7306): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 896, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7306): Exiting thread (ID: 895, name: Sender)
,I/wpa_supplicant( 2675): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7306): teardown
I/jxcore-log( 7306): 
,I/jxcore-log( 7306): testSendData stopped
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7306): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7306): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7306): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 7306): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7306): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2675): P2P-FIND-STOPPED 
D/WfdsMonitor( 1953): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=267 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7306): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7306): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7306): setState: NOT_STARTED
I/jxcore-log( 7306): StopBroadcasting went ok
I/jxcore-log( 7306): 
,D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-12ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-12ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/LGWifiP2pService( 1040): remove channel information from framework
I/jxcore-log( 7306): 2016-01-08T14:59:12.852Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7306): 
I/io.jxcore.node.ConnectionHelper( 7306): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7306): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7306): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7306): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7306): Service requests cleared successfully
I/jxcore-log( 7306): ****TEST TOOK:  ms ****
I/jxcore-log( 7306): 
I/jxcore-log( 7306): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7306): 
,I/chromium( 7306): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/AndroidRuntime( 8177): 
D/AndroidRuntime( 8177): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8177): CheckJNI is OFF
,D/AndroidRuntime( 8177): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1040): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1040): Killing 7306:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1040): Skipping PackageSetting{2f9d63b4 com.example.hello/10319} due to missing metadata
,D/WifiService( 1040): Client connection lost with reason: 4
I/WindowState( 1040): WIN DEATH: Window{64dd865 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher( 1040): Window went away: Window{64dd865 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1040):   Force finishing activity ActivityRecord{b8545a6 u0 com.test.thalitest/.MainActivity t4}
,V/ActivityManager( 1040): Display changed displayId=0
,D/DSDPConnection( 1859): Display #0 changed.
E/GBMv2   (  335): DFP En is all cleared set to be enabled
,W/ActivityManager( 1040): Spurious death for ProcessRecord{3db37450 7306:com.test.thalitest/u0a311}, curProc for 7306: null
I/ActivityManager( 1040): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1040):   Force finishing activity ActivityRecord{b8545a6 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1040): Duplicate finish request for ActivityRecord{b8545a6 u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{1a86a20d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{33c125c2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] [+] updateMediaPlayerInfo
,I/InputReader( 1040): Reconfiguring input devices.  changes=0x00000010
D/LIA_MrGDBLogger_PackageInfoDetector( 3732): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2020): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
W/GeofencerStateMachine( 1824): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 2075): [Launcher.java:5338:onStart()]onStart
D/PostponalbeReceiver( 6839): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]EVENT( 2075): [Launcher.java:903:onResume()]onResume
,I/art     ( 4616): Explicit concurrent mark sweep GC freed 21541(908KB) AllocSpace objects, 5(80KB) LOS objects, 35% free, 29MB/45MB, paused 535us total 167.176ms
,W/System.err( 4541): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4541): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4541): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4541): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4541): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4541): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4541): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4541): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4541): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4541): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/SplitUIManager( 1876): split_name #11 / not available #0
D/SplitUIService( 1876): removed split : 
I/ActivityManager( 1040): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8217 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2075): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1910): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2075): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2075): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2075): [Launcher.java:1114:onPause()]onPause
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
D/ActionManagerService( 1910): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2075): , create_time: 1430558575574
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2075): , create_time: 1430558575600
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2075): , create_time: 1452175675684
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
D/WallpaperManager( 2075): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/SplitUIManager( 1876): split_name #11 / not available #0
I/SplitUIService( 1876): split app #11
I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@e83ccf0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1040): Menu title from STK is T-Mobile
V/SIM_STK ( 1040): Menu title from STK is T-Mobile
I/LockScreenSettings( 8217): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
I/art     ( 1040): Explicit concurrent mark sweep GC freed 83751(4MB) AllocSpace objects, 19(944KB) LOS objects, 33% free, 49MB/73MB, paused 2.506ms total 266.294ms
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
,W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/art     ( 1040): WaitForGcToComplete blocked for 271.247ms for cause Explicit
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1040): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3791): [BTUI] [-] updateMediaPlayerInfo
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 2075): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): handleShortcutListChanged...
D/administrator( 1040): Handling package changes for user 0
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
,W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/AppUp4:PreloadHelper( 7597): added Exclude : com.test.thalitest
V/SIM_STK ( 1040): Menu title from STK is T-Mobile
,I/ThermalEngine(  329): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3094): Thermal-Lib-Client: Client request sent
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
I/ActivityManager( 1040): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8239 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 7447:com.lge.sync/1000 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService( 1040): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1040): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1040): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/KeyguardModel( 1459): handleShortcutListChanged...
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_7447/cgroup.procs: No such file or directory
I/[Concierge]WidgetView( 2075): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
D/[Concierge]Service( 2618): onStartCommand(). Type : 8
D/[Concierge]Service( 2618): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2618): Update widget ID : 11
D/TaskPersister( 1040): removeObsoleteFile: deleting file=4_task.xml
,I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{1f91403f u0 com.lge.launcher2/.Launcher t3} time:655878
D/[Concierge]WidgetView( 2075): change position of spinner
I/[Concierge]WidgetView( 2075): initWebView(). Time : 1452265154054
D/[Concierge]Service( 2618): onStartCommand(). Type : 0
W/ResourcesManager( 8239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8239): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8239): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8239): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8239): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2075): Return exist ConciergeWebView. Reuse : 182608706
D/[Concierge]WidgetView( 2075): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2075): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3dc5e77b
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2075): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2075): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2075): Widget kill message received. Destory myself. My : 1452264525793, New one : 1452265154054
D/[Concierge]WidgetView( 2075): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2075): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1040): Explicit concurrent mark sweep GC freed 16244(902KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 48MB/73MB, paused 2.670ms total 225.018ms
,W/ResourcesManager( 1040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourceType( 1040): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 8239): BUILD Country: EU
I/SystemConfig( 8239): BUILD Operator: OPEN
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Timeline( 2075): Timeline: Activity_idle id: android.os.BinderProxy@1dc241b9 time:656001
I/ActivityManager( 1040): Killing 6936:com.lge.email/u0a23 (adj 15): empty #17
,D/AndroidRuntime( 8177): Shutting down VM
,I/chromium( 2075): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_6936/cgroup.procs: No such file or directory
,I/SystemConfig( 8239): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8239): existFile = false
I/SystemConfig( 8239): canReadFile = false
I/SystemConfig( 8239): systemFeature RCS result false
D/SystemConfig( 8239): refreshRcsSupport() :false
D/VoicemailCleanupService( 2255): Cleaning up data for package: com.test.thalitest
I/GBoardtInterface( 2075): onReloaded()
,I/GBoardWebViewClient( 2075): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8261 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3732): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3732): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3732): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3732): onSettingEvent() : GBoard On - add scheduler - 0
,V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
W/ResourcesManager( 8261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8261): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8261): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8261): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 8261): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8261): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 8261): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 8261): LgDataFeature() Constructor: none
D/LgDataFeature( 8261): LgDataFeature() Constructor Done, null
,I/PackageChangeReceiver( 8261): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1040): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8287 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 7646:com.lge.formmanager/u0a26 (adj 15): empty #17

```
