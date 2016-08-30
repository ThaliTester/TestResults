#### Test 8288334193c2946_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 12:29:37.818   310   310 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
08-30 12:29:37.818   310   310 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
08-30 12:29:37.818   310   310 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 12:29:37.818   310   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-30 12:29:37.908   310   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
08-30 12:29:37.908   310   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
08-30 12:29:37.908   310   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-30 12:29:37.908   310   907 I rmt_storage: 
08-30 12:29:37.912   310   310 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
08-30 12:29:37.913   894   905 E Diag_Lib: [IMS_FATAL]| 3347 | 905 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-30 12:29:38.353   329   400 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 12:29:38.359  3194  6574 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 12:29:38.520  1794  4775 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-30 12:29:38.572  1794  4775 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 12:29:38.610  1794  4775 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-30 12:29:38.727  6548  6548 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:29:38.727  6548  6548 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:29:38.883  6581  6581 D AndroidRuntime: 
08-30 12:29:38.883  6581  6581 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:29:38.884  6106  6106 I LockScreenSettings: New app installed broadcast received ..
08-30 12:29:38.885  6581  6581 D AndroidRuntime: CheckJNI is OFF
08-30 12:29:38.895  6106  6106 I LockScreenSettings: Number of installed packages  1
08-30 12:29:38.908  6548  6548 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 12:29:38.955  1028  1899 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:29:38.990  6581  6581 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 12:29:39.031  1028  1043 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6611 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:29:39.033  1028  1864 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:29:39.052  1919  2548 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 12:29:39.056  1028  1864 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 12:29:39.058  1028  1864 D ActivityManager: setTaskToReturnTo : TaskRecord{3b5e9427 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:29:39.058  1028  1864 D ActivityManager: setTaskToReturnTo : TaskRecord{3b5e9427 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:29:39.059  1028  1864 D WindowStateEx: AppWindowTokenEx init.. 
08-30 12:29:39.060   341   417 E GBMv2   : DFP En is all cleared set to be enabled
08-30 12:29:39.097  1028  1864 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6629 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:29:39.098  6581  6581 D AndroidRuntime: Shutting down VM
08-30 12:29:39.158  1919  2548 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 12:29:39.158  1919  2548 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1090864b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 12:29:39.160  1919  1935 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 12:29:39.160  1919  1935 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f763828 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 12:29:39.182  6611  6611 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 12:29:39.182  6611  6611 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-30 12:29:39.228  1028  1900 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 12:29:39.229  1028  1900 I ActivityManager: Killing 5445:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 12:29:39.276  1028  1918 W libprocessgroup: failed to open /acct/uid_10005/pid_5445/cgroup.procs: No such file or directory
,08-30 12:29:39.278  6629  6629 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 12:29:39.325  6650  6650 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-30 12:29:39.345  6629  6629 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:29:39.351  6650  6650 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 12:29:39.352  6629  6629 I LibraryLoader: Loading: webviewchromium
08-30 12:29:39.353  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-30 12:29:39.354  6629  6629 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2185-2188)
08-30 12:29:39.354  6629  6629 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:29:39.371  6629  6629 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d3db931}
08-30 12:29:39.372  6629  6629 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:29:39.372  6629  6629 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:29:39.375  1028  1578 I ActivityManager: Killing 5644:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 12:29:39.384  5611  5611 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 12:29:39.384  5611  5611 W System.err: android.os.DeadObjectException
08-30 12:29:39.384  5611  5611 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:29:39.384  5611  5611 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:29:39.384  5611  5611 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 12:29:39.384  5611  5611 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 12:29:39.384  5611  5611 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:29:39.384  5611  5611 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:29:39.384  5611  5611 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:29:39.384  5611  5611 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:29:39.384  5611  5611 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:29:39.384  6629  6629 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 12:29:39.384  5611  5611 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:29:39.384  5611  5611 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:29:39.384  5611  5611 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:29:39.384  5611  5611 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:29:39.384  5611  5611 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:29:39.385  5611  5611 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 12:29:39.385  5611  5611 W System.err: android.os.DeadObjectException
08-30 12:29:39.385  5611  5611 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:29:39.385  5611  5611 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 12:29:39.385  5611  5611 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:29:39.385  5611  5611 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:29:39.385  5611  5611 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:29:39.385  5611  5611 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:29:39.385  5611  5611 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:29:39.385  5611  5611 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:29:39.385  5611  5611 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 12:29:39.385  5611  5611 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 12:29:39.385  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:29:39.395   316  1380 V AudioPolicyService: registerClient() client 0xb57c5ca0, uid 10118
08-30 12:29:39.396  6629  6629 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 12:29:39.397  6629  6629 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 12:29:39.397  6629  6629 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-30 12:29:39.399  1028  1110 D BluetoothManagerService: Message: 20
08-30 12:29:39.399  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34ec7c6c:true
08-30 12:29:39.407  6629  6629 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:29:39.407  6629  6629 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:29:39.407  6629  6629 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:29:39.407  6629  6629 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:29:39.407  6629  6629 I Adreno-EGL: Remote Branch: 
08-30 12:29:39.407  6629  6629 I Adreno-EGL: Local Patches: 
08-30 12:29:39.407  6629  6629 I Adreno-EGL: Reconstruct Branch: 
08-30 12:29:39.485  1028  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_5644/cgroup.procs: No such file or directory
08-30 12:29:39.485  1028  1972 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 12:29:39.491  5611  5611 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 12:29:39.491  5611  5611 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 12:29:39.539  1028  1044 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6687 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:29:39.542  5611  5611 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 12:29:39.563  6629  6681 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 12:29:39.572  6629  6629 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-30 12:29:39.590  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:29:39.595  6629  6629 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 12:29:39.599  6629  6629 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-30 12:29:39.602  6629  6629 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 12:29:39.602  6629  6629 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 12:29:39.613  6687  6687 D UEI.SmartControl: Quickset Services start...
,08-30 12:29:39.614  6687  6687 I UEI.SmartControl: Manufacture = LGE
08-30 12:29:39.615  6687  6687 D UEI.SmartControl: Id = LGNevo
08-30 12:29:39.616  6687  6687 D UEI.SmartControl: File observer start...
08-30 12:29:39.616  6687  6687 E UEI.SmartControl: IR Port is disabled: false
08-30 12:29:39.617  6687  6687 D UEI.SmartControl: Starting file observer...
08-30 12:29:39.617  6687  6687 D UEI.SmartControl: Extracting JNI libs...
08-30 12:29:39.617  6687  6687 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 12:29:39.619  6629  6629 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-30 12:29:39.625  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:29:39.625  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:29:39.654  6629  6711 D OpenGLRenderer: Render dirty regions requested: true
08-30 12:29:39.654  6629  6711 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 12:29:39.657  1028  1095 W ActivityManager: Activity pause timeout for ActivityRecord{159326d4 u0 com.test.thalitest/.MainActivity t6}
08-30 12:29:39.663  6629  6711 D OpenGLRenderer: Enabling debug mode 0
,08-30 12:29:39.669  6629  6629 D Atlas   : Validating map...
08-30 12:29:39.673  1028  1864 D SplitWindow: check instance of lgWin Window{2b87d15d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:29:39.736  6629  6709 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:29:39.737  6629  6709 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:29:39.749  6687  6687 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 12:29:39.749  6687  6687 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 12:29:39.749  6687  6687 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 12:29:39.764  1028  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +607ms (total +703ms)
08-30 12:29:39.764  1028  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{159326d4 u0 com.test.thalitest/.MainActivity t6} time:102598
,08-30 12:29:39.765  6629  6629 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16a665b4 time:102598
,08-30 12:29:39.786  6687  6687 I UEI.SmartControl: --- Selecting new region: 6
,08-30 12:29:39.788  6687  6687 I UEI.SmartControl: Model = LG-D855
08-30 12:29:39.790  6687  6687 D UEI.SmartControl: QS Service created
08-30 12:29:39.806  6687  6687 I UEI.SmartControl: Service initServices...
,08-30 12:29:39.810  6687  6687 D UEI.SmartControl: QS start get config
08-30 12:29:39.859  6687  6687 D UEI.SmartControl: Loading JNI Libs...
,08-30 12:29:39.900  6629  6629 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 12:29:39.900  6629  6629 I chromium: 
,08-30 12:29:39.929  6629  6629 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:29:40.028  6629  6709 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 12:29:40.028  6629  6709 I chromium: 
,08-30 12:29:40.119  6629  6727 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-30 12:29:40.128  6629  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:29:40.128  6629  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:29:40.128  6629  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:29:40.128  6629  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:29:40.128  6629  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:29:40.128  6629  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1573fc38 added. We now have 1 listener(s)
08-30 12:29:40.133  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:29:40.136  6687  6687 I UEI.SmartControl: Supports setup maps: true
08-30 12:29:40.138  6629  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 12:29:40.139  6629  6727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:29:40.140  6687  6687 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 12:29:40.140  6687  6687 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:29:40.140  6687  6687 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:29:40.141  6629  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:29:40.141  6687  6687 I UEI.SmartControl: ### init IR Blaster...
08-30 12:29:40.141  6629  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:29:40.145  6687  6687 D serial_port: Configuring serial port
,08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:29:40.148  6629  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26969b77 added. We now have 1 listener(s)
08-30 12:29:40.149  6629  6727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:29:40.149  6687  6687 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:29:40.149  6687  6687 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:29:40.150  6687  6687 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:29:40.150  6687  6687 I UEI.SmartControl: Get version...
08-30 12:29:40.152  1028  1382 D WifiService: New client listening to asynchronous messages
08-30 12:29:40.155  6629  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:29:40.155  6629  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:29:40.156  6629  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:29:40.156  6629  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:29:40.156  6629  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:29:40.159  6629  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:29:40.160  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:29:40.161  6629  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 12:29:40.168  6687  6732 D UEI.SmartControl: serial port data available: 21
,08-30 12:29:40.172  6629  6727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:40.172  6629  6727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:40.172  6629  6727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:29:40.172  6629  6727 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:40.174  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:40.175  6629  6727 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:29:40.176  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:40.195  6687  6687 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 12:29:40.196  6687  6687 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 12:29:40.196  6687  6687 I UEI.SmartControl: QS saving settings...
,08-30 12:29:40.197  6687  6687 D UEI.SmartControl: IR Blaster version: 25672567
08-30 12:29:40.210  6629  6629 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:29:40.214  6687  6732 D UEI.SmartControl: serial port data available: 4
08-30 12:29:40.245  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 12:29:40.245  6687  6737 I UEI.SmartControl: Device manager: loading config....
08-30 12:29:40.246  6687  6737 D UEI.SmartControl: ----------- loading internal config...
08-30 12:29:40.247  6687  6687 E UEI.SmartControl: Services init done
08-30 12:29:40.247  6687  6687 D UEI.SmartControl: QS Service init finished
08-30 12:29:40.248  6687  6687 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:29:40.248  6687  6687 D UEI.SmartControl: QS Service version code: 201091
08-30 12:29:40.248  6687  6687 D UEI.SmartControl: Service requested: Control
,08-30 12:29:40.256  6687  6737 E UEI.SmartControl: Loading SETTINGS...
08-30 12:29:40.259  6687  6687 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 12:29:40.262  5611  5611 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 12:29:40.262  6687  6705 I UEI.SmartControl: ------ IControl API: 11
08-30 12:29:40.264  6687  6705 I UEI.SmartControl: Registering callback...
08-30 12:29:40.265  1028  1864 I ActivityManager: Killing 5611:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 12:29:40.265  6687  6703 I UEI.SmartControl: ------ IControl API: 19
08-30 12:29:40.266  6687  6703 I UEI.SmartControl: Registering Services Ready callback...
08-30 12:29:40.269  6687  6737 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 12:29:40.286  6687  6736 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:29:40.286  6687  6736 D UEI.SmartControl: -----service ready thread exits
,08-30 12:29:40.348  1028  1569 W libprocessgroup: failed to open /acct/uid_10112/pid_5611/cgroup.procs: No such file or directory
08-30 12:29:40.348  6687  6687 D UEI.SmartControl: Internal service binding...
,08-30 12:29:41.002  6629  6734 W jxcore-log: Initializing JXcore engine
08-30 12:29:41.003  6629  6734 W jxcore-log: JXcore engine is ready
,08-30 12:29:41.015   341   419 E GBMv2   : DFP En is all cleared set to be enabled
08-30 12:29:41.015   341   419 E GBMv2   : Set value is all cleared set the max
08-30 12:29:41.015   341   419 I GBMv2   : DFP Enabled. Ignore VFP set
08-30 12:29:41.039  6734  6734 W Thread-772: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8391]" dev="sockfs" ino=8391 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 12:29:41.039  6734  6734 W Thread-772: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 12:29:41.039  6734  6734 W Thread-772: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9530]" dev="sockfs" ino=9530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 12:29:41.039  6734  6734 W Thread-772: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 12:29:41.039  6734  6734 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[32267]" dev="sockfs" ino=32267 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 12:29:41.069  6629  6734 W jxcore-log: Starting JXcore engine
,08-30 12:29:41.165  6629  6734 W jxcore-log: Platform android
08-30 12:29:41.165  6629  6734 W jxcore-log: 
08-30 12:29:41.165  6629  6734 W jxcore-log: Process ARCH arm
08-30 12:29:41.165  6629  6734 W jxcore-log: 
,08-30 12:29:41.364  6629  6734 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:29:41.364  6629  6734 I jxcore-log: 
08-30 12:29:41.364  6629  6734 W jxcore-log: JXcore engine is started
,08-30 12:29:41.371  6629  6727 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 12:29:41.374  6629  6629 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 12:29:42.811  6548  6548 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 12:29:42.818  1028  1863 I ActivityManager: Killing 5832:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 12:29:42.910  1028  1763 W libprocessgroup: failed to open /acct/uid_10072/pid_5832/cgroup.procs: No such file or directory
,08-30 12:29:43.477  2770  2770 I MusicWidget: mDelayedStopHandler : unbind
,08-30 12:29:43.482  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-30 12:29:43.483  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-30 12:29:43.483  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 12:29:43.484  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 12:29:43.484  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 12:29:43.484  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 12:29:43.485  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 12:29:43.485  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 12:29:43.496  1028  1899 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@28e0287com.lge.music.MediaPlaybackService$5@16a665b4
08-30 12:29:43.496  2130  2130 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 12:29:43.496  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.497  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.497  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.498  2130  2130 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3b83b76d
08-30 12:29:43.498  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.499  2130  2130 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 12:29:43.499  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.499  2130  2130 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 12:29:43.499  2130  2130 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 12:29:43.499  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.499  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.500  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.500  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.500  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:29:43.501  2130  2130 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-30 12:29:43.502  2130  2130 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 12:29:43.502  2130  2130 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 12:29:43.503  2130  2130 V MediaPlayer[Native]: reset
,08-30 12:29:43.510  2130  2130 V MediaPlayer[Native]: setListener
08-30 12:29:43.510  2130  2130 V MediaPlayer[Native]: disconnect
08-30 12:29:43.510  2130  2130 V MediaPlayer[Native]: destructor
08-30 12:29:43.510   316  2156 V AudioFlinger: releasing 16 from 2130 for -1
08-30 12:29:43.510   316  2156 V AudioFlinger:  decremented refcount to 0
08-30 12:29:43.510   316  2156 V AudioFlinger: purging stale effects
08-30 12:29:43.510  2130  2130 V MediaPlayer[Native]: disconnect
08-30 12:29:43.511  2130  2130 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 12:29:43.512  2130  2130 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 12:29:43.513  2130  2130 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 12:29:43.513  2130  2130 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 12:29:43.513  2130  2130 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 12:29:43.514  2130  2130 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 12:29:43.514  2130  2130 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 890131933
08-30 12:29:43.514  2130  2130 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 890131933
08-30 12:29:43.519  2130  2130 I SmartShareClient: [SmartShareManagerClient] terminate service: 2130/MediaPlaybackService/788076731
08-30 12:29:43.521  2130  2130 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 12:29:43.521  2130  2130 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3b321552
,08-30 12:29:43.525  2130  2130 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 12:29:43.525  2130  2130 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 12:29:43.526  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 12:29:43.526  2130  2130 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 12:29:43.527  1028  1863 I ActivityManager: Killing 6304:com.android.calendar/u0a13 (adj 15): empty #17
08-30 12:29:43.535  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,08-30 12:29:43.598  1028  1763 W libprocessgroup: failed to open /acct/uid_10013/pid_6304/cgroup.procs: No such file or directory
,08-30 12:29:43.792  6548  6583 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 12:29:45.246  6687  6738 D UEI.SmartControl: Internal timer expired: 1
08-30 12:29:45.247  6687  6738 D UEI.SmartControl: unbind internal service
,08-30 12:29:45.251  6687  6687 D UEI.SmartControl: Service.onUnbind: IControl
08-30 12:29:45.253  6687  6735 D serial_port: close(fd = 25)
08-30 12:29:45.255  6687  6687 D UEI.SmartControl: Service.onDestroy
08-30 12:29:45.255  6687  6687 D UEI.SmartControl: Lock is in USE false
08-30 12:29:45.255  6687  6687 D UEI.SmartControl: unbind internal service
08-30 12:29:45.256  6687  6687 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3b83b76d
08-30 12:29:45.257  6687  6687 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 12:29:45.257  6687  6687 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 12:29:45.257  6687  6687 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:29:45.257  6687  6687 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:29:45.257  6687  6687 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:29:45.257  6687  6687 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:29:45.257  6687  6687 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:29:45.257  6687  6687 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:29:45.257  6687  6687 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3b83b76d
08-30 12:29:45.260  6687  6735 I UEI.SmartControl: Serial port is closed.
08-30 12:29:45.261  6687  6687 I UEI.SmartControl: Serial port is closed.
08-30 12:29:45.261  6687  6687 I UEI.SmartControl: Serial port is closed.
08-30 12:29:45.261  6687  6687 D UEI.SmartControl: Blaster closed
08-30 12:29:45.261  6687  6687 D UEI.SmartControl: Shut down QS...
08-30 12:29:45.262  6687  6687 D UEI.SmartControl: Stopping QS lib
08-30 12:29:45.262  6687  6687 D UEI.SmartControl: QS lib stop result = true
08-30 12:29:45.262  6687  6687 D UEI.SmartControl: Stopped QS lib
,08-30 12:29:45.263  6687  6687 D UEI.SmartControl: Stopped file observer...
08-30 12:29:45.264  6687  6687 D UEI.SmartControl: QS shutdown complete
08-30 12:29:46.771  1794  6457 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 12:29:46.777   312  6746 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 12:29:46.778   312  6746 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 12:29:46.778   312  6746 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 12:29:46.984  1794  1794 I ConfigFetchService: fetch service done; releasing wakelock
08-30 12:29:46.985  1794  1794 I ConfigFetchService: stopping self
,08-30 12:29:46.992  2197  2197 I ConfigService: onDestroy
,08-30 12:29:51.370  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:29:51.370  6629  6734 I jxcore-log: 
,08-30 12:29:51.373  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:29:51.373  6629  6734 I jxcore-log: 
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:51.377  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:51.379  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:51.382  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:29:51.382  6629  6734 I jxcore-log: 
08-30 12:29:51.383  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:29:51.383  6629  6734 I jxcore-log: 
,08-30 12:29:51.883  1028  1095 I ActivityManager: Waited long enough for: ServiceRecord{a92f8b0 u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 12:29:51.890  6629  6734 I jxcore-log: Unit Test app is loaded
08-30 12:29:51.890  6629  6734 I jxcore-log: 
08-30 12:29:51.898  6629  6629 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:29:51.908  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:29:51.908  6629  6734 I jxcore-log: 
08-30 12:29:51.923  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 12:29:51.923  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c23d31 added. We now have 2 listener(s)
08-30 12:29:51.925  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:29:51.928  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:29:51.928  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:29:51.928  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:29:51.928  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:29:51.928  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73f2c16 added. We now have 2 listener(s)
08-30 12:29:51.928  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:29:51.928  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:29:51.930  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:51.932  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:51.933  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:51.933  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:51.934  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:51.935  6629  6734 D ExecuteNativeTests: Running unit tests
08-30 12:29:51.935  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:29:52.009  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:29:52.009  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 added. We now have 3 listener(s)
08-30 12:29:52.010  1028  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:29:52.011  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:29:52.011  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:29:52.011  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:29:52.011  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:29:52.011  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd added. We now have 3 listener(s)
08-30 12:29:52.011  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:29:52.011  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:29:52.013  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:52.014  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:52.015  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:52.016  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:52.018  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:29:52.019  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:29:52.019  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:29:52.019  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:29:52.021  6629  6734 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 12:29:52.022  6629  6734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 12:29:52.022  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 12:29:52.022  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:29:52.022  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:29:52.022  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:29:52.022  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:29:52.022  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:52.022  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:29:52.022  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:29:52.023  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 removed from the list
08-30 12:29:52.023  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:29:52.023  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd removed from the list
08-30 12:29:52.023  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:29:52.023  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:52.026  6629  6734 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 12:29:52.026  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:29:52.026  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:52.026  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:52.026  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:29:52.026  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:29:52.026  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:29:52.026  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:29:52.026  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:52.026  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:29:52.031  6629  6734, D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:29:52.031  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:29:52.032  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:29:52.032  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:52.032  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:52.032  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:29:52.032  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:29:52.032  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
,08-30 12:29:52.032  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:29:52.032  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:52.032  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:52.035  6629  6734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:29:52.036  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:52.039  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:52.039  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-30 12:29:52.039  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:52.040  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:52.041  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:52.042  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:29:52.042  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:29:52.042  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:29:52.042  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:29:52.042  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:29:52.045  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:29:52.045  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:29:52.048  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:29:52.052  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:29:52.053  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 12:29:52.054  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:29:52.054  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:29:52.055  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:29:52.055  6629  6734 I io.jxcore.node.ConnectionHelper: start: OK
08-30 12:29:53.547  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19980
,08-30 12:29:53.714  1028  1356 V AlarmManager: RTC_WAKEUP set : Alarm{e5ef383 type 0 when 1472552992337 com.android.vending} when 1472552992337
,08-30 12:29:53.772  4499  6750 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 12:29:53.891  1028  1918 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:29:54.052  6067  6067 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 12:29:57.070  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:29:57.070  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:29:57.070  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:30:00.059  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 12:30:00.059  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 12:30:00.060  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 12:30:00.060  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,08-30 12:30:00.072  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 12:30:00.072  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:30:00.074  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:30:00.078  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 12:30:01.269  1028  1356 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1056668800, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,08-30 12:30:01.333  1028  1095 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6774 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-30 12:30:01.372  2558  2558 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 12:30:01.495  6774  6774 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-30 12:30:01.500  6774  6774 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2795114a
08-30 12:30:01.501  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1056668800 [*alarm*], flags=0x0
08-30 12:30:01.502  1028  1864 I ActivityManager: Killing 6217:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 12:30:01.600  1028  1900 W libprocessgroup: failed to open /acct/uid_10014/pid_6217/cgroup.procs: No such file or directory
,08-30 12:30:02.079  6629  6734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 12:30:02.079  6629  6734 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-30 12:30:02.079  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:30:02.080  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:30:02.080  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:30:02.080  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:02.080  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:30:02.246  1028  1972 I art     : Explicit concurrent mark sweep GC freed 24312(1189KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.658ms total 147.818ms
,08-30 12:30:02.251  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:30:02.252  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:02.253  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:30:02.253  6629  6734 I io.jxcore.node.ConnectionHelper: start: OK
08-30 12:30:07.260  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:07.260  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:07.260  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:07.260  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:07.260  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:07.260  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:07.260  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:07.261  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:07.270  6629  6734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:30:07.278  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:07.284  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:07.286  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:07.286  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:30:07.288  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:07.289  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:07.291  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:30:07.291  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:30:07.291  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:30:07.291  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:30:07.291  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:30:07.297  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:30:07.298  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:07.299  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:30:07.300  6629  6734 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:30:12.300  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 12:30:12.301  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-30 12:30:12.301  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:30:13.537  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-30 12:30:13.543  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-30 12:30:17.318  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.318  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.318  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:17.319  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.319  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:17.319  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.319  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.319  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.335  6629  6734 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 12:30:17.338  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.338  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.338  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.338  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.338  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.338  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.338  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.338  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.338  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.340  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:30:17.340  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.340  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.340  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.340  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.340  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.340  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.340  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.340  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.340  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.341  6629  6734 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 12:30:17.341  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.341  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.341  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.341  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.341  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.341  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.341  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.341  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.342  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.342  6629  6734 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 12:30:17.343  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.343  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.343  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.343  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.343  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.343  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.343  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.343  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.343  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.344  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:30:17.348  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:17.348  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:17.348  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:30:17.348  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:17.348  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:17.348  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:30:17.348  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:17.348  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:17.349  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.349  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.349  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.349  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.349  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.349  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.349  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.349  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.349  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:17.361  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:17.362  6629  6734 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:30:17.363  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 12:30:17.373  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:17.373  6629  6734 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 12:30:17.373  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:30:17.373  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:30:17.373  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:30:17.373  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:30:17.373  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:30:17.373  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:30:17.374  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:30:17.376  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:30:17.376  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:30:17.376  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:30:17.376  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:30:17.376  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 12:30:17.379  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:30:17.379  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:30:17.379  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:30:17.380  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:30:17.380  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 12:30:17.380  6629  6734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:30:17.380  6629  6734 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 12:30:17.381  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:17.381  6629  6734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:30:17.381  6629  6734 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 12:30:17.381  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:17.381  6629  6734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:30:17.381  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 12:30:17.384  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 12:30:17.385  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 12:30:17.386  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 12:30:17.387  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 12:30:17.387  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 12:30:17.387  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 12:30:17.387  6629  6734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:17.388  6629  6734 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 12:30:17.388  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.388  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.388  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.388  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 12:30:17.389  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.389  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.389  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.389  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.389  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.389  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.390  6629  6734 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 12:30:17.390  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.390  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.390  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.390  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.390  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.391  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.391  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.391  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.391  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.391  6629  6734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 12:30:17.392  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.392  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.392  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.392  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.392  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.392  6629  6734 E org.thaliproje,ct.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.392  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.392  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.392  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.393  6629  6734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 12:30:17.393  6629  6734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 12:30:17.393  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:30:17.394  6629  6734 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 12:30:17.394  6629  6734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:30:17.394  6629  6734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 12:30:17.394  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:30:17.394  6629  6734 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 12:30:17.394  6629  6734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:30:17.394  6629  6734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:30:17.394  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:30:17.394  6629  6734 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 12:30:17.394  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:17.394  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.394  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.395  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:17.395  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:17.395  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:17.395  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:17.395  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:17.395  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:17.404  6629  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-30 12:30:17.407  6629  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-30 12:30:17.407  6629  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-30 12:30:17.409  6629  6734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:30:17.421  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:17.424  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:17.428  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:17.428  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:30:17.430  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:17.431  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:17.432  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:30:17.432  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:30:17.432  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:30:17.432  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:17.432  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:30:17.437  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:30:17.439  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:17.441  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:30:17.441  6629  6734 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:30:22.442  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:22.442  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:22.442  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:30:22.442  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:22.442  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.443  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:22.443  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:22.443  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-30 12:30:27.459  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:27.459  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
,08-30 12:30:27.459  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.459  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.460  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.460  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
,08-30 12:30:27.460  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.460  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.460  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.460  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
,08-30 12:30:27.460  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:27.461  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:27.461  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:27.461  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.461  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:27.479  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:30:27.479  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:27.481  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:30:27.482  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:30:27.482  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:30:27.482  6629  6629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:30:27.483  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:30:27.484  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:30:27.486  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.486  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 12:30:27.487  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:30:27.487  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:30:27.487  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.487  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:30:27.488  6629  6819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:30:27.488  6629  6819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 12:30:27.491  6629  6629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:30:27.491  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:27.492  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:27.492  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:30:27.492  6629  6734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:30:27.492  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:30:27.493  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:30:27.496  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:30:27.496  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:30:27.496  6629  6734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:30:27.496  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.496  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.499  6629  6734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:27.499  6629  6629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:27.499  6629  6629 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 12:30:27.499  6629  6629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:27.499  6629  6629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:27.500  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:27.500  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.500  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.500  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.500  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:27.500  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:27.500  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:27.500  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:27.500  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.500  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.501  6629  6734 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 12:30:27.505  6629  6734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 12:30:27.505  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:30:27.508  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:27.508  6629  6734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:27.508  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.508  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.508  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.508  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:27.508  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:27.508  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:27.508  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:27.508  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.508  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.513  1028  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:27.515  1028  1569 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:30:27.518  1028  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:27.519  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.519  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.519  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.519  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:27.519  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:27.519  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:27.519  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:27.519  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.519  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.520  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.521  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:27.521  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.521  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644b9b4 not in the list
08-30 12:30:27.521  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:27.521  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11019dd not in the list
08-30 12:30:27.521  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:27.521  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:27.521  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.522  6629  6734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 12:30:27.523  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:30:27.523  6629  6734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 12:30:27.523  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:30:27.523  6629  6734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 12:30:27.523  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:30:27.525  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:30:27.526  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 12:30:27.528  6629  6734 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 12:30:27.528  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:30:27.529  6629  6734 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 12:30:27.529  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:30:27.529  6629  6734 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 12:30:27.529  6629  6734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 12:30:27.530  6629  6734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 12:30:27.530  6629  6734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 12:30:27.531  6629  6734 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 12:30:27.531  6629  6734 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 12:30:27.531  6629  6734 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 12:30:27.531  6629  6734 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 12:30:27.532  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:27.532  6629  6734 V org.thaliproject.p2p.btconnector,lib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@323749b added. We now have 3 listener(s)
08-30 12:30:27.532  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:30:27.541  6629  6734 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 12:30:27.542  1028  1971 D WifiServiceImplEx: setWifiEnabled: true pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:30:27.543  1028  1971 D WifiService: setWifiEnabled: true pid=6629, uid=10118
08-30 12:30:27.543  1028  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 12:30:28.000  6629  6629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:30:32.551  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:30:32.551  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e821038 added. We now have 4 listener(s)
,08-30 12:30:32.551  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:30:32.570  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:32.572  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e821038 removed from the list
08-30 12:30:32.572  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:32.572  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:32.572  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.573  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:32.573  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31a22811 added. We now have 4 listener(s)
08-30 12:30:32.573  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:30:32.575  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:32.575  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31a22811 removed from the list
08-30 12:30:32.575  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:32.575  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:32.575  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.576  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:32.576  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18666d76 added. We now have 4 listener(s)
08-30 12:30:32.576  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:30:32.579  1028  1043 D WifiServiceImplEx: setWifiEnabled: false pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:30:32.580  1028  1043 D WifiService: setWifiEnabled: false pid=6629, uid=10118
08-30 12:30:32.580  1028  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:30:32.601  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:30:32.602  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:30:32.602  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:30:32.604  1028  1368 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:32.605  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:32.605  1028  1368 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:32.605  1028  1368 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:32.606  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:32.607  1028  1368 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 12:30:32.607  1028  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:30:32.607  1028  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:30:32.608  1028  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:30:32.608  1028  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 12:30:32.613  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:32.613  1028  1971 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3733c373 mBinding = false
08-30 12:30:32.616  1028  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:30:32.617  1028  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.617  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.618  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:30:32.618  2687  2687 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:30:32.619  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:30:32.619  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:30:32.619  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:30:32.620  1028  2839 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:32.628   312   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:32.687  1028  1899 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-30 12:30:32.689  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:32.689  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.690  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 12:30:32.690  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.690  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:30:32.722  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:30:32.723  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-30 12:30:32.729  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 12:30:32.729  1028  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.729  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.729  1028  1367 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@343d5d37
08-30 12:30:32.736  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.736  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.736  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:30:32.736  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 12:30:32.738  1919  1919 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-30 12:30:32.740  1028  1110 D BluetoothManagerService: Message: 2
08-30 12:30:32.745  1028  1110 D BluetoothManagerService: Sending off request.
08-30 12:30:32.746  3890  3907 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 12:30:32.748  3890  3970 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 12:30:32.748  3890  3970 D BluetoothAdapterProperties: Setting state to 13
08-30 12:30:32.748  3890  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:30:32.749  3890  3970 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:30:32.749  3890  3970 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 12:30:32.750  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.750  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.751  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:30:32.751  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 12:30:32.751  1028  1028 D RttService: SCAN_AVAILABLE : 1
08-30 12:30:32.751  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:30:32.751  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:30:32.751  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:30:32.752  1028  1534 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.752  1028  1535 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.754  1028  1367 D LGWifiP2pService: P2pDisablingState
08-30 12:30:32.754  1028  1367 D LGWifiP2pService: P2pDisablingState{ when=-25ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.754  1028  1367 D LGWifiP2pService: p2p socket connection lost
08-30 12:30:32.754  1028  1367 D LGWifiP2pService: P2pDisabledState
08-30 12:30:32.755  3890  3973 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:30:32.755  3890  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 12:30:32.756  3890  4335 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 12:30:32.757  3890  4273 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 12:30:32.758  3890  3970 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:30:32.760  3890  4332 V BluetoothFtpService:Rfcom,mSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:32.761  3890  4331 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:32.761  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:32.761  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 12:30:32.763  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:30:32.763  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 12:30:32.764  1919  1919 D WfdsService: WifiP2pState is changed : false
08-30 12:30:32.764  3890  4109 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 12:30:32.764  1919  2212 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 12:30:32.764  1919  2212 D WfdsService: Set the WFDS Monitor: false
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 12:30:32.765  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 12:30:32.765  3890  4109 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:30:32.766  3890  4276 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:32.767  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:30:32.767  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 12:30:32.767  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 12:30:32.769  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.771  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:32.771  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:32.772  1919  2212 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:30:32.772  1919  2212 D WfdsService: STATE : WfdsDisabledState - enter
08-30 12:30:32.772  1919  2724 D CtrlSupplicant: Received on exit socket, terminate
08-30 12:30:32.772  1919  2724 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 12:30:32.773  1919  2724 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 12:30:32.773  1919  2724 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 12:30:32.773  1919  2226 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 12:30:32.774  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.774  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:32.774  1919  2212 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 12:30:32.776  1028  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:32.777  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:32.777  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:32.778  1028  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:32.778  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:32.778  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:32.779  1028  1368 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:30:32.779  1028  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 12:30:32.780  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:32.780  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:32.780  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.780  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:32.784  3890  3890 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:32.784  3890  3890 D BluetoothMapService: STATE_TURNING_OFF
08-30 12:30:32.784  3890  3890 V BluetoothMapService: Handler(): got msg=4
08-30 12:30:32.784  3890  3890 D BluetoothMapService: MAP Service closeService in
08-30 12:30:32.784  3890  3890 D BluetoothMapMasInstance: MAP Service shutdown
08-30 12:30:32.784  3890  3890 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:30:32.785  3890  3890 V BluetoothMapService: MAP Service closeService out
08-30 12:30:32.785  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:32.785  3890  3890 V BtOppService: Receiver DISABLED_ACTION 
08-30 12:30:32.785  3890  3890 I BtOppRfcommListener: stopping Accept Thread
08-30 12:30:32.785  3890  3890 V BtOppRfcommListener: close mBtServerSocket
08-30 12:30:32.786  3890  3890 V BtOppRfcommListener: waiting for thread to terminate
08-30 12:30:32.786  3890  4331 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:30:32.787  3890  3890 V BtOppRfcommListener: done waiting for thread to terminate
,08-30 12:30:32.796  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:30:32.796  1028  1396 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 12:30:32.796   312  6853 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:30:32.796  1028  1396 D DSQN    : disableDataServiceNotify
08-30 12:30:32.796  1028  1396 D DSQN    : stop dsqn bin
08-30 12:30:32.797  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 12:30:32.798  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:32.798  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:32.798  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:30:32.798  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 12:30:32.798  2687  2687 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:30:32.798  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.798  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:32.798  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:30:32.798  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 12:30:32.799  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:30:32.799   312   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:32.800  1028  1367 D LGWifiP2pService: P2pDisabledState{ when=-21ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.800  1028  1367 D LGWifiP2pService: DefaultState{ when=-21ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.803  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:32.804  1028  1396 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 12:30:32.804  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:32.804  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:32.804  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:32.804  1028  1396 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:32.804  1028  1396 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 12:30:32.804  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 12:30:32.805  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.805  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.805  1028  2838 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 12:30:32.807  1028  1396 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 12:30:32.807  1028  1396 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 12:30:32.807  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:30:32.820  1028  1095 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6854 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:30:32.821  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:32.834   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 308us total 14.205ms
,08-30 12:30:32.846   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 256us total 12.120ms
,08-30 12:30:32.858   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 11.522ms
,08-30 12:30:32.896  1028  1044 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6872 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:30:32.899  1028  1368 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 12:30:32.900  1028  1396 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:32.900  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:30:32.900  3890  3890 V BtOppService: onDestroy
08-30 12:30:32.901  1028  1396 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:32.901  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 12:30:32.903  1028  1396 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:32.903  1028  1368 D WifiNative-p2p0: TERMINATE: returned true
08-30 12:30:32.903  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:30:32.903  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:30:32.903  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:30:32.903  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 12:30:32.903  1028  1396 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:32.903  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:32.904  1028  1396 D NetworkManagementService: Removing idletimer
08-30 12:30:32.904  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.904  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.904  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.904  1829  1829 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:32.905  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:30:32.905  1829  1829 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:30:32.905  1028  1396 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:32.906  1028  1396 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 12:30:32.908  1028  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:30:32.909  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:30:32.909  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:30:32.909  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:30:32.910  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:30:32.911  1028  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:30:32.913  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:30:32.913  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:30:32.914  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavail,able info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:30:32.914  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:30:32.921  1028  1368 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:32.921  1028  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:30:32.922  3890  3890 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 12:30:32.925  1028  2839 D DhcpStateMachine: StoppedState
08-30 12:30:32.926  1028  2839 D DhcpStateMachine: StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:32.926  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:32.926  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:32.927  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.927  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:32.927  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:30:32.930  1028  1368 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 12:30:32.931  1028  1368 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 12:30:32.931  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 12:30:32.931  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:32.931  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:32.937  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:32.937  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 12:30:32.938  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:32.938  1028  1028 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 12:30:32.946  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:32.946  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:32.947  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.947  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:32.950  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:32.950  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:32.951  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:32.951  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:32.951  6854  6854 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:30:32.951  6854  6854 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 12:30:32.952  6854  6854 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:30:32.952  6854  6854 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 12:30:32.953  6854  6854 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:30:32.954  6854  6854 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 12:30:32.956  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:32.970  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:30:32.971  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.972  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:30:32.987  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:30:32.988  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.989  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.989  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:32.991  2687  2687 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 12:30:32.991  2687  2687 I wpa_supplicant: monitor socket send errors count : 1
08-30 12:30:32.991  2687  2687 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1919-2\x00 that cannot receive messages
08-30 12:30:32.992  1028  2716 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 12:30:32.992  1028  2716 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 12:30:32.995  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:30:32.998  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:32.998  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:30:33.000  1028  2010 I ActivityManager: Killing 6277:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 12:30:33.029  2687  2687 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:30:33.030  2687  2687 W wpa_supplicant: USIM:  scard_deinit function
08-30 12:30:33.031  1028  2716 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 12:30:33.031  1028  2716 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:30:33.031  1028  2716 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:30:33.031  1028  2716 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 12:30:33.032  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 12:30:33.032  1028  2716 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:30:33.032  1028  2716 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:30:33.032  1028  1368 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=155855
08-30 12:30:33.033  1028  1368 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=155855
08-30 12:30:33.033  1028  1368 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=155855  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:30:33.034  1028  1368 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=155856  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:30:33.034  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:30:33.057  1028  1863 W libprocessgroup: failed to open /acct/uid_10004/pid_6277/cgroup.procs: No such file or directory
,08-30 12:30:33.060  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:30:33.065  1028  1368 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:33.066  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:33.067  3890  3890 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:30:33.067  3890  3890 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:33.067  3890  3890 V BluetoothPbapReceiver: ***********state = 13
08-30 12:30:33.069  3890  3890 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 12:30:33.071  3890  3890 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:33.071  3890  3890 V BluetoothPbapService: state: 13
08-30 12:30:33.071  3890  3890 V BluetoothPbapService: Pbap Service closeService in
,08-30 12:30:33.073  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:30:33.077  3890  3890 V BluetoothPbapService: successfully stopped pbap service
08-30 12:30:33.077  3890  3890 V BluetoothPbapService: Pbap Service closeService out
08-30 12:30:33.077  3890  3890 V BluetoothPbapService: Pbap Service onDestroy
08-30 12:30:33.077  3890  3890 V BluetoothPbapService: Pbap Service closeService in
08-30 12:30:33.077  3890  3890 V BluetoothPbapService: Pbap Service closeService out
08-30 12:30:33.077  3890  3890 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 12:30:33.085  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:33.127  6854  6854 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:33.127  6854  6854 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:33.137  2687  2687 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 12:30:33.137  1028  1938 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6894 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 12:30:33.140  1028  2716 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-30 12:30:33.140  1028  2716 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 12:30:33.140  1028  2716 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 12:30:33.144  1028  1368 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 12:30:33.147  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:33.147  1919  1919 D WfdsService: Supplicant Connection state is changed : false
08-30 12:30:33.147  1919  2212 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 12:30:33.147  1919  2212 D WfdsService: Set the WFDS Monitor: false
08-30 12:30:33.147  1919  2212 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:30:33.150  1028  1368 D WifiOffDelayIfNotUsed: stopMonitoring
,08-30 12:30:33.150  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:30:33.150  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:30:33.150  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:30:33.152  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:30:33.152  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:33.154  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 12:30:33.155  1028  1372 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 12:30:33.155  1028  1372 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 12:30:33.155  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:33.157  1028  1110 D BluetoothManagerService: Message: 20
08-30 12:30:33.157  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32dd7d3a:true
08-30 12:30:33.157  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:33.158  2482  2482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:33.159  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:33.169  1028  1110 D BluetoothManagerService: Message: 30
,08-30 12:30:33.174  1028  1110 D BluetoothManagerService: Message: 30
08-30 12:30:33.176  6854  6854 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 12:30:33.178  6854  6854 D BluetoothMap: Create BluetoothMap proxy object
08-30 12:30:33.178  1028  1110 D BluetoothManagerService: Message: 30
,08-30 12:30:33.185  1028  1110 D BluetoothManagerService: Message: 30
08-30 12:30:33.187  6854  6854 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 12:30:33.188  6854  6854 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 12:30:33.203  6854  6854 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 12:30:33.206  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-30 12:30:33.219  6854  6854 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:30:33.230  6854  6854 D BluetoothInputDevice: Proxy object connected
08-30 12:30:33.231  6854  6854 D HidProfile: Bluetooth service connected
,08-30 12:30:33.233  6854  6854 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:30:33.233  6854  6854 D PanProfile: Bluetooth service connected
08-30 12:30:33.234  6854  6854 D BluetoothMap: Proxy object connected
08-30 12:30:33.235  6854  6854 D MapProfile: Bluetooth service connected
08-30 12:30:33.235  6854  6854 D BluetoothMap: getConnectedDevices()
08-30 12:30:33.235  6854  6854 D BluetoothMap: Bluetooth is Not enabled
08-30 12:30:33.235  6854  6854 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 12:30:33.299  1028  1044 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6918 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 12:30:33.304  1028  1044 I ActivityManager: Killing 6465:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-30 12:30:33.384  1028  1918 W libprocessgroup: failed to open /acct/uid_10008/pid_6465/cgroup.procs: No such file or directory
08-30 12:30:33.384  6894  6894 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 12:30:33.384  6894  6894 W LG Account v2.2: No ProfileInfo entries
08-30 12:30:33.385  6894  6894 I LG Account v2.2: isEnabled: false
08-30 12:30:33.385  6894  6894 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 12:30:33.385  6894  6894 I Feature : [Lifetracker]Country: EU
08-30 12:30:33.385  6894  6894 I Feature : [Lifetracker]Operator: OPEN
08-30 12:30:33.385  6894  6894 I Feature : [Lifetracker]Ranking support: false
08-30 12:30:33.385  6894  6894 I Feature : [Lifetracker]Comfort support: false
08-30 12:30:33.385  6894  6894 I Feature : [Lifetracker]Accessory: true
08-30 12:30:33.386  6894  6894 I Feature : [Lifetracker]Health device: true
08-30 12:30:33.386  6894  6894 I Feature : [Lifetracker]Extra Pedometer: false
08-30 12:30:33.386  6894  6894 I Feature : [Lifetracker]Blood glucose device: false
08-30 12:30:33.386  6894  6894 I Feature : [Lifetracker]Device Number: 3
08-30 12:30:33.417  6854  6854 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 12:30:33.428  6854  6854 D BluetoothPermissionRequest: onReceive
08-30 12:30:33.431  6854  6854 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 12:30:33.444  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 12:30:33.446  1028  1918 I ActivityManager: Killing 5980:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-30 12:30:33.449  6918  6918 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:30:33.478  3890  3890 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 12:30:33.478  3890  3890 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 12:30:33.478  1028  1864 W libprocessgroup: failed to open /acct/uid_10011/pid_5980/cgroup.procs: No such file or directory
08-30 12:30:33.479  3890  3890 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-30 12:30:33.483  6918  6918 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 12:30:33.485  3890  3890 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:33.485  3890  3890 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:30:33.487  3890  3890 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:30:33.487  3890  3890 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:33.487  3890  3890 V BluetoothFtpService: Ftp Service closeService
08-30 12:30:33.488  3890  3890 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 12:30:33.493  3890  3890 V BluetoothFtpService: successfully stopped ftp service
,08-30 12:30:33.493  3890  3890 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:30:33.494  3890  3890 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:30:33.494  3890  3890 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:30:33.494  3890  3890 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:33.494  3890  3890 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 12:30:33.494  3890  3890 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:30:33.496  3890  3890 V BluetoothFtpService: Ftp Service onDestroy
08-30 12:30:33.496  3890  3890 V BluetoothFtpService: Ftp Service closeService
08-30 12:30:33.522  6918  6918 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 12:30:33.522  6918  6918 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 12:30:33.523  6918  6918 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 12:30:33.523  6918  6918 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 12:30:33.523  6918  6918 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 12:30:33.525  6918  6918 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 12:30:33.530  6918  6918 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 12:30:33.576  1028  1569 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6937 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:30:33.578  3890  3890 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:33.578  3890  3890 V BluetoothSapService: state: 13
08-30 12:30:33.579  3890  3890 V BluetoothSapService: Stopping SAP server process
,08-30 12:30:33.580  3890  3890 V BluetoothSapService: Sap Service closeSapService in
08-30 12:30:33.580  3890  3890 V BluetoothSapService: Close listen Socket : 
08-30 12:30:33.580  3890  3890 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:30:33.580  3890  3890 V BluetoothSapService: Close sapd  Socket : 
08-30 12:30:33.581  3890  3890 V BluetoothSapService: Sap Service closeSapService out
08-30 12:30:33.581  3890  3890 V BluetoothSapService: Sap Service onDestroy
08-30 12:30:33.581  3890  3890 V BluetoothSapService: Sap Service closeSapService in
08-30 12:30:33.582  3890  3890 V BluetoothSapService: Close listen Socket : 
08-30 12:30:33.582  3890  3890 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:30:33.582  3890  3890 V BluetoothSapService: Close sapd  Socket : 
08-30 12:30:33.582  3890  3890 V BluetoothSapService: Sap Service closeSapService out
08-30 12:30:33.596  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:30:33.602  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:33.632  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:33.634  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:33.637  6918  6918 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 12:30:33.638  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:30:33.638  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:33.638  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:30:33.641  6918  6918 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-30 12:30:33.642  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:30:33.648  6937  6937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:30:33.648  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:33.655  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:33.655  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:33.657  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 12:30:33.664  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:33.671  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:30:33.671  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:33.671  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:30:33.674  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:33.680  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:33.685  1028  1578 I ActivityManager: Killing 6002:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 12:30:33.720  1028  1900 W libprocessgroup: failed to open /acct/uid_10019/pid_6002/cgroup.procs: No such file or directory
08-30 12:30:33.720  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:30:33.721  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:33.725  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:33.769  3890  3973 D bt_hci_bdroid: cleanup
08-30 12:30:33.769  3890  4115 I bt_lpm  : LPM is already off!!!
,08-30 12:30:33.769  3890  4250 I bt_userial_mct: exiting userial_read_thread
08-30 12:30:33.769  3890  4250 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 12:30:33.770  3890  4109 W bt-btif : ag scb idx 1 not allocated
08-30 12:30:33.770  3890  4109 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:33.770  3890  3973 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:33.770  3890  4115 I bt_vendor: hw_epilog_process
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:33.770  3890  4109 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:33.770  3890  4109 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:30:33.771  3890  3973 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 12:30:33.771  3890  3973 D bt_userial_mct: userial_close
08-30 12:30:33.771  3890  3973 E bt_userial_mct: pthread_join() FAILED result:3
08-30 12:30:33.771  3890  3973 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 12:30:33.811  1028  1938 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6958 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 12:30:33.836  3890  3973 D bt_hci_bdroid: set_power 0
08-30 12:30:33.836  3890  3973 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 12:30:33.836  3890  3973 I bt_vendor: bluetooth satus is on
08-30 12:30:33.836  3890  3973 I bt_vendor: bt-vendor : resetting BT status
08-30 12:30:33.836  3890  3973 I bt_vendor: Starting hciattach daemon
08-30 12:30:33.836  3890  3973 I bt_vendor: try to set false
08-30 12:30:33.837  3890  3973 I bt_vendor: Starting hciattach daemon
08-30 12:30:33.837  3890  3973 I bt_vendor: try to set false
08-30 12:30:33.839  3890  3973 I bt_vendor: cleanup
08-30 12:30:33.840  3890  4109 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 12:30:33.841  3890  3973 I GKI_LINUX: GKI_exit_task 0 done
08-30 12:30:33.841  3890  3973 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 12:30:33.844  3890  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 12:30:33.848  3890  3890 D HeadsetService: Received stop request...Stopping profile...
08-30 12:30:33.850  3890  3890 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-30 12:30:33.850  3890  3890 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:33.850  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
08-30 12:30:33.851  3890  4011 D HeadsetStateMachine: Exit Disconnected: -1
08-30 12:30:33.853  1028  1028 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:33.853  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 12:30:33.855  1829  1829 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:33.855  1829  1829 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:33.855  1829  1829 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:33.858  3890  3890 D A2dpService: Received stop request...Stopping profile...
08-30 12:30:33.858  3890  4041 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:30:33.858  3890  3970 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 12:30:33.859  3890  3890 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 12:30:33.861  3890  3890 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 12:30:33.861  3890  3890 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:33.861  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
08-30 12:30:33.862  1028  1028 D BluetoothA2dp: Proxy object disconnected
08-30 12:30:33.863  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 12:30:33.864  3890  3890 D HidService: Received stop request...Stopping profile...
08-30 12:30:33.864  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
,08-30 12:30:33.866  3890  3890 D HealthService: Received stop request...Stopping profile...
08-30 12:30:33.867  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
08-30 12:30:33.869  6854  6854 D BluetoothInputDevice: Proxy object disconnected
08-30 12:30:33.869  6854  6854 D HidProfile: Bluetooth service disconnected
,08-30 12:30:33.870  3890  3890 D HeadsetStateMachine: Unbinding service...
08-30 12:30:33.871  3890  3890 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:30:33.871  3890  3890 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:30:33.871  3890  3890 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:30:33.871  3890  3890 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:30:33.871  3890  3890 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:30:33.871  3890  3890 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:33.871  3890  3890 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:30:33.872  3890  3890 D PanService: Received stop request...Stopping profile...
08-30 12:30:33.872  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
08-30 12:30:33.874  3890  3890 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:30:33.874  3890  3890 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:30:33.874  3890  3890 D BtGatt.GattService: stop()
08-30 12:30:33.874  6854  6854 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:30:33.874  6854  6854 D PanProfile: Bluetooth service disconnected
08-30 12:30:33.874  3890  3890 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 12:30:33.875  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
08-30 12:30:33.876  3890  3890 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:30:33.876  3890  3890 D BluetoothMapService: stop()
08-30 12:30:33.877  3890  3890 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 12:30:33.877  3890  3890 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 12:30:33.878  3890  3890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e9af816
,08-30 12:30:33.879  3890  3890 I BluetoothA2dpServiceJni: cleanupNative
08-30 12:30:33.879  3890  4042 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 12:30:33.880  3890  3890 I GKI_LINUX: GKI_exit_task 2 done
08-30 12:30:33.880  3890  3890 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 12:30:33.880  3890  3890 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:30:33.880  3890  3890 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:30:33.881  6854  6854 D BluetoothMap: Proxy object disconnected
08-30 12:30:33.881  6854  6854 D MapProfile: Bluetooth service disconnected
08-30 12:30:33.881  3890  3890 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:30:33.881  3890  3890 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:30:33.881  3890  3890 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:30:33.882  3890  3890 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:30:33.882  3890  3890 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:30:33.883  3890  3890 V BluetoothMapService: Handler(): got msg=4
08-30 12:30:33.883  3890  3890 D BluetoothMapService: MAP Service closeService in
08-30 12:30:33.883  3890  3890 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:30:33.883  3890  3890 V BluetoothMapService: MAP Service closeService out
08-30 12:30:33.884  3890  3890 D BluetoothMapService: cleanup()
08-30 12:30:33.884  3890  3890 D BluetoothMapService: MAP Service closeService in
08-30 12:30:33.884  3890  3890 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:30:33.884  3890  3890 V BluetoothMapService: MAP Service closeService out
08-30 12:30:33.884  3890  3970 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 12:30:33.884  3890  3970 D BluetoothAdapterProperties: Setting state to 10
08-30 12:30:33.884  3890  3970 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 12:30:33.884  3890  3970 I BluetoothAdapterState: Entering OffState
08-30 12:30:33.885  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:30:33.886  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 12:30:33.886  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 12:30:33.887  1829  1844 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:33.889  6854  6869 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:30:33.889  6854  6870 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 12:30:33.891  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:33.892  1829  1845 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:33.893  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:30:33.893  6854  6869 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:30:33.894  1829  2442 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:33.895  6854  6870 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:30:33.896  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 12:30:33.896  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 12:30:33.899  1028  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 12:30:33.899  1028  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,08-30 12:30:33.899  1028  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3733c373 mBinding = false
08-30 12:30:33.899  1028  1110 D BluetoothManagerService: Sending unbind request.
08-30 12:30:33.901  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 12:30:33.903  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:30:33.906  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:33.907  1919  2071 D LGBluetoothAPIService: Message: 2
08-30 12:30:33.908  6854  6854 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:30:33.909  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 12:30:33.909  6854  6854 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 12:30:33.910  1919  2071 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@21624941 mBinding = false
08-30 12:30:33.910  3890  3973 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 12:30:33.910  1582  1582 D BluetoothAdapter: 446821486: getState() :  mService = null. Returning STATE_OFF
08-30 12:30:33.910  1582  1582 D BluetoothAdapter: 446821486: getState() :  mService = null. Returning STATE_OFF
08-30 12:30:33.910  1919  2071 D LGBluetoothAPIService: Sending unbind request.
08-30 12:30:33.911  3890  3890 I GKI_LINUX: GKI_exit_task 1 done
08-30 12:30:33.911  3890  3890 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 12:30:33.911  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:33.911  3890  3890 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 12:30:33.911  3890  3890 I art     : --- WEIRD: removing null entry 246
08-30 12:30:33.911  3890  3890 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 12:30:33.911  3890  3890 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 12:30:33.914  3890  3890 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 12:30:33.914  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:30:33.914  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:33.916  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:33.917  3890  3890 I art     : System.exit called, status: 0
08-30 12:30:33.917  3890  3890 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:30:33.923  6854  6854 D DockEventReceiver: finishStartingService: stopping service
08-30 12:30:33.940   316  1380 V AudioFlinger: 3890 died, releasing its sessions
,08-30 12:30:33.940   316  1380 V AudioFlinger:  pid 1829 @ 0
08-30 12:30:33.940   316  1380 V AudioFlinger:  pid 3467 @ 1
08-30 12:30:33.940   316  1380 V AudioFlinger:  pid 3467 @ 2
08-30 12:30:33.941  6854  6854 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-30 12:30:33.956  1028  2010 I ActivityManager: Process com.android.bluetooth (pid 3890) has died
08-30 12:30:33.956  1028  2010 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 12:30:33.964  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:30:33.966  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:33.976  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 12:30:33.981  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:33.985  6854  6854 D BluetoothPermissionRequest: onReceive
08-30 12:30:33.987  6854  6854 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 12:30:33.987  6854  6854 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 12:30:33.989  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 12:30:34.042  1028  1972 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6981 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 12:30:34.056  6958  6979 W FormManager: Network not available. Please check & try again.
,08-30 12:30:34.073  6958  6980 V FormManager: Network unavailable.
,08-30 12:30:34.075  6958  6980 V FormManager: Network unavailable.
08-30 12:30:34.078  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:30:34.078  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:30:34.078  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:30:34.078  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:30:34.079  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:30:34.092  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:30:34.092  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:30:34.092  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:30:34.092  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:30:34.092  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:30:34.093  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 12:30:34.095  1028  1763 I ActivityManager: Killing 6497:com.lge.email/u0a23 (adj 15): empty #17
,08-30 12:30:34.128  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 12:30:34.128  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:34.130  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:34.132  1028  2009 W libprocessgroup: failed to open /acct/uid_10023/pid_6497/cgroup.procs: No such file or directory
08-30 12:30:34.145  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:30:34.154  4310  7000 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:30:34.155  6981  6981 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 12:30:34.155  6981  6981 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:30:34.156  6981  6981 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 12:30:34.156  6981  6981 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 12:30:34.156  4310  7001 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:30:34.157  4310  7001 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:30:34.161  6872  6872 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 12:30:34.162  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:34.162  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:30:34.166  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:30:34.173  6958  7003 W FormManager: Network not available. Please check & try again.
08-30 12:30:34.175  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:34.187  6981  6981 D BluetoothAdapterApp: Loading JNI Library
,08-30 12:30:34.187  6958  7004 V FormManager: Network unavailable.
08-30 12:30:34.190  6958  7004 V FormManager: Network unavailable.
08-30 12:30:34.195  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 12:30:34.196  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 12:30:34.197  6918  6918 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 12:30:34.230  6981  6981 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@134c019f Instance Count = 1
,08-30 12:30:34.233  6918  6918 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:34.234  6918  6918 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:30:34.236  6981  6981 D BluetoothAdapterApp: onCreate
08-30 12:30:34.243  6918  6918 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-30 12:30:34.244  6918  6918 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 12:30:34.244  6918  6918 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 12:30:34.244  6918  6918 V SoundPool: doLoad: loading sample sampleID=1
08-30 12:30:34.245  6918  6918 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 12:30:34.248  6918  6918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 12:30:34.248  6687  6687 D UEI.SmartControl: QS Service created
08-30 12:30:34.249  6918  7007 V SoundPool: Start decode
08-30 12:30:34.250  6918  7007 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 12:30:34.250   316  2156 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 12:30:34.251   316  2156 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 12:30:34.251   316  2156 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 12:30:34.251   316  2156 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 12:30:34.251   316  2156 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 12:30:34.251   316  2156 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
,08-30 12:30:34.251   316  2156 V MediaPlayerService: player type = 3
08-30 12:30:34.251   316  2156 V AwesomePlayer: AwesomePlayer create()
,08-30 12:30:34.251   316  2156 V AwesomePlayer: reset_l() 
08-30 12:30:34.251   316  2156 V AwesomePlayer: cancelPlayerEvents
,08-30 12:30:34.252   316  2156 V AwesomePlayer: setAudioSink() 
08-30 12:30:34.252   316  2156 V AwesomePlayer: reset_l() 
08-30 12:30:34.252   316  2156 V AudioCache: notify(0xb1432140, 8, 0, 0)
,08-30 12:30:34.252   316  2156 V AudioCache: ignored
08-30 12:30:34.252   316  2156 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:34.252   316  2156 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 12:30:34.252   316  2156 V AwesomePlayer: setDataSource_l dataSource,
08-30 12:30:34.252   316  2156 V LGParserOSAL: SniffLGParser start
08-30 12:30:34.252   316  2156 V LGParserOSAL: MainType:5, SubType=0
08-30 12:30:34.252   316  2156 V LGParserOSAL: #### check Mime : application/ogg
08-30 12:30:34.253   316  2156 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 12:30:34.253   316  2156 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 12:30:34.260  6981  6981 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 12:30:34.261  6981  6981 D ProfileConfigQcom: Adding HeadsetService
08-30 12:30:34.261  6981  6981 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 12:30:34.261  6981  6981 D ProfileConfigQcom: Adding A2dpService
08-30 12:30:34.261  6687  6687 I UEI.SmartControl: Service initServices...
08-30 12:30:34.261  6981  6981 D ProfileConfigQcom: [BTUI] HidService is supported
,08-30 12:30:34.261  6687  6687 D UEI.SmartControl: QS start get config
08-30 12:30:34.261  6981  6981 D ProfileConfigQcom: Adding HidService
,08-30 12:30:34.264  6981  6981 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 12:30:34.266  6981  6981 D ProfileConfigQcom: Adding HealthService
08-30 12:30:34.266  6981  6981 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 12:30:34.267  6981  6981 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 12:30:34.267  6981  6981 D ProfileConfigQcom: Adding PanService
08-30 12:30:34.267  6981  6981 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 12:30:34.267  6981  6981 D ProfileConfigQcom: Adding GattService
08-30 12:30:34.268  6981  6981 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 12:30:34.268  6981  6981 D ProfileConfigQcom: Adding BluetoothMapService
08-30 12:30:34.268  6981  6981 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 12:30:34.270  6981  6981 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 12:30:34.275  6854  6854 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 12:30:34.277  6981  6981 V LGMDMManagerInternal: Create singleton instance
08-30 12:30:34.275  6918  6918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:30:34.280  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 12:30:34.300  6918  6918 V LGMDMManager: Create singleton instance
,08-30 12:30:34.307   316  2156 V LGParserOSAL: supported mime: application/ogg
08-30 12:30:34.307   316  2156 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 12:30:34.307   316  2156 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 12:30:34.307   316  2156 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 12:30:34.307   316  2156 V AwesomePlayer: AudioTrack Setting
08-30 12:30:34.307   316  2156 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 12:30:34.307   316  2156 V AwesomePlayer: setAudioSource() 
08-30 12:30:34.307   316  2156 V MediaPlayerService: prepare
08-30 12:30:34.307   316  2156 V AwesomePlayer: prepareAsync_l() 
08-30 12:30:34.307   316  2156 V MediaPlayerService: wait for prepare
08-30 12:30:34.307   316  7009 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 12:30:34.307   316  7009 V AwesomePlayer: initAudioDecoder() 
08-30 12:30:34.307   316  7009 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 12:30:34.308   316  7009 V AudioSystem: isOffloadSupported()
08-30 12:30:34.308   316  7009 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 12:30:34.308   316  7009 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 12:30:34.308   316  7009 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:30:34.308   316  7009 V AwesomePlayer: getUseOffload() = 0 
08-30 12:30:34.308   316  7009 V OMXCodec: OMXCodec::Create
08-30 12:30:34.308   316  7009 V OMXCodec: findMatchingCodecs()
08-30 12:30:34.308   316  7009 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 12:30:34.308   316  7009 V OMXCodec: matchingCodecs.size()=1
08-30 12:30:34.308   316  7009 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 12:30:34.309   316  7009 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 12:30:34.309   316  7009 V LGCodecAdapter: LG Codec Adapter start
08-30 12:30:34.309   316  7009 V OMXCodec: OMXCodec Createtor
08-30 12:30:34.309   316  7009 V OMXCodec: setComponentRole
08-30 12:30:34.310   316  7009 V OMXCodec: configureCodec protected=0
08-30 12:30:34.310   316  7009 V LGCodecAdapter: called getLGCodecSpecificData
08-30 12:30:34.310   316  7009 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 12:30:34.310   316  7009 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 12:30:34.310   316  7009 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 12:30:34.310   316  7009 V LGCodecOSAL: Not support LGCodec
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 12:30:34.310   316  7009 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 12:30:34.310   316  7009 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 12:30:34.310   316  7009 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 12:30:34.310   316  7009 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 12:30:34.310   316  7009 V AudioSystem: isOffloadSupported()
08-30 12:30:34.310   316  7009 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 12:30:34.310   316  7009 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 12:30:34.310   316  7009 V OMXCodec: init()
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-30 12:30:34.310   316  7009 V OMXCodec: allocateBuffers
08-30 12:30:34.310   316  7009 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-30 12:30:34.310   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-30 12:30:34.310   316  7009 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 12:30:34.311   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 12:30:34.311   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-30 12:30:34.311   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-30 12:30:34.311   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 12:30:34.311   316  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-30 12:30:34.311   316  7009 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 12:30:34.311   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 12:30:34.311   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 12:30:34.312   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 12:30:34.312   316  7009 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 12:30:34.312   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 12:30:34.312   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 12:30:34.312   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 12:30:34.312   316  7009 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 12:30:34.312   316  7009 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 12:30:34.312   316  7009 V AudioCache: notify(0xb1432140, 5, 0, 0)
08-30 12:30:34.312   316  7009 V AudioCache: ignored
08-30 12:30:34.312   316  7009 V AudioCache: notify(0xb1432140, 1, 0, 0)
08-30 12:30:34.312   316  7009 V AudioCache: prepared
08-30 12:30:34.312   316  2156 V AudioCache: wait - success
08-30 12:30:34.312   316  2156 V MediaPlayerService: start
08-30 12:30:34.312   316  2156 V AwesomePlayer: play_l() 
08-30 12:30:34.312   316  2156 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 12:30:34.313   316  2156 V AwesomePlayer: createAudioPlayer_l
,08-30 12:30:34.313   316  2156 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 12:30:34.313   316  2156 V AwesomePlayer: startAudioPlayer_l() 
08-30 12:30:34.313   316  2156 D AudioPlayer: start of Playback, useOffload 0
08-30 12:30:34.313   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 12:30:34.313   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 12:30:34.315   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 12:30:34.315   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 12:30:34.315   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-30 12:30:34.315   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 12:30:34.315   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 12:30:34.315   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 12:30:34.316   316  7011 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-30 12:30:34.316   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-30 12:30:34.317   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on output port
08-30 12:30:34.317   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 12:30:34.317   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 12:30:34.318   316  2156 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 12:30:34.318   316  2156 V AudioCache: notify(0xb1432140, 6, 0, 0)
08-30 12:30:34.318   316  2156 V AudioCache: ignored
,08-30 12:30:34.318   316  2156 V MediaPlayerService: wait for playback complete
,08-30 12:30:34.326   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.327   316  7012 V AudioCache: memcpy(0xaf006000, 0xb17fb000, 4096)
08-30 12:30:34.328   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.328   316  7012 V AudioCache: memcpy(0xaf007000, 0xb17fb000, 4096)
08-30 12:30:34.328   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.328   316  7012 V AudioCache: memcpy(0xaf008000, 0xb17fb000, 4096)
08-30 12:30:34.329   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.329   316  7012 V AudioCache: memcpy(0xaf009000, 0xb17fb000, 4096)
08-30 12:30:34.329   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.329   316  7012 V AudioCache: memcpy(0xaf00a000, 0xb17fb000, 4096)
08-30 12:30:34.330   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.330   316  7012 V AudioCache: memcpy(0xaf00b000, 0xb17fb000, 4096)
08-30 12:30:34.330   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.330   316  7012 V AudioCache: memcpy(0xaf00c000, 0xb17fb000, 4096)
08-30 12:30:34.331   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.331   316  7012 V AudioCache: memcpy(0xaf00d000, 0xb17fb000, 4096)
08-30 12:30:34.331   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.331   316  7012 V AudioCache: memcpy(0xaf00e000, 0xb17fb000, 4096)
08-30 12:30:34.331   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.331   316  7012 V AudioCache: memcpy(0xaf00f000, 0xb17fb000, 4096)
08-30 12:30:34.332   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.332   316  7012 V AudioCache: memcpy(0xaf010000, 0xb17fb000, 4096)
08-30 12:30:34.332   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.332   316  7012 V AudioCache: memcpy(0xaf011000, 0xb17fb000, 4096)
08-30 12:30:34.333   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.333   316  7012 V AudioCache: memcpy(0xaf012000, 0xb17fb000, 4096)
08-30 12:30:34.333   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.333   316  7012 V AudioCache: memcpy(0xaf013000, 0xb17fb000, 4096)
08-30 12:30:34.334   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.334   316  7012 V AudioCache: memcpy(0xaf014000, 0xb17fb000, 4096)
08-30 12:30:34.334   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.334   316  7012 V AudioCache: memcpy(0xaf015000, 0xb17fb000, 4096)
08-30 12:30:34.334   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.334   316  7012 V AudioCache: memcpy(0xaf016000, 0xb17fb000, 4096)
08-30 12:30:34.335   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.335   316  7012 V AudioCache: memcpy(0xaf017000, 0xb17fb000, 4096)
08-30 12:30:34.335   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.335   316  7012 V AudioCache: memcpy(0xaf018000, 0xb17fb000, 4096)
08-30 12:30:34.336   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.336   316  7012 V AudioCache: memcpy(0xaf019000, 0xb17fb000, 4096)
08-30 12:30:34.336   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.337   316  7012 V AudioCache: memcpy(0xaf01a000, 0xb17fb000, 4096)
08-30 12:30:34.337   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.337   316  7012 V AudioCache: memcpy(0xaf01b000, 0xb17fb000, 4096)
08-30 12:30:34.337   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.337   316  7012 V AudioCache: memcpy(0xaf01c000, 0xb17fb000, 4096)
08-30 12:30:34.338   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.338   316  7012 V AudioCache: memcpy(0xaf01d000, 0xb17fb000, 4096)
08-30 12:30:34.338   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.338   316  7012 V AudioCache: memcpy(0xaf01e000, 0xb17fb000, 4096)
08-30 12:30:34.339   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.339   316  7012 V AudioCache: memcpy(0xaf01f000, 0xb17fb000, 4096)
08-30 12:30:34.339   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.339   316  7012 V AudioCache: mem,cpy(0xaf020000, 0xb17fb000, 4096)
08-30 12:30:34.339   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.339   316  7012 V AudioCache: memcpy(0xaf021000, 0xb17fb000, 4096)
08-30 12:30:34.340   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.340   316  7012 V AudioCache: memcpy(0xaf022000, 0xb17fb000, 4096)
08-30 12:30:34.340   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.340   316  7012 V AudioCache: memcpy(0xaf023000, 0xb17fb000, 4096)
08-30 12:30:34.340  6981  6981 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:34.341   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.341   316  7012 V AudioCache: memcpy(0xaf024000, 0xb17fb000, 4096)
08-30 12:30:34.341   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.341   316  7012 V AudioCache: memcpy(0xaf025000, 0xb17fb000, 4096)
08-30 12:30:34.342   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.342   316  7012 V AudioCache: memcpy(0xaf026000, 0xb17fb000, 4096)
08-30 12:30:34.342   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.342   316  7012 V AudioCache: memcpy(0xaf027000, 0xb17fb000, 4096)
08-30 12:30:34.342   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.343   316  7012 V AudioCache: memcpy(0xaf028000, 0xb17fb000, 4096)
08-30 12:30:34.343  6981  6981 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:30:34.343  6981  6981 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:30:34.343   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.343   316  7012 V AudioCache: memcpy(0xaf029000, 0xb17fb000, 4096)
08-30 12:30:34.343  6981  6981 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:30:34.343   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.343   316  7012 V AudioCache: memcpy(0xaf02a000, 0xb17fb000, 4096)
08-30 12:30:34.344   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.344   316  7012 V AudioCache: memcpy(0xaf02b000, 0xb17fb000, 4096)
08-30 12:30:34.344  6981  6981 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:34.344  6981  6981 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 12:30:34.344   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.344   316  7012 V AudioCache: memcpy(0xaf02c000, 0xb17fb000, 4096)
08-30 12:30:34.345   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.345   316  7012 V AudioCache: memcpy(0xaf02d000, 0xb17fb000, 4096)
08-30 12:30:34.345   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.345   316  7012 V AudioCache: memcpy(0xaf02e000, 0xb17fb000, 4096)
08-30 12:30:34.346   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.346   316  7012 V AudioCache: memcpy(0xaf02f000, 0xb17fb000, 4096)
,08-30 12:30:34.347   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.347   316  7012 V AudioCache: memcpy(0xaf030000, 0xb17fb000, 4096)
08-30 12:30:34.347   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.347   316  7012 V AudioCache: memcpy(0xaf031000, 0xb17fb000, 4096)
08-30 12:30:34.348   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.348   316  7012 V AudioCache: memcpy(0xaf032000, 0xb17fb000, 4096)
08-30 12:30:34.348   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.348   316  7012 V AudioCache: memcpy(0xaf033000, 0xb17fb000, 4096)
08-30 12:30:34.348   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.348   316  7012 V AudioCache: memcpy(0xaf034000, 0xb17fb000, 4096)
08-30 12:30:34.348   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-30 12:30:34.349   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.349   316  7012 V AudioCache: memcpy(0xaf035000, 0xb17fb000, 4096)
08-30 12:30:34.349   316  7012 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 12:30:34.349   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.349   316  7012 V AudioCache: memcpy(0xaf036000, 0xb17fb000, 4096)
08-30 12:30:34.349   316  7012 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 12:30:34.349   316  7012 V AudioCache: write(0xb17fb000, 4096)
08-30 12:30:34.349   316  7012 V AudioCache: memcpy(0xaf037000, 0xb17fb000, 4096)
08-30 12:30:34.349   316  7012 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 12:30:34.349   316  7012 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 12:30:34.349   316  7012 V AwesomePlayer: postAudioEOS() 
08-30 12:30:34.349   316  7012 V AudioCache: write(0xb17fb000, 280)
08-30 12:30:34.349   316  7012 V AudioCache: memcpy(0xaf038000, 0xb17fb000, 280)
08-30 12:30:34.350  6937  6937 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 12:30:34.350   316  7009 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 12:30:34.350   316  7009 V AwesomePlayer: onStreamDone
08-30 12:30:34.350   316  7009 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 12:30:34.350   316  7009 V AudioCache: notify(0xb1432140, 2, 0, 0)
08-30 12:30:34.350   316  7009 V AudioCache: playback complete
08-30 12:30:34.350   316  7009 V AwesomePlayer: pause_l() 
08-30 12:30:34.350   316  7009 V AudioCache: notify(0xb1432140, 7, 0, 0)
08-30 12:30:34.351   316  7009 V AudioCache: ignored
08-30 12:30:34.351   316  7009 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:34.351   316  7009 D AudioPlayer: Pause Playback at 1068125
08-30 12:30:34.351   316  2156 V AudioCache: wait - success
08-30 12:30:34.351   316  2156 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 12:30:34.351   316  2156 V AwesomePlayer: reset_l() 
08-30 12:30:34.351   316  2156 V AudioCache: notify(0xb1432140, 8, 0, 0)
08-30 12:30:34.351   316  2156 V AudioCache: ignored
08-30 12:30:34.351   316  2156 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:34.351   316  2156 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 12:30:34.351   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 12:30:34.351   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 12:30:34.351   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 12:30:34.351   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-30 12:30:34.351   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] f,reeBuffer portIndex=0,bufIndex=0
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 12:30:34.352   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 12:30:34.352   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 12:30:34.352   316  7011 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 12:30:34.352   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 12:30:34.352   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 12:30:34.353   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 12:30:34.354   316  2156 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 12:30:34.354   316  2156 D AudioPlayer: AudioPlayer releasing audio source
08-30 12:30:34.354   316  2156 D AudioPlayer: AudioPlayer done releasing audio source
08-30 12:30:34.354   316  2156 V AwesomePlayer: reset_l() 
08-30 12:30:34.354   316  2156 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:34.354   316  2156 V AwesomePlayer: ~AwesomePlayer call
08-30 12:30:34.355   316  2156 V AwesomePlayer: reset_l() 
08-30 12:30:34.355   316  2156 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:34.355  6918  7007 V SoundPool: close(31)
08-30 12:30:34.355  6918  7007 V SoundPool: pointer = 0xa0032000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 12:30:34.372  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 12:30:34.373  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 12:30:34.375  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7674
,08-30 12:30:34.528  6687  6687 I UEI.SmartControl: Supports setup maps: true,
,08-30 12:30:34.530  6687  6687 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 12:30:34.530  6687  6687 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:30:34.530  6687  6687 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:30:34.530  6687  6687 I UEI.SmartControl: ### init IR Blaster...
08-30 12:30:34.533  6687  6687 D serial_port: Configuring serial port
08-30 12:30:34.534  6687  6687 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:30:34.534  6687  6687 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:30:34.534  6687  6687 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:30:34.534  6687  6687 I UEI.SmartControl: Get version...
08-30 12:30:34.552  6687  7014 D UEI.SmartControl: serial port data available: 21
,08-30 12:30:34.579  6687  6687 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 12:30:34.579  6687  6687 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 12:30:34.579  6687  6687 I UEI.SmartControl: QS saving settings...
,08-30 12:30:34.582  6687  6687 D UEI.SmartControl: IR Blaster version: 25672567
08-30 12:30:34.598  6687  7014 D UEI.SmartControl: serial port data available: 4
,08-30 12:30:34.632  6687  7020 I UEI.SmartControl: Device manager: loading config....
,08-30 12:30:34.634  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 12:30:34.636  6687  7020 D UEI.SmartControl: ----------- loading internal config...
08-30 12:30:34.637  6687  6687 E UEI.SmartControl: Services init done
08-30 12:30:34.637  6687  6687 D UEI.SmartControl: QS Service init finished
08-30 12:30:34.640  6687  6687 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:30:34.640  6687  6687 D UEI.SmartControl: QS Service version code: 201091
08-30 12:30:34.641  6687  6687 D UEI.SmartControl: Service requested: Control
08-30 12:30:34.646  6687  6687 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 12:30:34.646  6687  7020 E UEI.SmartControl: Loading SETTINGS...
08-30 12:30:34.649  6687  6687 D UEI.SmartControl: Internal service binding...
,08-30 12:30:34.649  6918  6918 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 12:30:34.652  6687  6703 I UEI.SmartControl: ------ IControl API: 11
08-30 12:30:34.652  6687  6703 D UEI.SmartControl: File observer start...
08-30 12:30:34.653  6687  6703 E UEI.SmartControl: IR Port is disabled: false
08-30 12:30:34.654  6687  6703 D UEI.SmartControl: Starting file observer...
,08-30 12:30:34.654  6687  6703 I UEI.SmartControl: Registering callback...
08-30 12:30:34.656  6687  6705 I UEI.SmartControl: ------ IControl API: 19
08-30 12:30:34.657  6687  6705 I UEI.SmartControl: Registering Services Ready callback...
08-30 12:30:34.658  6687  7020 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 12:30:34.672  6687  7019 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:30:34.673  6918  6933 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 12:30:34.674  6687  7019 D UEI.SmartControl: -----service ready thread exits
,08-30 12:30:34.676  6918  7005 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 12:30:34.677  6918  7005 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 12:30:34.679  6918  6918 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 12:30:34.680  6918  6918 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 12:30:34.680  6687  6703 I UEI.SmartControl: ------ IControl API: 8
08-30 12:30:34.684  6918  6918 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 12:30:34.685  6918  6918 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 12:30:34.686  6918  6918 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 12:30:34.687  6918  6918 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-30 12:30:34.689  6918  6918 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 12:30:34.690  6918  6918 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 12:30:34.692  6918  6918 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 12:30:34.697  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 12:30:34.699  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 12:30:34.701  6918  6918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:30:34.702  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 12:30:34.704  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 12:30:34.707  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 12:30:34.708  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-30 12:30:34.711  6918  6918 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472553034709]
08-30 12:30:34.718  6918  6918 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 12:30:34.722  1028  1569 I ActivityManager: Killing 6548:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-30 12:30:34.747  6918  7022 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 12:30:34.777  1028  1569 I ActivityManager: Killing 6034:com.android.gallery3d/u0a27 (adj 15): empty #18
,08-30 12:30:34.878  1028  1578 W libprocessgroup: failed to open /acct/uid_10027/pid_6034/cgroup.procs: No such file or directory
,08-30 12:30:34.890  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 12:30:34.894  1028  2009 W libprocessgroup: failed to open /acct/uid_10061/pid_6548/cgroup.procs: No such file or directory
08-30 12:30:34.895  6918  6918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:30:34.898  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 12:30:34.899  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 12:30:34.900  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 12:30:34.901  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 12:30:34.902  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-30 12:30:34.920  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3],
,08-30 12:30:35.904  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:35.919  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 12:30:35.941  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:35.944  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:35.945  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:35.946  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:35.952  1028  1110 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:30:35.956  1028  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:35.966  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:35.968  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:35.970  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:35.971  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:30:35.974  6422  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:30:35.985  5737  5737 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:30:35.993  5737  5737 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 12:30:36.011  2197  2197 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:36.073  1028  1569 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7029 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 12:30:36.121  1028  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:36.123  1028  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:36.123  1028  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:30:36.154  7029  7029 I AppUp4:AppBoxCP: onCreate
08-30 12:30:36.155  7029  7029 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 12:30:36.165  7029  7029 I AppUp4:DB:  setFingerPrint start
08-30 12:30:36.165  7029  7029 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 12:30:36.173  7029  7029 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-30 12:30:36.173  7029  7029 I AppUp4:DB:  SDK version = 21
08-30 12:30:36.173  7029  7029 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 12:30:36.174  7029  7029 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 12:30:36.175  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:30:36.175  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:36.178  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:30:36.178  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 12:30:36.185  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:30:36.227  7029  7029 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:36.228  7029  7029 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:36.234  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
08-30 12:30:36.234  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:30:36.234  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:30:36.235  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:30:36.235  7029  7029 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 12:30:36.235  7029  7029 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 12:30:36.236  7029  7062 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 12:30:36.236  7029  7062 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 12:30:36.237  7029  7062 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 12:30:36.239  1028  1043 I ActivityManager: Killing 6106:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 12:30:36.419  1028  1863 W libprocessgroup: failed to open /acct/uid_10080/pid_6106/cgroup.procs: No such file or directory
,08-30 12:30:36.422  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:36.423  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 12:30:36.428  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:36.430  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:36.437  4310  7068 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:30:36.446  4310  7069 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:36.446  4310  7069 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:30:36.497  1028  1971 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7070 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 12:30:36.563  7070  7070 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:30:36.564  7070  7070 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:30:36.566  7070  7070 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:30:36.567  7070  7070 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:30:36.667  7070  7070 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 12:30:36.699  7070  7070 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 12:30:36.759  7070  7070 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:30:36.798  7070  7070 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:30:36.798  7070  7070 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:36.936  7070  7070 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:30:36.986  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-30 12:30:36.986  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:36.987  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 12:30:36.990  7070  7070 I HubEmail: JNI_OnLoad()
08-30 12:30:36.991  7070  7070 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:30:36.991  7070  7070 I HubEmail: registerNatives()
08-30 12:30:36.991  7070  7070 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:30:36.991  7070  7070 I HubEmail: registerNativeMethods()
08-30 12:30:36.991  7070  7070 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:30:36.991  7070  7070 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 12:30:37.036  1028  1938 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7099 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 12:30:37.046  7070  7096 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:37.057  6958  7097 W FormManager: Network not available. Please check & try again.
,08-30 12:30:37.064  6958  7098 V FormManager: Network unavailable.
08-30 12:30:37.067  6958  7098 V FormManager: Network unavailable.
08-30 12:30:37.073  1028  1863 I ActivityManager: Killing 6137:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 12:30:37.174  1028  1569 W libprocessgroup: failed to open /acct/uid_10097/pid_6137/cgroup.procs: No such file or directory
,08-30 12:30:37.272  7099  7099 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:37.272  7099  7099 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:37.278  7099  7099 D PhoneMonitor: Register our PhoneStateListener
08-30 12:30:37.286  1028  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{398fea1c type 2 when 160106 com.google.android.gms} when 160106
08-30 12:30:37.303  7099  7099 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 12:30:37.307  7099  7099 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:30:37.334  7099  7099 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 12:30:37.337  7099  7099 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 12:30:37.338  7099  7099 D TelephonyAutoProfiling: [parse] Load xml
08-30 12:30:37.348  7099  7099 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
,08-30 12:30:37.348  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
,08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
,08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
,08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 12:30:37.349  7099  7099 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 12:30:37.349  7099  7099 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 12:30:37.364  7099  7099 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 12:30:37.382  1028  1972 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7132 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:30:37.385  1028  1972 I ActivityManager: Killing 6611:com.lge.eula/1000 (adj 15): empty #17
08-30 12:30:37.447  1028  1918 W libprocessgroup: failed to open /acct/uid_1000/pid_6611/cgroup.procs: No such file or directory
,08-30 12:30:37.696  1028  1918 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7153 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 12:30:37.697  1028  1918 I ActivityManager: Killing 6650:com.lge.bnr/1000 (adj 15): empty #17
08-30 12:30:37.715   345   345 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 490us total 27.018ms
,08-30 12:30:37.739   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 731us total 20.774ms
,08-30 12:30:37.758  1028  1367 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:37.759  1028  1367 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:37.766   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 25.134ms
,08-30 12:30:37.811  1028  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6650/cgroup.procs: No such file or directory
,08-30 12:30:37.907  1028  1368 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-30 12:30:37.909  1028  1368 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 12:30:37.917  1028  1578 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7179 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:30:37.920  1028  1578 I ActivityManager: Killing 2130:com.lge.music/u0a34 (adj 15): empty #17
08-30 12:30:37.957   316  1380 V AudioFlinger: 2130 died, releasing its sessions
08-30 12:30:37.957   316  1380 V AudioFlinger:  pid 1829 @ 0
08-30 12:30:37.957   316  1380 V AudioFlinger:  pid 3467 @ 1
08-30 12:30:37.957   316  1380 V AudioFlinger:  pid 3467 @ 2
,08-30 12:30:37.997  1028  1900 D WifiServiceImplEx: setWifiEnabled: true pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 12:30:37.998  1028  1863 W libprocessgroup: failed to open /acct/uid_10034/pid_2130/cgroup.procs: No such file or directory
08-30 12:30:38.001  1028  1900 D WifiService: setWifiEnabled: true pid=6629, uid=10118
08-30 12:30:38.001  1028  1900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:30:38.015  1028  1368 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 12:30:38.015  1028  1368 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-30 12:30:38.016  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:30:38.016  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 12:30:38.016  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:30:38.016  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 12:30:38.016  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:30:38.017  1028  1368 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 12:30:38.017  1028  1368 E WifiHW  : unknown target_country: EU , set to default
08-30 12:30:38.017  1028  1368 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 12:30:38.017  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:30:38.017  1028  1368 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 12:30:38.017  1028  1368 I WifiUtil: gEnableBmps=1
08-30 12:30:38.017  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:30:38.039  7179  7179 I art     : Almond Protected OAT
,08-30 12:30:38.093  7179  7179 D WeatherApplication: removeAccount
,08-30 12:30:38.095  7179  7179 D WeatherApplication: Account.length = 0
,08-30 12:30:38.096  7179  7179 E WeatherApplication: OPERATOR:OPEN
08-30 12:30:38.105  7179  7179 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:38
,08-30 12:30:38.112  7179  7179 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 12:30:38.112  7179  7179 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:30:38.116  7179  7179 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:30:38.120  7179  7179 D WeatherAncestor: connectivity changed - connection : true
,08-30 12:30:38.121  7179  7179 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 12:30:38.134  7179  7179 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-30 12:30:38.134  7179  7179 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-30 12:30:38.134  7179  7179 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 12:30:38.157  7179  7179 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 12:30:38.157  7179  7179 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:38
,08-30 12:30:38.223  1028  1938 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7202 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:30:38.225  1028  1938 I ActivityManager: Killing 6067:com.android.vending/u0a44 (adj 15): empty #17
,08-30 12:30:38.319  1028  1863 W libprocessgroup: failed to open /acct/uid_10044/pid_6067/cgroup.procs: No such file or directory
,08-30 12:30:38.477   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 12:30:38.477   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:30:38.477   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:30:38.479  7202  7223 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:30:38.481   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:30:38.481   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:30:38.481   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:30:38.482  7202  7223 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 12:30:38.495   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:30:38.495   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:30:38.495   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:30:38.495  7202  7227 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 12:30:38.498   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:30:38.498   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:30:38.498   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:30:38.499  7202  7227 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 12:30:38.705  7202  7202 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:30:38.714  7202  7202 I LibraryLoader: Loading: webviewchromium
08-30 12:30:38.717  7202  7202 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1547-1550)
08-30 12:30:38.717  7202  7202 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:30:38.724  7202  7202 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b321552}
,08-30 12:30:38.728  7202  7202 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:30:38.729  7202  7202 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:30:38.763  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 12:30:38.767   312   887 D SoftapController: Softap fwReload - Ok
08-30 12:30:38.769  1028  1368 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (747ms)
08-30 12:30:38.773   312   887 D CommandListener: Setting iface cfg
08-30 12:30:38.773   312   887 D CommandListener: Trying to bring down wlan0
08-30 12:30:38.776  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 12:30:38.779  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:30:38.783  7202  7202 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 12:30:38.785  7202  7202 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:30:38.797   312   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:38.802  1028  1368 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 12:30:38.799  7258  7258 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:38.799  7258  7258 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:38.808  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:30:38.808  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:30:38.808  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:30:38.814  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:38.815  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 12:30:38.819  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:38.822  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:38.824  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 12:30:38.825  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:38.825  1028  1368 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 12:30:38.825  1028  1368 D WifiMonitor: connecting to supplicant
08-30 12:30:38.844  7258  7258 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 12:30:38.845  7202  7202 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 12:30:38.847  7202  7202 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 12:30:38.847  7202  7202 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 12:30:38.849   316  2159 V AudioPolicyService: registerClient() client 0xb102cdc0, uid 10093
08-30 12:30:38.850  7202  7257 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 12:30:38.868  7202  7202 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:30:38.868  7202  7202 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:30:38.868  7202  7202 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:30:38.868  7202  7202 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:30:38.868  7202  7202 I Adreno-EGL: Remote Branch: 
08-30 12:30:38.868  7202  7202 I Adreno-EGL: Local Patches: 
08-30 12:30:38.868  7202  7202 I Adreno-EGL: Reconstruct Branch: 
08-30 12:30:38.877  7258  7258 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 12:30:38.877  7258  7258 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 12:30:38.951  7202  7202 I NSApplication: Starting up...
,08-30 12:30:38.965  7258  7258 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 12:30:39.015  7258  7258 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 12:30:39.016  1028  1971 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7282 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 12:30:39.018  1028  1971 I ActivityManager: Killing 6774:com.lge.clock/u0a10 (adj 15): empty #17
08-30 12:30:39.022  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 12:30:39.023  7258  7258 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 12:30:39.026  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 12:30:39.026  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:30:39.026  1028  7294 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 12:30:39.026  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 12:30:39.026  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 12:30:39.026  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:30:39.026  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:30:39.027  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 12:30:39.028  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:30:39.029  1028  1368 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-30 12:30:39.031  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.033  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.034  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.035  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.037  1028  1368 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 12:30:39.037  1028  1368 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 12:30:39.038  1028  1368 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 12:30:39.038  1028  1368 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 12:30:39.038  1028  1368 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-30 12:30:39.076  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:30:39.076  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:30:39.076  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:30:39.076  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.076  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.076  1028  1972 W libprocessgroup: failed to open /acct/uid_10010/pid_6774/cgroup.procs: No such file or directory
,08-30 12:30:39.076  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.076  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.077  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:30:39.082  1028  1368 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 12:30:39.083  1028  1368 D WifiNative-wlan0: SET update_config 1: returned true
08-30 12:30:39.084  1028  1368 D WifiConfigStore: Loading config and enabling all networks 
08-30 12:30:39.084  1028  1368 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 12:30:39.086  1028  1368 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 12:30:39.089  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.090  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-30 12:30:39.090  1028  1372 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 12:30:39.092  1919  1919 D WfdService: Waiting for WifiP2p enabling
08-30 12:30:39.094  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:39.094  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:39.094  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:39.094  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:39.095  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:39.095  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:39.095  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:39.095  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:39.097  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: nu,ll
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:39.097  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:39.097  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:39.097  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:39.102  1028  1368 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 12:30:39.114  1028  1368 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 12:30:39.114  1028  1368 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 12:30:39.115  1028  1368 D WifiStateMachine: enableVerboseLogging : level 2
08-30 12:30:39.115  1028  1368 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 12:30:39.116  1028  1368 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 12:30:39.116  1028  1368 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 12:30:39.116  1028  1368 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 12:30:39.116  1028  1368 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-30 12:30:39.117  1028  1368 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 12:30:39.117  1028  1368 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 12:30:39.117  1028  1368 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 12:30:39.117  1028  1368 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 12:30:39.118  1028  1368 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 12:30:39.118  1028  1368 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 12:30:39.118  1028  1368 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 12:30:39.119  1028  1368 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 12:30:39.119  1028  1368 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 12:30:39.120  1028  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:30:39.120  1028  1368 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 12:30:39.120  1919  1919 D WfdsService: Supplicant Connection state is changed : true
08-30 12:30:39.120  1028  1368 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 12:30:39.120  1028  1368 D WifiNative-HAL: Setting external_sim to 1
08-30 12:30:39.120  1028  1368 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 12:30:39.120  1919  2212 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,08-30 12:30:39.120  1919  2212 D WfdsService: Set the WFDS Monitor: true
08-30 12:30:39.120  1919  2212 D WfdsMonitor: WfdsMonitorThread create
08-30 12:30:39.120  1919  2212 D WfdsMonitor: WFDS Monitor is created and started
08-30 12:30:39.120  1028  1368 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 12:30:39.120  1919  2212 D WfdsService: WiFi: Supplicant connection re-established
08-30 12:30:39.120  1028  1368 I WifiNative-HAL: startHal
08-30 12:30:39.121  1028  1368 D wifi    : setting scan oui 0xaf5f03e0
,08-30 12:30:39.121  1028  1368 D WifiStateMachine: Setting OUI to DA-A1-19
,08-30 12:30:39.121  1028  1368 I WifiNative-HAL: startHal
08-30 12:30:39.121  1028  1368 D wifi    : setting scan oui 0xaf5f03e0
08-30 12:30:39.121  1028  1368 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 12:30:39.122  1028  1368 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 12:30:39.122  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,08-30 12:30:39.122  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 12:30:39.122  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 12:30:39.122  1919  7300 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 12:30:39.123  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:30:39.123  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:30:39.123  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-30 12:30:39.123  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 12:30:39.123  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 12:30:39.123  1919  7300 E CtrlSupplicant: Succeed to open control connection
08-30 12:30:39.123  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 12:30:39.123  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-30 12:30:39.124  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:30:39.124  1919  7300 E CtrlSupplicant: Succeed to open monitor connection
08-30 12:30:39.124  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:30:39.124  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:30:39.124  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:30:39.124  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:30:39.124  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-30 12:30:39.124  1919  7300 D WfdsMonitor: Supplicant connection established
08-30 12:30:39.125  7258  7258 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 12:30:39.125  1919  2212 D WfdsService: Connected to the supplicant for wfds
08-30 12:30:39.125  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 12:30:39.125  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:30:39.125  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START,
08-30 12:30:39.125  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:30:39.126  1028  1368 E WifiNative: : [161,948,186 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 12:30:39.126  1028  1368 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 12:30:39.127  1028  1368 D WifiNative-wlan0: RECONNECT: returned true
,08-30 12:30:39.127  1028  1368 D WifiNative-wlan0: doString: [STATUS]
08-30 12:30:39.127  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:30:39.127  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 12:30:39.128  1028  1368 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:30:39.128  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 12:30:39.128  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:30:39.128  1028  1367 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.129  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 12:30:39.129  1028  1028 D RttService: SCAN_AVAILABLE : 3
08-30 12:30:39.129  1028  1534 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:39.129  1028  1534 I WifiNative-HAL: startHal
08-30 12:30:39.129  1028  1534 D wifi    : getting scan capabilities on interface[1] = 0xaf5f03e0
08-30 12:30:39.129  1028  1534 D wifi    : failed to get capabilities : -3
08-30 12:30:39.129  1028  1534 E WifiScanningService: could not get scan capabilities
08-30 12:30:39.130  1028  1535 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:39.130  1028  1368 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:30:39.130  1028  1368 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 12:30:39.130   312   887 D CommandListener: Setting iface cfg
08-30 12:30:39.130   312   887 D CommandListener: Trying to bring up p2p0
08-30 12:30:39.131  1028  1367 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 12:30:39.131  1028  1368 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 12:30:39.131  1028  1367 D LGWifiP2pService: P2pEnablingState
,08-30 12:30:39.131  1028  1367 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.131  1028  1367 D LGWifiP2pService: P2p socket connection successful
08-30 12:30:39.131  1028  1367 D LGWifiP2pService: P2pEnabledState
08-30 12:30:39.131  1028  1368 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 12:30:39.131  1028  1367 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 12:30:39.133  1028  1367 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 12:30:39.134  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-30 12:30:39.134  1919  1919 D WfdsService: WifiP2pState is changed : true
08-30 12:30:39.134  1919  2212 D WfdsService: Receive the WFDS_ENABLE Method
08-30 12:30:39.134  1919  2212 D WfdsService: Set the WFDS Monitor: true
08-30 12:30:39.134  1919  2212 D WfdsService: Connected to the supplicant for wfds
08-30 12:30:39.134  1919  2212 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 12:30:39.134  7258  7258 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 12:30:39.135  1919  2212 D WfdsService: selectPreferredScanChannel [36]
08-30 12:30:39.135  1919  2212 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 12:30:39.136  1919  1919 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 12:30:39.138  1028  1367 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 12:30:39.138  1919  1919 D WfdsService: isConnected: false
08-30 12:30:39.138  1028  1367 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 12:30:39.139  1028  1367 D WifiNative-p2p0: SET device_name G3: returned true
08-30 12:30:39.139  1028  1367 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 12:30:39.139  1028  1367 D LGWifiP2pService: before postfix = G3
08-30 12:30:39.139  1028  1367 D WifiServerServiceExt: postfix byte check : 2
08-30 12:30:39.139  1028  1367 D LGWifiP2pService: after postfix = G3
08-30 12:30:39.139  1028  1367 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 12:30:39.139  1028  1367 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 12:30:39.139  1028  1367 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 12:30:39.140  1028  1367 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 12:30:39.140  1028  1367 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 12:30:39.140  1028  1367 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 12:30:39.140  1028  1367 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 12:30:39.140  1028  1367 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 12:30:39.140  1028  1367 D WifiNative-HAL: p2pGetDeviceAddress
08-30 12:30:39.141  1028  1367 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 12:30:39.141  7282  7282 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:30:39.143  1919  1919 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 12:30:39.143  1919  1919 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 12:30:39.143  1919  1919 D WfdsService: Update P2p Interface State: 3
08-30 12:30:39.143  1028  1367 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 12:30:39.143  1028  1367 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 12:30:39.144  1028  1367 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 12:30:39.144  1028  1367 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 12:30:39.144  1028  1367 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 12:30:39.144  1028  1367 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 12:30:39.145  1028  1367 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 12:30:39.145  1028  1367 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 12:30:39.146  1028  1368 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 12:30:39.147  1028  1368 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 12:30:39.147  1028  1368 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 12:30:39.147  1028  1368 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-30 12:30:39.156  7258  7258 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-30 12:30:39.157  1028  1368 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 12:30:39.157  1028  1368 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 12:30:39.157  1028  1368 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 12:30:39.157  1028  1368 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 12:30:39.157  7258  7258 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 12:30:39.158  1028  1368 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 12:30:39.158  1028  1368 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 12:30:39.158  1028  1368 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 12:30:39.158  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 12:30:39.159  1028  1367 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 12:30:39.159  1028  1367 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 12:30:39.159  1028  1367 D LGWifiP2pService: InactiveState
08-30 12:30:39.159  1028  1367 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.159  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.159  1028  1367 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 12:30:39.160  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:30:39.160  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 12:30:39.161  7258  7258 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:30:39.161  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.161  1028  1367 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 12:30:39.161  1028  1367 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.161  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.161  1028  1367 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.161  1028  1367 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.162  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.162  1028  1367 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.162  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.162  1028  1367 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.162  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.162  1028  1367 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.162  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:30:39.162  1028  7294 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.162  1919  2212 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 12:30:39.162  1919  7300 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:30:39.162  1919  7300 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.163  1919  7300 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.163  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.163  1028  1367 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.163  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.163  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.163  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.163  1028  1367 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.163  1028  7294 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.163  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.163  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.163  1028  1028 E WifiServerServiceExt: No p2p device connected
08-30 12:30:39.163  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.163  1028  7294 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.163  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.1,63  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.164  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:30:39.164  7258  7258 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.164  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:30:39.164  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.164  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.164  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:30:39.165  7258  7258 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:30:39.165  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.165  1919  7300 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.165  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.165  1028  7294 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.165  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.165  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.165  1028  1368 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 12:30:39.165  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.166  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:30:39.166  1028  7294 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.166  1919  7300 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-30 12:30:39.166  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.166  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:30:39.166  1028  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.166  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.166  1028  1368 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:30:39.167  1028  1368 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:30:39.167  1028  1368 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,08-30 12:30:39.167  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 12:30:39.167  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 12:30:39.167  7258  7258 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:30:39.168  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 12:30:39.168  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:30:39.168  1028  7294 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:30:39.168  1028  7294 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:30:39.168  1028  1368 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-30 12:30:39.168  1028  1368 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 12:30:39.169  1028  1368 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 12:30:39.169  1028  1368 D WifiNative-wlan0: doBoolean: SCAN
08-30 12:30:39.169  1028  1368 D WifiNative-wlan0: SCAN: returned false
08-30 12:30:39.170  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=161992  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:30:39.172  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.172  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 12:30:39.173  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.173  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.173  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:30:39.173  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.173  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=161996  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:30:39.174  1028  1368 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:30:39.174  1028  1368 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:30:39.174  1028  1368 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:30:39.175  1028  1368 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:30:39.175  1028  1368 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:30:39.176  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.176  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 12:30:39.490  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:30:39.492  6422  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 12:30:39.513  2197  2197 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:39.524  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:30:39.524  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:39.524  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:30:39.524  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 12:30:39.527  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:30:39.531  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
08-30 12:30:39.531  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:30:39.531  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:30:39.532  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:30:39.532  7029  7029 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:30:39.537  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:39.538  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:39.539  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:39.542  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:39.551  7070  7070 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:30:39.573  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:30:39.573  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:39.573  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 12:30:39.579  4310  7314 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:30:39.586  4310  7315 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:39.592  4310  7315 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 12:30:39.595  7070  7318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.596  7099  7099 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:30:39.596  7099  7099 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:30:39.612  6958  7319 W FormManager: Network not available. Please check & try again.
,08-30 12:30:39.620  7179  7179 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:39
08-30 12:30:39.621  6958  7320 V FormManager: Network unavailable.
08-30 12:30:39.622  7179  7179 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:30:39.622  7179  7179 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:30:39.623  7179  7179 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:30:39.623  7179  7179 D WeatherAncestor: connectivity changed - connection : true
08-30 12:30:39.623  7179  7179 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36968597
08-30 12:30:39.624  7179  7179 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:30:39.624  7179  7179 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:30:39.624  7179  7179 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:30:39.624  7179  7179 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 12:30:39.624  7179  7179 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:39
08-30 12:30:39.627  7258  7258 E wpa_supplicant: USIM:  scard_init function
08-30 12:30:39.627  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 12:30:39.627  1028  7294 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 12:30:39.627  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 12:30:39.627  7258  7258 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 12:30:39.627  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 12:30:39.628  1028  7294 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 12:30:39.628  1028  1368 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:30:39.628  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:30:39.628  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 12:30:39.628  6958  7320 V FormManager: Network unavailable.
08-30 12:30:39.628  1028  1368 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:30:39.629  1028  1368 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:30:39.629  1028  1368 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:30:39.629  1028  1368 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 12:30:39.633  6687  7021 D UEI.SmartControl: Internal timer expired: 2
08-30 12:30:39.633  6687  7021 D UEI.SmartControl: unbind internal service
08-30 12:30:39.634  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=162456  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 12:30:39.635  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=162457  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 12:30:39.636  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.636  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.636  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-30 12:30:39.638  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.638  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.639  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.641  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.641  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.641  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 12:30:39.643  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.643  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 12:30:39.656  1028  1938 I art     : Explicit concurrent mark sweep GC freed 74847(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 4.606ms total 228.289ms
,08-30 12:30:39.661   312  7332 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:30:39.661  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 12:30:39.661  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:30:39.661  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:30:39.661  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:30:39.661  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:30:39.663  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.663  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.663  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.665  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:30:39.665  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:30:39.665  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:30:39.665  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:30:39.665  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:30:39.665  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:30:39.666  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 12:30:39.673  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:39.676  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:30:39.678  6958  7334 W FormManager: Network not available. Please check & try again.
,08-30 12:30:39.686  6958  7335 V FormManager: Network unavailable.
08-30 12:30:39.686  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:39.693  6958  7335 V FormManager: Network unavailable.
,08-30 12:30:39.696  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:39.700  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:30:39.701  6958  7336 W FormManager: Network not available. Please check & try again.
,08-30 12:30:39.705  6958  7338 V FormManager: Network unavailable.
,08-30 12:30:39.707  6958  7338 V FormManager: Network unavailable.
08-30 12:30:39.708  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:39.721  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:30:39.722  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:39.723  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:30:39.725  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:39.731  4310  7341 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:30:39.733  4310  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:30:39.733  4310  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:30:39.735  7258  7258 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:30:39.736  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 12:30:39.736  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 12:30:39.736  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 12:30:39.736  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 12:30:39.737  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:30:39.737  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:30:39.737  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=162559  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:30:39.737  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=162559  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:30:39.737  1028  1368 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162560
08-30 12:30:39.738  1028  1368 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162560
08-30 12:30:39.738  1028  1368 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162560
08-30 12:30:39.738  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162560
08-30 12:30:39.739  1028  1368 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162561
08-30 12:30:39.739  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=162561  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:30:39.748  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:30:39.748  6687  7015 D serial_port: close(fd = 24)
08-30 12:30:39.748  7258  7258 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:30:39.748  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:30:39.748  7258  7258 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:30:39.748  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 12:30:39.748  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:30:39.748  1028  7294 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:30:39.748  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 12:30:39.748  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:30:39.748  1028  7294 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:30:39.749  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:30:39.749  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 12:30:39.752  6687  7015 I UEI.SmartControl: Serial port is closed.
08-30 12:30:39.775  1028  1938 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7346 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 12:30:39.778  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 12:30:39.780  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.780  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.781  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.785  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.786  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.786  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 12:30:39.790  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=162612  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:30:39.793  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=162615  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:30:39.794  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=162616  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:30:39.795  1028  1368 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=162617
08-30 12:30:39.795  1028  1368 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=162618
08-30 12:30:39.795  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.796  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.796  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 12:30:39.796  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.796  1028  1368 D WifiNative-wlan0: doString: [STATUS]
08-30 12:30:39.796  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 12:30:39.797  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:30:39.797  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:30:39.797  1028  1368 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:30:39.799  1028  1368 I WifiServiceExtension: setVHTCapabilityType  : false
,08-30 12:30:39.803  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.803  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.804  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.807  1028  1368 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 12:30:39.807  1028  1368 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 12:30:39.818  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.818  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.818  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 12:30:39.821  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.821  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.821  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 12:30:39.823  1028  1368 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 12:30:39.823  1028  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:30:39.823  1028  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:30:39.823  1028  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:30:39.823  1028  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:30:39.824  1028  1396 D ConnectivityService: Got NetworkAgent Messenger
08-30 12:30:39.825  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.825  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.825  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 12:30:39.825  1028  1396 D ConnectivityService: NetworkAgent connected
08-30 12:30:39.826  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.828  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.828  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.828  1028  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:30:39.828  1028  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:30:39.828  1028  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:30:39.829  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.829  1028  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:30:39.829  1028  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:30:39.833  1028  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 12:30:39.835   312   887 D CommandListener: Setting iface cfg
08-30 12:30:39.839  1028  1368 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 12:30:39.839  1028  7366 D DhcpStateMachine: StoppedState
08-30 12:30:39.839  1028  7366 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.839  1028  7366 D DhcpStateMachine: WaitBeforeStartState
08-30 12:30:39.840  1028  1368 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162662  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:30:39.840  1028  1368 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162662  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:30:39.841  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162663  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:30:39.841  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.842  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.842  1028  1368 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.843  1028  1368 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.844  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.844  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:39.844  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.845  1028  1028 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 12:30:39.845  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.845  1028  1028 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-30 12:30:39.846  1028  1368 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162668  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 12:30:39.847  1028  1368 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:30:39.848  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:30:39.849  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:116862] from screen [on:0 period:-620742679] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:30:39.850  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-620742678] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:30:39.850  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:30:39.854  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.855  1028  1396 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 12:30:39.856  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.856  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.857  1028  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.857  1028  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.857  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.858  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 12:30:39.859  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 12:30:39.860  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-30 12:30:39.860  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-30 12:30:39.860  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 12:30:39.861  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 12:30:39.861  1028  1368 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 12:30:39.861  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 12:30:39.862  1028  1368 D WifiNative-wlan0: SET ps 0: returned true
08-30 12:30:39.862  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 12:30:39.862  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 12:30:39.863  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-30 12:30:39.863  1028  1368 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 12:30:39.863  1028  1368 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:30:39.863  1028  1367 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28e6eb0c target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.863  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28e6eb0c target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.863  1028  1368 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:30:39.863  1028  7366 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.863  1028  7366 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 12:30:39.864   312   887 D CommandListener: Setting iface cfg
08-30 12:30:39.864   312   887 D CommandListener: Trying to bring up wlan0
08-30 12:30:39.865  1028  1368 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 12:30:39.865  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.865  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:30:39.866  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:39.866  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:30:39.866  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.867  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.867  1028  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.867  1028  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.867  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.868  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:39.868  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 12:30:39.868  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 12:30:39.869  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 12:30:39.869  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:30:39.869  1028  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.869  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.869  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:30:39.869  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:30:39.869  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 12:30:39.869  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 12:30:39.870  1028  1368 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 12:30:39.870  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 12:30:39.888  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:30:39.888  7346  7346 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 12:30:39.888  7346  7346 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-30 12:30:39.889  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 12:30:39.889  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-30 12:30:39.890  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:30:39.890  1028  1368 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 12:30:39.890  1028  1396 D ConnectivityService: ignoring duplicate network state non-change
08-30 12:30:39.893  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.893  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.893  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.894  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.894  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.895  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:30:39.895  7346  7346 V [BNRBootReceiver]: Boot Receiver Return
08-30 12:30:39.896  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 12:30:39.896  7346  7346 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 12:30:39.896  1028  1396 D ConnectivityService: Adding iface wlan0 to network 101
08-30 12:30:39.901  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.901  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.901  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-30 12:30:39.907  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:39.908  1028  1368 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 12:30:39.912  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:30:39.913  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.913  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.913  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:30:39.914  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:30:39.916  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.916  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:39.917  1028  1396 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 12:30:39.917  1028  1396 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 12:30:39.918  1028  1396 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 12:30:39.918  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.918  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:39.918  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:30:39.919   312   887 E Netd    : netlink response contains error (File exists)
08-30 12:30:39.919  1028  1396 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 12:30:39.920  1919  1919 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 12:30:39.920  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:39.921  1028  1396 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 12:30:39.921  1028  1396 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 12:30:39.921  1028  1396 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 12:30:39.922  1028  1396 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:30:39.922  1028  1396 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:39.922  1028  1396 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:39.922  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.923  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.923  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 12:30:39.923  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:30:39.923  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:39.923  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:30:39.924  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:30:39.925  1028  1396 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 12:30:39.926  1028  1396 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:30:39.926  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:39.926   312  7371 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 12:30:39.926  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:30:39.926  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:39.926  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 12:30:39.926  1028  1396 D ConnectivityService: currentScore = 0, newScore = 20
08-30 12:30:39.926  1028  1396 D ConnectivityService:    accepting network in place of null
08-30 12:30:39.926  1028  1396 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:39.927  1028  1368 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:39.927  1028  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:30:39.928  1829  1829 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:39.928  1829  1829 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:30:39.929  1028  1396 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 12:30:39.929  1028  1396 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 12:30:39.929  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:30:39.929  1028  1396 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:39.929  1028  1396 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 12:30:39.930  1028  1396 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1,048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 12:30:39.930  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:39.930  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:30:39.931  1028  1396 D ConnectivityService: validation of new default Network = false
08-30 12:30:39.931  1028  1396 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 12:30:39.931  1028  1396 D DSQN    : enableDataServiceNotify 
08-30 12:30:39.931  1028  1396 D DSQN    : start dsqn bin
08-30 12:30:39.931  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:30:39.932  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 12:30:39.933  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:30:39.933  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:30:39.933  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:30:39.935  1028  1396 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:39.935  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:39.935  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:39.936  1028  1396 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:39.936  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:30:39.929  7372  7372 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:39.929  7372  7372 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:39.949  1028  1095 I ActivityManager: Killing 6894:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 12:30:39.951  7372  7372 E DSQN    : DSQN ssw
,08-30 12:30:39.981   312  7371 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 12:30:39.995  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:39.997  1028  1863 W libprocessgroup: failed to open /acct/uid_10037/pid_6894/cgroup.procs: No such file or directory
08-30 12:30:40.004  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.018   312  7371 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 12:30:40.030  1028  1366 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 12:30:40.036  1794  7376 I CheckinService: active receiver: enabled
,08-30 12:30:40.049   312   886 D LGDataListener: argv[0]=dsqncommand
08-30 12:30:40.049   312   886 D LGDataListener: argv[1]=wlan0
,08-30 12:30:40.049   312   886 D LGDataListener: argv[2]=1
08-30 12:30:40.049   312   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-30 12:30:40.049  1028  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 12:30:40.049  1028  1108 D DSQN    : start to monitor internet connection
08-30 12:30:40.053  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.054  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.057  1794  7376 I CheckinService: Preparing to send checkin request
08-30 12:30:40.057  1794  7376 I EventLogService: Accumulating logs since 1472552935031
08-30 12:30:40.058  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:40.063  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 12:30:40.067  1028  7366 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 12:30:40.068  1028  7366 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 12:30:40.068  1028  7366 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 12:30:40.071  6854  6854 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 12:30:40.059  7380  7380 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:40.059  7380  7380 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:40.075  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:40.083  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:30:40 GMT], X-Android-Received-Millis=[1472553040082], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472553040048]}
08-30 12:30:40.083  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:30:40.083  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 12:30:40.083  1028  1396 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 12:30:40.083  1028  1396 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 12:30:40.084  1028  1396 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:30:40.084  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:40.084  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:30:40.084  1028  1396 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 12:30:40.084  1028  1396 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:40.084  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:40.084  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:40.084  1028  1396 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:40.085  7380  7380 I dhcpcd  : version 5.5.6 starting
08-30 12:30:40.085  1028  1396 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:40.085  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:30:40.085  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 12:30:40.085  1829  1829 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:40.086  1829  1829 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:30:40.086  1028  1368 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:40.086  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:30:40.086  1028  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:30:40.087  7380  7380 E dhcpcd  : get_duid: m
08-30 12:30:40.087  7380  7380 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 12:30:40.087  7380  7380 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 12:30:40.100  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:30:40.102  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:40.102  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:30:40.119  1794  7376 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 12:30:40.120  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.128  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.129  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:40.129  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:30:40.130  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:40.131  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:40.132  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:40.134  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:40.142  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.150  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.150  7380  7380 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:30:40.150  7380  7380 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:30:40.150  7380  7380 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:30:40.150  7380  7380 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 12:30:40.151  7380  7380 D dhcpcd  : wlan0: sending REQUEST (xid 0xfac36c08), next in 4.58 seconds
,08-30 12:30:40.157  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.157  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.157  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:30:40.160  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:40.167  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:30:40.167  7380  7380 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 12:30:40.173  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.181  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.182  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:40.182  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:30:40.186  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:30:40.186  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:30:40.186  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:30:40.186  7380  7380 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 12:30:40.186  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:30:40.186  7380  7380 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 12:30:40.186  7380  7380 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 12:30:40.187  7380  7380 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 12:30:40.187  7380  7380 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:30:40.187  7380  7380 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:30:40.187  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:30:40.187  7380  7380 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:30:40.187  7380  7380 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 12:30:40.188  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:30:40.188  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 12:30:40.188  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:30:40.188  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:30:40.188  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:30:40.188  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 12:30:40.189  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:30:40.192  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:40.198  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.206  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.271  1028  1763 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7393 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 12:30:40.288  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.288  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.289  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:30:40.295  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:40.302  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.309  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.320  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.320  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:40.321  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:30:40.325  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:40.333  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.345  7393  7393 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 12:30:40.345  7393  7393 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:30:40.350  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.360  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.360  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.360  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:30:40.367  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:40.378  7393  7393 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:30:40.378  7393  7393 I MultiDex: install
08-30 12:30:40.379  7393  7393 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 12:30:40.381  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:30:40.390  7393  7393 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 12:30:40.390  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:30:40.398  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.398  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.403  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:30:40.406  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:40.415  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.424  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.429  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.429  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.430  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:30:40.434  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:40.437  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 12:30:40.440  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:40.443  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.448  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.454  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.454  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.455  6918  6918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 12:30:40.456  6918  6918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:30:40.456  6918  6918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 12:30:40.460  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:40.462  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 12:30:40.463  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:40.465  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:40.471  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:40.473  1028  7366 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 12:30:40.475  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:40.475  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:40.475  1028  7366 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 12:30:40.476  6918  6918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 12:30:40.476  1028  7366 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:30:40.476  6918  6918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:30:40.476  1028  7366 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 12:30:40.476  1028  7366 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 12:30:40.476  1028  7366 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:30:40.477  1028  7366 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 12:30:40.477  1028  7366 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 12:30:40.477  6918  6918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 12:30:40.478  1028  7366 D DhcpStateMachine: RunningState
08-30 12:30:40.482  2197  2197 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 12:30:40.492  2197  2197 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 12:30:40.492  2197  2197 D c       : Getting all permits...
08-30 12:30:40.492  2197  2197 D a       : Opening database...
08-30 12:30:40.496  2197  2197 D a       : Opening database auth.proximity.permit_store...
08-30 12:30:40.497  2197  2197 D a       : Closing database...
08-30 12:30:40.734  7393  7412 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:30:40.734  7393  7412 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:40.938  1028  1396 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 12:30:41.066  7433  7433 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 12:30:41.099  1028  1368 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:30:41.099  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:30:41.099  1028  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:30:41.100  1028  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:30:41.100  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:30:41.101  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:30:41.104  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,08-30 12:30:41.104  1028  1396 D ConnectivityService: identical MTU - not setting
08-30 12:30:41.104  1028  1396 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:30:41.104  1028  1396 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:41.104  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:41.105  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:41.105  1028  1396 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:41.107  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 12:30:41.173  7433  7433 I dex2oat : dex2oat took 105.920ms (threads: 4)
,08-30 12:30:41.195  7393  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:30:41.195  7393  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:30:41.195  7393  7412 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:30:41.195  7393  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:30:41.195  7393  7412 I Adreno-EGL: Remote Branch: 
08-30 12:30:41.195  7393  7412 I Adreno-EGL: Local Patches: 
08-30 12:30:41.195  7393  7412 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:30:41.320  7393  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:30:41.320  7393  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:30:41.320  7393  7412 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:30:41.320  7393  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:30:41.320  7393  7412 I Adreno-EGL: Remote Branch: 
08-30 12:30:41.320  7393  7412 I Adreno-EGL: Local Patches: 
08-30 12:30:41.320  7393  7412 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:30:41.445  7393  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:30:41.445  7393  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:30:41.445  7393  7412 I Adreno-EGL: Build Date: 12/12/14 금
,08-30 12:30:41.445  7393  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:30:41.445  7393  7412 I Adreno-EGL: Remote Branch: 
08-30 12:30:41.445  7393  7412 I Adreno-EGL: Local Patches: 
08-30 12:30:41.445  7393  7412 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:30:41.611   312  7457 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:30:41.611   312  7457 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 12:30:41.660   312  7457 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 12:30:41.765  1794  7376 I CheckinTask: Sending checkin request (7865 bytes)
,08-30 12:30:41.970  1794  7376 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 12:30:41.987  1794  7376 I CheckinService: active receiver: disabled
,08-30 12:30:42.010  2197  2197 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-30 12:30:42.029  2197  2197 I GCM     : GCM config loaded
,08-30 12:30:42.047   312  7464 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 12:30:42.049   312  7464 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-30 12:30:42.055  7099  7099 V SetupWizard: Connected to Gservices successfully
,08-30 12:30:42.132   312  7464 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 12:30:42.421  2197  7466 D GCM     : Connected
,08-30 12:30:42.461  2197  7466 D GCM     : Message class com.google.e.a.a.q
,08-30 12:30:42.859  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=49.5, 0.0, 0.0  rx=45.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-620739669] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:30:42.861  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=49.5, 0.0, 0.0  rx=45.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-620739667] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:30:42.861  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:30:42.900  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:30:42.914  1028  1369 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 12:30:42.929  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:42.939  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 12:30:42.962  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:42.962  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:42.962  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.962  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:30:42.968  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:42.968  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:42.968  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.968  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:42.970  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:42.970  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:42.970  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.970  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:42.974  1028  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:42.982  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 12:30:42.987  6422  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:30:42.997  5737  5737 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 12:30:43.014  2197  2197 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:43.020  1028  1918 D WifiServiceImplEx: setWifiEnabled: false pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:30:43.020  1028  1918 D WifiService: setWifiEnabled: false pid=6629, uid=10118
08-30 12:30:43.021  1028  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 12:30:43.034  1028  1368 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:43.034  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:43.035  1028  1368 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:43.035  1028  1368 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:43.035  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:30:43.035  1028  1368 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 12:30:43.035  1028  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:30:43.036  1028  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 12:30:43.040  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:30:43.040  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:30:43.040  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:30:43.049  1028  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:30:43.049  1028  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 12:30:43.053  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:30:43.057  1028  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:30:43.057  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:30:43.057  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:30:43.057  1028  1367 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.058  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.058  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:30:43.058  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:30:43.058  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:30:43.059   312   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:43.067  1028  7366 D DhcpStateMachine: RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:43.100  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:43.100  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:30:43.100  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:30:43.129  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:30:43.143  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
08-30 12:30:43.143  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:30:43.143  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:30:43.144  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:30:43.145  7029  7029 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 12:30:43.147  1028  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:43.148  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:43.148  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:43.149  1028  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:43.149  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:43.149  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:30:43.150  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:30:43.151  1028  1396 D ConnectivityService: ignoring duplicate network state non-change
08-30 12:30:43.151  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 12:30:43.155  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:43.155  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:43.159  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:30:43.163  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:43.163  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:43.164  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.168  1919  1919 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 12:30:43.169  1028  1368 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:30:43.169  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 12:30:43.170  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.170  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.170  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-30 12:30:43.170  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 12:30:43.172  1028  1367 D LGWifiP2pService: InactiveState{ when=-25ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.172  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.172  1028  1367 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@343d5d37
08-30 12:30:43.178  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.179  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.179  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:30:43.179  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 12:30:43.179  1028  1028 D RttService: SCAN_AVAILABLE : 1
08-30 12:30:43.181  1028  1535 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:43.183  1028  1534 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.186  1028  1367 D LGWifiP2pService: P2pDisablingState
08-30 12:30:43.186  1028  1367 D LGWifiP2pService: P2pDisablingState{ when=-14ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.186  1028  1367 D LGWifiP2pService: p2p socket connection lost
08-30 12:30:43.186  1028  1367 D LGWifiP2pService: P2pDisabledState
08-30 12:30:43.187  1028  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 12:30:43.187  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:30:43.187  7258  7258 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:30:43.188  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:30:43.188  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:30:43.188  1028  1367 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.188  1028  1367 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.189  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:30:43.190  1919  1919 D WfdsService: WifiP2pState is changed : false
08-30 12:30:43.190  1919  2212 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 12:30:43.190  1919  2212 D WfdsService: Set the WFDS Monitor: false
08-30 12:30:43.190  1919  2212 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:30:43.191  1919  2212 D WfdsService: STATE : WfdsDisabledState - enter
08-30 12:30:43.191  1919  7300 D CtrlSupplicant: Received on exit socket, terminate
08-30 12:30:43.191  1919  7300 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 12:30:43.191  1919  7300 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 12:30:43.191  1919  7300 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 12:30:43.191  1919  2226 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 12:30:43.191  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:30:43.193  1919  2212 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 12:30:43.194  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:43.194  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:43.195  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:30:43.198  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:43.201  1028  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:43.202   312   887 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:43.202  1028  1971 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-30 12:30:43.202  1028  1396 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 12:30:43.202  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.202  1028  1396 D DSQN    : disableDataServiceNotify
08-30 12:30:43.202  1028  1396 D DSQN    : stop dsqn bin
08-30 12:30:43.202  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.202  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 12:30:43.202  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.202  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 12:30:43.205   312  7491 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:30:43.205  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 12:30:43.206  1028  1368 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 12:30:43.206  1028  1368 D WifiNative-p2p0: TERMINATE: returned true
08-30 12:30:43.206  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:30:43.206  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:30:43.206  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:30:43.206  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 12:30:43.207  1028  1396 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:43.207  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:43.207  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:43.208  1028  1396 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:30:43.208  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 12:30:43.208  1028  1396 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 12:30:43.208  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 12:30:43.208  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.208  1028  1396 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddres,ses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 12:30:43.208  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.208  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:43.208  1028  1396 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 12:30:43.208  1028  7365 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 12:30:43.208  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.208  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:30:43.208  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:30:43.209  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 12:30:43.213  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 12:30:43.213  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:30:43.213  4310  7492 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:30:43.214  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.215  1028  1396 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:43.215  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:30:43.215  1028  1396 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:43.215  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 12:30:43.215  1028  1396 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:43.215  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:30:43.215  1028  1028 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 12:30:43.215  1028  1396 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:43.215  1028  1396 D NetworkManagementService: Removing idletimer
08-30 12:30:43.215  1028  1396 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.216  1829  1829 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:43.216  1829  1829 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:30:43.216  1028  1368 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:30:43.216  1028  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:30:43.217  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.217  1028  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:30:43.218  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:30:43.218  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:30:43.218  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:30:43.218  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:30:43.219  4310  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:43.219  4310  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:30:43.220  1028  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:30:43.221  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:30:43.221  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:30:43.221  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:30:43.221  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:30:43.225  7070  7070 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 12:30:43.226  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:43.226  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:43.226  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.226  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:43.227  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:43.227  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.227  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:43.227  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:43.227  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:43.227  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.227  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:43.247  7070  7494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.250  6958  7496 W FormManager: Network not available. Please check & try again.
08-30 12:30:43.252  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:30:43.252  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:43.253  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 12:30:43.253  3467  3467 D PhoneState: setPdpRejectCasuse : false
08-30 12:30:43.258  7099  7099 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:30:43.259  7099  7099 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 12:30:43.268  6958  7498 V FormManager: Network unavailable.
,08-30 12:30:43.269  7258  7258 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 12:30:43.269  7258  7258 I wpa_supplicant: monitor socket send errors count : 1
08-30 12:30:43.269  7258  7258 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1919-4\x00 that cannot receive messages
08-30 12:30:43.270  1028  7294 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 12:30:43.270  1028  7294 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 12:30:43.273  7179  7179 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:43
08-30 12:30:43.274  7179  7179 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:30:43.274  7179  7179 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:30:43.275  6958  7498 V FormManager: Network unavailable.
08-30 12:30:43.275  7179  7179 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:30:43.275  7179  7179 D WeatherAncestor: connectivity changed - connection : true
08-30 12:30:43.275  7179  7179 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36968597
08-30 12:30:43.276  7179  7179 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:30:43.276  7179  7179 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:30:43.276  7179  7179 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:30:43.276  7179  7179 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:30:43.276  7179  7179 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:43
08-30 12:30:43.288  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 12:30:43.289  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.290  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.301  1028  7366 D DhcpStateMachine: StoppedState
08-30 12:30:43.301  1028  7366 D DhcpStateMachine: StoppedState{ when=-110ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:30:43.303  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:30:43.304  1028  1368 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 12:30:43.304  1028  1368 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 12:30:43.307  7258  7258 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:30:43.308  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 12:30:43.308  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:30:43.308  1028  7294 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:30:43.308  1028  7294 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 12:30:43.308  7258  7258 W wpa_supplicant: USIM:  scard_deinit function
08-30 12:30:43.308  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:30:43.308  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:30:43.309  1028  1368 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=166132
08-30 12:30:43.310  1028  1368 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=166132
08-30 12:30:43.311  1028  1368 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=166133  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:30:43.311  1028  1368 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=166133  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:30:43.311  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 12:30:43.312  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:30:43.313  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:30:43.313  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:43.313  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:30:43.314  1028  1368 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:43.315  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:30:43.321  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:43.329  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:30:43.338  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:30:43.339  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.340  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:43.340  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:30:43.344  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:43.340  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.349  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:43.353  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:30:43.353  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:43.353  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:43.360  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:30:43.371  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:43.379  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:43.380  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:43.382  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:43.388  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:30:43.393  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:30:43.393  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:43.394  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:30:43.398  7258  7258 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 12:30:43.399  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:30:43.399  1028  7294 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 12:30:43.399  1028  7294 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 12:30:43.399  1028  7294 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-30 12:30:43.400  1028  1368 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 12:30:43.408  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:43.414  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:30:43.415  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:30:43.416  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:30:43.424  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:43.427  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 12:30:43.432  6958  7501 W FormManager: Network not available. Please check & try again.
08-30 12:30:43.434  6958  7502 V FormManager: Network unavailable.
08-30 12:30:43.434  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:43.441  6958  7502 V FormManager: Network unavailable.
,08-30 12:30:43.454  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:30:43.454  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-30 12:30:43.455  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:30:43.455  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:30:43.456  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 12:30:43.456  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:30:43.456  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:30:43.457  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:30:43.457  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:30:43.457  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:30:43.457  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:30:43.503  7202  7225 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 12:30:43.503  1919  1919 D WfdsService: Supplicant Connection state is changed : false
,08-30 12:30:43.503  1919  2212 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 12:30:43.503  1919  2212 D WfdsService: Set the WFDS Monitor: false
08-30 12:30:43.504  1919  2212 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:30:43.507  1028  1368 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 12:30:43.507  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:30:43.507  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:30:43.507  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:30:43.508  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:30:43.508  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:43.510  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:43.511  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:30:43.511  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:30:43.514  2482  2482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:43.517  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:43.517  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:43.517  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 12:30:43.518  1028  1372 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 12:30:43.518  1028  1372 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 12:30:43.520  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:43.524  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:43.525  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:43.533  4310  7505 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:30:43.537  6872  6872 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 12:30:43.537  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:30:43.537  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:30:43.541  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:30:43.542  4310  7506 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:30:43.542  4310  7506 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 12:30:43.549  6958  7508 W FormManager: Network not available. Please check & try again.
08-30 12:30:43.552  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:30:43.560  6958  7509 V FormManager: Network unavailable.
,08-30 12:30:43.571  6958  7509 V FormManager: Network unavailable.
,08-30 12:30:43.821  1028  1095 W ProcessCpuTracker: Skipping unknown process pid 7477
,08-30 12:30:43.823  1028  1095 W ProcessCpuTracker: Skipping unknown process pid 7480
,08-30 12:30:43.827  1028  1095 W ProcessCpuTracker: Skipping unknown process pid 7511
08-30 12:30:43.827  1028  1095 W ProcessCpuTracker: Skipping unknown process pid 7512
08-30 12:30:44.491  1028  2009 I ActivityManager: Killing 6937:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 12:30:44.523  1028  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6937/cgroup.procs: No such file or directory
,08-30 12:30:45.911  1028  1368 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-620736618] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:30:45.913  1028  1368 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-620736615] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:30:46.218  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:46.232  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 12:30:46.247  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:46.252  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:46.254  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:46.256  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.261  1028  1110 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:30:46.269  1028  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.273  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:46.276  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:46.278  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:46.281  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:30:46.282  6422  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:30:46.293  5737  5737 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:30:46.302  5737  5737 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:30:46.321  2197  2197 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:46.340  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:30:46.340  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.340  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:30:46.340  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:30:46.344  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:30:46.348  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
08-30 12:30:46.348  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:30:46.348  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:30:46.349  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:30:46.349  7029  7029 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:30:46.353  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.354  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:46.355  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:30:46.361  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:46.368  7070  7070 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:30:46.392  1028  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:46.399  4310  7524 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:30:46.400  4310  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.400  4310  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:30:46.414  7070  7535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:30:46.419  6958  7538 W FormManager: Network not available. Please check & try again.
08-30 12:30:46.429  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:30:46.429  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.429  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 12:30:46.431  1028  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:46.431  1028  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:30:46.436  7099  7099 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:30:46.436  7099  7099 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 12:30:46.437  6958  7539 V FormManager: Network unavailable.
08-30 12:30:46.448  6958  7539 V FormManager: Network unavailable.
,08-30 12:30:46.454  7179  7179 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:46
08-30 12:30:46.458  7179  7179 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 12:30:46.458  7179  7179 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 12:30:46.458  7179  7179 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:30:46.459  7179  7179 D WeatherAncestor: connectivity changed - connection : true
08-30 12:30:46.459  7179  7179 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36968597
08-30 12:30:46.460  7179  7179 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:30:46.460  7179  7179 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:30:46.460  7179  7179 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:30:46.460  7179  7179 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:30:46.460  7179  7179 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:46
,08-30 12:30:46.490  6422  6422 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:30:46.491  6422  6450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 12:30:46.514  2197  2197 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:46.528  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:30:46.528  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.528  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:30:46.528  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:30:46.532  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:30:46.540  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
,08-30 12:30:46.540  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:30:46.540  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:30:46.541  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:30:46.542  7029  7029 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 12:30:46.550  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:46.551  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:30:46.555  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:30:46.560  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:30:46.570  4310  7544 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:30:46.577  7070  7070 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 12:30:46.580  4310  7545 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.581  4310  7545 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 12:30:46.618  7070  7546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:30:46.632  6958  7548 W FormManager: Network not available. Please check & try again.
,08-30 12:30:46.639  6958  7549 V FormManager: Network unavailable.
,08-30 12:30:46.639  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:30:46.639  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:30:46.640  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 12:30:46.644  7099  7099 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:30:46.644  7099  7099 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:30:46.644  6958  7549 V FormManager: Network unavailable.
08-30 12:30:46.661  7179  7179 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:46
,08-30 12:30:46.664  7179  7179 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:30:46.664  7179  7179 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:30:46.665  7179  7179 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:30:46.665  7179  7179 D WeatherAncestor: connectivity changed - connection : true
08-30 12:30:46.665  7179  7179 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36968597
08-30 12:30:46.666  7179  7179 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:30:46.666  7179  7179 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:30:46.666  7179  7179 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:30:46.666  7179  7179 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:30:46.666  7179  7179 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:30:46
08-30 12:30:46.684  1028  1863 I ActivityManager: Killing 7346:com.lge.bnr/1000 (adj 15): empty #17
,08-30 12:30:46.739  1028  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_7346/cgroup.procs: No such file or directory
,08-30 12:30:48.036  1028  1569 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:48.037  1028  1569 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 12:30:48.068  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 12:30:48.068  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:30:48.068  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:30:48.069  1028  1110 D BluetoothManagerService: Message: 1
08-30 12:30:48.069  1028  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 12:30:48.095  1028  1110 D BluetoothManagerService: Message: 20
08-30 12:30:48.095  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25a4ac6e:true
,08-30 12:30:48.100  6981  6981 D BluetoothAdapterState: make
08-30 12:30:48.105  6981  6981 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 12:30:48.106  6981  6981 I bluedroid-qcom: init
08-30 12:30:48.106  6981  7561 I BluetoothAdapterState: Entering OffState
08-30 12:30:48.107  6981  6981 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 12:30:48.108  6981  6981 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 12:30:48.108  6981  6981 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:30:48.108  6981  6981 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:30:48.108  6981  6981 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 12:30:48.110  6981  6981 I bluedroid-qcom: get_profile_interface socket
08-30 12:30:48.110  6981  6981 I bluedroid-qcom: get_profile_interface map_client
,08-30 12:30:48.115  6981  7565 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 12:30:48.109  7564  7564 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:48.109  7564  7564 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:48.128  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-30 12:30:48.131  1028  1110 D BluetoothManagerService: Message: 40
08-30 12:30:48.131  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 12:30:48.132  6981  6997 I bluedroid-qcom: config_hci_snoop_log
08-30 12:30:48.133  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 12:30:48.134  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 12:30:48.138  7564  7564 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 12:30:48.138  7564  7564 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 12:30:48.138  7564  7564 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 12:30:48.140  7564  7564 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-30 12:30:48.147  6981  7561 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 12:30:48.148  6981  7561 D BluetoothAdapterProperties: Setting state to 11
08-30 12:30:48.149  7564  7564 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 12:30:48.149  7564  7564 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 12:30:48.151  6981  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 12:30:48.152  6981  7561 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 12:30:48.156  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:30:48.156  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 12:30:48.157  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 12:30:48.159  6981  7565 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 12:30:48.164  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:48.165  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:30:48.168  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:48.172  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:48.173  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:48.176  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 12:30:48.178  6981  7565 D BluetoothAdapterProperties: Name is: G3
08-30 12:30:48.183  6981  6981 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:30:48.184  6981  6981 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:48.184  6981  6981 V BluetoothPbapReceiver: ***********state = 11
,08-30 12:30:48.191  1028  1367 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:48.191  1028  1367 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:30:48.195  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:48.195  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:30:48.196  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 12:30:48.198  6981  7561 D BluetoothBondStateMachine: make
,08-30 12:30:48.216  1028  1368 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 12:30:48.217  1028  1368 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 12:30:48.222  6981  7561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.222  6981  7561 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 12:30:48.222  6981  7561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.222  6981  7561 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 12:30:48.223  6981  7561 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 12:30:48.224  6981  7566 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 12:30:48.227  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:30:48.269  1028  1864 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7581 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 12:30:48.274  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:30:48.274  6981  6981 D HeadsetService: Received start request. Starting profile...
08-30 12:30:48.275  6981  6981 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:30:48.275  6981  6981 D LGBluetoothHfpAdapter: Version 1.6
08-30 12:30:48.278  6981  6981 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:30:48.279  6981  6981 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:30:48.279  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:30:48.279  6981  6981 D HeadsetStateMachine: make
08-30 12:30:48.284  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:30:48.291  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:30:48.296  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:30:48.303  6981  7561 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:30:48.312  6981  6981 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:48.312  6981  6981 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:30:48.315  6981  6981 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:30:48.315  6981  6981 I bluedroid-qcom: get_profile_interface handsfree
,08-30 12:30:48.317  6981  6981 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 12:30:48.317   316  2156 V AudioPolicyService: registerClient() client 0xb102cc40, uid 1002
08-30 12:30:48.317   316  1380 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:30:48.317   316  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:30:48.317   316  1380 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:30:48.318  6981  6981 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:30:48.318   316  2159 V AudioFlinger: registerClient() client 0xb1433160, pid 6981
08-30 12:30:48.319   316  1374 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:30:48.319   316  1374 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:30:48.319  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:30:48.319  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:30:48.319  1582  2043 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:30:48.319  1582  2043 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:30:48.319  1829  2442 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:30:48.319  1829  2442 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:30:48.319   316  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:30:48.319   316  1375 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:30:48.319  6981  6998 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:30:48.319  1582  1595 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:30:48.319  1582  1595 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:30:48.319  1829  2759 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:30:48.319  1829  2759 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:30:48.319  3467  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:30:48.319  3467  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:30:48.320  6981  6981 V ToneGenerator: Create Track: 0xb4928080
08-30 12:30:48.320  6981  6981 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 12:30:48.320  6981  6981 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 12:30:48.320   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:30:48.320   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:30:48.320   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:30:48.320   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:30:48.320  6981  6981 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:30:48.320   316  1380 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:30:48.320   316  2159 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:30:48.320   316  2159 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 12:30:48.320   316  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:30:48.320   316  2159 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:30:48.321  6981  6981 V AudioSystem: getLatency() output 2, latency 50
08-30 12:30:48.321  6981  6981 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 12:30:48.321  6981  6981 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:30:48.321  6981  6998 V AudioSystem: ioConfigChanged() new output samplingRate, 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 12:30:48.321  6981  6981 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 12:30:48.321   316  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:30:48.321   316  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:30:48.321   316  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:30:48.321   316  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:30:48.321   316  1380 V AudioFlinger: createTrack() lSessionId: 20
08-30 12:30:48.322  6981  6981 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 12:30:48.322  1028  1763 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:30:48.322  1028  1763 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:30:48.322  1028  1763 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:30:48.322  1028  1763 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:30:48.322  6981  6998 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:30:48.322  6981  6998 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 12:30:48.322   316  1380 V AudioFlinger: acquiring 20 from 6981, for 6981
08-30 12:30:48.322   316  1380 V AudioFlinger:  added new entry for 20
08-30 12:30:48.322  6981  6981 V ToneGenerator: ToneGenerator INIT OK, time: 171156
08-30 12:30:48.322  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.323  6981  7594 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 12:30:48.323  6981  7594 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:30:48.323  6981  7594 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:30:48.323  6981  7594 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 12:30:48.324   316  2159 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6981
08-30 12:30:48.324  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.324   316  2159 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 12:30:48.324   316  2159 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 12:30:48.324   316  2159 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 12:30:48.324   316  2159 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 12:30:48.324   316  2159 V voice   : voice_set_parameters: exit with code(0)
08-30 12:30:48.324   316  2159 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 12:30:48.324   316  2159 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 12:30:48.324   316  2159 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 12:30:48.324   316  2159 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 12:30:48.324   316  2159 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 12:30:48.324   316  2159 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 12:30:48.324  6981  7594 V ToneGenerator: ToneGenerator destructor
08-30 12:30:48.324  6981  7594 V ToneGenerator: stopTone
08-30 12:30:48.324  6981  7594 V ToneGenerator: Delete Track: 0xb4928080
08-30 12:30:48.325  6981  7594 V AudioTrack: ~AudioTrack, releasing session id from 6981 on behalf of 6981
08-30 12:30:48.325   316  1379 V AudioFlinger: releasing 20 from 6981 for 6981
08-30 12:30:48.325   316  1379 V AudioFlinger:  decremented refcount to 0
08-30 12:30:48.325   316  1379 V AudioFlinger: purging stale effects
08-30 12,:30:48.325   316  1379 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 12:30:48.325   316  1379 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 12:30:48.325  6981  6981 D A2dpService: Received start request. Starting profile...
08-30 12:30:48.325   316  1266 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:30:48.325   316  1266 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 12:30:48.325   316  1266 V AudioPolicyManager: releaseOutput() 2
08-30 12:30:48.325   316  1266 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:30:48.325   316  1379 V AudioFlinger: PlaybackThread::Track destructor
08-30 12:30:48.325   316  1379 V AudioFlinger: removeClient_l() pid 6981, calling pid 316
08-30 12:30:48.326  6981  6981 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:30:48.326  6981  7561 V LGMDMManager: Create singleton instance
08-30 12:30:48.327  6981  6981 V Avrcp   : make
08-30 12:30:48.327  6981  6981 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 12:30:48.327  6981  6981 I bluedroid-qcom: get_profile_interface avrcp
08-30 12:30:48.328  6981  7561 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 12:30:48.330  1028  1971 W Process : Unable to open /proc/7602/status
08-30 12:30:48.341  6981  6981 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 12:30:48.343  6981  6981 E AudioManager: No RCC entry present to update
08-30 12:30:48.343  6981  6981 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 12:30:48.347  6981  6981 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 12:30:48.348  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 12:30:48.348  6981  6981 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 12:30:48.351  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 12:30:48.460  1028  1763 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:30:48.460  1028  1763 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:30:48.481  7581  7581 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 12:30:48.481  7581  7581 W LG Account v2.2: No ProfileInfo entries
08-30 12:30:48.481  7581  7581 I LG Account v2.2: isEnabled: false
08-30 12:30:48.481  7581  7581 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 12:30:48.481  7581  7581 I Feature : [Lifetracker]Country: EU
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Operator: OPEN
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Ranking support: false
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Comfort support: false
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Accessory: true
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Health device: true
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Extra Pedometer: false
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Blood glucose device: false
08-30 12:30:48.482  7581  7581 I Feature : [Lifetracker]Device Number: 3
08-30 12:30:48.491  6854  6854 D BluetoothPermissionRequest: onReceive
08-30 12:30:48.495  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 12:30:48.527  1028  1864 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 12:30:48.534  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 12:30:48.537  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:30:48.538  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:30:48.539  6981  6981 I BluetoothA2dpServiceJni: classInitNative
08-30 12:30:48.539  6981  6981 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:30:48.539  6981  6981 D A2dpStateMachine: make
08-30 12:30:48.542  6981  6981 I bluedroid-qcom: get_profile_interface a2dp
08-30 12:30:48.542  6981  7609 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 12:30:48.549  6981  6981 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:30:48.550  6981  6981 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 12:30:48.552  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.553  6981  7608 D A2dpStateMachine: Enter Disconnected: -2
08-30 12:30:48.555  6981  6981 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 12:30:48.560  6981  6981 D HidService: Received start request. Starting profile...
,08-30 12:30:48.560  6981  6981 I bluedroid-qcom: get_profile_interface hidhost
08-30 12:30:48.561  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.563  6981  6981 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:30:48.567  6981  6981 D HealthService: Received start request. Starting profile...
08-30 12:30:48.571  6981  6981 I bluedroid-qcom: get_profile_interface health
08-30 12:30:48.571  6981  6981 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:30:48.571  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
,08-30 12:30:48.574  6981  6981 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 12:30:48.578  6981  6981 D PanService: Received start request. Starting profile...
08-30 12:30:48.579  6981  6981 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:30:48.579  6981  6981 I bluedroid-qcom: get_profile_interface pan
08-30 12:30:48.594  6981  6981 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 12:30:48.594  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
,08-30 12:30:48.599  6981  6981 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 12:30:48.613  6981  6981 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:30:48.614  6981  6981 D BtGatt.GattService: Received start request. Starting profile...
08-30 12:30:48.614  6981  6981 D BtGatt.GattService: start()
08-30 12:30:48.614  6981  6981 I bluedroid-qcom: get_profile_interface gatt
08-30 12:30:48.615  6981  6981 D BtGatt.AdvertiseManager: advertise manager created
08-30 12:30:48.626  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
,08-30 12:30:48.629  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
,08-30 12:30:48.629  6981  6981 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 12:30:48.632  6981  6981 V BluetoothMapService: BluetoothMapBinder()
08-30 12:30:48.633  6981  6981 D BluetoothMapService: Received start request. Starting profile...
08-30 12:30:48.633  6981  6981 D BluetoothMapService: start()
08-30 12:30:48.638  6981  6981 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 12:30:48.639  6981  6981 D BluetoothMapEmailAppObserver: createReceiver()
,08-30 12:30:48.641  6981  6981 D BluetoothMapEmailAppObserver: initObservers()
,08-30 12:30:48.641  6981  6981 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 12:30:48.653  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:48.653  6981  6981 D HeadsetStateMachine: Proxy object connected
08-30 12:30:48.655  6981  6981 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 12:30:48.655  6981  6981 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 12:30:48.657  6981  7594 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:30:48.658  6981  7594 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 12:30:48.658  6981  7594 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 12:30:48.664  6981  6981 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:30:48.671  6981  6981 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:30:48.676  6981  6981 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:30:48.681  6981  6981 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:30:48.681  6981  6981 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 12:30:48.686  6981  6981 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:30:48.690  6981  6981 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 12:30:48.691  6981  6981 V BluetoothMapService: Handler(): got msg=1
08-30 12:30:48.692  6981  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 12:30:48.692  6981  7561 I bluedroid-qcom: enable
08-30 12:30:48.692  6981  7561 I bt_hci_bdroid: init
08-30 12:30:48.694  6981  7561 I bt_vendor: bt-vendor : init
08-30 12:30:48.694  6981  7561 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 12:30:48.694  6981  7561 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 12:30:48.694  6981  7561 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
,08-30 12:30:48.694  6981  7561 D bt_userial_mct: userial_init
08-30 12:30:48.694  6981  7619 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 12:30:48.694  6981  7619 I bt-btu  : btu_task pending for preload complete event
08-30 12:30:48.694  6981  7561 D bt_hci_bdroid: set_power 1
08-30 12:30:48.694  6981  7561 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 12:30:48.694  6981  7561 I bt_vendor: Starting hciattach daemon
08-30 12:30:48.694  6981  7561 I bt_vendor: try to set true
08-30 12:30:48.697  6981  6981 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:48.689  7622  7622 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:48.689  7622  7622 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:48.702  6981  6981 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:30:48.702  6981  6981 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:30:48.702  6981  6981 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:30:48.702  6981  6981 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:48.703  6981  6981 V BluetoothSapReceiver:  Bluetooth Adapter state = 11,
,08-30 12:30:48.731  7623  7623 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 12:30:48.793  1028  1578 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7629 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:30:48.820  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 12:30:48.840  7647  7647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 12:30:48.864  7629  7629 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:30:48.867  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 12:30:48.878  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 12:30:48.882  1028  2010 I ActivityManager: Killing 6687:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 12:30:48.890  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 12:30:48.899  6918  6918 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 12:30:48.900  6918  6918 W System.err: android.os.DeadObjectException
08-30 12:30:48.901  6918  6918 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:30:48.901  6918  6918 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 12:30:48.901  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 12:30:48.901  6918  6918 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:30:48.901  6918  6918 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:30:48.901  6918  6918 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:48.901  6918  6918 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:30:48.901  6918  6918 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:30:48.901  6918  6918 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:30:48.902  6918  6918 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 12:30:48.902  6918  6918 W System.err: android.os.DeadObjectException
08-30 12:30:48.902  6918  6918 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:30:48.902  6918  6918 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 12:30:48.902  6918  6918 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:30:48.902  6918  6918 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:30:48.902  6918  6918 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:48.903  6918  6918 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-30 12:30:48.903  6918  6918 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:30:48.903  6918  6918 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:30:48.903  6918  6918 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 12:30:48.903  6918  6918 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 12:30:48.921  7655  7655 I libmdmdetect: ESOC framework not supported
08-30 12:30:48.922  7655  7655 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 12:30:48.934  7655  7655 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 12:30:48.934  7655  7655 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 12:30:48.934  7655  7655 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 12:30:48.934  7655  7655 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 12:30:48.934  7655  7655 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 12:30:48.934  7655  7655 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 12:30:48.934  7655  7655 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 12:30:48.973  7655  7658 E QC-QMI  : qmi_client [7655] 14: failed to locate client data
,08-30 12:30:48.979   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 12:30:48.979   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-30 12:30:48.994  1028  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_6687/cgroup.procs: No such file or directory
08-30 12:30:48.994  1028  1578 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 12:30:49.002  6918  6918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 12:30:49.003  6918  6918 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 12:30:49.034  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 12:30:49.049  7660  7660 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 12:30:49.073  1028  1899 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7662 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:30:49.075  6918  6918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 12:30:49.099  6981  7561 I bt_vendor: bluetooth satus is on
08-30 12:30:49.099  6981  7561 D bt_hci_bdroid: preload
,08-30 12:30:49.099  6981  7621 D bt_userial_mct: userial_open(port:0)
08-30 12:30:49.099  6981  7621 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 12:30:49.103  6981  7621 I bt_vendor: Done intiailizing UART
08-30 12:30:49.104  6981  7621 I bt_vendor: Done intiailizing UART
08-30 12:30:49.104  6981  7621 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 12:30:49.104  6981  7621 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 12:30:49.104  6981  7619 I bt-btu  : btu_task received preload complete event
08-30 12:30:49.104  6981  7679 D bt_userial_mct: Entering userial_read_thread()
,08-30 12:30:49.105  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 12:30:49.105  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 12:30:49.108  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 12:30:49.111  6981  7619 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 12:30:49.111  6981  7619 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 12:30:49.111  6981  7619 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:30:49.111  6981  7619 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:30:49.111  6981  7619 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:30:49.111  6981  7619 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:30:49.112  6981  7619 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:30:49.169  7662  7662 D UEI.SmartControl: Quickset Services start...
,08-30 12:30:49.172  7662  7662 I UEI.SmartControl: Manufacture = LGE
08-30 12:30:49.172  7662  7662 D UEI.SmartControl: Id = LGNevo
08-30 12:30:49.174  7662  7662 D UEI.SmartControl: File observer start...
08-30 12:30:49.177  7662  7662 E UEI.SmartControl: IR Port is disabled: false
08-30 12:30:49.177  7662  7662 D UEI.SmartControl: Starting file observer...
08-30 12:30:49.178  7662  7662 D UEI.SmartControl: Extracting JNI libs...
08-30 12:30:49.178  7662  7662 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 12:30:49.180  6981  7619 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 12:30:49.180  6981  7619 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0240061 
,08-30 12:30:49.180  6981  7619 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0240061 
08-30 12:30:49.192  6981  7565 E bt-btif : Calling BTA_HhEnable
08-30 12:30:49.192  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 12:30:49.192  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 12:30:49.193  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 12:30:49.193  6981  7565 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 12:30:49.193  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 12:30:49.193  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 12:30:49.193  6981  7565 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 12:30:49.195  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:30:49.195  6981  7565 D BluetoothAdapterProperties: Name is: G3
08-30 12:30:49.195  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 12:30:49.197  6981  7565 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:30:49.198  6981  7565 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:30:49.198  6981  7565 D bt_hci_bdroid: postload
08-30 12:30:49.198  6981  7621 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:30:49.199  6981  7619 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 12:30:49.199  6981  7565 D bte_conf: Device ID record 1 : primary
08-30 12:30:49.199  6981  7565 D bte_conf:   vendorId            = 00c4
08-30 12:30:49.199  6981  7565 D bte_conf:   vendorIdSource      = 0001
08-30 12:30:49.199  6981  7565 D bte_conf:   product             = 13a1
08-30 12:30:49.199  6981  7565 D bte_conf:   version             = 1000
08-30 12:30:49.199  6981  7565 D bte_conf:   clientExecutableURL = 
08-30 12:30:49.199  6981  7565 D bte_conf:   serviceDescription  = 
08-30 12:30:49.199  6981  7565 D bte_conf:   documentationURL    = 
08-30 12:30:49.199  6981  7565 D bte_conf: bte_load_did_conf no section named DID2.
08-30 12:30:49.200  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:49.201  6981  7621 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:30:49.202  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:49.203  6981  7621 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:30:49.203  6981  7621 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:30:49.189  7682  7682 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:49.189  7682  7682 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:49.204  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:49.204  6981  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 12:30:49.204  6981  7561 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:30:49.204  6981  7561 D BluetoothAdapterProperties: State =  11
,08-30 12:30:49.206  6981  7561 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 12:30:49.208  6981  7561 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
,08-30 12:30:49.217  6981  7619 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:30:49.218  6981  7619 W bt-smp  : Plain text(LSB ~ MSB) = 1a cb 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:30:49.218  6981  7561 D BluetoothAdapterProperties: Setting state to 12
08-30 12:30:49.218  6981  7619 W bt-smp  : Encrypted text(LSB ~ MSB) = df 02 49 f8 be cd b0 5f 43 fc 69 5c ca 07 a2 fd 
08-30 12:30:49.218  6981  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:30:49.218  6981  7619 W bt-btm  : Stopping oneshot timer
08-30 12:30:49.218  6981  7621 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:30:49.218  6981  7565 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 12:30:49.220  6981  7565 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:30:49.221  6981  7679 E bt_mct  : hci lib postload completed
08-30 12:30:49.227  6981  7561 I BluetoothAdapterState: Entering On State
,08-30 12:30:49.226  1028  1110 D BluetoothManagerService: Message: 60
,08-30 12:30:49.227  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 12:30:49.227  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 12:30:49.228  1829  1845 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:49.230  6981  7561 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 12:30:49.230  6981  7561 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 12:30:49.230  6981  7561 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 12:30:49.231  6981  7561 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 12:30:49.234  6854  6869 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:30:49.234  6854  6869 D BluetoothPan: onBluetoothStateChange call bindService
08-30 12:30:49.235  1829  1829 D BluetoothHeadset: Proxy object connected
08-30 12:30:49.236  6981  7565 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:30:49.236  6981  7565 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 12:30:49.238  6854  6870 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:30:49.240  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:49.241  1028  1028 D BluetoothHeadset: Proxy object connected
,08-30 12:30:49.243  1829  2759 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:49.246  6854  6854 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:30:49.246  6854  6854 D PanProfile: Bluetooth service connected
08-30 12:30:49.246  1829  1829 D BluetoothHeadset: Proxy object connected
08-30 12:30:49.248  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:30:49.249  6854  6869 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:30:49.250  1028  1028 D BluetoothA2dp: Proxy object connected
08-30 12:30:49.253  1829  1845 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:49.253  6981  7619 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:30:49.253  6981  7619 W bt-smp  : Plain text(LSB ~ MSB) = 5a 09 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:30:49.253  6981  7619 W bt-smp  : Encrypted text(LSB ~ MSB) = b0 52 f1 a8 66 ae be cc 5e 6c bc fa 64 6d 40 96 
08-30 12:30:49.253  6981  7619 W bt-btm  : Stopping oneshot timer
,08-30 12:30:49.258  1829  1829 D BluetoothHeadset: Proxy object connected
08-30 12:30:49.259  6854  7685 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:30:49.265  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 12:30:49.266  1028  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 12:30:49.266  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 12:30:49.273  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:49.273  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:30:49.276  7689  7689 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 12:30:49.276  1919  2071 D LGBluetoothAPIService: Message: 1
08-30 12:30:49.277  1919  2071 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 12:30:49.277  6981  7619 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:30:49.277  6981  7619 W bt-smp  : Plain text(LSB ~ MSB) = 69 83 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:30:49.277  6981  7619 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e 15 2f a0 87 35 14 0a 1c 14 c8 57 9d fc ea c5 
08-30 12:30:49.277  6981  7619 W bt-btm  : Stopping oneshot timer
08-30 12:30:49.278  6981  7561 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 12:30:49.283  6629  6629 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 12:30:49.283  1028  1110 D BluetoothManagerService: Message: 40
08-30 12:30:49.283  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 12:30:49.284  6854  6854 D BluetoothMap: Proxy object connected
08-30 12:30:49.284  6854  6854 D MapProfile: Bluetooth service connected
08-30 12:30:49.284  6854  6854 D BluetoothMap: getConnectedDevices()
08-30 12:30:49.287  6981  6997 V BluetoothMapService: getConnectedDevices()
08-30 12:30:49.289  6981  7619 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:30:49.289  6981  7619 W bt-smp  : Plain text(LSB ~ MSB) = 7d 2d 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:30:49.289  6981  7619 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 c8 be b6 52 df 6a c6 0b 03 44 16 3f af eb 55 
08-30 12:30:49.289  6981  7619 W bt-btm  : Stopping oneshot timer
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:49.291  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:49.297  6981  6981 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.297  6981  6981 D BluetoothMapService: STATE_ON
08-30 12:30:49.298  1919  2071 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 12:30:49.299  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:49.299  6854  6854 D BluetoothInputDevice: Proxy object connected
08-30 12:30:49.299  6854  6854 D HidProfile: Bluetooth service connected
08-30 12:30:49.302  6981  6981 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-30 12:30:49.303  6981  6981 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 12:30:49.305  1919  1919 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 12:30:49.305  1919  2071 D LGBluetoothAPIService: Message: 100
08-30 12:30:49.305  1919  2071 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 12:30:49.305  6981  6981 V BluetoothMapService: Handler(): got msg=1
08-30 12:30:49.306  6981  7619 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:30:49.306  6981  7619 W bt-smp  : Plain text(LSB ~ MSB) = b1 90 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:30:49.306  6981  7619 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a c6 01 3f ee 93 2c 4a f5 77 b5 40 5a a6 0c 0a 
08-30 12:30:49.306  6981  7619 W bt-btm  : Stopping oneshot timer
08-30 12:30:49.307  6981  6981 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 12:30:49.308  6981  7696 D BluetoothMapMasInstance: MAS initSocket()
08-30 12:30:49.308  6854  6854 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 12:30:49.309  6981  7696 D BluetoothMapMasInstance:   masId = 00
08-30 12:30:49.309  6981  7696 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 12:30:49.309  6981  7696 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 12:30:49.309  6981  7696 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 12:30:49.310  1028  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:49.311  1028  1110 D BluetoothManagerService: Message: 30
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:49.312  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:49.312  6981  7696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:30:49.314  6981  7696 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 12:30:49.314  6981  7696 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 12:30:49.314  6981  7696 D BluetoothMapMasInstance: Accepting socket connection...
08-30 12:30:49.316  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:49.317  6981  7565 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:30:49.318  6981  7565 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:49.321  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:49.323  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:49.324  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:49.325  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:49.328  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:49.329  6854  6854 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 12:30:49.331  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:49.331  6981  6981 V BluetoothPbapService: Pbap Service onCreate
08-30 12:30:49.331  6981  6981 V BluetoothPbapService: Starting PBAP service
08-30 12:30:49.332  1028  1110 D BluetoothManagerService: Message: 30
08-30 12:30:49.334  6981  6981 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 12:30:49.334  6981  6981 V BluetoothPbapService: Pbap Service onBind
08-30 12:30:49.336  7662  7662 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 12:30:49.337  7662  7662 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 12:30:49.337  7662  7662 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 12:30:49.337  6981  6981 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.337  6981  6981 V BluetoothPbapService: state: 12
08-30 12:30:49.338  6981  6981 V BluetoothPbapService: Handler(): got msg=1
08-30 12:30:49.339  6981  6981 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 12:30:49.340  6981  7697 V BluetoothPbapService: Pbap Service initSocket
08-30 12:30:49.341  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 12:30:49.341  1028  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:49.341  6981  7697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:30:49.342  6981  7697 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 12:30:49.342  6981  7697 V BluetoothPbapService: Succeed to create listening socket 
08-30 12:30:49.342  6981  7697 V BluetoothPbapService: Accepting socket connection...
08-30 12:30:49.342  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 12:30:49.346  6854  6854 D BluetoothA2dp: Proxy object connected
08-30 12:30:49.346  6981  6981 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:30:49.347  6981  6981 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.347  6981  6981 V BluetoothPbapReceiver: ***********state = 12
08-30 12:30:49.347  6854  6854 D A2dpProfile: Bluetooth service connected
08-30 12:30:49.350  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:49.350  2197  2197 D c       : Getting all permits...
08-30 12:30:49.350  2197  2197 D a       : Opening database...
08-30 12:30:49.351  6854  6854 D BluetoothPbap: Proxy object connected
08-30 12:30:49.352  6854  6854 D PbapServerProfile: Bluetooth service connected
,08-30 12:30:49.352  6854  6854 D BluetoothHeadset: Proxy object connected
08-30 12:30:49.353  6854  6854 D HeadsetProfile: Bluetooth service connected
08-30 12:30:49.353  2197  2197 D a       : Opening database auth.proximity.permit_store...
08-30 12:30:49.354  2197  2197 D a       : Closing database...
,08-30 12:30:49.360  6854  6854 D DockEventReceiver: finishStartingService: stopping service
08-30 12:30:49.368  6854  6854 D BluetoothPermissionRequest: onReceive
,08-30 12:30:49.370  6854  6854 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 12:30:49.372  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:30:49.374  6981  6981 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 12:30:49.375  6981  6981 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 12:30:49.381  6981  6981 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 12:30:49.384  7662  7662 I UEI.SmartControl: --- Selecting new region: 6
08-30 12:30:49.386  7662  7662 I UEI.SmartControl: Model = LG-D855
08-30 12:30:49.388  7662  7662 D UEI.SmartControl: QS Service created
08-30 12:30:49.398  7662  7662 I UEI.SmartControl: Service initServices...
,08-30 12:30:49.400  6981  6981 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:30:49.400  6981  6981 V BtOppService: onCreate
08-30 12:30:49.401  7662  7662 D UEI.SmartControl: QS start get config
08-30 12:30:49.437  7662  7662 D UEI.SmartControl: Loading JNI Libs...
,08-30 12:30:49.534  1028  1578 I art     : Explicit concurrent mark sweep GC freed 122978(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.553ms total 132.029ms
08-30 12:30:49.536  6981  6981 V BluetoothOppNotification: send message
,08-30 12:30:49.540  6981  6981 V BtOppService: Starting RfcommListener
08-30 12:30:49.541  6981  7703 V BtOppService: Deleted complete outbound shares, number =  0
08-30 12:30:49.542  6981  7703 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 12:30:49.542  6981  7703 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 12:30:49.543  6981  7703 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd68c03 on behalf of 
08-30 12:30:49.549  6981  6981 D BluetoothOppPreference: Dumping Names:  
08-30 12:30:49.549  6981  6981 D BluetoothOppPreference: {}
08-30 12:30:49.549  6981  6981 D BluetoothOppPreference: Dumping Channels:  
08-30 12:30:49.549  6981  6981 D BluetoothOppPreference: {}
08-30 12:30:49.549  6981  6981 V BtOppService: onStartCommand
08-30 12:30:49.550  6981  7706 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:30:49.550  6981  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 12:30:49.552  6981  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10fb51b9 on behalf of 
08-30 12:30:49.552  6981  6981 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.552  6981  6981 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:30:49.552  6981  7706 V BluetoothOppNotification: update too frequent, put in queue
,08-30 12:30:49.554  6981  7706 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:30:49.554  6981  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:30:49.554  6981  6981 V BluetoothOppNotification: new notify threadi!
08-30 12:30:49.555  6981  6981 V BluetoothOppNotification: send delay message
08-30 12:30:49.555  6981  6981 V BtOppService: start RfcommListener
08-30 12:30:49.556  6981  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfe59fe on behalf of 
08-30 12:30:49.558  6981  6981 V BtOppService: RfcommListener started
08-30 12:30:49.558  6981  6981 V BtOppService: ContentObserver received notification
08-30 12:30:49.559  6981  6981 V BtOppService: ContentObserver received notification
08-30 12:30:49.559  6981  7707 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:30:49.566  6981  7708 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 12:30:49.566  1028  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:30:49.567  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:49.567  6981  6981 V BluetoothFtpService: Ftp Service onCreate
08-30 12:30:49.567  6981  6981 I BluetoothFtpService: Ftp Service onCreate
08-30 12:30:49.567  6981  6981 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:30:49.568  6981  6981 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.568  6981  6981 V BluetoothFtpService: Starting Listening on sockets
08-30 12:30:49.568  6981  6981 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:30:49.568  6981  6981 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:30:49.568  6981  6981 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:30:49.568  6981  6981 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.568  6981  6981 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 12:30:49.568  6981  6981 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:30:49.569  6981  7708 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:30:49.569  6981  7706 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:30:49.569  6981  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:30:49.570  6981  7707 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@200dcbac on behalf of 
08-30 12:30:49.570  6981  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cf65075 on behalf of 
08-30 12:30:49.571  6981  6981 V BluetoothFtpService: Handler(): got msg=1
08-30 12:30:49.571  6981  6981 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 12:30:49.571  6981  6981 V BluetoothFtpService: Ftp Service initSocket
08-30 12:30:49.571  6981  7708 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-30 12:30:49.571  6981  7708 V BtOppRfcommListener: Started RFCOMM listener....
08-30 12:30:49.571  6981  7708 I BtOppRfcommListener: Accept thread started.
08-30 12:30:49.571  6981  7708 V BtOppRfcommListener: Accepting connection...
08-30 12:30:49.572  6981  7707 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:30:49.572  6981  7706 V BluetoothOppNotification: update too frequent, put in queue
08-30 12:30:49.572  6981  7707 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 12:30:49.573  6981  7706 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 12:30:49.573  6981  7707 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e2180a on behalf of 
08-30 12:30:49.574  6981  7707 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:30:49.574  6981  7707 V BluetoothOppNotification: outbound notification was removed.
08-30 12:30:49.575  6981  7707 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:30:49.575  1028  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:49.576  6981  6981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:30:49.576  6981  7707 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2553787b on behalf of 
08-30 12:30:49.577  6981  7707 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 12:30:49.578  6981  6981 V BluetoothFtpService: Succeed to create listening, socket on channel 20
08-30 12:30:49.578  6981  7709 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 12:30:49.582  6981  7707 V BluetoothOppNotification: inbound notification was removed.
08-30 12:30:49.582  6981  7707 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 12:30:49.584  6981  7707 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d61f698 on behalf of 
08-30 12:30:49.586  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:49.586  6981  6981 V BluetoothSapService: Sap Service onCreate
08-30 12:30:49.588  6981  6981 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:49.588  6981  6981 V BluetoothSapService: state: 12
08-30 12:30:49.588  6981  6981 V BluetoothSapService: Starting SAP server process
08-30 12:30:49.579  7710  7710 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:30:49.589  6981  6981 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-30 12:30:49.579  7710  7710 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:30:49.591  6981  7711 V BluetoothSapService: Sap Service initRfcommSocket
08-30 12:30:49.592  1028  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:49.594  6981  7711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:30:49.595  7710  7710 V BT_SAP  : Event pipe created
08-30 12:30:49.595  7710  7710 V BT_SAP  : create_server_socket qcom.sap.server
08-30 12:30:49.595  7710  7710 V BT_SAP  : created socket fd 6
08-30 12:30:49.595  6981  7711 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 12:30:49.595  6981  7711 V BluetoothSapService: Succeed to create listening socket 
08-30 12:30:49.595  6981  7711 V BluetoothSapService: Accepting socket connection...
08-30 12:30:49.718  7662  7662 I UEI.SmartControl: Supports setup maps: true
,08-30 12:30:49.721  7662  7662 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 12:30:49.721  7662  7662 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:30:49.721  7662  7662 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:30:49.721  7662  7662 I UEI.SmartControl: ### init IR Blaster...
08-30 12:30:49.725  7662  7662 D serial_port: Configuring serial port
08-30 12:30:49.728  7662  7662 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:30:49.728  7662  7662 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:30:49.729  7662  7662 I UEI.SmartControl: configuring settings for MAXQ616
,08-30 12:30:49.729  7662  7662 I UEI.SmartControl: Get version...
08-30 12:30:49.746  7662  7712 D UEI.SmartControl: serial port data available: 21
,08-30 12:30:49.776  7662  7662 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 12:30:49.776  7662  7662 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 12:30:49.777  7662  7662 I UEI.SmartControl: QS saving settings...
08-30 12:30:49.779  7662  7662 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 12:30:49.797  7662  7712 D UEI.SmartControl: serial port data available: 4
,08-30 12:30:49.840  7662  7715 I UEI.SmartControl: Device manager: loading config....
,08-30 12:30:49.842  7662  7715 D UEI.SmartControl: ----------- loading internal config...
,08-30 12:30:49.847  7662  7662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 12:30:49.851  7662  7662 E UEI.SmartControl: Services init done
08-30 12:30:49.851  7662  7662 D UEI.SmartControl: QS Service init finished
08-30 12:30:49.857  7662  7662 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:30:49.857  7662  7662 D UEI.SmartControl: QS Service version code: 201091
08-30 12:30:49.860  7662  7662 D UEI.SmartControl: Service requested: Control
,08-30 12:30:49.863  7662  7715 E UEI.SmartControl: Loading SETTINGS...
08-30 12:30:49.865  7662  7662 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 12:30:49.868  6918  6918 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 12:30:49.870  7662  7678 I UEI.SmartControl: ------ IControl API: 11
08-30 12:30:49.871  1028  1899 I ActivityManager: Killing 6918:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 12:30:49.872  7662  7678 I UEI.SmartControl: Registering callback...
08-30 12:30:49.874  7662  7715 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 12:30:49.879  7662  7714 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:30:49.880  7662  7714 D UEI.SmartControl: -----service ready thread exits
08-30 12:30:49.917  1028  1043 W libprocessgroup: failed to open /acct/uid_10112/pid_6918/cgroup.procs: No such file or directory
,08-30 12:30:49.917  7662  7662 D UEI.SmartControl: Internal service binding...
,08-30 12:30:50.146  1582  1582 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 12:30:50.190  1028  1358 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:30:50.233  1028  1095 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7728 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 12:30:50.239  1582  1582 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 12:30:50.240  1582  1582 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 12:30:50.272  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 12:30:50.275  1028  1028 D administrator: Handling package changes for user 0
,08-30 12:30:50.323  7728  7728 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 12:30:50.324  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:30:50.393  7728  7728 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:50.393  7728  7728 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:50.394  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 12:30:50.394  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 12:30:50.485  1028  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:30:50.490  7728  7771 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 12:30:50.490  7728  7771 I Babel   : MmsConfig.loadMmsSettings
08-30 12:30:50.493  1028  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 12:30:50.494  7728  7771 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 12:30:50.494  7728  7771 I Babel   : MmsConfig.loadFromDatabase
08-30 12:30:50.502  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 12:30:50.504  2482  2482 V GmsNetworkLocationProvi: DISABLE
,08-30 12:30:50.530  7728  7771 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 12:30:50.531  7728  7771 I Babel   : MmsConfig.loadFromResources
08-30 12:30:50.532  7728  7771 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 12:30:50.533  7728  7771 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 12:30:50.534  2482  2482 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 12:30:50.534  1028  1093 D LocationProviderProxy: applying state to connected service
08-30 12:30:50.546  7728  7769 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:30:50.546  7728  7728 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:30:50.548  7728  7769 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:30:50.550  7728  7769 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:30:50.558  6981  6981 V BluetoothOppNotification: new notify threadi!
08-30 12:30:50.558  6981  6981 V BluetoothOppNotification: send delay message
08-30 12:30:50.558  7728  7769 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 12:30:50.559  7728  7769 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:30:50.560  6981  7774 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:30:50.560  6981  7774 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1acbe444 on behalf of 
08-30 12:30:50.561  6981  7774 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:30:50.561  7728  7769 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:30:50.562  6981  7774 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 12:30:50.563  6981  7774 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18f5192d on behalf of 
08-30 12:30:50.563  6981  7774 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:30:50.565  6981  7774 V BluetoothOppNotification: outbound notification was removed.
08-30 12:30:50.565  6981  7774 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:30:50.565  6981  7774 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33d59e62 on behalf of 
08-30 12:30:50.566  6981  7774 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 12:30:50.568  6981  7774 V BluetoothOppNotification: inbound notification was removed.
08-30 12:30:50.568  6981  7774 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 12:30:50.569  6981  7774 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a027bf3 on behalf of 
08-30 12:30:50.575  7728  7769 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 12:30:50.576  1794  7776 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 12:30:50.576  1794  7776 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 12:30:50.577  7728  7769 W VideoCapabilities: Unsupported mime video/divx
,08-30 12:30:50.588  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:30:50.598  7728  7769 W VideoCapabilities: Unsupported mime video/divx311
,08-30 12:30:50.600  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
08-30 12:30:50.600  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:30:50.600  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:30:50.600  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:30:50.600  7029  7029 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 12:30:50.602  7728  7769 W VideoCapabilities: Unsupported mime video/divx4
08-30 12:30:50.607  1794  4775 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 12:30:50.612  7728  7769 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 12:30:50.634  1028  1569 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7780 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 12:30:50.638  1028  1043 I ActivityManager: Killing 6872:com.lge.sync/1000 (adj 15): empty #17
08-30 12:30:50.639  7728  7769 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 12:30:50.656  7728  7769 W AudioCapabilities: Unsupported mime audio/eac3
,08-30 12:30:50.657  7728  7769 W AudioCapabilities: Unsupported mime audio/ac3
08-30 12:30:50.658  7728  7769 W AudioCapabilities: Unsupported mime audio/g726
08-30 12:30:50.659  7728  7769 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 12:30:50.660  7728  7769 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 12:30:50.660  7728  7769 W AudioCapabilities: Unsupported mime audio/adpcm
,08-30 12:30:50.662  7728  7769 W VideoCapabilities: Unsupported mime video/theora
08-30 12:30:50.663  7728  7769 W VideoCapabilities: Unsupported mime video/mjpg
08-30 12:30:50.818  1028  1971 W libprocessgroup: failed to open /acct/uid_1000/pid_6872/cgroup.procs: No such file or directory
,08-30 12:30:50.861  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:30:50.861  7780  7780 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:30:50.861  7780  7780 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:30:50.863  7780  7780 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-30 12:30:50.863  7780  7780 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 12:30:50.943  7780  7780 I SystemConfig: BUILD Country: EU
08-30 12:30:50.943  7780  7780 I SystemConfig: BUILD Operator: OPEN
,08-30 12:30:50.993  1028  1899 I ActivityManager: Killing 7070:com.lge.email/u0a23 (adj 15): empty #17
,08-30 12:30:51.028  1028  2010 W libprocessgroup: failed to open /acct/uid_10023/pid_7070/cgroup.procs: No such file or directory
,08-30 12:30:51.033  7780  7798 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-30 12:30:51.033  7780  7798 I SystemConfig: existFile = false
08-30 12:30:51.033  7780  7798 I SystemConfig: canReadFile = false
08-30 12:30:51.033  7780  7798 I SystemConfig: systemFeature RCS result false
08-30 12:30:51.033  7780  7798 D SystemConfig: refreshRcsSupport() :false
08-30 12:30:51.116  1028  1899 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7800 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 12:30:51.139   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 502us total 24.782ms
,08-30 12:30:51.159   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 19.795ms
,08-30 12:30:51.179   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 379us total 18.020ms
,08-30 12:30:51.184  7800  7800 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:30:51.184  7800  7800 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 12:30:51.184  7800  7800 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:30:51.185  7800  7800 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:30:51.269  7800  7800 I AppConfig: Total System Memory = 2995761152
,08-30 12:30:51.279  7800  7800 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 12:30:51.372  1028  1569 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7822 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:30:51.373  1028  1569 I ActivityManager: Killing 6958:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 12:30:51.478  1028  1863 W libprocessgroup: failed to open /acct/uid_10026/pid_6958/cgroup.procs: No such file or directory
,08-30 12:30:51.753  7822  7822 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 12:30:51.829  7822  7822 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:30:51.830  7822  7822 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:51.894  7822  7822 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 12:30:51.917  7822  7822 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:30:51.918  7822  7822 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 12:30:51.935  7822  7822 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 12:30:51.936  7822  7822 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 12:30:51.959  1028  1044 I ActivityManager: Killing 7393:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-30 12:30:52.117  1028  1918 W libprocessgroup: failed to open /acct/uid_10005/pid_7393/cgroup.procs: No such file or directory
,08-30 12:30:52.142  4601  7874 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 12:30:52.198  1028  1578 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7875 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 12:30:52.276  3510  6252 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-30 12:30:52.287  3510  6252 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e8d5c05 on behalf of 7822
08-30 12:30:52.326  7822  7822 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 12:30:52.332  7875  7875 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-30 12:30:52.347  7822  7822 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 12:30:52.364  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 12:30:52.364  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 12:30:52.364  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 12:30:52.364  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 12:30:52.364  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 12:30:52.364  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 12:30:52.383  1028  1918 I ActivityManager: Killing 6422:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 12:30:52.471  1028  1864 W libprocessgroup: failed to open /acct/uid_1000/pid_6422/cgroup.procs: No such file or directory
,08-30 12:30:52.693  1028  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{170f53e0 type 2 when 175513 com.google.android.gms} when 175513
,08-30 12:30:52.704   312  7917 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:30:52.707  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 12:30:52.745  1028  1971 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7918 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 12:30:52.820  7918  7918 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:30:52.832  1028  1044 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:30:52.846  7918  7918 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 12:30:52.863  4601  7874 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 722 ms] updated apps [took 722 ms] 
,08-30 12:30:52.886  7918  7918 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 12:30:52.887  7918  7918 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 12:30:52.887  7918  7918 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 12:30:52.888  7918  7918 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 12:30:52.888  7918  7918 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 12:30:52.890  7918  7918 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 12:30:52.897  7918  7918 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 12:30:52.905  7918  7918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 12:30:52.905  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7674
,08-30 12:30:52.911  7918  7918 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 12:30:52.915  7918  7918 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 12:30:52.917  7918  7918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 12:30:52.918  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 12:30:52.918  7918  7918 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 12:30:52.955  7918  7918 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:30:52.956  7918  7918 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:30:52.965  7918  7918 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 12:30:52.970  7918  7918 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 12:30:52.970  7918  7918 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 12:30:52.970  7918  7918 V SoundPool: doLoad: loading sample sampleID=1
,08-30 12:30:52.972  7918  7939 V SoundPool: Start decode
08-30 12:30:52.972  7918  7939 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 12:30:52.973  7918  7918 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 12:30:52.973   316   316 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 12:30:52.973   316   316 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 12:30:52.974   316   316 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 12:30:52.974   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 12:30:52.974   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 12:30:52.974   316   316 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 12:30:52.974   316   316 V MediaPlayerService: player type = 3
08-30 12:30:52.974   316   316 V AwesomePlayer: AwesomePlayer create()
08-30 12:30:52.974   316   316 V AwesomePlayer: reset_l() 
08-30 12:30:52.974   316   316 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:52.974   316   316 V AwesomePlayer: setAudioSink() 
08-30 12:30:52.974   316   316 V AwesomePlayer: reset_l() 
08-30 12:30:52.974   316   316 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-30 12:30:52.974   316   316 V AudioCache: ignored
08-30 12:30:52.974   316   316 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:52.974   316   316 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 12:30:52.974   316   316 V AwesomePlayer: setDataSource_l dataSource
08-30 12:30:52.974   316   316 V LGParserOSAL: SniffLGParser start
08-30 12:30:52.974   316   316 V LGParserOSAL: MainType:5, SubType=0
08-30 12:30:52.975   316   316 V LGParserOSAL: #### check Mime : application/ogg
08-30 12:30:52.975   316   316 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 12:30:52.975   316   316 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 12:30:52.980  7918  7918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 12:30:52.983  7918  7918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:30:52.983  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-30 12:30:53.002  7918  7918 V LGMDMManager: Create singleton instance
08-30 12:30:53.033   316   316 V LGParserOSAL: supported mime: application/ogg
08-30 12:30:53.033   316   316 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 12:30:53.033   316   316 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 12:30:53.033   316   316 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 12:30:53.033   316   316 V AwesomePlayer: AudioTrack Setting
,08-30 12:30:53.033   316   316 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 12:30:53.033   316   316 V AwesomePlayer: setAudioSource() 
08-30 12:30:53.033   316   316 V MediaPlayerService: prepare
08-30 12:30:53.033   316   316 V AwesomePlayer: prepareAsync_l() 
08-30 12:30:53.033   316   316 V MediaPlayerService: wait for prepare
,08-30 12:30:53.034   316  7940 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 12:30:53.034   316  7940 V AwesomePlayer: initAudioDecoder() 
08-30 12:30:53.034   316  7940 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 12:30:53.034   316  7940 V AudioSystem: isOffloadSupported()
08-30 12:30:53.034   316  7940 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 12:30:53.034   316  7940 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 12:30:53.034   316  7940 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:30:53.034   316  7940 V AwesomePlayer: getUseOffload() = 0 
08-30 12:30:53.034   316  7940 V OMXCodec: OMXCodec::Create
08-30 12:30:53.034   316  7940 V OMXCodec: findMatchingCodecs()
08-30 12:30:53.034   316  7940 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,08-30 12:30:53.034   316  7940 V OMXCodec: matchingCodecs.size()=1
08-30 12:30:53.034   316  7940 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 12:30:53.036   316  7940 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 12:30:53.036   316  7940 V LGCodecAdapter: LG Codec Adapter start
08-30 12:30:53.037   316  7940 V OMXCodec: OMXCodec Createtor
08-30 12:30:53.037   316  7940 V OMXCodec: setComponentRole
08-30 12:30:53.037   316  7940 V OMXCodec: configureCodec protected=0
08-30 12:30:53.037   316  7940 V LGCodecAdapter: called getLGCodecSpecificData
08-30 12:30:53.037   316  7940 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 12:30:53.037   316  7940 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 12:30:53.037   316  7940 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 12:30:53.037   316  7940 V LGCodecOSAL: Not support LGCodec
08-30 12:30:53.037   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 12:30:53.037   316  7940 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 12:30:53.037   316  7940 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 12:30:53.037   316  7940 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 12:30:53.037   316  7940 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 12:30:53.037   316  7940 V AudioSystem: isOffloadSupported()
,08-30 12:30:53.037   316  7940 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 12:30:53.037   316  7940 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 12:30:53.037   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 12:30:53.037   316  7940 V OMXCodec: init()
08-30 12:30:53.037   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 12:30:53.037   316  7940 V OMXCodec: allocateBuffers
08-30 12:30:53.037   316  7940 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 12:30:53.037   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-30 12:30:53.038   316  7940 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fd420 on output port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fd880 on output port
08-30 12:30:53.038   316  7940 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fd920 on output port
08-30 12:30:53.038   316  7940 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 12:30:53.038   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 12:30:53.038   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 12:30:53.038   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 12:30:53.038   316  7940 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 12:30:53.039   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 12:30:53.039   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 12:30:53.039   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 12:30:53.039   316  7940 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 12:30:53.039   316  7940 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 12:30:53.039   316  7940 V AudioCache: notify(0xb54749c0, 5, 0, 0)
08-30 12:30:53.039   316  7940 V AudioCache: ignored
08-30 12:30:53.039   316  7940 V AudioCache: notify(0xb54749c0, 1, 0, 0)
08-30 12:30:53.039   316  7940 V AudioCache: prepared
08-30 12:30:53.039   316   316 V AudioCache: wait - success
08-30 12:30:53.039   316   316 V MediaPlayerService: start
08-30 12:30:53.039   316   316 V AwesomePlayer: play_l() 
08-30 12:30:53.039   316   316 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 12:30:53.039   316   316 V AwesomePlayer: createAudioPlayer_l
08-30 12:30:53.039   316   316 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 12:30:53.039   316   316 V AwesomePlayer: startAudioPlayer_l() 
08-30 12:30:53.039   316   316 D AudioPlayer: start of Playback, useOffload 0
08-30 12:30:53.039   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 12:30:53.039   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.v,orbis.decoder] setState mState=4 , newState=7
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045053472
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045054592
08-30 12:30:53.042   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045054752
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 12:30:53.043   316  7942 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fd880 on output port
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fd420 on output port
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on output port
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 12:30:53.043   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 12:30:53.044   316   316 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 12:30:53.045   316   316 V AudioCache: notify(0xb54749c0, 6, 0, 0)
08-30 12:30:53.045   316   316 V AudioCache: ignored
08-30 12:30:53.045   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.045   316  7943 V AudioCache: memcpy(0xaf006000, 0xb17fc000, 4096)
08-30 12:30:53.045   316   316 V MediaPlayerService: wait for playback complete
08-30 12:30:53.050   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.050   316  7943 V AudioCache: memcpy(0xaf007000, 0xb17fc000, 4096)
08-30 12:30:53.050   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.050   316  7943 V AudioCache: memcpy(0xaf008000, 0xb17fc000, 4096)
08-30 12:30:53.050   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.050   316  7943 V AudioCache: memcpy(0xaf009000, 0xb17fc000, 4096)
08-30 12:30:53.051   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.051   316  7943 V AudioCache: memcpy(0xaf00a000, 0xb17fc000, 4096)
08-30 12:30:53.052   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.052   316  7943 V AudioCache: memcpy(0xaf00b000, 0xb17fc000, 4096)
08-30 12:30:53.053   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: memcpy(0xaf00c000, 0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: memcpy(0xaf00d000, 0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: memcpy(0xaf00e000, 0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: memcpy(0xaf00f000, 0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.054   316  7943 V AudioCache: memcpy(0xaf010000, 0xb17fc000, 4096)
08-30 12:30:53.055   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.055   316  7943 V AudioCache: memcpy(0xaf011000, 0xb17fc000, 4096)
08-30 12:30:53.055   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.055   316  7943 V AudioCache: memcpy(0xaf012000, 0xb17fc000, 4096)
08-30 12:30:53.056   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.056   316  7943 V AudioCache: memcpy(0xaf013000, 0xb17fc000, 4096)
08-30 12:30:53.056   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.056   316  7943 V AudioCache: memcpy(0xaf014000, 0xb17fc000, 4096)
08-30 12:30:53.057   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.057   316  7943 V AudioCache: memcpy(0xaf015000, 0xb17fc000, 4096)
08-30 12:30:53.058   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.058   316  7943 V AudioCache: memcpy(0xaf016000, 0xb17fc000, 4096)
08-30 12:30:53.059   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.059   316  7943 V AudioCache: memcpy(0xaf017000, 0xb17fc000, 4096)
08-30 12:30:53.060   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.060   316  7943 V AudioCache: memcpy(0xaf018000, 0xb17fc000, 4096)
08-30 12:30:53.060   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.060   316  7943 V AudioCache: memcpy(0xaf019000, 0xb17fc000, 4096)
08-30 12:30:53.061   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.061   316  7943 V AudioCache: memcpy(0xaf01a000, 0xb17fc000, 4096)
08-30 12:30:53.062   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.062   316  7943 V AudioCache: memcpy(0xaf01b000, 0xb17fc000, 4096)
08-30 12:30:53.063   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.063   316  7943 V AudioCache: memcpy(0xaf01c000, 0xb17fc000, 4096)
08-30 12:30:53.063   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.063   316  7943 V AudioCache: memcpy(0xaf01d000, 0xb17fc000, 4096)
08-30 12:30:53.064   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.064   316  7943 V AudioCache: memcpy(0xaf01e000, 0xb17fc000, 4096)
08-30 12:30:53.065   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.065   316  7943 V AudioCache: memcpy(0xaf01f000, 0xb17fc000, 4096)
08-30 12:30:53.066   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.066   316  7943 V AudioCache: memcpy(0xaf020000, 0xb17fc000, 4096)
08-30 12:30:53.067   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.067   316  7943 V AudioCache: memcpy(0xaf021000, 0xb17fc000, 4096)
08-30 12:30:53.069   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.069   316  7943 V AudioCache: memcpy(0xaf022000, 0xb17fc000, 4096)
08-30 12:30:53.070   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.070   316  7943 V AudioCache: memcpy(0xaf023000, 0xb17fc000, 4096)
08-30 12:30:53.071   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.072   316  7943 V AudioCache: memcpy(0xaf024000, 0xb17fc000, 4096)
08-30 12:30:53.073   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.073   316  7943 V AudioCache: memcpy(0xaf025000, 0xb17fc000, 4096)
08-30 12:30:53.073   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.073   316  7943 V AudioCache: memcpy(0xaf026000, 0xb17fc000, 4096)
08-30 12:30:53.074   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.074   316  7943 V AudioCache: memcpy(0xaf027000, 0xb17fc000, 4096)
08-30 12:30:53.075   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.075   316  7943 V AudioCache: memcpy(0xaf028000, 0xb17fc000, 4096)
08-30 12:30:53.075   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.075   316  7943 V AudioCache: memcpy(0xaf029000, 0xb17fc000, 4096)
08-30 12:30:53.076   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.076   316  7943 V AudioCache: memcpy(0xaf02a000, 0xb17fc000, 4096)
08-30 12:30:53.077   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.077   316  7943 V AudioCache: memcpy(0xaf02b000, 0xb17fc000, 4096)
08-30 12:30:53.077   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.077   316  7943 V AudioCache: memcpy(0xaf02c000, 0xb17fc000, 4096)
,08-30 12:30:53.078   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.078   316  7943 V AudioCache: memcpy(0xaf02d000, 0xb17fc000, 4096)
08-30 12:30:53.078   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.078   316  7943 V AudioCache: memcpy(0xaf02e000, 0xb17fc000, 4096)
08-30 12:30:53.079   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.079   316  7943 V AudioCache: memcpy(0xaf02f000, 0xb17fc000, 4096)
08-30 12:30:53.080   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.080   316  7943 V AudioCache: memcpy(0xaf030000, 0xb17fc000, 4096)
08-30 12:30:53.080   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.080   316  7943 V AudioCache: memcpy(0xaf031000, 0xb17fc000, 4096)
08-30 12:30:53.081   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.081   316  7943 V AudioCache: memcpy(0xaf032000, 0xb17fc000, 4096)
08-30 12:30:53.082   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.082   316  7943 V AudioCache: memcpy(0xaf033000, 0xb17fc000, 4096)
08-30 12:30:53.083   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.083   316  7943 V AudioCache: memcpy(0xaf034000, 0xb17fc000, 4096)
08-30 12:30:53.083   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.083   316  7943 V AudioCache: memcpy(0xaf035000, 0xb17fc000, 4096)
08-30 12:30:53.084   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.084   316  7943 V AudioCache: memcpy(0xaf036000, 0xb17fc000, 4096)
08-30 12:30:53.084   316  7943 V AudioCache: write(0xb17fc000, 4096)
08-30 12:30:53.084   316  7943 V AudioCache: memcpy(0xaf037000, 0xb17fc000, 4096)
08-30 12:30:53.085   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 12:30:53.085   316  7943 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 12:30:53.085   316  7943 V AwesomePlayer: postAudioEOS() 
08-30 12:30:53.085   316  7943 V AudioCache: write(0xb17fc000, 280)
08-30 12:30:53.085   316  7943 V AudioCache: memcpy(0xaf038000, 0xb17fc000, 280)
08-30 12:30:53.087   316  7940 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 12:30:53.087   316  7940 V AwesomePlayer: onStreamDone
08-30 12:30:53.087   316  7940 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 12:30:53.087   316  7940 V AudioCache: notify(0xb54749c0, 2, 0, 0)
08-30 12:30:53.087   316  7940 V AudioCache: playback complete
08-30 12:30:53.087   316  7940 V AwesomePlayer: pause_l() 
08-30 12:30:53.087   316  7940 V AudioCache: notify(0xb54749c0, 7, 0, 0)
08-30 12:30:53.087   316  7940 V AudioCache: ignored
08-30 12:30:53.087   316  7940 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:53.087   316   316 V AudioCache: wait - success
08-30 12:30:53.087   316   316 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 12:30:53.087   316  7940 D AudioPlayer: Pause Playback at 1068125
08-30 12:30:53.088   316   316 V AwesomePlayer: reset_l() 
08-30 12:30:53.088   316   316 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-30 12:30:53.088   316   316 V AudioCache: ignored
08-30 12:30:53.088   316   316 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:53.088   316   316 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 12:30:53.088   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 12:30:53.088   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 12:30:53.088   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 12:30:53.088   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 12:30:53.088  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:30:53.088  1028  1971 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@9cc0fd1 mBinding = false
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 1
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-30 12:30:53.089   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57fd420 on port 1
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57fd880 on port 1
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 12:30:53.090   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 12:30:53.090   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 12:30:53.090   316  7942 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 12:30:53.090   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 12:30:53.090   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 12:30:53.090   316   316 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 12:30:53.092   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 12:30:53.092   316   316 D AudioPlayer: AudioPlayer releasing audio source
08-30 12:30:53.092   316   316 D AudioPlayer: AudioPlayer done releasing audio source
08-30 12:30:53.092   316   316 V AwesomePlayer: reset_l() 
08-30 12:30:53.092   316   316 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:53.092   316   316 V AwesomePlayer: ~AwesomePlayer call
08-30 12:30:53.092   316   316 V AwesomePlayer: reset_l() 
08-30 12:30:53.092   316   316 V AwesomePlayer: cancelPlayerEvents
08-30 12:30:53.093  7918  7939 V SoundPool: close(31)
08-30 12:30:53.093  7918  7939 V SoundPool: pointer = 0xa0032000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 12:30:53.104  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:30:53.104  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:30:53.104  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:30:53.104  1028  1110 D BluetoothManagerService: Message: 2
08-30 12:30:53.105  1028  1110 D BluetoothManagerService: Sending off request.
08-30 12:30:53.106  6981  7695 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 12:30:53.107  6981  7561 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 12:30:53.107  6981  7561 D BluetoothAdapterProperties: Setting state to 13
08-30 12:30:53.107  6981  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:30:53.108  6981  7561 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:30:53.108  6981  7561 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 12:30:53.108  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:30:53.108  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 12:30:53.108  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 12:30:53.109  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.111  6981  6981 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.111  6981  6981 D BluetoothMapService: STATE_TURNING_OFF
08-30 12:30:53.111  6981  6981 V BluetoothMapService: Handler(): got msg=4
08-30 12:30:53.112  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:30:53.116  6981  6981 D BluetoothMapService: MAP Service closeService in
08-30 12:30:53.116  6981  6981 D BluetoothMapMasInstance: MAP Service shutdown
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 12:30:53.118  6981  7696 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 12:30:53.119  6981  6981 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:30:53.120  6981  6981 V BluetoothMapService: MAP Service closeService out
08-30 12:30:53.125  6981  7565 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:30:53.125  6981  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 12:30:53.126  6981  6981 V BtOppService: Receiver DISABLED_ACTION 
08-30 12:30:53.126  6981  7697 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:53.126  6981  6981 I BtOppRfcommListener: stopping Accept Thread
08-30 12:30:53.127  6981  6981 V BtOppRfcommListener: close mBtServerSocket
08-30 12:30:53.127  6981  6981 V BtOppRfcommListener: waiting for thread to terminate
08-30 12:30:53.127  6981  7708 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:53.127  6981  7708 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:30:53.128  6981  7709 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:53.128  6981  7561 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:30:53.128  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 12:30:53.129  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:53.129  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:53.129  6981  7711 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:53.129  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 12:30:53.130  6981  7619 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-30 12:30:53.133  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 12:30:53.133  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 12:30:53.133  6981  7619 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:30:53.134  6981  6981 V BtOppRfcommListener: done waiting for thread to terminate
08-30 12:30:53.135  6981  6981 V BtOppService: onDestroy
08-30 12:30:53.137  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:53.137  6981  6981 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 12:30:53.143  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:30:53.145  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:53.145  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:53.145  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:53.146  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:53.149  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:53.149  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:53.150  6981  6981 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:30:53.150  6981  6981 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.150  6981  6981 V BluetoothPbapReceiver: ***********state = 13
08-30 12:30:53.150  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 12:30:53.151  6629  6629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:53.151  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:53.152  6981  6981 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 12:30:53.153  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 12:30:53.153  6854  6854 D DockEventReceiver: finishStartingService: stopping service
08-30 12:30:53.153  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:53.154  6981  6981 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.154  6981  6981 V BluetoothPbapService: state: 13
08-30 12:30:53.154  6981  6981 V BluetoothPbapService: Pbap Service closeService in
08-30 12:30:53.155  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:53.157  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:53.157  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:53.158  6981  6981 V BluetoothPbapService: successfully stopped pbap service
08-30 12:30:53.158  6981  6981 V BluetoothPbapService: Pbap Service closeService out
08-30 12:30:53.158  6981  6981 V BluetoothPbapService: Pbap Service onDestroy
08-30 12:30:53.158  6981  6981 V BluetoothPbapService: Pbap Service closeService in
08-30 12:30:53.158  6981  6981 V BluetoothPbapService: Pbap Service closeService out
08-30 12:30:53.159  6981  6981 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 12:30:53.159  6854  6854 D BluetoothPbap: Proxy object disconnected
08-30 12:30:53.159  6854  6854 D PbapServerProfile: Bluetooth service disconnected
08-30 12:30:53.160  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7950
08-30 12:30:53.161  7918  7918 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 12:30:53.161  7662  7721 I UEI.SmartControl: ------ IControl API: 11
08-30 12:30:53.162  7662  7721 I UEI.SmartControl: Registering callback...
08-30 12:30:53.162  7662  7678 I UEI.SmartControl: ------ IControl API: 19
08-30 12:30:53.163  7662  7678 I UEI.SmartControl: Registering Services Ready callback...
08-30 12:30:53.163  7662  7678 I UEI.SmartControl: Notify client services are ready...
08-30 12:30:53.164  7918  7933 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 12:30:53.164  7918  7937 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 12:30:53.164  7918  7937 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 12:30:53.165  7918  7918 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 12:30:53.165  7918  7918 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 12:30:53.165  7662  7720 I UEI.SmartControl: ------ IControl API: 8
08-30 12:30:53.170  7918  7918 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 12:30:53.170  7918  7918 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 12:30:53.170  7918  7918 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-30 12:30:53.172  7918  7918 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 12:30:53.175  7918  7918 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 12:30:53.176  7918  7918 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 12:30:53.177  7918  7918 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 12:30:53.179  7918  7918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 12:30:53.180  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 12:30:53.181  7918  7918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 12:30:53.181  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 12:30:53.181  6854  6854 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 12:30:53.182  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 12:30:53.184  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-30 12:30:53.185  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 12:30:53.186  7918  7918 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472553053185]
08-30 12:30:53.186  6854  6854 D BluetoothPermissionRequest: onReceive
08-30 12:30:53.186  6854  6854 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 12:30:53.189  7918  7918 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 12:30:53.193  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:30:53.195  1028  1864 I ActivityManager: Killing 7099:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 12:30:53.209  7918  7952 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 12:30:53.221  1028  1396 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-30 12:30:53.228  1028  1863 W libprocessgroup: failed to open /acct/uid_10046/pid_7099/cgroup.procs: No such file or directory
08-30 12:30:53.229  6981  6981 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 12:30:53.229  6981  6981 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 12:30:53.231  6981  6981 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-30 12:30:53.234  7918  7918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 12:30:53.235  7918  7918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:30:53.235  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 12:30:53.236  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 12:30:53.236  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 12:30:53.236  6981  6981 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.236  6981  6981 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 12:30:53.236  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 12:30:53.237  6981  6981 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:30:53.237  6981  6981 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.238  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 12:30:53.238  6981  6981 V BluetoothFtpService: Ftp Service closeService
08-30 12:30:53.238  6981  6981 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 12:30:53.239  6981  6981 V BluetoothFtpService: successfully stopped ftp service
08-30 12:30:53.240  6981  6981 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:30:53.240  6981  6981 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:30:53.240  6981  6981 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:30:53.240  6981  6981 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:53.240  6981  6981 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 12:30:53.240  6981  6981 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 12:30:53.241  6981  6981 V BluetoothFtpService: Ftp Service onDestroy
08-30 12:30:53.242  6981  6981 V BluetoothFtpService: Ftp Service closeService
08-30 12:30:53.245  6981  6981 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:53.246  6981  6981 V BluetoothSapService: state: 13
08-30 12:30:53.246  6981  6981 V BluetoothSapService: Stopping SAP server process
08-30 12:30:53.247  6981  6981 V BluetoothSapService: Sap Service closeSapService in
08-30 12:30:53.247  6981  6981 V BluetoothSapService: Close listen Socket : 
,08-30 12:30:53.247  6981  6981 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:30:53.247  6981  6981 V BluetoothSapService: Close sapd  Socket : 
,08-30 12:30:53.249  6981  6981 V BluetoothSapService: Sap Service closeSapService out
,08-30 12:30:53.249  6981  6981 V BluetoothSapService: Sap Service onDestroy
,08-30 12:30:53.249  6981  6981 V BluetoothSapService: Sap Service closeSapService in
08-30 12:30:53.249  6981  6981 V BluetoothSapService: Close listen Socket : 
08-30 12:30:53.249  6981  6981 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:30:53.249  6981  6981 V BluetoothSapService: Close sapd  Socket : ,
08-30 12:30:53.255  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 12:30:53.258  6981  6981 V BluetoothSapService: Sap Service closeSapService out
08-30 12:30:54.121  6981  7565 D bt_hci_bdroid: cleanup
,08-30 12:30:54.136  6981  7621 I bt_lpm  : LPM is already off!!!
,08-30 12:30:54.137  6981  7679 I bt_userial_mct: exiting userial_read_thread
,08-30 12:30:54.137  6981  7679 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 12:30:54.138  6981  7619 W bt-btif : ag scb idx 1 not allocated
08-30 12:30:54.138  6981  7619 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 12:30:54.138  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:54.138  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:54.138  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 12:30:54.138  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:54.138  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:54.138  6981  7619 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:30:54.139  6981  7619 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:30:54.139  6981  7619 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:30:54.140  6981  7565 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 12:30:54.140  6981  7621 I bt_vendor: hw_epilog_process
08-30 12:30:54.140  6981  7565 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 12:30:54.140  6981  7565 D bt_userial_mct: userial_close
08-30 12:30:54.141  6981  7565 E bt_userial_mct: pthread_join() FAILED result:3
08-30 12:30:54.141  6981  7565 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 12:30:54.177  6981  7565 D bt_hci_bdroid: set_power 0
08-30 12:30:54.177  6981  7565 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 12:30:54.177  6981  7565 I bt_vendor: bluetooth satus is on
08-30 12:30:54.177  6981  7565 I bt_vendor: bt-vendor : resetting BT status
08-30 12:30:54.177  6981  7565 I bt_vendor: Starting hciattach daemon
08-30 12:30:54.177  6981  7565 I bt_vendor: try to set false
,08-30 12:30:54.187  6981  7565 I bt_vendor: Starting hciattach daemon
08-30 12:30:54.187  6981  7565 I bt_vendor: try to set false
08-30 12:30:54.188  6981  7565 I bt_vendor: cleanup
08-30 12:30:54.189  6981  7619 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 12:30:54.189  6981  7565 I GKI_LINUX: GKI_exit_task 0 done
08-30 12:30:54.189  6981  7565 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 12:30:54.190  6981  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 12:30:54.197  6981  6981 D HeadsetService: Received stop request...Stopping profile...
,08-30 12:30:54.200  6981  6981 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:30:54.201  6981  7594 D HeadsetStateMachine: Exit Disconnected: -1
08-30 12:30:54.202  6981  6981 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:54.202  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.205  1028  1028 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:54.205  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 12:30:54.206  1829  1829 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:54.208  6981  6981 D A2dpService: Received stop request...Stopping profile...
08-30 12:30:54.208  6981  7608 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:30:54.209  6981  7561 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 12:30:54.214  6981  6981 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 12:30:54.215  6981  6981 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 12:30:54.215  6981  6981 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:54.215  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.217  1829  1829 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:54.220  1028  1028 D BluetoothA2dp: Proxy object disconnected
08-30 12:30:54.220  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 12:30:54.222  1829  1829 D BluetoothHeadset: Proxy object disconnected
,08-30 12:30:54.225  6981  6981 D HidService: Received stop request...Stopping profile...
08-30 12:30:54.225  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.228  6981  6981 D HealthService: Received stop request...Stopping profile...
08-30 12:30:54.228  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.230  6981  6981 D PanService: Received stop request...Stopping profile...
08-30 12:30:54.230  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.232  6981  6981 D HeadsetStateMachine: Unbinding service...
08-30 12:30:54.233  6981  6981 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:30:54.233  6981  6981 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:30:54.233  6981  6981 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:30:54.233  6981  6981 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:30:54.233  6981  6981 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:30:54.233  6981  6981 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:54.233  6981  6981 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:30:54.233  6981  6981 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:30:54.234  6981  6981 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:30:54.234  6981  6981 D BtGatt.GattService: stop()
08-30 12:30:54.234  6981  6981 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 12:30:54.238  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.240  6981  6981 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:30:54.240  6981  6981 D BluetoothMapService: stop()
08-30 12:30:54.241  6981  6981 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 12:30:54.241  6981  6981 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 12:30:54.241  6981  6981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36968597
08-30 12:30:54.242  6981  6981 I BluetoothA2dpServiceJni: cleanupNative
08-30 12:30:54.243  6981  7609 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 12:30:54.243  6981  6981 I GKI_LINUX: GKI_exit_task 2 done
08-30 12:30:54.243  6981  6981 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 12:30:54.243  6981  6981 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:30:54.243  6981  6981 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:30:54.244  6981  6981 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:30:54.244  6981  6981 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:30:54.244  6981  6981 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:30:54.244  6981  6981 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:30:54.244  6981  6981 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:30:54.247  6981  6981 V BluetoothMapService: Handler(): got msg=4
08-30 12:30:54.247  6981  6981 D BluetoothMapService: MAP Service closeService in
08-30 12:30:54.247  6981  6981 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:30:54.247  6981  6981 V BluetoothMapService: MAP Service closeService out
,08-30 12:30:54.251  6981  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 12:30:54.251  6981  7561 D BluetoothAdapterProperties: Setting state to 10
08-30 12:30:54.251  6981  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 12:30:54.252  6981  6981 D BluetoothMapService: cleanup()
08-30 12:30:54.253  6981  6981 D BluetoothMapService: MAP Service closeService in
08-30 12:30:54.253  6981  6981 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:30:54.253  6981  6981 V BluetoothMapService: MAP Service closeService out
08-30 12:30:54.253  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:30:54.253  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 12:30:54.253  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 12:30:54.254  6981  7561 I BluetoothAdapterState: Entering OffState
08-30 12:30:54.254  1829  2759 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:54.255  6854  6870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:54.256  6854  6870 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:30:54.256  6854  6870 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:30:54.257  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:54.257  1829  1845 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:54.257  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:30:54.258  6854  6870 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:30:54.258  6854  6870 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:30:54.259  1829  1844 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:54.259  6854  6870 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 12:30:54.263  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
,08-30 12:30:54.263  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 12:30:54.267  1028  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 12:30:54.267  1028  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 12:30:54.267  1028  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@9cc0fd1 mBinding = false
08-30 12:30:54.270  1028  1110 D BluetoothManagerService: Sending unbind request.
08-30 12:30:54.274  6981  7565 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 12:30:54.277  6981  6981 I GKI_LINUX: GKI_exit_task 1 done
08-30 12:30:54.277  6981  6981 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 12:30:54.278  6981  6981 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 12:30:54.278  6981  6981 I art     : --- WEIRD: removing null entry 248
08-30 12:30:54.278  6981  6981 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 12:30:54.278  6981  6981 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 12:30:54.279  6981  6981 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 12:30:54.280  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 12:30:54.282  6981  6981 I art     : System.exit called, status: 0
08-30 12:30:54.282  6981  6981 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 12:30:54.300   316  2156 V AudioFlinger: 6981 died, releasing its sessions
08-30 12:30:54.300   316  2156 V AudioFlinger:  pid 1829 @ 0
08-30 12:30:54.300   316  2156 V AudioFlinger:  pid 3467 @ 1
08-30 12:30:54.300   316  2156 V AudioFlinger:  pid 3467 @ 2
,08-30 12:30:54.304  1919  1919 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-30 12:30:54.304  1919  2071 D LGBluetoothAPIService: Message: 101
08-30 12:30:54.304  1919  2071 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 12:30:54.305  1919  2071 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 12:30:54.305  1919  2071 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 12:30:54.306  6854  6854 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 12:30:54.308  1028  2009 I ActivityManager: Process com.android.bluetooth (pid 6981) has died
08-30 12:30:54.308  1028  2009 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-30 12:30:54.308  1028  2009 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-30 12:30:54.314  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:54.321  1919  2071 D LGBluetoothAPIService: Message: 2
,08-30 12:30:54.321  1919  2071 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 12:30:54.323  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 12:30:54.323  6854  6854 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 12:30:54.325  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:54.326  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 12:30:54.333  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.337  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.339  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:30:54.343  1582  1582 D BluetoothAdapter: 446821486: getState() :  mService = null. Returning STATE_OFF
,08-30 12:30:54.343  1582  1582 D BluetoothAdapter: 446821486: getState() :  mService = null. Returning STATE_OFF
08-30 12:30:54.386  1028  1864 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7982 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 12:30:54.388  6854  6854 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:30:54.439  7982  7982 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 12:30:54.440  7982  7982 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:30:54.440  7982  7982 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-30 12:30:54.441  7982  7982 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 12:30:54.461  7982  7982 D BluetoothAdapterApp: Loading JNI Library
,08-30 12:30:54.495  7982  7982 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@134c019f Instance Count = 1
,08-30 12:30:54.502  7982  7982 D BluetoothAdapterApp: onCreate
08-30 12:30:54.525  7982  7982 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 12:30:54.526  7982  7982 D ProfileConfigQcom: Adding HeadsetService
08-30 12:30:54.526  7982  7982 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 12:30:54.526  7982  7982 D ProfileConfigQcom: Adding A2dpService
08-30 12:30:54.526  7982  7982 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 12:30:54.526  7982  7982 D ProfileConfigQcom: Adding HidService
08-30 12:30:54.527  7982  7982 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 12:30:54.527  7982  7982 D ProfileConfigQcom: Adding HealthService
08-30 12:30:54.527  7982  7982 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 12:30:54.529  7982  7982 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 12:30:54.529  7982  7982 D ProfileConfigQcom: Adding PanService
08-30 12:30:54.529  7982  7982 D ProfileConfigQcom: [BTUI] GattService is supported
,08-30 12:30:54.529  7982  7982 D ProfileConfigQcom: Adding GattService
,08-30 12:30:54.529  7982  7982 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 12:30:54.530  7982  7982 D ProfileConfigQcom: Adding BluetoothMapService
08-30 12:30:54.530  7982  7982 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 12:30:54.531  7982  7982 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:30:54.532  7982  7982 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:54.532  7982  7982 V BluetoothPbapReceiver: ***********state = 10
08-30 12:30:54.534  7982  7982 V LGMDMManagerInternal: Create singleton instance
08-30 12:30:54.596  7982  7982 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 12:30:54.597  7982  7982 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 12:30:54.600  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:54.601  1919  1919 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 12:30:54.601  1919  2071 D LGBluetoothAPIService: Message: 100
08-30 12:30:54.601  1919  2071 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-30 12:30:54.604  6854  6854 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 12:30:54.620  6854  6854 D BluetoothPermissionRequest: onReceive
,08-30 12:30:54.622  6854  6854 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 12:30:54.622  6854  6854 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 12:30:54.626  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:30:54.636  7982  7982 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 12:30:54.644  7982  7982 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:54.652  7982  7982 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 12:30:54.653  7982  7982 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-30 12:30:54.653  7982  7982 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:30:54.658  7982  7982 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:54.658  7982  7982 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 12:30:54.679  7629  7629 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 12:30:54.839  7662  7716 D UEI.SmartControl: Internal timer expired: 1
,08-30 12:30:54.840  7662  7716 D UEI.SmartControl: unbind internal service
,08-30 12:30:55.120  7662  7713 D serial_port: close(fd = 25)
,08-30 12:30:55.131  7662  7713 I UEI.SmartControl: Serial port is closed.
,08-30 12:30:58.105  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:58.105  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:58.119  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:58.119  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18666d76 removed from the list
08-30 12:30:58.119  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:58.119  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:58.119  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:58.122  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:58.123  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2463f7e4 added. We now have 4 listener(s)
08-30 12:30:58.123  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:30:58.127  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:58.127  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2463f7e4 removed from the list
08-30 12:30:58.127  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:58.127  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:58.127  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:58.129  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:58.129  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1270344d added. We now have 4 listener(s)
08-30 12:30:58.130  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:30:58.141  1028  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:30:58.141  1028  1938 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-30 12:30:58.141  1028  1110 D BluetoothManagerService: Message: 2
08-30 12:31:00.003  1028  1356 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1056668800, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,08-30 12:31:00.028  7918  7918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 12:31:00.028  7918  7918 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7950
,08-30 12:31:00.053  2558  2558 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 12:31:00.069  1582  1582 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 12:31:00.069  1582  1582 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 12:31:00.069  1582  1582 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 12:31:00.069  1582  1582 I [SystemUI]Clock: called onTimeUpdated()
,08-30 12:31:00.077  1582  1582 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 12:31:00.077  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:31:00.078  1582  1582 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:31:00.078  1582  1582 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 12:31:00.135  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1056668800 [*alarm*], flags=0x0
,08-30 12:31:03.149  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:03.158  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:03.158  1028  1043 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 12:31:03.174  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:31:03.175  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:31:03.175  1028  1028 D Ulp_jni : JNI:system_update. Event-4
,08-30 12:31:03.178  1028  1110 D BluetoothManagerService: Message: 1
08-30 12:31:03.178  1028  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 12:31:03.208  1028  1110 D BluetoothManagerService: Message: 20
08-30 12:31:03.208  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a0f7510:true
,08-30 12:31:03.212  7982  7982 D BluetoothAdapterState: make
08-30 12:31:03.217  7982  7982 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 12:31:03.217  7982  7982 I bluedroid-qcom: init
08-30 12:31:03.218  7982  8013 I BluetoothAdapterState: Entering OffState
08-30 12:31:03.219  7982  7982 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 12:31:03.219  7982  7982 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 12:31:03.219  7982  7982 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:31:03.219  7982  7982 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:31:03.219  7982  7982 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 12:31:03.221  7982  7982 I bluedroid-qcom: get_profile_interface socket
08-30 12:31:03.221  7982  7982 I bluedroid-qcom: get_profile_interface map_client
,08-30 12:31:03.226  7982  8017 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 12:31:03.229  7982  8017 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 12:31:03.219  8016  8016 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:03.219  8016  8016 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:03.239  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:31:03.239  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 12:31:03.245  8016  8016 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 12:31:03.245  8016  8016 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 12:31:03.245  8016  8016 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 12:31:03.247  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 12:31:03.247  1028  1110 D BluetoothManagerService: Message: 40
08-30 12:31:03.247  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 12:31:03.248  7982  7997 I bluedroid-qcom: config_hci_snoop_log
08-30 12:31:03.249  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 12:31:03.249  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 12:31:03.250  8016  8016 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 12:31:03.252  7982  8017 D BluetoothAdapterProperties: Name is: G3
,08-30 12:31:03.256  8016  8016 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 12:31:03.256  8016  8016 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 12:31:03.262  7982  8013 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 12:31:03.263  7982  8013 D BluetoothAdapterProperties: Setting state to 11
08-30 12:31:03.263  7982  8013 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 12:31:03.264  7982  8013 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 12:31:03.268  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:31:03.268  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 12:31:03.268  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 12:31:03.272  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:03.273  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:31:03.276  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:03.277  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:03.281  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 12:31:03.290  7982  7982 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:31:03.290  7982  7982 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:03.290  7982  7982 V BluetoothPbapReceiver: ***********state = 11
,08-30 12:31:03.309  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:31:03.318  7982  8013 D BluetoothBondStateMachine: make
08-30 12:31:03.321  7982  8013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.321  7982  8013 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 12:31:03.321  7982  8013 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.321  7982  8013 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 12:31:03.322  7982  8013 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 12:31:03.323  7982  8027 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 12:31:03.328  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:31:03.328  6854  6854 D BluetoothPermissionRequest: onReceive
08-30 12:31:03.335  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:31:03.337  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:31:03.340  7982  7982 D HeadsetService: Received start request. Starting profile...
08-30 12:31:03.340  7982  7982 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 12:31:03.340  7982  7982 D LGBluetoothHfpAdapter: Version 1.6
08-30 12:31:03.343  7982  7982 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:31:03.344  7982  7982 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:31:03.345  7982  7982 D HeadsetStateMachine: make
08-30 12:31:03.347  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:31:03.356  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:31:03.360  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:31:03.364  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:31:03.369  7982  8013 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:31:03.381  7982  8013 V LGMDMManager: Create singleton instance
,08-30 12:31:03.382  7982  8013 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 12:31:03.384  7982  7982 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:31:03.384  7982  7982 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:31:03.388  7982  7982 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:31:03.389  7982  7982 I bluedroid-qcom: get_profile_interface handsfree
08-30 12:31:03.391  7982  7982 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 12:31:03.391   316   316 V AudioPolicyService: registerClient() client 0xb57c5d80, uid 1002
,08-30 12:31:03.391   316  2156 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:31:03.392   316  2156 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:31:03.392   316  2156 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:31:03.392  7982  7982 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:31:03.392   316  1380 V AudioFlinger: registerClient() client 0xb5581da8, pid 7982
08-30 12:31:03.393   316  1374 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:31:03.393   316  1374 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:31:03.393  1582  1597 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:31:03.393  1582  1597 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:31:03.393  1829  2442 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 12:31:03.393  1829  2442 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-30 12:31:03.393  7982  7998 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 12:31:03.393  1028  1900 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:31:03.393  1028  1900 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:31:03.393  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:31:03.393  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:31:03.394  7982  7998 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 12:31:03.394   316  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:31:03.394   316  1375 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:31:03.394  1028  1043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:31:03.394  7982  7982 V ToneGenerator: Create Track: 0xb4928080
08-30 12:31:03.394  1028  1043 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:31:03.394  7982  7982 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 12:31:03.394  7982  7982 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 12:31:03.394  1582  2043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-30 12:31:03.394  1582  2043 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:31:03.394  1829  2759 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:31:03.395   316  1379 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:31:03.395  1829  2759 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:31:03.395   316  1379 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:31:03.395   316  1379 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:31:03.395   316  1379 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:31:03.395  3467  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:31:03.395  3467  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:31:03.395  7982  7998 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:31:03.395  7982  7998 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
,08-30 12:31:03.395   316   316 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:31:03.395   316  2156 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:31:03.395   316  2156 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 12:31:03.395   316  2156 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:31:03.395   316  2156 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:31:03.396  7982  7982 V AudioSystem: getLatency() output 2, latency 50
08-30 12:31:03.396  7982  7982 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 12:31:03.397  7982  7982 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 12:31:03.397   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:31:03.397   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:31:03.397   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:31:03.397   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:31:03.397   316  2159 V AudioFlinger: createTrack() lSessionId: 21
08-30 12:31:03.401  7982  7982 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 12:31:03.401   316  2159 V AudioFlinger: acquiring 21 from 7982, for 7982
08-30 12:31:03.401   316  2159 V AudioFlinger:  added new entry for 21
08-30 12:31:03.402  7982  7982 V ToneGenerator: ToneGenerator INIT OK, time: 186235
08-30 12:31:03.402  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.404  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.407  7982  8030 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 12:31:03.407  7982  8030 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:31:03.407  7982  8030 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:31:03.408  7982  8030 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 12:31:03.408   316  1379 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7982
08-30 12:31:03.409   316  1379 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 12:31:03.409   316  1379 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 12:31:03.409   316  1379 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 12:31:03.409   316  1379 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 12:31:03.409   316  1379 V voice   : voice_set_parameters: exit with code(0)
08-30 12:31:03.409   316  1379 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 12:31:03.409   316  1379 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 12:31:03.409   316  1379 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 12:31:03.409   316  1379 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 12:31:03.409   316  1379 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 12:31:03.409   316  1379 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 12:31:03.409  7982  8030 V ToneGenerator: ToneGenerator destructor
08-30 12:31:03.409  7982  8030 V ToneGenerator: stopTone
08-30 12:31:03.409  7982  8030 V ToneGenerator: Delete Track: 0xb4928080
,08-30 12:31:03.410  7982  8030 V AudioTrack: ~AudioTrack, releasing session id from 7982 on behalf of 7982
08-30 12:31:03.410   316  1380 V AudioFlinger: releasing 21 from 7982 for 7982
08-30 12:31:03.410   316  1380 V AudioFlinger:  decremented refcount to 0
08-30 12:31:03.410   316  1380 V AudioFlinger: purging stale effects
08-30 12:31:03.410   316  1380 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 12:31:03.410   316  1380 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 12:31:03.410   316  1380 V AudioFlinger: PlaybackThread::Track destructor
08-30 12:31:03.410   316  1380 V AudioFlinger: removeClient_l() pid 7982, calling pid 316
08-30 12:31:03.410   316  1266 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:31:03.410   316  1266 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 12:31:03.410   316  1266 V AudioPolicyManager: releaseOutput() 2
08-30 12:31:03.411   316  1266 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:31:03.412  7982  7982 D A2dpService: Received start request. Starting profile...
08-30 12:31:03.413  7982  7982 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:31:03.414  7982  7982 V Avrcp   : make
08-30 12:31:03.414  7982  7982 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 12:31:03.415  7982  7982 I bluedroid-qcom: get_profile_interface avrcp
08-30 12:31:03.435  7982  7982 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 12:31:03.439  7982  7982 E AudioManager: No RCC entry present to update
08-30 12:31:03.439  7982  7982 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 12:31:03.443  7982  7982 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 12:31:03.445  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 12:31:03.445  7982  7982 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 12:31:03.449  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 12:31:03.625  1028  1864 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:31:03.625  1028  1864 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:31:03.817  1028  2009 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 12:31:03.831  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 12:31:03.840  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 12:31:03.841  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 12:31:03.841  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:31:03.842  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:31:03.843  7982  7982 I BluetoothA2dpServiceJni: classInitNative
08-30 12:31:03.843  7982  7982 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:31:03.843  7982  7982 D A2dpStateMachine: make
08-30 12:31:03.845  7982  7982 I bluedroid-qcom: get_profile_interface a2dp
08-30 12:31:03.846  7982  8048 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 12:31:03.851  7982  7982 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:31:03.851  7982  7982 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 12:31:03.852  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.852  7982  8047 D A2dpStateMachine: Enter Disconnected: -2
08-30 12:31:03.853  7982  7982 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 12:31:03.856  7982  7982 D HidService: Received start request. Starting profile...
08-30 12:31:03.856  7982  7982 I bluedroid-qcom: get_profile_interface hidhost
08-30 12:31:03.856  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.857  7982  7982 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:31:03.859  7982  7982 D HealthService: Received start request. Starting profile...
,08-30 12:31:03.862  7982  7982 I bluedroid-qcom: get_profile_interface health
08-30 12:31:03.862  7982  7982 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:31:03.862  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:03.864  7982  7982 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 12:31:03.866  7982  7982 D PanService: Received start request. Starting profile...
08-30 12:31:03.867  7982  7982 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:31:03.867  7982  7982 I bluedroid-qcom: get_profile_interface pan
,08-30 12:31:04.025  1028  1578 I art     : Explicit concurrent mark sweep GC freed 27856(1373KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.088ms total 149.108ms
,08-30 12:31:04.026  7982  7982 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-30 12:31:04.027  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.028  7982  7982 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 12:31:04.033  7982  7982 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:31:04.034  7982  7982 D BtGatt.GattService: Received start request. Starting profile...
08-30 12:31:04.034  7982  7982 D BtGatt.GattService: start()
08-30 12:31:04.034  7982  7982 I bluedroid-qcom: get_profile_interface gatt
08-30 12:31:04.035  7982  7982 D BtGatt.AdvertiseManager: advertise manager created
08-30 12:31:04.043  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.045  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.045  7982  7982 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-30 12:31:04.047  7982  7982 V BluetoothMapService: BluetoothMapBinder()
08-30 12:31:04.048  7982  7982 D BluetoothMapService: Received start request. Starting profile...
08-30 12:31:04.048  7982  7982 D BluetoothMapService: start()
08-30 12:31:04.051  7982  7982 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 12:31:04.051  7982  7982 D BluetoothMapEmailAppObserver: createReceiver()
08-30 12:31:04.052  7982  7982 D BluetoothMapEmailAppObserver: initObservers()
08-30 12:31:04.052  7982  7982 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 12:31:04.061  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.061  7982  7982 D HeadsetStateMachine: Proxy object connected
08-30 12:31:04.062  7982  7982 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 12:31:04.062  7982  7982 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 12:31:04.065  7982  8030 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:31:04.065  7982  8030 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 12:31:04.065  7982  8030 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 12:31:04.067  7982  7982 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:31:04.069  7982  7982 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.074  7982  7982 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:31:04.079  7982  7982 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:31:04.083  7982  7982 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:31:04.083  7982  7982 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 12:31:04.086  7982  7982 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:31:04.091  7982  7982 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 12:31:04.091  7982  7982 V BluetoothMapService: Handler(): got msg=1
08-30 12:31:04.092  7982  7982 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:31:04.092  7982  7982 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:31:04.092  7982  7982 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:31:04.093  7982  7982 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.093  7982  7982 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 12:31:04.093  7982  8013 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 12:31:04.093  7982  8013 I bluedroid-qcom: enable
08-30 12:31:04.093  7982  8013 I bt_hci_bdroid: init
08-30 12:31:04.095  7982  8055 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 12:31:04.098  7982  8013 I bt_vendor: bt-vendor : init
08-30 12:31:04.098  7982  8013 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 12:31:04.098  7982  8013 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 12:31:04.098  7982  8013 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 12:31:04.098  7982  8013 D bt_userial_mct: userial_init
,08-30 12:31:04.098  7982  8055 I bt-btu  : btu_task pending for preload complete event
08-30 12:31:04.098  7982  8013 D bt_hci_bdroid: set_power 1
08-30 12:31:04.098  7982  8013 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 12:31:04.098  7982  8013 I bt_vendor: Starting hciattach daemon
08-30 12:31:04.098  7982  8013 I bt_vendor: try to set true
08-30 12:31:04.089  8058  8058 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:04.089  8058  8058 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:04.118  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 12:31:04.173  8065  8065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 12:31:04.183  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 12:31:04.203  8068  8068 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 12:31:04.212  8069  8069 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 12:31:04.221  8070  8070 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 12:31:04.230  8071  8071 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 12:31:04.248  8073  8073 I libmdmdetect: ESOC framework not supported
,08-30 12:31:04.251  8073  8073 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 12:31:04.262  8073  8073 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 12:31:04.262  8073  8073 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 12:31:04.262  8073  8073 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 12:31:04.262  8073  8073 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 12:31:04.262  8073  8073 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 12:31:04.262  8073  8073 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-30 12:31:04.262  8073  8073 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 12:31:04.310  8073  8074 E QC-QMI  : qmi_client [8073] 15: failed to locate client data
08-30 12:31:04.311   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 12:31:04.311   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 12:31:04.375  8075  8075 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 12:31:04.389  8076  8076 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 12:31:04.403  7982  8013 I bt_vendor: bluetooth satus is on
,08-30 12:31:04.403  7982  8013 D bt_hci_bdroid: preload
08-30 12:31:04.405  7982  8057 D bt_userial_mct: userial_open(port:0)
08-30 12:31:04.405  7982  8057 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 12:31:04.409  7982  8057 I bt_vendor: Done intiailizing UART
08-30 12:31:04.410  7982  8057 I bt_vendor: Done intiailizing UART
,08-30 12:31:04.410  7982  8057 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 12:31:04.410  7982  8057 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 12:31:04.411  7982  8055 I bt-btu  : btu_task received preload complete event
08-30 12:31:04.411  7982  8078 D bt_userial_mct: Entering userial_read_thread()
08-30 12:31:04.411  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 12:31:04.411  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 12:31:04.413  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:31:04.418  7982  8055 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:31:04.513  7982  8055 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-30 12:31:04.513  7982  8055 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0240061 
,08-30 12:31:04.513  7982  8055 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0240061 
,08-30 12:31:04.573  7982  8017 E bt-btif : Calling BTA_HhEnable
,08-30 12:31:04.573  7982  8017 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-30 12:31:04.573  7982  8017 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 12:31:04.585  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:31:04.587  7982  8017 D BluetoothAdapterProperties: Name is: G3
08-30 12:31:04.589  7982  8017 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:31:04.589  7982  8017 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:31:04.589  7982  8017 D bt_hci_bdroid: postload
08-30 12:31:04.590  7982  8017 D bte_conf: Device ID record 1 : primary
08-30 12:31:04.590  7982  8017 D bte_conf:   vendorId            = 00c4
08-30 12:31:04.590  7982  8017 D bte_conf:   vendorIdSource      = 0001
08-30 12:31:04.590  7982  8017 D bte_conf:   product             = 13a1
08-30 12:31:04.590  7982  8017 D bte_conf:   version             = 1000
08-30 12:31:04.590  7982  8017 D bte_conf:   clientExecutableURL = 
08-30 12:31:04.590  7982  8017 D bte_conf:   serviceDescription  = 
08-30 12:31:04.590  7982  8017 D bte_conf:   documentationURL    = 
08-30 12:31:04.592  7982  8057 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 12:31:04.594  7982  8017 D bte_conf: bte_load_did_conf no section named DID2.
08-30 12:31:04.597  7982  8013 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 12:31:04.598  7982  8013 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:31:04.598  7982  8013 D BluetoothAdapterProperties: State =  11
08-30 12:31:04.598  7982  8013 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 12:31:04.598  7982  8013 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 12:31:04.598  7982  8013 D BluetoothAdapterProperties: Setting state to 12
08-30 12:31:04.598  7982  8013 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:31:04.599  7982  8017 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:31:04.589  8083  8083 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:04.589  8083  8083 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:04.607  1028  1110 D BluetoothManagerService: Message: 60
08-30 12:31:04.607  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 12:31:04.607  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-30 12:31:04.625  1829  1845 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:31:04.628  7982  8013 I BluetoothAdapterState: Entering On State
08-30 12:31:04.632  7982  8013 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 12:31:04.632  7982  8013 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 12:31:04.632  7982  8013 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 12:31:04.638  7982  8013 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-30 12:31:04.641  7982  8017 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:31:04.641  7982  8017 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:04.649  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:31:04.655  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:04.670  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:31:04.677  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:31:04.677  7982  8013 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 12:31:04.678  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 12:31:04.688  1829  1829 D BluetoothHeadset: Proxy object connected
,08-30 12:31:04.695  6854  6870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:04.696  7982  8057 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:31:04.707  6854  6869 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:31:04.707  6854  6869 D BluetoothPan: onBluetoothStateChange call bindService
,08-30 12:31:04.710  7982  8057 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:31:04.710  7982  8078 E bt_mct  : hci lib postload completed
08-30 12:31:04.710  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 12:31:04.711  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 12:31:04.711  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 12:31:04.711  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 12:31:04.711  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 12:31:04.711  7982  8055 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 12:31:04.712  7982  8017 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 12:31:04.723  8088  8088 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 12:31:04.731  6854  6870 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:31:04.732  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:04.733  1028  1028 D BluetoothHeadset: Proxy object connected
08-30 12:31:04.735  1829  2442 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:04.737  7982  8055 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:31:04.737  7982  8055 W bt-smp  : Plain text(LSB ~ MSB) = b9 39 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:31:04.737  7982  8055 W bt-smp  : Encrypted text(LSB ~ MSB) = 5d f3 11 9f 6f 2d 83 02 4b 08 3a 4e a1 a2 4e 6e 
,08-30 12:31:04.739  7982  8055 W bt-btm  : Stopping oneshot timer
08-30 12:31:04.740  1829  1829 D BluetoothHeadset: Proxy object connected
08-30 12:31:04.741  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:31:04.743  1028  1028 D BluetoothA2dp: Proxy object connected
08-30 12:31:04.745  6854  7685 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:31:04.751  6854  6870 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 12:31:04.763  1829  1844 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:31:04.767  7982  8055 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:31:04.767  7982  8055 W bt-smp  : Plain text(LSB ~ MSB) = 43 a0 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:31:04.767  7982  8055 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 cf f8 ce 7f 03 18 36 b8 2c b5 69 b8 94 10 28 
08-30 12:31:04.767  7982  8055 W bt-btm  : Stopping oneshot timer
,08-30 12:31:04.772  6854  6854 D BluetoothHeadset: Proxy object connected
08-30 12:31:04.772  6854  6854 D HeadsetProfile: Bluetooth service connected
08-30 12:31:04.774  1829  1829 D BluetoothHeadset: Proxy object connected
08-30 12:31:04.775  6854  6854 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:31:04.775  6854  6854 D PanProfile: Bluetooth service connected
08-30 12:31:04.776  6854  7685 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:31:04.780  1028  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 12:31:04.780  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 12:31:04.781  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 12:31:04.781  1028  1110 D BluetoothManagerService: Message: 40
,08-30 12:31:04.782  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 12:31:04.782  6854  6854 D BluetoothA2dp: Proxy object connected
08-30 12:31:04.782  6854  6854 D A2dpProfile: Bluetooth service connected
08-30 12:31:04.782  7982  8055 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:31:04.782  7982  8055 W bt-smp  : Plain text(LSB ~ MSB) = 5b 96 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:31:04.782  7982  8055 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 0c 38 1b a9 3c 05 47 40 18 c9 0e 62 84 f0 b6 
08-30 12:31:04.782  7982  8055 W bt-btm  : Stopping oneshot timer
08-30 12:31:04.786  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:31:04.787  1919  1919 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.787  1919  2071 D LGBluetoothAPIService: Message: 1
08-30 12:31:04.787  1919  2071 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 12:31:04.787  1919  2071 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 12:31:04.788  1919  2071 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 12:31:04.789  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:04.791  7982  7982 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.791  7982  7982 D BluetoothMapService: STATE_ON
08-30 12:31:04.791  7982  7982 V BluetoothMapService: Handler(): got msg=1
08-30 12:31:04.792  7982  7982 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 12:31:04.793  7982  8105 D BluetoothMapMasInstance: MAS initSocket()
08-30 12:31:04.794  6854  6854 D BluetoothMap: Proxy object connected
08-30 12:31:04.794  6854  6854 D MapProfile: Bluetooth service connected
08-30 12:31:04.794  6854  6854 D BluetoothMap: getConnectedDevices()
08-30 12:31:04.794  7982  8105 D BluetoothMapMasInstance:   masId = 00
08-30 12:31:04.794  7982  8105 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 12:31:04.794  7982  8105 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 12:31:04.794  7982  8105 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 12:31:04.794  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:04.795  7982  8055 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:31:04.795  7982  8055 W bt-smp  : Plain text(LSB ~ MSB) = e8 27 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:31:04.795  7982  8055 W bt-smp  : Encrypted text(LSB ~ MSB) = 88 ec bd db 36 33 da 17 a6 ee 7c 92 e9 85 87 f4 
08-30 12:31:04.795  7982  8055 W bt-btm  : Stopping oneshot timer
,08-30 12:31:04.799  7982  7997 V BluetoothMapService: getConnectedDevices()
08-30 12:31:04.800  6854  6854 D BluetoothInputDevice: Proxy object connected
08-30 12:31:04.800  6854  6854 D HidProfile: Bluetooth service connected
08-30 12:31:04.804  6854  6854 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 12:31:04.804  7982  8055 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:31:04.804  7982  8055 W bt-smp  : Plain text(LSB ~ MSB) = 5e ea 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:31:04.804  7982  8055 W bt-smp  : Encrypted text(LSB ~ MSB) = 33 56 76 2e 8f ad 55 e7 f7 81 49 32 57 6e e0 a4 
08-30 12:31:04.804  7982  8055 W bt-btm  : Stopping oneshot timer
08-30 12:31:04.805  1028  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:04.805  6854  6854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:31:04.809  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.809  7982  7982 V BluetoothPbapService: Pbap Service onCreate
08-30 12:31:04.809  7982  7982 V BluetoothPbapService: Starting PBAP service
,08-30 12:31:04.811  7982  7982 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 12:31:04.812  7982  7982 V BluetoothPbapService: Pbap Service onBind
08-30 12:31:04.814  7982  7982 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.814  7982  7982 V BluetoothPbapService: state: 12
08-30 12:31:04.814  7982  7982 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 12:31:04.814  7982  8105 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:04.814  7982  7982 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.814  7982  7982 V BluetoothPbapReceiver: ***********state = 12
08-30 12:31:04.816  7982  7982 V BluetoothPbapService: Handler(): got msg=1
08-30 12:31:04.816  7982  8105 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 12:31:04.816  7982  8105 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 12:31:04.816  7982  7982 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 12:31:04.817  7982  8105 D BluetoothMapMasInstance: Accepting socket connection...
08-30 12:31:04.819  7982  8108 V BluetoothPbapService: Pbap Service initSocket
08-30 12:31:04.819  2197  2197 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:31:04.820  2197  2197 D c       : Getting all permits...
08-30 12:31:04.820  2197  2197 D a       : Opening database...
08-30 12:31:04.822  2197  2197 D a       : Opening database auth.proximity.permit_store...
08-30 12:31:04.823  7982  8017 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:31:04.823  7982  8017 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-30 12:31:04.823  2197  2197 D a       : Closing database...
,08-30 12:31:04.825  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:04.826  1028  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:04.826  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:04.827  6854  6854 D DockEventReceiver: finishStartingService: stopping service
08-30 12:31:04.827  7982  8108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:04.828  6854  6854 D BluetoothPbap: Proxy object connected
08-30 12:31:04.828  6854  6854 D PbapServerProfile: Bluetooth service connected
08-30 12:31:04.829  7982  8108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 12:31:04.831  7982  8108 V BluetoothPbapService: Succeed to create listening socket 
08-30 12:31:04.831  7982  8108 V BluetoothPbapService: Accepting socket connection...
08-30 12:31:04.834  6854  6854 D BluetoothPermissionRequest: onReceive
08-30 12:31:04.835  6854  6854 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 12:31:04.837  6854  6854 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 12:31:04.841  7982  7982 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 12:31:04.842  7982  7982 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 12:31:04.848  7982  7982 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 12:31:04.871  7982  7982 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 12:31:04.871  7982  7982 V BtOppService: onCreate
,08-30 12:31:04.875  7982  7982 V BluetoothOppNotification: send message
08-30 12:31:04.878  7982  7982 V BtOppService: Starting RfcommListener
08-30 12:31:04.881  7982  7982 D BluetoothOppPreference: Dumping Names:  
08-30 12:31:04.881  7982  7982 D BluetoothOppPreference: {}
08-30 12:31:04.881  7982  7982 D BluetoothOppPreference: Dumping Channels:  
08-30 12:31:04.881  7982  7982 D BluetoothOppPreference: {}
08-30 12:31:04.883  7982  7982 V BtOppService: onStartCommand
,08-30 12:31:04.885  7982  7982 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.885  7982  7982 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:31:04.885  7982  8116 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:31:04.887  7982  8116 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:31:04.887  7982  7982 V BluetoothOppNotification: new notify threadi!
08-30 12:31:04.888  7982  7982 V BluetoothOppNotification: send delay message
08-30 12:31:04.889  7982  7982 V BtOppService: start RfcommListener
08-30 12:31:04.890  7982  8117 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:31:04.890  7982  8113 V BtOppService: Deleted complete outbound shares, number =  0
08-30 12:31:04.892  7982  7982 V BtOppService: RfcommListener started
08-30 12:31:04.894  7982  8116 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3054b780 on behalf of 
08-30 12:31:04.896  7982  8118 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 12:31:04.897  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:04.897  7982  8117 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10fb51b9 on behalf of 
,08-30 12:31:04.898  7982  8118 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:04.901  7982  8117 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 12:31:04.902  7982  8118 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-30 12:31:04.903  7982  8118 V BtOppRfcommListener: Started RFCOMM listener....
08-30 12:31:04.903  7982  8113 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 12:31:04.903  7982  8118 I BtOppRfcommListener: Accept thread started.
08-30 12:31:04.903  7982  8113 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 12:31:04.903  7982  8118 V BtOppRfcommListener: Accepting connection...
08-30 12:31:04.904  7982  8117 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 12:31:04.904  7982  8116 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 12:31:04.904  7982  8113 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfe59fe on behalf of 
08-30 12:31:04.908  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.908  7982  7982 V BluetoothFtpService: Ftp Service onCreate
08-30 12:31:04.908  7982  7982 I BluetoothFtpService: Ftp Service onCreate
08-30 12:31:04.908  7982  7982 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:31:04.908  7982  8117 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@200dcbac on behalf of 
08-30 12:31:04.908  7982  7982 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:31:04.909  7982  7982 V BluetoothFtpService: Starting Listening on sockets
08-30 12:31:04.909  7982  7982 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:31:04.909  7982  7982 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:31:04.909  7982  7982 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:31:04.909  7982  7982 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.909  7982  7982 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 12:31:04.909  7982  7982 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:31:04.912  7982  7982 V BtOppService: ContentObserver received notification
08-30 12:31:04.912  7982  8117 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:31:04.912  7982  7982 V BtOppService: ContentObserver received notification
08-30 12:31:04.912  7982  7982 V BluetoothFtpService: Handler(): got msg=1
08-30 12:31:04.913  7982  7982 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 12:31:04.913  7982  7982 V BluetoothFtpService: Ftp Service initSocket
08-30 12:31:04.914  7982  8119 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:31:04.914  7982  8117 V BluetoothOppNotification: outbound notification was removed.
08-30 12:31:04.915  7982  8117 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:31:04.915  7982  8119 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:31:04.917  1028  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:04.918  7982  8117 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cf65075 on behalf of 
08-30 12:31:04.918  7982  8119 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e2180a on behalf of 
08-30 12:31:04.919  7982  7982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:04.919  7982  8117 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 12:31:04.919  7982  8119 V BluetoothOppNotification: update too frequent, put in queue
08-30 12:31:04.921  7982  7982 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-30 12:31:04.921  7982  7982 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 12:31:04.921  7982  8119 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 12:31:04.922  7982  8117 V BluetoothOppNotification: inbound notification was removed.
,08-30 12:31:04.922  7982  8117 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 12:31:04.923  7982  8120 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 12:31:04.923  7982  8117 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2553787b on behalf of 
08-30 12:31:04.946  7982  7982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4951384
08-30 12:31:04.946  7982  7982 V BluetoothSapService: Sap Service onCreate
,08-30 12:31:04.948  7982  7982 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:04.948  7982  7982 V BluetoothSapService: state: 12
,08-30 12:31:04.948  7982  7982 V BluetoothSapService: Starting SAP server process
08-30 12:31:04.950  7982  7982 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 12:31:04.939  8121  8121 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:31:04.939  8121  8121 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:04.952  7982  8122 V BluetoothSapService: Sap Service initRfcommSocket
08-30 12:31:04.952  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:04.953  7982  8122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:04.954  7982  8122 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 12:31:04.954  7982  8122 V BluetoothSapService: Succeed to create listening socket 
08-30 12:31:04.954  7982  8122 V BluetoothSapService: Accepting socket connection...
08-30 12:31:04.968  8121  8121 V BT_SAP  : Event pipe created
08-30 12:31:04.968  8121  8121 V BT_SAP  : create_server_socket qcom.sap.server
08-30 12:31:04.968  8121  8121 V BT_SAP  : created socket fd 6
,08-30 12:31:05.891  7982  7982 V BluetoothOppNotification: new notify threadi!
,08-30 12:31:05.892  7982  7982 V BluetoothOppNotification: send delay message
,08-30 12:31:05.905  7982  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:31:05.909  7982  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26972157 on behalf of 
08-30 12:31:05.910  7982  8132 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:31:05.912  7982  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 12:31:05.918  7982  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1acbe444 on behalf of 
08-30 12:31:05.920  7982  8132 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:31:05.923  7982  8132 V BluetoothOppNotification: outbound notification was removed.
08-30 12:31:05.923  7982  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:31:05.924  7982  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18f5192d on behalf of 
08-30 12:31:05.925  7982  8132 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 12:31:05.928  7982  8132 V BluetoothOppNotification: inbound notification was removed.
,08-30 12:31:05.928  7982  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 12:31:05.930  7982  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33d59e62 on behalf of 
,08-30 12:31:07.255  1028  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{40bd03d type 2 when 187853 com.google.android.gms} when 187853
,08-30 12:31:07.276   312  8134 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 12:31:07.280  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:08.209  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:31:08.220  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:31:08.221  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:31:08.221  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1270344d removed from the list
08-30 12:31:08.221  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:31:08.221  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:08.221  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 12:31:08.222  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:08.222  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a43eb02 added. We now have 4 listener(s)
08-30 12:31:08.222  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:31:08.224  1028  1044 D WifiServiceImplEx: setWifiEnabled: false pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:31:08.225  1028  1044 D WifiService: setWifiEnabled: false pid=6629, uid=10118
08-30 12:31:08.225  1028  1044 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:31:13.235  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:13.250  1028  1043 D WifiServiceImplEx: setWifiEnabled: true pid=6629, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:31:13.251  1028  1043 D WifiService: setWifiEnabled: true pid=6629, uid=10118
08-30 12:31:13.251  1028  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:31:13.272  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 12:31:13.272  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:31:13.272  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 12:31:13.274  1028  1368 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-30 12:31:13.274  1028  1368 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 12:31:13.276  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 12:31:13.276  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:31:13.277  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 12:31:13.277  1028  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:31:13.277  1028  1368 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 12:31:13.277  1028  1368 E WifiHW  : unknown target_country: EU , set to default
08-30 12:31:13.277  1028  1368 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 12:31:13.277  1028  1368 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 12:31:13.277  1028  1368 I WifiUtil: gEnableBmps=1
08-30 12:31:13.855   312   887 D SoftapController: Softap fwReload - Ok
,08-30 12:31:13.876  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:31:13.876  1028  1110 D Tethering: InitialState.processMessage what=4
,08-30 12:31:13.880  1028  1368 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (599ms)
,08-30 12:31:13.885   312   887 D CommandListener: Setting iface cfg
08-30 12:31:13.885   312   887 D CommandListener: Trying to bring down wlan0
08-30 12:31:13.896   312   887 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:31:13.902  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:31:13.905  1028  1368 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 12:31:13.909  8145  8145 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:31:13.919  8145  8145 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:13.929  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:31:13.929  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:31:13.929  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:31:13.930  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:31:13.930  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:31:13.930  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:31:13.930  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:31:13.946  1028  1368 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 12:31:13.946  1028  1368 D WifiMonitor: connecting to supplicant
,08-30 12:31:13.975  8145  8145 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 12:31:14.001  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:31:14.005  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 12:31:14.011  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 12:31:14.013  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:14.014  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:31:14.015  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:14.018  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:31:14.018  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:31:14.018  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:31:14.018  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:31:14.018  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:31:14.019  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:31:14.021  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:31:14.021  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:31:14.021  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:31:14.021  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:31:14.021  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:31:14.022  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:31:14.022  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:31:14.022  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:31:14.022  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:31:14.022  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:31:14.022  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:31:14.035  8145  8145 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 12:31:14.035  8145  8145 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 12:31:14.068  1028  1938 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8162 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 12:31:14.156  8145  8145 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 12:31:14.177  1028  1044 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8184 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:31:14.181  8162  8182 W FormManager: Network not available. Please check & try again.
08-30 12:31:14.186  8162  8183 V FormManager: Network unavailable.
08-30 12:31:14.188  8162  8183 V FormManager: Network unavailable.
,08-30 12:31:14.200  1028  1971 I ActivityManager: Killing 7132:com.android.chrome/u0a57 (adj 15): empty #17
08-30 12:31:14.200  8145  8145 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 12:31:14.207  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:31:14.208  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 12:31:14.208  8145  8145 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 12:31:14.208  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 12:31:14.208  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 12:31:14.208  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:31:14.208  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:31:14.208  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:31:14.209  1028  1368 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:31:14.209  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.210  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.210  1028  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.210  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.211  1028  1368 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 12:31:14.211  1028  1368 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 12:31:14.211  1028  1368 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 12:31:14.211  1028  1368 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 12:31:14.211  1028  1368 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 12:31:14.223  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:31:14.227  1028  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:31:14.227  1028  1368 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:31:14.227  1028  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:31:14.227  1028  1763 W libprocessgroup: failed to open /acct/uid_10057/pid_7132/cgroup.procs: No such file or directory
08-30 12:31:14.229  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.229  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.229  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.229  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.229  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:31:14.230  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:31:14.231  1028  1368 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 12:31:14.232  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:14.233  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 12:31:14.233  1919  1919 D WfdService: Waiting for WifiP2p enabling
08-30 12:31:14.233  1028  1368 D WifiNative-wlan0: SET update_config 1: returned true
08-30 12:31:14.233  1028  1368 D WifiConfigStore: Loading config and enabling all networks 
08-30 12:31:14.233  1028  1368 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 12:31:14.233  1028  1372 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 12:31:14.233  1028  1368 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-30 12:31:14.238  1028  1368 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:14.238  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:31:14.239  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:31:14.240  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:14.241  1028  1900 I ActivityManager: Killing 7153:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:14.243  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:31:14.244  1028  1368 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 12:31:14.244  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:31:14.244  1028  1368 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 12:31:14.322  1028  1938 W libprocessgroup: failed to open /acct/uid_10062/pid_7153/cgroup.procs: No such file or directory
08-30 12:31:14.322  1028  1368 D WifiStateMachine: enableVerboseLogging : level 2
,08-30 12:31:14.322  1028  1368 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 12:31:14.323  1028  1368 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 12:31:14.323  1028  1368 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 12:31:14.324  1028  1368 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 12:31:14.325  1028  1368 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 12:31:14.326  1028  1368 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 12:31:14.326  1028  1368 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 12:31:14.327  1028  1368 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 12:31:14.327  1028  1368 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 12:31:14.328  1028  1368 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 12:31:14.328  1028  1368 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 12:31:14.330  1028  1368 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 12:31:14.330  1028  1368 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 12:31:14.332  1028  1368 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 12:31:14.335  1919  1919 D WfdsService: Supplicant Connection state is changed : true
08-30 12:31:14.335  1028  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:31:14.335  1028  1368 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 12:31:14.336  1919  2212 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 12:31:14.336  1919  2212 D WfdsService: Set the WFDS Monitor: true
08-30 12:31:14.336  1919  2212 D WfdsMonitor: WfdsMonitorThread create
08-30 12:31:14.337  1028  1368 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 12:31:14.337  1028  1368 D WifiNative-HAL: Setting external_sim to 1
08-30 12:31:14.337  1028  1368 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 12:31:14.337  1028  1368 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 12:31:14.337  1028  1368 I WifiNative-HAL: startHal
08-30 12:31:14.337  1028  1368 D wifi    : setting scan oui 0xaf5f03e0
,08-30 12:31:14.337  1919  2212 D WfdsMonitor: WFDS Monitor is created and started
08-30 12:31:14.337  1919  2212 D WfdsService: WiFi: Supplicant connection re-established
08-30 12:31:14.338  1028  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:31:14.338  1028  1368 I WifiNative-HAL: startHal
08-30 12:31:14.338  1028  1368 D wifi    : setting scan oui 0xaf5f03e0
08-30 12:31:14.338  1028  1368 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 12:31:14.339  1028  1368 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 12:31:14.339  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 12:31:14.339  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 12:31:14.339  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 12:31:14.340  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:31:14.340  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:31:14.341  7728  7728 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.342  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:31:14.342  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 12:31:14.342  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 12:31:14.342  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 12:31:14.342  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:31:14.343  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:31:14.343  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:31:14.343  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:31:14.343  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:31:14.343  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:31:14.343  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 12:31:14.344  8145  8145 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 12:31:14.344  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 12:31:14.344  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:31:14.344  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:31:14.344  1028  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:31:14.344  1919  8206 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 12:31:14.345  1919  8206 E CtrlSupplicant: Succeed to open control connection
08-30 12:31:14.345  1919  8206 E CtrlSupplicant: Succeed to open monitor connection
08-30 12:31:14.345  1028  1368 E WifiNative: : [197,167,133 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 12:31:14.345  1028  1368 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 12:31:14.345  1919  8206 D WfdsMonitor: Supplicant connection established
08-30 12:31:14.346  1028  1368 D WifiNative-wlan0: RECONNECT: returned true
08-30 12:31:14.346  1028  1368 D WifiNative-wlan0: doString: [STATUS]
08-30 12:31:14.346  1919  2212 D WfdsService: Connected to the supplicant for wfds
08-30 12:31:14.346  1028  1368 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:31:14.346  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:31:14.346  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:31:14.346  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 12:31:14.347  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:31:14.348  10,28  1367 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.351  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 12:31:14.351  1028  1028 D RttService: SCAN_AVAILABLE : 3
,08-30 12:31:14.351  1028  1534 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.351  1028  1534 I WifiNative-HAL: startHal
08-30 12:31:14.351  1028  1534 D wifi    : getting scan capabilities on interface[1] = 0xaf5f03e0
08-30 12:31:14.351  1028  1534 D wifi    : failed to get capabilities : -3
08-30 12:31:14.351  1028  1534 E WifiScanningService: could not get scan capabilities
08-30 12:31:14.351  1028  1368 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:31:14.351  1028  1535 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.352  1028  1368 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 12:31:14.352   312   887 D CommandListener: Setting iface cfg
08-30 12:31:14.352   312   887 D CommandListener: Trying to bring up p2p0
08-30 12:31:14.353  1028  1367 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 12:31:14.353  1028  1367 D LGWifiP2pService: P2pEnablingState
08-30 12:31:14.354  1028  1367 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.354  1028  1367 D LGWifiP2pService: P2p socket connection successful
08-30 12:31:14.355  1028  1368 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 12:31:14.355  1028  1368 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 12:31:14.354  1028  1367 D LGWifiP2pService: P2pEnabledState
08-30 12:31:14.356  1028  1368 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 12:31:14.357  1028  1368 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 12:31:14.358  1028  1368 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 12:31:14.358  1028  1368 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 12:31:14.358  1919  1919 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 12:31:14.358  1919  1919 D WfdsService: WifiP2pState is changed : true
08-30 12:31:14.358  8145  8145 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 12:31:14.358  1919  2212 D WfdsService: Receive the WFDS_ENABLE Method
08-30 12:31:14.358  1919  2212 D WfdsService: Set the WFDS Monitor: true
08-30 12:31:14.358  1919  2212 D WfdsService: Connected to the supplicant for wfds
08-30 12:31:14.358  1919  2212 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 12:31:14.358  8145  8145 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 12:31:14.358  1919  2212 D WfdsService: selectPreferredScanChannel [36]
08-30 12:31:14.358  1919  2212 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 12:31:14.359  1028  1367 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 12:31:14.359  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:31:14.359  1028  1368 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 12:31:14.360  1028  1368 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 12:31:14.360  1028  1368 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 12:31:14.360  1028  1367 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 12:31:14.360  1919  1919 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 12:31:14.360  1028  1368 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 12:31:14.361  1028  1367 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 12:31:14.361  1919  1919 D WfdsService: isConnected: false
08-30 12:31:14.361  1028  1367 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 12:31:14.361  1028  1367 D WifiNative-p2p0: SET device_name G3: returned true
08-30 12:31:14.361  1028  1367 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 12:31:14.361  1028  1367 D LGWifiP2pService: before postfix = G3
08-30 12:31:14.361  1028  1367 D Wif,iServerServiceExt: postfix byte check : 2
08-30 12:31:14.361  1028  1367 D LGWifiP2pService: after postfix = G3
08-30 12:31:14.361  1028  1367 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 12:31:14.362  8145  8145 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 12:31:14.362  1028  1367 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 12:31:14.362  1028  1367 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 12:31:14.362  1028  1368 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 12:31:14.362  1028  1367 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 12:31:14.362  1028  1367 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 12:31:14.363  1028  1368 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 12:31:14.363  1028  1367 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 12:31:14.363  1028  1368 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 12:31:14.363  1028  1367 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 12:31:14.363  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 12:31:14.365  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:31:14.366  1028  1367 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 12:31:14.366  1028  1367 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:31:14.367  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:31:14.367  8145  8145 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.368  8145  8145 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:31:14.368  8145  8145 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.369  8145  8145 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.370  1919  8206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.370  1919  8206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.370  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:31:14.370  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.370  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.370  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.370  1028  8203 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.370  1028  8203 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.370  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.370  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.370  1028  1368 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 12:31:14.370  1028  8203 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.370  1028  8203 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.370  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.371  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.371  1028  1368 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:31:14.372  1028  1368 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:31:14.372  1028  1367 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 12:31:14.372  1028  1367 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 12:31:14.372  1028  1367 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 12:31:14.372  1028  1367 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 12:31:14.372  1028  1367 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 12:31:14.373  1919  1919 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 12:31:14.373  1028  1367 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 12:31:14.373  1919  1919 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 12:31:14.373  1028  1367 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 12:31:14.373  1919  1919 D WfdsService: Update P2p Interface State: 3
08-30 12:31:14.373  1028  1368 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:31:14.373  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 12:31:14.374  1028  1367 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 12:31:14.374  1028  1367 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 12:31:14.374  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 12:31:14.374  8145  8145 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:31:14.374  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 12:31:14.374  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=,UNKNOWN
08-30 12:31:14.374  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:31:14.374  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:31:14.375  1028  1368 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 12:31:14.375  1028  1368 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 12:31:14.377  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:31:14.383  8162  8209 V FormManager: Network unavailable.
08-30 12:31:14.385  8162  8208 W FormManager: Network not available. Please check & try again.
08-30 12:31:14.391  8162  8209 V FormManager: Network unavailable.
,08-30 12:31:14.395  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:31:14.395  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:31:14.396  1028  1367 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 12:31:14.396  1028  1367 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 12:31:14.396  1028  1368 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 12:31:14.396  1028  1368 D WifiNative-wlan0: doBoolean: SCAN
08-30 12:31:14.397  1028  1368 D WifiNative-wlan0: SCAN: returned false
08-30 12:31:14.397  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=197219  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:31:14.398  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:31:14.398  1028  1367 D LGWifiP2pService: InactiveState
08-30 12:31:14.398  1028  1367 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.398  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.398  1028  1367 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 12:31:14.399  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:31:14.399  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=197221  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:31:14.399  8145  8145 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.400  1919  8206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:31:14.400  1028  1368 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:31:14.400  1028  8203 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:31:14.400  1028  8203 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.400  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 12:31:14.400  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:31:14.400  1028  1368 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:31:14.400  8145  8145 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:31:14.400  8145  8145 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.400  1919  8206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.401  1028  1368 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:31:14.401  1028  1367 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 12:31:14.401  8145  8145 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.401  1028  1368 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:31:14.401  1919  8206 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.401  1028  1367 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.401  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.401  1028  1367 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.401  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.401  1028  1367 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.401  1028  1368 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  8203 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  8203 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.402  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.402  1028  8203 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  8203 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  8203 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  8203 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1,ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1028  1367 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:14.402  1919  2212 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 12:31:14.403  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:14.403  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:14.404  1028  1028 E WifiServerServiceExt: No p2p device connected
08-30 12:31:14.404  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:31:14.406  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:31:14.406  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:31:14.406  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:31:14.406  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:31:14.406  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 12:31:14.407  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:31:14.415  4310  8210 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:31:14.418  4310  8211 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:31:14.419  4310  8211 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 12:31:14.463  1028  1569 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8212 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 12:31:14.604  8212  8212 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 12:31:14.604  8212  8212 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 12:31:14.615  8212  8212 V [BNRBootReceiver]: Boot Receiver Return
08-30 12:31:14.615  8212  8212 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 12:31:14.698  1028  2010 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8233 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:31:14.703  1028  2010 I ActivityManager: Killing 7179:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-30 12:31:14.757  1028  1900 W libprocessgroup: failed to open /acct/uid_10085/pid_7179/cgroup.procs: No such file or directory
,08-30 12:31:14.797  8233  8233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:31:14.825  8233  8233 D PluginManager: init()
,08-30 12:31:14.853  8145  8145 E wpa_supplicant: USIM:  scard_init function
,08-30 12:31:14.854  8145  8145 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 12:31:14.855  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 12:31:14.856  1028  8203 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 12:31:14.857  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 12:31:14.857  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-30 12:31:14.857  1028  8203 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 12:31:14.857  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:31:14.857  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 12:31:14.858  1028  1368 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:31:14.859  1028  1368 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:31:14.861  1028  1368 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:31:14.863  1028  1368 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:31:14.863  1028  1368 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 12:31:14.868  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=197691  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 12:31:14.871  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.871  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.871  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:31:14.872  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:14.872  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:14.873  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=197695  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 12:31:14.875  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.875  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:14.875  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 12:31:14.877  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:31:14.877  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 12:31:14.878  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:14.882  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:31:14.883  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:14.884  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:14.973  8145  8145 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:31:14.975  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 12:31:14.976  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 12:31:14.976  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 12:31:14.977  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 12:31:14.977  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 12:31:14.978  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:31:14.978  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:31:14.986  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=197808  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:31:14.987  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=197810  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:31:14.989  1028  1368 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.989  1028  1368 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.990  1028  1368 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.991  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.992  1028  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:31:14.993  1028  1368 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197815
08-30 12:31:14.994  1028  1368 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197816
08-30 12:31:14.994  1028  1368 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197817
08-30 12:31:14.995  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197817
08-30 12:31:14.995  8145  8145 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:31:14.996  8145  8145 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 12:31:14.997  1028  1368 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197819
08-30 12:31:14.998  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=197820  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:31:15.003  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:31:15.003  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:31:15.005  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.005  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:15.006  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.006  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.006  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 12:31:15.006  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 12:31:15.006  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:31:15.006  1028  8203 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:31:15.007  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 12:31:15.007  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:31:15.007  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.008  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=197826  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:31:15.007  1028  8203 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:31:15.009  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.009  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:31:15.009  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.009  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:31:15.009  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 12:31:15.010  1028  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=197832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:31:15.010  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=197832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:31:15.010  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.010  1582  1582 I StatusBa,r.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:15.010  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:31:15.010  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 12:31:15.012  1028  1368 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=197834
08-30 12:31:15.012  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.012  1028  1368 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=197834
08-30 12:31:15.012  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-30 12:31:15.012  1028  1028 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-30 12:31:15.013  1028  1368 D WifiNative-wlan0: doString: [STATUS]
08-30 12:31:15.013  1028  8203 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:31:15.013  1028  8203 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:31:15.014  1028  1368 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:31:15.015  1028  1368 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 12:31:15.023  1028  1368 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 12:31:15.023  1028  1368 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 12:31:15.027  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.027  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.027  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 12:31:15.029  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.029  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:15.030  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.037  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.037  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.037  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 12:31:15.039  1028  1368 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 12:31:15.039  1028  1396 D ConnectivityService: Got NetworkAgent Messenger
08-30 12:31:15.039  1028  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:31:15.039  1028  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:31:15.039  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 12:31:15.039  1028  1396 D ConnectivityService: NetworkAgent connected
,08-30 12:31:15.041  1028  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:31:15.041  1028  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:31:15.044  1028  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:31:15.044  1028  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:31:15.044  1028  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:31:15.045  1028  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:31:15.046  1028  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:31:15.048  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.048  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:15.049  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.050  1028  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:31:15.051   312   887 D CommandListener: Setting iface cfg
,08-30 12:31:15.054  1028  1368 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 12:31:15.055  1028  1368 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=197877  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:31:15.055  1028  8251 D DhcpStateMachine: StoppedState
08-30 12:31:15.055  1028  8251 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.055  1028  8251 D DhcpStateMachine: WaitBeforeStartState
08-30 12:31:15.055  1028  1368 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=197877  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:31:15.056  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=197878  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:31:15.056  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:31:15.057  1028  1028 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 12:31:15.057  1028  1368 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=197879  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:31:15.057  1028  1368 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=197879  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:31:15.058  1028  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=197880  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:31:15.059  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29145] from screen [on:0 period:-620707469] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:15.059  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-620707469] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:15.060  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:31:15.064  1028  1396 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 12:31:15.064  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:31:15.065  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:31:15.065  1028  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 12:31:15.069  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.069  1028  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:31:15.069  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:31:15.069  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:31:15.070  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 12:31:15.070  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=130,0,0
08-30 12:31:15.070  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=130,0,0
08-30 12:31:15.070  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-30 12:31:15.071  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 12:31:15.071  1028  1368 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 12:31:15.071  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 12:31:15.072  1028  1368 D WifiNative-wlan0: SET ps 0: returned true
08-30 12:31:15.072  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 12:31:15.072  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 12:31:15.072  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 12:31:15.072  1028  1368 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 12:31:15.072  1028  1368 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:31:15.072  1028  1367 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5b6ffb6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.072  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5b6ffb6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.072  1028  8251 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.072  1028  8251 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 12:31:15.073  1028  1368 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:31:15.074   312   887 D CommandListener: Setting iface cfg
08-30 12:31:15.074   312   887 D CommandListener: Trying to bring up wlan0
08-30 12:31:15.076  1028  1368 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 12:31:15.077  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:31:15.077  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:31:15.078  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 12:31:15.078  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 12:31:15.078  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:31:15.078  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:31:15.079  1028  1367 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.079  1028  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.079  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:31:15.079  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:31:15.079  1028  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:31:15.079  1028  1368 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 12:31:15.080  8145  8145 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 12:31:15.080  1028  1368 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 12:31:15.080  1028  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:31:15.103  1028  1368 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:31:15.103  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 12:31:15.104  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:31:15.104  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:31:15.104  1028  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:31:15.105  1028  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4, v4r v4dns
08-30 12:31:15.105  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:31:15.105  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:31:15.107  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 12:31:15.108  1028  1368 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:31:15.109  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:31:15.109  1028  1368 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 12:31:15.110  1028  1396 D ConnectivityService: ignoring duplicate network state non-change
08-30 12:31:15.114  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.114  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.114  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:31:15.115  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.115  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:15.116  1028  1396 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 12:31:15.116  1028  1396 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 12:31:15.120  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.123  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.123  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:31:15.124  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.124  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.124  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:31:15.125  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.127  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:31:15.132  1919  1919 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 12:31:15.136  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.136  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.136  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:31:15.139  1028  1368 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 12:31:15.140  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 12:31:15.147  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.147  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:15.147  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:31:15.147  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.147  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:31:15.147  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.150  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:31:15.151  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:31:15.151  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.155  1028  1396 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 12:31:15.155  1028  1396 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 12:31:15.156  1028  1396 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 12:31:15.157   312   887 E Netd    : netlink response contains error (File exists)
08-30 12:31:15.157  1028  1396 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 12:31:15.158  1028  1396 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 12:31:15.158  1028  1396 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 12:31:15.158  1028  1396 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 12:31:15.166  1028  1396 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:31:15.167  1028  1396 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.167  1028  1396 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.167  1028  1396 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.167  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.167  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 12:31:15.167  1028  1396 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:31:15.167  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:15.167  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:15.167  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:31:15.167  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:31:15.167  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.167  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 12:31:15.167  1028  1396 D ConnectivityService: currentScore = 0, newScore = 20
08-30 12:31:15.167  1028  1396 D ConnectivityService:    accepting network in place of null
08-30 12:31:15.167  1028  1396 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.169   312  8261 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 12:31:15.170  1028  1368 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.170  1028  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:31:15.170  1829  1829 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:31:15.170  1829  1829 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:31:15.171  1028  1396 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 12:31:15.171  1028  1396 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 12:31:15.171  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:31:15.172  1028  1396 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:31:15.172  1028  1396 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 12:31:15.173  1028  1396 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 12:31:15.174  1028  1396 D ConnectivityService: validation of new default Network = false
08-30 12:31:15.174  1028  1396 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 12:31:15.174  1028  1396 D DSQN    : enableDataServiceNotify 
08-30 12:31:15.174  1028  1396 D DSQN    : start dsqn bin
08-30 12:31:15.175  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 12:31:15.175  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:31:15.176  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:31:15.176  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:31:15.178  1028  1396 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.178  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.178  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:15.179  1028  1396 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:15.169  8262  8262 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:15.169  8262  8262 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block,/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:15.179  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 12:31:15.191  8262  8262 E DSQN    : DSQN ssw
08-30 12:31:15.198  1028  1366 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 12:31:15.206  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:31:15.207  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.208  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.222   312  8261 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 12:31:15.274  1028  8251 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 12:31:15.275  1028  8251 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 12:31:15.275  1028  8251 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 12:31:15.269  8266  8266 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:15.269  8266  8266 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:31:15.281   312  8261 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 12:31:15.284  8266  8266 I dhcpcd  : version 5.5.6 starting
08-30 12:31:15.286  8266  8266 E dhcpcd  : get_duid: m
08-30 12:31:15.286  8266  8266 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 12:31:15.286  8266  8266 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 12:31:15.309   312   886 D LGDataListener: argv[0]=dsqncommand
,08-30 12:31:15.309   312   886 D LGDataListener: argv[1]=wlan0
,08-30 12:31:15.309   312   886 D LGDataListener: argv[2]=1
08-30 12:31:15.309   312   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 12:31:15.311  1028  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 12:31:15.311  1028  1108 D DSQN    : start to monitor internet connection
08-30 12:31:15.342  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:31:15 GMT], X-Android-Received-Millis=[1472553075341], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472553075308]}
08-30 12:31:15.342  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:31:15.342  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 12:31:15.342  1028  1396 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.342  1028  1396 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.342  1028  1396 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:31:15.342  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:15.342  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:31:15.342  1028  1396 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 12:31:15.342  1028  1396 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:15.342  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.342  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:15.342  1028  1396 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:15.343  1028  1396 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.343  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 12:31:15.343  1829  1829 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.343  1829  1829 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:31:15.344  1028  1368 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:15.344  1028  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:31:15.344  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 12:31:15.365  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 12:31:15.366  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.367  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:31:15.367  8266  8266 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:31:15.368  8266  8266 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:31:15.368  8266  8266 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:31:15.368  8266  8266 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 12:31:15.368  8266  8266 D dhcpcd  : wlan0: sending REQUEST (xid 0x8d8ba76), next in 3.36 seconds
08-30 12:31:15.407  8266  8266 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 12:31:15.426  8266  8266 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 12:31:15.426  8266  8266 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 12:31:15.427  8266  8266 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 12:31:15.427  8233  8233 W ExternalStrings: load override strings
08-30 12:31:15.427  8233  8233 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:15.427  8233  8233 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 12:31:15.427  8266  8266 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 12:31:15.428  8266  8266 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:31:15.428  8266  8266 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:31:15.429  8266  8266 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:31:15.429  8266  8266 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 12:31:15.430  8233  8233 D StatusProvider: onCreate
,08-30 12:31:15.474  8233  8233 V Signer  : override build config not found
,08-30 12:31:15.474  8233  8233 D Signer  : value of property debug is false
,08-30 12:31:15.499  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 12:31:15.500  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 12:31:15.501  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 12:31:15.501  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 12:31:15.501  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 12:31:15.501  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 12:31:15.501  8233  8233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 12:31:15.508  8233  8233 V LGMDMManager: Create singleton instance
08-30 12:31:15.546  8233  8233 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 12:31:15.635  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:15.637  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 12:31:15.647  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:15.654  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:15.661  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:31:15.664  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.672  7918  7918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:31:15.675  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 12:31:15.678  6854  6854 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 12:31:15.680  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:15.684  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.686  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:31:15.692  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:31:15.698  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:15.699  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.700  7918  7918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:31:15.702  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:31:15.702  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.706  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:15.712  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:15.716  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:15.717  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.717  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:31:15.719  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:31:15.720  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-30 12:31:15.720  6854  6854 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:31:15.721  6854  6854 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:31:15.722  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:31:15.722  6854  6854 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:31:15.722  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 12:31:15.722  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:31:15.722  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:31:15.722  6854  6854 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:31:15.722  6854  6854 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 12:31:15.723  6854  6854 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:31:15.824  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:31:15.829  8233  8293 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 12:31:15.832  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.837  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:15.850  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:15.862  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:15.863  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.863  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:31:15.873  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:15.873  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.880  1028  8251 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 12:31:15.886  1028  8251 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 12:31:15.887  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:31:15.887  1028  8251 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:31:15.887  1028  8251 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 12:31:15.887  1028  8251 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-30 12:31:15.887  1028  8251 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:31:15.887  1028  8251 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 12:31:15.887  1028  8251 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 12:31:15.888  1028  8251 D DhcpStateMachine: RunningState
08-30 12:31:15.892  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:15.898  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:15.899  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.899  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:31:15.904  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:15.904  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.914  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:15.921  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:15.930  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:15.930  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.930  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:31:15.935  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:31:15.936  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.945  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:15.951  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:15.958  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:31:15.958  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:15.959  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:31:15.971  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:15.971  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:31:15.987  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:15.993  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:31:16.003  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:16.004  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:16.013  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:31:16.019  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:16.019  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:16.030  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:16.040  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:31:16.049  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:16.049  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:16.050  7918  7918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:31:16.057  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:16.058  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:16.063  8184  8184 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 12:31:16.069  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:31:16.072  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:16.082  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:16.092  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:16.093  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:16.094  7918  7918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 12:31:16.095  7918  7918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:31:16.096  7918  7918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 12:31:16.103  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:31:16.103  8233  8294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:31:16.108  8184  8184 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 12:31:16.109  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:31:16.113  6854  6854 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:31:16.127  6854  6854 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:31:16.139  8233  8293 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:31:16.139  8233  8293 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:16.140  7918  7918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:31:16.141  7918  7918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:31:16.142  7918  7918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 12:31:16.143  7918  7918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:31:16.143  7918  7918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 12:31:16.148  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.150  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.152  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.154  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.157  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 12:31:16.160  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.162  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.164  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.167  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.169  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:31:16.172  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 12:31:16.173  1028  1918 I ActivityManager: Killing 7202:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 12:31:16.289  8233  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 12:31:16.387  1028  2010 W libprocessgroup: failed to open /acct/uid_10093/pid_7202/cgroup.procs: No such file or directory
,08-30 12:31:16.439  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-30 12:31:16.457  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-30 12:31:16.461  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 12:31:16.461  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 12:31:16.462  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 12:31:16.463  8233  8293 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 12:31:16.468  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 12:31:16.471  8233  8293 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-30 12:31:16.943  1028  1368 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:31:16.944  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:31:16.946  1028  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:31:16.957  1028  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:31:16.958  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:31:16.958  1028  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:31:16.959  1028  1396 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 12:31:16.959  1028  1396 D ConnectivityService: identical MTU - not setting
08-30 12:31:16.959  1028  1396 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:31:16.959  1028  1396 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:16.959  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:16.959  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:16.960  1028  1396 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 12:31:16.961  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 12:31:18.069  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=65.0, 0.0, 0.0  rx=57.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-620704459] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:18.072  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=65.0, 0.0, 0.0  rx=57.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-620704456] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:18.073  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:18.090  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:31:18.130  1028  1369 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 12:31:18.174  1028  1396 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:31:18.188  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:18.213  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:18.217  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:18.222  6629  6629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:31:18.224  6629  6629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:18.227  1028  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:31:18.231  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:31:18.237  5737  5737 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 12:31:18.266  1028  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:31:18.275  8233  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:18.287  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:18.291  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:18.292  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:18.292  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a43eb02 removed from the list
08-30 12:31:18.292  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:18.292  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:18.292  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:18.297  6629  8334 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 12:31:18.297  6629  8334 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 12:31:18.308  2197  2197 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:31:18.323  1028  1938 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-30 12:31:18.325  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:18.325  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:18.325  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 12:31:18.325  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:18.325  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:31:18.326   312  8337 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:31:18.327   312  8337 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-30 12:31:18.357  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:31:18.357  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:31:18.357  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:31:18.357  7029  7029 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:31:18.361  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:31:18.366  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
08-30 12:31:18.366  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:31:18.366  7029  7029 D AppUp4:CustFacade: isPhone : true
08-30 12:31:18.367  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:31:18.367  7029  7029 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:31:18.369  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:31:18.369  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:31:18.370   312  8337 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 12:31:18.371  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:31:18 GMT], X-Android-Received-Millis=[1472553078370], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472553078338]}
08-30 12:31:18.371  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:31:18.371  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 12:31:18.372  1028  1396 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 12:31:18.372  1028  1396 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:31:18.372  1028  1396 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:31:18.372  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:18.372  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:31:18.372  1028  1396 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 12:31:18.372  1028  1396 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:18.372  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:31:18.372  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:18.372  1028  1396 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:18.373  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:31:18.374  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:31:18.376  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:31:18.379  4310  8353 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:31:18.381  3510  3510 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-30 12:31:18.384  3510  3510 V DownloadManager: DownloadService onCreate
08-30 12:31:18.385  4310  8353 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-30 12:31:18.387  3510  8355 I DownloadManager: in removeSpuriousFiles
08-30 12:31:18.387  4310  8354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:31:18.387  4310  8354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 12:31:18.388  3510  8355 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-30 12:31:18.392  3510  8355 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1517e45a on behalf of 3510
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-30 12:31:18.394  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-30 12:31:18.395  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-30 12:31:18.395  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-30 12:31:18.395  3510  8355 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-30 12:31:18.396  3510  8355 I DownloadManager: in trimDatabase
08-30 12:31:18.396  3510  8355 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-30 12:31:18.397  3510  8355 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a5bd68b on behalf of 3510
08-30 12:31:18.416  1028  1899 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8360 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 12:31:18.430  4310  8353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-30 12:31:18.431  3510  3510 V DownloadManager: DownloadService onStartCommand
08-30 12:31:18.432  3510  8356 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,08-30 12:31:18.433  4310  4310 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-30 12:31:18.434  4310  4310 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-30 12:31:18.434  4310  4310 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-30 12:31:18.435  4310  4310 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-30 12:31:18.437  3510  8356 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1d5fec26 on behalf of 3510
08-30 12:31:18.438  4310  4310 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-30 12:31:18.439  3510  8356 V DownloadManager: processing inserted download 1
08-30 12:31:18.439  3510  8356 V DownloadManager: processing inserted download 4
08-30 12:31:18.440  3510  8356 V DownloadManager: processing inserted download 7
08-30 12:31:18.441  3510  8356 V DownloadManager: processing inserted download 8
08-30 12:31:18.442  3510  8356 V DownloadManager: processing inserted download 9
08-30 12:31:18.443  3510  8356 V DownloadManager: processing inserted download 10
08-30 12:31:18.444  3510  8356 V DownloadManager: processing inserted download 11
08-30 12:31:18.445  3510  8356 V DownloadManager: processing inserted download 12
08-30 12:31:18.446  3510  8356 V DownloadManager: processing inserted download 13
,08-30 12:31:18.447  3510  8356 V DownloadManager: processing inserted download 14
,08-30 12:31:18.448  3510  8356 V DownloadManager: processing inserted download 16
08-30 12:31:18.450  3510  3510 V DownloadManager: DownloadService onDestroy
08-30 12:31:18.461  8360  8360 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:31:18.462  8360  8360 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:31:18.463  8360  8360 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 12:31:18.463  8360  8360 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:31:18.527  8360  8360 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 12:31:18.558  8360  8360 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 12:31:18.598  8360  8360 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:31:18.636  8360  8360 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:31:18.637  8360  8360 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:18.784  8360  8360 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:31:18.845  8360  8360 I HubEmail: JNI_OnLoad()
,08-30 12:31:18.845  8360  8360 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:31:18.845  8360  8360 I HubEmail: registerNatives()
08-30 12:31:18.845  8360  8360 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:31:18.845  8360  8360 I HubEmail: registerNativeMethods()
08-30 12:31:18.845  8360  8360 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:31:18.846   312  8394 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:31:18.846   312  8394 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-30 12:31:18.850  8360  8360 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 12:31:18.855  8360  8395 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:18.871  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:31:18.871  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:31:18.873  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 12:31:18.873  3467  3467 D PhoneState: setPdpRejectCasuse : false
08-30 12:31:18.897   312  8394 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-30 12:31:18.900  1028  1864 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8397 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 12:31:18.946  8162  8392 V FormManager: There are no updated forms. The schedule will be deleted.
08-30 12:31:18.948  8162  8392 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-30 12:31:18.967  1028  2010 I ActivityManager: Killing 7728:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 12:31:19.014  8397  8397 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:31:19.014  8397  8397 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:19.017  8397  8397 D PhoneMonitor: Register our PhoneStateListener
08-30 12:31:19.038  1028  1971 W libprocessgroup: failed to open /acct/uid_10072/pid_7728/cgroup.procs: No such file or directory
,08-30 12:31:19.045  1028  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2e558f type 2 when 201865 com.google.android.gms} when 201865
,08-30 12:31:19.059  8397  8397 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:31:19.062  8397  8397 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:31:19.082  8397  8397 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 12:31:19.083  8397  8397 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 12:31:19.085  8397  8397 D TelephonyAutoProfiling: [parse] Load xml
,08-30 12:31:19.093  8397  8397 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-30 12:31:19.093  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 12:31:19.093  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 12:31:19.093  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 12:31:19.093  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 12:31:19.093  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 12:31:19.093  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 12:31:19.094  8397  8397 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 12:31:19.095  8397  8397 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 12:31:19.109  8397  8397 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 12:31:19.124  1028  1900 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8428 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:31:19.126  1028  1900 I ActivityManager: Killing 7780:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 12:31:19.155   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 27.762ms
,08-30 12:31:19.179   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 23.559ms
,08-30 12:31:19.200   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 19.540ms
,08-30 12:31:19.230  1028  2009 W libprocessgroup: failed to open /acct/uid_10019/pid_7780/cgroup.procs: No such file or directory
,08-30 12:31:19.249  1794  8446 I CheckinService: active receiver: enabled
,08-30 12:31:19.276  1794  8446 I CheckinService: Preparing to send checkin request
08-30 12:31:19.276  1794  8446 I EventLogService: Accumulating logs since 1472553040057
,08-30 12:31:19.334  1794  8446 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 12:31:19.346   312  8449 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 12:31:19.346   312  8449 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-30 12:31:19.379   312  8449 D libc-netbsd: res_queryN name = www.google.com succeed
,08-30 12:31:19.386   312  8451 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:31:19.386   312  8451 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 12:31:19.386   312  8451 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 12:31:19.438  1028  1370 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-30 12:31:19.491  1028  1918 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8452 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 12:31:19.493  1028  1918 I ActivityManager: Killing 7800:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-30 12:31:19.641  1028  2010 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8472 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 12:31:19.643  1028  1863 W libprocessgroup: failed to open /acct/uid_10027/pid_7800/cgroup.procs: No such file or directory
,08-30 12:31:19.762  1028  1918 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8489 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:31:19.765  1028  1918 I ActivityManager: Killing 7875:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 12:31:19.841  1028  1368 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:31:19.841  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:31:19.842  1028  1368 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:31:19.842  1028  1368 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:31:19.842  1028  1368 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:31:19.843  1028  1368 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-30 12:31:19.860  1028  1863 W libprocessgroup: failed to open /acct/uid_10080/pid_7875/cgroup.procs: No such file or directory
08-30 12:31:19.891  8489  8489 I art     : Almond Protected OAT
,08-30 12:31:19.898  8472  8472 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:31:19.898  8472  8472 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 12:31:19.928  8472  8472 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:31:19.928  8472  8472 I MultiDex: install
,08-30 12:31:19.928  8472  8472 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:31:19.940  8472  8472 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 12:31:19.966  8489  8489 D WeatherApplication: removeAccount
,08-30 12:31:19.967  8489  8489 D WeatherApplication: Account.length = 0
08-30 12:31:19.967  8489  8489 E WeatherApplication: OPERATOR:OPEN
08-30 12:31:19.973  8489  8489 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:19
08-30 12:31:19.976  8489  8489 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:31:19.976  8489  8489 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:31:19.978  8489  8489 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:31:19.981  8489  8489 D WeatherAncestor: connectivity changed - connection : true
08-30 12:31:19.982  8489  8489 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 12:31:19.991  8489  8489 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:31:19.991  8489  8489 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-30 12:31:19.992  8489  8489 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 12:31:20.021  8489  8489 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:31:20.021  8489  8489 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:31:20
,08-30 12:31:20.058  1028  1864 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8508 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:31:20.059  1028  1864 I ActivityManager: Killing 7822:com.android.vending/u0a44 (adj 15): empty #17
08-30 12:31:20.163  1028  2010 I art     : Explicit concurrent mark sweep GC freed 77739(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.835ms total 181.619ms
,08-30 12:31:20.168  1028  1938 W libprocessgroup: failed to open /acct/uid_10044/pid_7822/cgroup.procs: No such file or directory
08-30 12:31:20.282   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:31:20.283   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:31:20.283   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 12:31:20.289  8508  8528 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:31:20.294   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:31:20.294   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:31:20.294   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 12:31:20.295  8508  8528 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 12:31:20.306   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:31:20.306   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:31:20.306   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:31:20.307  8508  8532 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:31:20.309   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:31:20.309   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:31:20.309   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:31:20.309  8508  8532 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-30 12:31:20.409  2197  2329 I art     : Explicit concurrent mark sweep GC freed 8910(559KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.235ms total 22.360ms
,08-30 12:31:20.495  8472  8487 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:31:20.495  8472  8487 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:20.522  8508  8508 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:31:20.542  8508  8508 I LibraryLoader: Loading: webviewchromium
,08-30 12:31:20.549  8508  8508 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 3374-3382)
08-30 12:31:20.549  8508  8508 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:31:20.555  8508  8508 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e1e2920}
08-30 12:31:20.557  8508  8508 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:31:20.557  8508  8508 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:31:20.570  8508  8508 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 12:31:20.572  8508  8508 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:31:20.586  8508  8508 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 12:31:20.587  8508  8508 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 12:31:20.587  8508  8508 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 12:31:20.592   316  1380 V AudioPolicyService: registerClient() client 0xb1427140, uid 10093
08-30 12:31:20.594  8508  8552 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 12:31:20.606  8508  8508 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:31:20.606  8508  8508 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:31:20.606  8508  8508 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:31:20.606  8508  8508 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:31:20.606  8508  8508 I Adreno-EGL: Remote Branch: 
08-30 12:31:20.606  8508  8508 I Adreno-EGL: Local Patches: 
08-30 12:31:20.606  8508  8508 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:31:20.711  8508  8508 I NSApplication: Starting up...
,08-30 12:31:20.730  1028  1578 I ActivityManager: Killing 7581:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 12:31:20.741  8564  8564 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-30 12:31:20.769  1028  1763 W libprocessgroup: failed to open /acct/uid_10037/pid_7581/cgroup.procs: No such file or directory
,08-30 12:31:20.785   312  8573 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:31:20.785  2197  2197 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 12:31:20.786   312  8573 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 12:31:20.786   312  8573 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 12:31:20.795  2197  2197 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 12:31:20.797  2197  2197 D c       : Getting all permits...
08-30 12:31:20.797  2197  2197 D a       : Opening database...
08-30 12:31:20.801  2197  2197 D a       : Opening database auth.proximity.permit_store...
,08-30 12:31:20.802  2197  2197 D a       : Closing database...
,08-30 12:31:20.823  8564  8564 I dex2oat : dex2oat took 81.946ms (threads: 4)
,08-30 12:31:20.839  8472  8487 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:31:20.839  8472  8487 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:31:20.839  8472  8487 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:31:20.839  8472  8487 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:31:20.839  8472  8487 I Adreno-EGL: Remote Branch: 
08-30 12:31:20.839  8472  8487 I Adreno-EGL: Local Patches: 
08-30 12:31:20.839  8472  8487 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:31:20.988  8472  8487 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:31:20.988  8472  8487 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:31:20.988  8472  8487 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:31:20.988  8472  8487 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:31:20.988  8472  8487 I Adreno-EGL: Remote Branch: 
08-30 12:31:20.988  8472  8487 I Adreno-EGL: Local Patches: 
08-30 12:31:20.988  8472  8487 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:31:21.095  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=38.0, 0.0, 0.0  rx=31.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-620701433] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:21.100  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=38.0, 0.0, 0.0  rx=31.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-620701430] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:21.100  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:31:21.101  2197  8578 D GCM     : Connected
,08-30 12:31:21.126  2197  8578 D GCM     : Message class com.google.e.a.a.q
,08-30 12:31:21.195  8472  8487 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:31:21.195  8472  8487 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:31:21.195  8472  8487 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:31:21.195  8472  8487 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:31:21.195  8472  8487 I Adreno-EGL: Remote Branch: 
08-30 12:31:21.195  8472  8487 I Adreno-EGL: Local Patches: 
08-30 12:31:21.195  8472  8487 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:31:21.305  6629  8579 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 12:31:21.305  6629  8579 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 12:31:21.305  6629  8334 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-30 12:31:21.305  6629  8334 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:31:21.309  6629  8334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:21.309  6629  8334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:21.309  6629  8334 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 12:31:21.312  6629  8579 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:21.314  6629  8582 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: OutgoingSocketThread/Receiver)
,08-30 12:31:21.315  6629  8581 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: OutgoingSocketThread/Sender)
08-30 12:31:21.316  6629  8579 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:21.316  6629  8582 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: OutgoingSocketThread/Receiver)
08-30 12:31:21.316  6629  8582 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:31:21.318  6629  8579 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 12:31:21.319  6629  8582 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 12:31:21.320  6629  8583 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: IncomingSocketThread/Sender)
08-30 12:31:21.327  6629  8584 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: IncomingSocketThread/Receiver)
08-30 12:31:21.327  6629  8584 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: IncomingSocketThread/Receiver)
08-30 12:31:21.327  6629  8584 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 12:31:21.327  6629  8584 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 12:31:21.453   312  8586 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:31:21.453   312  8586 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 12:31:21.489   312  8586 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 12:31:21.639  1794  8446 I CheckinTask: Sending checkin request (7859 bytes)
,08-30 12:31:21.828  1794  8446 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 12:31:21.843  1794  8446 I CheckinService: active receiver: disabled
,08-30 12:31:21.870  2197  2197 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 12:31:21.889  2197  2197 I GCM     : GCM config loaded
,08-30 12:31:21.909  8397  8397 V SetupWizard: Connected to Gservices successfully
,08-30 12:31:24.110  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=32.5, 0.0, 0.0  rx=27.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-620698418] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:24.111  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=32.5, 0.0, 0.0  rx=27.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-620698417] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:24.111  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:24.302  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 12:31:24.303  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 12:31:24.305  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a9da6ab Bundle[{}]
08-30 12:31:24.306  6629  6734 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 12:31:24.310  6629  6734 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 12:31:24.311  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 12:31:24.312  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 12:31:24.313  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 12:31:24.313  6629  6734 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 12:31:24.320  6629  6734 I System.out: Running OutgoingSocketThread
,08-30 12:31:24.326  6629  8595 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 12:31:24.326  6629  8595 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 12:31:25.310  8508  8530 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 12:31:26.454  1028  2010 I ActivityManager: Killing 7629:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 12:31:26.489  1028  1971 W libprocessgroup: failed to open /acct/uid_1000/pid_7629/cgroup.procs: No such file or directory
,08-30 12:31:27.133  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=23.2, 0.0, 0.0  rx=18.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-620695395] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:27.144  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=23.2, 0.0, 0.0  rx=18.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-620695384] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:27.144  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:31:27.337  6629  8595 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 12:31:27.337  6629  8595 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:31:27.338  6629  8595 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:27.338  6629  8595 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:27.338  6629  8595 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 12:31:27.343  6629  8598 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 12:31:27.343  6629  8598 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:31:27.344  6629  8598 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:27.344  6629  8598 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:27.345  6629  8601 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: OutgoingSocketThread/Receiver)
08-30 12:31:27.346  6629  8598 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 12:31:27.348  6629  8600 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: OutgoingSocketThread/Sender)
08-30 12:31:27.350  6629  8602 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: IncomingSocketThread/Sender)
08-30 12:31:27.351  6629  8603 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: IncomingSocketThread/Receiver)
08-30 12:31:27.351  6629  8603 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: IncomingSocketThread/Receiver)
08-30 12:31:27.351  6629  8603 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 12:31:27.351  6629  8603 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 12:31:27.353  6629  8601 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: OutgoingSocketThread/Receiver)
08-30 12:31:27.353  6629  8601 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:31:27.353  6629  8601 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 12:31:29.336  1028  1358 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:31:29.339  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 12:31:29.362  1582  1582 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 12:31:29.456  1028  1095 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8604 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 12:31:29.463  1582  1582 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 12:31:29.464  1582  1582 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 12:31:29.483  1028  1028 D administrator: Handling package changes for user 0
,08-30 12:31:29.486  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 12:31:29.541  8604  8604 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 12:31:29.595  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 12:31:29.595  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 12:31:29.643  8604  8604 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:31:29.644  8604  8604 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:29.670  1028  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:31:29.676  1028  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 12:31:29.684  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 12:31:29.684  2482  2482 V GmsNetworkLocationProvi: DISABLE
,08-30 12:31:29.714  1028  1093 D LocationProviderProxy: applying state to connected service
,08-30 12:31:29.715  2482  2482 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 12:31:29.757  8604  8649 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 12:31:29.757  8604  8649 I Babel   : MmsConfig.loadMmsSettings
,08-30 12:31:29.763  8604  8649 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 12:31:29.763  8604  8649 I Babel   : MmsConfig.loadFromDatabase
,08-30 12:31:29.785  8604  8649 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 12:31:29.785  8604  8649 I Babel   : MmsConfig.loadFromResources
08-30 12:31:29.787  8604  8649 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 12:31:29.788  8604  8649 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 12:31:29.819  8604  8604 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:31:29.830  8604  8648 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 12:31:29.833  8604  8648 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 12:31:29.835  8604  8648 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:31:29.852  1794  8652 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 12:31:29.852  1794  8652 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 12:31:29.854  8604  8648 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 12:31:29.856  8604  8648 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:31:29.858  8604  8648 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:31:29.860  7029  7029 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:31:29.865  1794  4775 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 12:31:29.865  7029  7029 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d3db931
,08-30 12:31:29.865  7029  7029 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:31:29.865  7029  7029 D AppUp4:CustFacade: isPhone : true
,08-30 12:31:29.866  7029  7029 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:31:29.866  7029  7029 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 12:31:29.873  8604  8648 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 12:31:29.877  8604  8648 W VideoCapabilities: Unsupported mime video/divx
08-30 12:31:29.897  8604  8648 W VideoCapabilities: Unsupported mime video/divx311
,08-30 12:31:29.899  8604  8648 W VideoCapabilities: Unsupported mime video/divx4
08-30 12:31:29.900  1028  1972 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8654 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 12:31:29.911  1028  1569 I ActivityManager: Killing 8212:com.lge.bnr/1000 (adj 15): empty #17
,08-30 12:31:29.924  8604  8648 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 12:31:29.941  8604  8648 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 12:31:29.945  8604  8648 W AudioCapabilities: Unsupported mime audio/eac3
,08-30 12:31:29.946  8604  8648 W AudioCapabilities: Unsupported mime audio/ac3
08-30 12:31:29.947  8604  8648 W AudioCapabilities: Unsupported mime audio/g726
08-30 12:31:29.947  8604  8648 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 12:31:29.948  8604  8648 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 12:31:29.949  8604  8648 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 12:31:29.951  8604  8648 W VideoCapabilities: Unsupported mime video/theora
08-30 12:31:29.952  8604  8648 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 12:31:30.001  1028  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_8212/cgroup.procs: No such file or directory
,08-30 12:31:30.024  8654  8654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:31:30.024  8654  8654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:31:30.025  8654  8654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:31:30.027  8654  8654 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 12:31:30.027  8654  8654 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:31:30.106  8654  8654 I SystemConfig: BUILD Country: EU
08-30 12:31:30.106  8654  8654 I SystemConfig: BUILD Operator: OPEN
,08-30 12:31:30.150  1028  1899 I ActivityManager: Killing 8184:com.lge.sync/1000 (adj 15): empty #17
,08-30 12:31:30.163  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=12.1, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-620692365] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:30.166  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=12.1, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-620692363] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:30.167  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:30.287  1028  2009 W libprocessgroup: failed to open /acct/uid_1000/pid_8184/cgroup.procs: No such file or directory
,08-30 12:31:30.331  6629  6734 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 891)
,08-30 12:31:30.332  6629  6734 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 12:31:30.332  6629  6734 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
08-30 12:31:30.335  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:30.336  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1611dc13 added. We now have 3 listener(s)
08-30 12:31:30.365  1028  1899 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8675 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-30 12:31:30.367  1028  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:31:30.369  8654  8673 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 12:31:30.369  8654  8673 I SystemConfig: existFile = false
08-30 12:31:30.370  8654  8673 I SystemConfig: canReadFile = false
08-30 12:31:30.370  8654  8673 I SystemConfig: systemFeature RCS result false
08-30 12:31:30.370  8654  8673 D SystemConfig: refreshRcsSupport() :false
08-30 12:31:30.370  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:31:30.370  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:30.370  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:30.371  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:30.371  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205aae50 added. We now have 4 listener(s)
08-30 12:31:30.371  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:31:30.372  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:31:30.375  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:30.380  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:30.383  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:30.383  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:30.384  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:31:30.385  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:30.385  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:31:30.385  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:30.385  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:30.386  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:30.386  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:30.386  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:30.386  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1611dc13 removed from the list
08-30 12:31:30.386  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:30.386  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205aae50 removed from the list
08-30 12:31:30.388  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:30.388  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:30.388  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:30.389  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:30.389  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:30.390  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:30.390  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:30.390  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:30.390  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205aae50 not in the list
08-30 12:31:30.390  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:30.390  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:30.391  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:30.391  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:30.391  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:30.391  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205aae50 not in the list
08-30 12:31:30.391  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:30.391  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:30.391  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:30.391  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1611dc13 not in the list
08-30 12:31:30.392  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:30.392  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1489b54e added. We now have 3 listener(s)
08-30 12:31:30.392  1028  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:30.395  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:31:30.395  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:30.395  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:30.396  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:30.396  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c34266f added. We now have 4 listener(s)
08-30 12:31:30.396  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:31:30.396  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:31:30.400  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:30.405  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:31:30.407  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:30.407  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:30.409  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:31:30.409  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:31:30.409  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:31:30.409  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:30.409  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:31:30.409  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:30.411  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:30.415  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 12:31:30.415  1028  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:30.421  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:31:30.422  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:31:30.424  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:31:30.424  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:30.426  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:31:30.426  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:30.426  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:31:30.469  8675  8675 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:31:30.470  8675  8675 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:31:30.470  8675  8675 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:31:30.470  8675  8675 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:31:30.578  8675  8675 I AppConfig: Total System Memory = 2995761152
,08-30 12:31:30.590  8675  8675 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 12:31:30.710  1028  1918 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8697 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:31:30.710  1028  1918 I ActivityManager: Killing 7662:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 12:31:30.738  7918  7918 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 12:31:30.738  7918  7918 W System.err: android.os.DeadObjectException
08-30 12:31:30.738  7918  7918 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:31:30.738  7918  7918 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-30 12:31:30.738  7918  7918 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 12:31:30.738  7918  7918 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 12:31:30.738  7918  7918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:31:30.738  7918  7918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:31:30.738  7918  7918 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:31:30.738  7918  7918 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:31:30.739  7918  7918 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:30.739  7918  7918 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:31:30.739  7918  7918 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:30.739  7918  7918 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:30.739  7918  7918 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:30.739  7918  7918 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:31:30.739  7918  7918 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 12:31:30.739  7918  7918 W System.err: android.os.DeadObjectException
08-30 12:31:30.739  7918  7918 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:31:30.739  7918  7918 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:31:30.739  7918  7918 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 12:31:30.739  7918  7918 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 12:31:30.739  7918  7918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:31:30.739  7918  7918 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:31:30.740  7918  7918 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:31:30.740  7918  7918 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:31:30.740  7918  7918 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:30.740  7918  7918 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:31:30.740  7918  7918 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:30.740  7918  7918 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:30.740  7918  7918 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:30.740  7918  7918 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:31:30.740  7918  7918 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 12:31:30.740  7918  7918 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 12:31:30.843  1028  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_7662/cgroup.procs: No such file or directory
,08-30 12:31:30.844  1028  1043 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 12:31:30.851  7918  7918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 12:31:30.851  7918  7918 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 12:31:30.906  1028  1863 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8715 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:31:30.907  7918  7918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 12:31:30.988  8715  8715 D UEI.SmartControl: Quickset Services start...
,08-30 12:31:30.990  8715  8715 I UEI.SmartControl: Manufacture = LGE
08-30 12:31:30.990  8715  8715 D UEI.SmartControl: Id = LGNevo
08-30 12:31:30.991  8715  8715 D UEI.SmartControl: File observer start...
08-30 12:31:30.992  8715  8715 E UEI.SmartControl: IR Port is disabled: false
08-30 12:31:30.992  8715  8715 D UEI.SmartControl: Starting file observer...
08-30 12:31:30.992  8715  8715 D UEI.SmartControl: Extracting JNI libs...
08-30 12:31:30.993  8715  8715 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 12:31:31.059  8697  8697 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 12:31:31.095  8715  8715 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 12:31:31.095  8715  8715 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 12:31:31.096  8715  8715 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 12:31:31.128  8697  8697 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:31:31.129  8697  8697 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:31.136  8715  8715 I UEI.SmartControl: --- Selecting new region: 6
08-30 12:31:31.138  8715  8715 I UEI.SmartControl: Model = LG-D855
08-30 12:31:31.140  8715  8715 D UEI.SmartControl: QS Service created
,08-30 12:31:31.156  8715  8715 I UEI.SmartControl: Service initServices...
,08-30 12:31:31.161  8715  8715 D UEI.SmartControl: QS start get config
08-30 12:31:31.190  8697  8697 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 12:31:31.218  8697  8697 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:31:31.219  8697  8697 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 12:31:31.221  8715  8715 D UEI.SmartControl: Loading JNI Libs...
08-30 12:31:31.231  8697  8697 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 12:31:31.231  8697  8697 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 12:31:31.244  1028  1044 I ActivityManager: Killing 6854:com.android.settings/1000 (adj 15): empty #17
,08-30 12:31:31.322  1028  1899 W libprocessgroup: failed to open /acct/uid_1000/pid_6854/cgroup.procs: No such file or directory
,08-30 12:31:31.334  3510  3525 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 12:31:31.338  3510  3525 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@104ece14 on behalf of 8697
08-30 12:31:31.348  4601  8752 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 12:31:31.350  8697  8697 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-30 12:31:31.397  1028  1899 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8754 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 12:31:31.425  8697  8697 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 12:31:31.484  8754  8754 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 12:31:31.506  8754  8754 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 12:31:31.506  8754  8754 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 12:31:31.506  8754  8754 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 12:31:31.506  8754  8754 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 12:31:31.506  8754  8754 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 12:31:31.506  8754  8754 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 12:31:31.518  1028  1971 I ActivityManager: Killing 7918:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 12:31:31.626  8715  8715 I UEI.SmartControl: Supports setup maps: true
08-30 12:31:31.630  8715  8715 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 12:31:31.630  8715  8715 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 12:31:31.630  8715  8715 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-30 12:31:31.630  8715  8715 I UEI.SmartControl: ### init IR Blaster...
,08-30 12:31:31.636  1028  1569 W libprocessgroup: failed to open /acct/uid_10112/pid_7918/cgroup.procs: No such file or directory
08-30 12:31:31.636  8715  8715 D serial_port: Configuring serial port
08-30 12:31:31.642  8715  8715 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:31:31.642  8715  8715 I UEI.SmartControl: Setting serial record hearder size = 2
,08-30 12:31:31.642  8715  8715 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:31:31.643  8715  8715 I UEI.SmartControl: Get version...
,08-30 12:31:31.661  8715  8780 D UEI.SmartControl: serial port data available: 21
08-30 12:31:31.688  8715  8715 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 12:31:31.688  8715  8715 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 12:31:31.688  8715  8715 I UEI.SmartControl: QS saving settings...
08-30 12:31:31.688  8715  8715 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 12:31:31.705  8715  8780 D UEI.SmartControl: serial port data available: 4
,08-30 12:31:31.742  8715  8783 I UEI.SmartControl: Device manager: loading config....
08-30 12:31:31.742  8715  8783 D UEI.SmartControl: ----------- loading internal config...
,08-30 12:31:31.750  8715  8715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 12:31:31.754  8715  8715 E UEI.SmartControl: Services init done
08-30 12:31:31.754  8715  8715 D UEI.SmartControl: QS Service init finished
08-30 12:31:31.755  8715  8783 E UEI.SmartControl: Loading SETTINGS...
08-30 12:31:31.756  8715  8715 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:31:31.756  8715  8715 D UEI.SmartControl: QS Service version code: 201091
08-30 12:31:31.758  8715  8715 D UEI.SmartControl: Service requested: Control
,08-30 12:31:31.760  8715  8715 D UEI.SmartControl: Service.onUnbind: IControl
08-30 12:31:31.762  8715  8715 D UEI.SmartControl: Service.onDestroy
08-30 12:31:31.762  8715  8715 D UEI.SmartControl: Lock is in USE false
08-30 12:31:31.762  8715  8715 D UEI.SmartControl: unbind internal service
08-30 12:31:31.763  8715  8715 D serial_port: close(fd = 25)
08-30 12:31:31.766  8715  8715 I UEI.SmartControl: Serial port is closed.
08-30 12:31:31.766  8715  8715 I UEI.SmartControl: Serial port is closed.
08-30 12:31:31.766  8715  8715 D UEI.SmartControl: Blaster closed
08-30 12:31:31.767  8715  8715 D UEI.SmartControl: Shut down QS...
08-30 12:31:31.767  8715  8715 D UEI.SmartControl: Stopping QS lib
08-30 12:31:31.768  8715  8715 D UEI.SmartControl: QS lib stop result = true
08-30 12:31:31.768  8715  8715 D UEI.SmartControl: Stopped QS lib
08-30 12:31:31.768  8715  8715 D UEI.SmartControl: Stopped file observer...
08-30 12:31:31.768  8715  8715 D UEI.SmartControl: QS shutdown complete
08-30 12:31:31.769  8715  8715 D UEI.SmartControl: QS Service created
08-30 12:31:31.771  8715  8782 I UEI.SmartControl: Notify AllClients services are ready: 11
08-30 12:31:31.771  8715  8782 D UEI.SmartControl: -----service ready thread exits
,08-30 12:31:31.773  8715  8783 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 12:31:31.791  8715  8715 I UEI.SmartControl: Service initServices...
08-30 12:31:31.791  8715  8715 D UEI.SmartControl: QS start get config
,08-30 12:31:31.849  1028  1044 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:31:31.878  4601  8752 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 529 ms] updated apps [took 529 ms] 
,08-30 12:31:32.108  8715  8715 I UEI.SmartControl: Supports setup maps: true
,08-30 12:31:32.114  8715  8715 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 12:31:32.114  8715  8715 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:31:32.114  8715  8715 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:31:32.114  8715  8715 I UEI.SmartControl: ### init IR Blaster...
08-30 12:31:32.118  8715  8715 D serial_port: Configuring serial port
08-30 12:31:32.119  8715  8715 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:31:32.119  8715  8715 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:31:32.119  8715  8715 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:31:32.119  8715  8715 I UEI.SmartControl: Get version...
,08-30 12:31:32.138  8715  8789 D UEI.SmartControl: serial port data available: 21
,08-30 12:31:32.164  8715  8715 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 12:31:32.164  8715  8715 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 12:31:32.164  8715  8715 I UEI.SmartControl: QS saving settings...
08-30 12:31:32.167  8715  8715 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 12:31:32.185  8715  8789 D UEI.SmartControl: serial port data available: 4
,08-30 12:31:32.228  8715  8798 I UEI.SmartControl: Device manager: loading config....
,08-30 12:31:32.229  8715  8798 D UEI.SmartControl: ----------- loading internal config...
,08-30 12:31:32.237  8715  8715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 12:31:32.239  8715  8715 E UEI.SmartControl: Services init done
08-30 12:31:32.239  8715  8715 D UEI.SmartControl: QS Service init finished
08-30 12:31:32.240  8715  8715 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:31:32.240  8715  8715 D UEI.SmartControl: QS Service version code: 201091
08-30 12:31:32.242  8715  8715 D UEI.SmartControl: Service requested: Control
08-30 12:31:32.243  8715  8798 E UEI.SmartControl: Loading SETTINGS...
08-30 12:31:32.248  8715  8715 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 12:31:32.255  1028  1900 I ActivityManager: Killing 8360:com.lge.email/u0a23 (adj 15): empty #17
08-30 12:31:32.267  8715  8798 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 12:31:32.298  8715  8797 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:31:32.298  8715  8797 D UEI.SmartControl: -----service ready thread exits
,08-30 12:31:32.318  1028  1938 W libprocessgroup: failed to open /acct/uid_10023/pid_8360/cgroup.procs: No such file or directory
,08-30 12:31:32.330  8715  8715 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3b83b76d that was originally bound here
08-30 12:31:32.330  8715  8715 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3b83b76d that was originally bound here
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:32.330  8715  8715 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 12:31:32.332  8715  8715 D UEI.SmartControl: Internal service binding...
,08-30 12:31:32.763  8715  8785 D UEI.SmartControl: Internal timer expired: 2
,08-30 12:31:33.185  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-620689344] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:33.195  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-620689333] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:31:33.195  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:31:33.428  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:33.428  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:31:33.428  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:31:33.441  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:33.441  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:33.442  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:33.442  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:33.442  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1489b54e removed from the list
08-30 12:31:33.442  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:33.442  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c34266f removed from the list
08-30 12:31:33.443  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:33.443  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:33.445  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:33.445  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:33.449  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:33.449  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:31:33.453  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:33.453  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:33.453  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:33.453  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c34266f not in the list
08-30 12:31:33.453  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:33.453  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:33.457  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:33.457  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:33.457  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:33.457  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:33.457  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:33.457  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c34266f not in the list
08-30 12:31:33.457  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:33.457  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:33.457  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:33.458  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1489b54e not in the list
08-30 12:31:33.458  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:33.459  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86ba8b added. We now have 3 listener(s)
08-30 12:31:33.461  1028  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:33.463  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:31:33.464  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:33.464  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:33.464  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:33.464  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b5f768 added. We now have 4 listener(s)
08-30 12:31:33.464  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:33.468  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:31:33.472  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:33.478  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:33.481  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:33.482  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:33.484  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:33.485  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:33.488  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:31:33.489  6629  6734 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 12:31:33.489  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-30 12:31:33.494  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:31:33.494  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 12:31:33.494  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:31:33.494  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:33.496  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:31:33.497  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:31:33.497  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:31:33.497  6629  6629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:31:33.500  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:31:33.500  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 12:31:33.501  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:33.501  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:31:33.506  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:31:33.508  1028  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:33.515  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:33.518  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:31:33.520  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:31:33.522  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:31:33.522  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:31:33.524  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:31:33.527  6629  8800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:33.529  7982  7997 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-30 12:31:33.531  6629  8800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 12:31:35.987  8715  8726 E UEI.SmartControl: file observer is disposed!
,08-30 12:31:36.218  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-620686313] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:31:36.221  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-620686307] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:31:36.221  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:36.528  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:36.528  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:31:36.528  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 12:31:36.529  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 12:31:36.529  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 12:31:36.529  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,08-30 12:31:36.547  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:36.547  6629  6734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:31:36.548  6629  8800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:31:36.548  6629  8800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:31:36.548  6629  8800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:31:36.549  6629  6629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:31:36.550  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:31:36.550  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:36.550  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:36.552  6629  6629 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:36.552  6629  6629 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 12:31:36.553  6629  6629 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 12:31:36.553  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:36.553  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:36.553  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:36.553  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:36.553  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86ba8b removed from the list
08-30 12:31:36.553  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:36.553  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b5f768 removed from the list
08-30 12:31:36.553  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:36.553  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:36.554  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:36.554  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:36.559  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:36.559  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:36.560  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:36.560  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:36.560  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:36.560  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b5f768 not in the list
08-30 12:31:36.560  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:36.560  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:36.562  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:36.563  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:36.563  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:36.563  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:36.563  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:36.563  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b5f768 not in the list
,08-30 12:31:36.563  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:36.563  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:36.563  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:36.563  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86ba8b not in the list
08-30 12:31:36.564  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:36.564  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a72214 added. We now have 3 listener(s)
08-30 12:31:36.565  1028  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:36.568  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:31:36.568  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:36.568  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:36.568  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:36.568  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1403cabd added. We now have 4 listener(s)
08-30 12:31:36.568  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:36.574  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:31:36.579  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:36.582  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:36.587  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:36.587  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:36.590  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:36.592  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:36.592  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:31:36.592  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:31:36.592  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:31:36.593  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:36.593  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:31:36.597  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:31:36.600  1028  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:36.605  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:31:36.606  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:31:36.608  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:31:36.608  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:36.610  6629  6734 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 12:31:37.226  8715  8799 D UEI.SmartControl: Internal timer expired: 3
,08-30 12:31:37.234  8715  8799 D UEI.SmartControl: unbind internal service
08-30 12:31:37.244  8715  8715 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 12:31:37.254  8715  8715 D UEI.SmartControl: Service.onDestroy
08-30 12:31:37.255  8715  8715 D UEI.SmartControl: Lock is in USE false
08-30 12:31:37.255  8715  8715 D UEI.SmartControl: unbind internal service
08-30 12:31:37.255  8715  8715 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@15494f1c
08-30 12:31:37.255  8715  8715 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 12:31:37.255  8715  8715 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 12:31:37.255  8715  8715 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 12:31:37.255  8715  8715 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 12:31:37.256  8715  8715 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 12:31:37.256  8715  8715 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 12:31:37.256  8715  8715 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 12:31:37.256  8715  8715 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 12:31:37.256  8715  8715 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:37.257  8715  8715 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:37.257  8715  8715 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:31:37.257  8715  8715 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:37.257  8715  8715 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:37.257  8715  8715 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:37.257  8715  8715 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:31:37.257  8715  8715 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@15494f1c
,08-30 12:31:37.262  8715  8715 D serial_port: close(fd = 24)
,08-30 12:31:37.265  8715  8715 I UEI.SmartControl: Serial port is closed.
08-30 12:31:37.266  8715  8715 I UEI.SmartControl: Serial port is closed.
08-30 12:31:37.266  8715  8715 D UEI.SmartControl: Blaster closed
08-30 12:31:37.266  8715  8715 D UEI.SmartControl: Shut down QS...
,08-30 12:31:37.266  8715  8715 D UEI.SmartControl: Stopping QS lib
08-30 12:31:37.266  8715  8715 D UEI.SmartControl: QS lib stop result = true
08-30 12:31:37.266  8715  8715 D UEI.SmartControl: Stopped QS lib
08-30 12:31:37.266  8715  8715 D UEI.SmartControl: QS shutdown complete
08-30 12:31:38.531  1028  1043 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-30 12:31:38.536  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:31:38.536  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-5ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:31:38.536  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 12:31:38.537  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:31:38.537  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:31:38.565  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:31:38 GMT], X-Android-Received-Millis=[1472553098564], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472553098541]}
08-30 12:31:38.565  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:31:38.565  1028  8250 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-30 12:31:38.571  1028  1396 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-30 12:31:38.571  1028  1396 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-30 12:31:38.571  1028  1396 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 12:31:38.572  1028  1396 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 12:31:38.572  1028  1396 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-30 12:31:38.572  1028  1396 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 12:31:38.572  1028  1396 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:38.572  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:31:38.572  1028  1396 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:38.572  1028  1396 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:31:38.573  1582  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 12:31:38.703  1028  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2e390cf type 2 when 221519 android} when 221519
,08-30 12:31:39.244  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-620683284] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:31:39.253  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-620683275] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:31:39.253  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:39.619  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:31:39.620  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:39.620  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:31:39.629  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:39.629  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.629  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:39.629  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:39.630  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a72214 removed from the list
08-30 12:31:39.630  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:39.630  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1403cabd removed from the list
08-30 12:31:39.630  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:39.630  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.631  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.631  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.632  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:39.632  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:39.632  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:39.633  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:39.633  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:39.633  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1403cabd not in the list
08-30 12:31:39.633  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.633  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.634  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:39.634  6629  6734 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:39.634  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:39.634  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:39.634  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:39.635  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1403cabd not in the list
08-30 12:31:39.635  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:39.635  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.635  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.635  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a72214 not in the list
08-30 12:31:39.636  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:39.636  662,9  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a755b9 added. We now have 3 listener(s)
08-30 12:31:39.636  1028  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:31:39.641  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:31:39.641  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:39.641  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:39.641  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:39.641  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23740dfe added. We now have 4 listener(s)
08-30 12:31:39.641  6629  6734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:39.650  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:31:39.655  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:39.661  6629  6734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:31:39.662  6629  6734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:39.662  6629  6734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:39.665  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:39.668  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:39.671  6629  6734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:39.671  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:31:39.671  6629  6734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:31:39.671  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:39.671  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.671  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:31:39.671  6629  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:39.671  6629  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a755b9 removed from the list
08-30 12:31:39.672  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:39.672  6629  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23740dfe removed from the list
,08-30 12:31:39.672  6629  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:39.672  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:39.672  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.673  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.673  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:39.674  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:39.674  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:39.674  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23740dfe not in the list
08-30 12:31:39.674  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.674  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.675  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:39.675  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 12:31:39.675  6629  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:39.675  6629  6734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23740dfe not in the list
,08-30 12:31:39.675  6629  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:39.675  6629  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:39.675  6629  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:39.675  6629  6734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a755b9 not in the list
,08-30 12:31:39.676  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 12:31:39.676  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:31:39.677  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 12:31:39.677  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:31:39.677  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 12:31:39.677  6629  6734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:39.752  1028  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3326aeb type 2 when 222565 com.google.android.gms} when 222565
,08-30 12:31:39.771   312  8802 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:31:39.773   312  8802 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-30 12:31:39.775   312  8802 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 12:31:40.058  2197  8804 D GCM     : Connected
,08-30 12:31:40.095  2197  8804 D GCM     : Message class com.google.e.a.a.q
,08-30 12:31:41.698  6629  8805 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 901, name: My test thread name)
,08-30 12:31:42.273  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-620680256] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:31:42.275  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-620680253] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:31:42.276  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:43.695  6629  6734 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 901
,08-30 12:31:43.695  6629  6734 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 901, name: My test thread name)
,08-30 12:31:43.710  6629  8806 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 902, name: My test thread name)
08-30 12:31:43.711  6629  8806 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 902, thread name: My test thread name)
08-30 12:31:43.711  6629  8806 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 902, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-30 12:31:43.712  6629  6734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:43.717  6629  8807 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: My test thread name)
08-30 12:31:43.718  6629  8807 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 906, thread name: My test thread name): Test exception.
08-30 12:31:43.718  6629  8807 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 12:31:43.723  6629  6734 I jxcore-log: Total number of executed tests:  82
08-30 12:31:43.723  6629  6734 I jxcore-log: 
08-30 12:31:43.723  6629  6734 I jxcore-log: Number of passed tests:  82
08-30 12:31:43.723  6629  6734 I jxcore-log: 
08-30 12:31:43.723  6629  6734 I jxcore-log: Number of failed tests:  0
08-30 12:31:43.723  6629  6734 I jxcore-log: 
08-30 12:31:43.724  6629  6734 I jxcore-log: Number of ignored tests:  0
08-30 12:31:43.724  6629  6734 I jxcore-log: 
08-30 12:31:43.724  6629  6734 I jxcore-log: Total duration:  111714
08-30 12:31:43.724  6629  6734 I jxcore-log: 
08-30 12:31:43.727  6629  6734 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 12:31:43.727  6629  6734 I jxcore-log: 
08-30 12:31:43.728  6629  6734 I jxcore-log: My device name is: LGE-LG-D855
08-30 12:31:43.728  6629  6734 I jxcore-log: 
08-30 12:31:43.743  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.743  6629  6734 I jxcore-log: 
08-30 12:31:43.744  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.744  6629  6734 I jxcore-log: 
08-30 12:31:43.745  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.745  6629  6734 I jxcore-log: 
,08-30 12:31:43.757  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.757  6629  6734 I jxcore-log: 
08-30 12:31:43.758  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.758  6629  6734 I jxcore-log: 
08-30 12:31:43.761  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:43.761  6629  6734 I jxcore-log: 
08-30 12:31:43.763  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.763  6629  6734 I jxcore-log: 
08-30 12:31:43.764  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.764  6629  6734 I jxcore-log: 
08-30 12:31:43.765  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.765  6629  6734 I jxcore-log: 
08-30 12:31:43.766  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.766  6629  6734 I jxcore-log: 
08-30 12:31:43.767  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.767  6629  6734 I jxcore-log: 
08-30 12:31:43.769  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.769  6629  6734 I jxcore-log: 
08-30 12:31:43.770  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.770  6629  6734 I jxcore-log: 
08-30 12:31:43.770  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.770  6629  6734 I jxcore-log: 
,08-30 12:31:43.775  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.775  6629  6734 I jxcore-log: 
08-30 12:31:43.776  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.776  6629  6734 I jxcore-log: 
08-30 12:31:43.777  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.777  6629  6734 I jxcore-log: 
08-30 12:31:43.778  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.778  6629  6734 I jxcore-log: 
08-30 12:31:43.779  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.779  6629  6734 I jxcore-log: 
08-30 12:31:43.780  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.780  6629  6734 I jxcore-log: 
08-30 12:31:43.780  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.780  6629  6734 I jxcore-log: 
08-30 12:31:43.781  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.781  6629  6734 I jxcore-log: 
08-30 12:31:43.782  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.782  6629  6734 I jxcore-log: 
08-30 12:31:43.783  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.783  6629  6734 I jxcore-log: 
08-30 12:31:43.784  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.784  6629  6734 I jxcore-log: 
08-30 12:31:43.785  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.785  6629  6734 I jxcore-log: 
08-30 12:31:43.785  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.785  6629  6734 I jxcore-log: 
08-30 12:31:43.787  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.787  6629  6734 I jxcore-log: 
08-30 12:31:43.788  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:43.788  6629  6734 I jxcore-log: 
08-30 12:31:43.789  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.789  6629  6734 I jxcore-log: 
08-30 12:31:43.790  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:31:43.790  6629  6734 I jxcore-log: 
08-30 12:31:43.791  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":,"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.791  6629  6734 I jxcore-log: 
08-30 12:31:43.791  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.791  6629  6734 I jxcore-log: 
08-30 12:31:43.792  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.792  6629  6734 I jxcore-log: 
08-30 12:31:43.793  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.793  6629  6734 I jxcore-log: 
08-30 12:31:43.794  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.794  6629  6734 I jxcore-log: 
,08-30 12:31:43.800  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.800  6629  6734 I jxcore-log: 
,08-30 12:31:43.802  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.802  6629  6734 I jxcore-log: 
,08-30 12:31:43.802  6629  6734 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:43.802  6629  6734 I jxcore-log: 
08-30 12:31:43.845  6629  8805 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 901, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,08-30 12:31:44.038  8808  8808 D AndroidRuntime: 
08-30 12:31:44.038  8808  8808 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:31:44.041  8808  8808 D AndroidRuntime: CheckJNI is OFF
,08-30 12:31:44.169  8808  8808 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:31:44.178  1028  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-30 12:31:44.179  1028  1095 I ActivityManager: Killing 6629:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 12:31:44.214  1028  1899 I WindowState: WIN DEATH: Window{2b87d15d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:31:44.217  1028  1382 D WifiService: Client connection lost with reason: 4
,08-30 12:31:44.222  1028  1899 D InputDispatcher: Window went away: Window{2b87d15d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:31:44.297  1028  1095 I ActivityManager:   Force finishing activity ActivityRecord{159326d4 u0 com.test.thalitest/.MainActivity t6}
,08-30 12:31:44.321   341   417 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 12:31:44.327  1028  1763 W ActivityManager: Spurious death for ProcessRecord{15cd5048 6629:com.test.thalitest/u0a118}, curProc for 6629: null
,08-30 12:31:44.328  1028  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 12:31:44.331  1028  1116 I ActivityManager:   Force finishing activity ActivityRecord{159326d4 u0 com.test.thalitest/.MainActivity t6 f}
08-30 12:31:44.331  1028  1116 W ActivityManager: Duplicate finish request for ActivityRecord{159326d4 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 12:31:44.371  2011  2011 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 12:31:44.371  1919  2548 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 12:31:44.372  1919  2548 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23915372 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 12:31:44.373  2011  2011 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 12:31:44.374  1919  1935 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 12:31:44.374  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 12:31:44.374  1919  1935 D SplitWindowPolicy: topRunningActivity=ActivityInfo{287973c3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 12:31:44.374  2011  2082 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 12:31:44.379  1882  1882 D ActionManagerService: notifyUserLog: 1000003
08-30 12:31:44.380  2011  2011 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-30 12:31:44.381  3841  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 12:31:44.383  1582  1582 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 12:31:44.384  4601  4601 I art     : Explicit concurrent mark sweep GC freed 15410(882KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 572us total 44.296ms
08-30 12:31:44.387  1028  1093 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 12:31:44.388  1028  1358 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 12:31:44.401  2482  2698 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 12:31:44.403  3841  3841 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 12:31:44.403  1973  1973 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 12:31:44.405  7982  7982 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 12:31:44.405  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 12:31:44.409  2011  2011 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 12:31:44.411  8233  8233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 12:31:44.415  4499  4499 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 12:31:44.415  4499  4499 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 12:31:44.415  4499  4499 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 12:31:44.415  4499  4499 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 12:31:44.415  4499  4499 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:31:44.415  4499  4499 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:31:44.415  4499  4499 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:44.415  4499  4499 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-30 12:31:44.415  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:44.415  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:44.415  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:44.415  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:31:44.440  1028  1900 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:31:44.473  2011  2011 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-30 12:31:44.479  1794  1794 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 12:31:44.479  2011  2011 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 12:31:44.483  1582  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:31:44.483  1582  1638 D KeyguardModel: createShortcutInfo...
08-30 12:31:44.484  1882  1882 D ActionManagerService: notifyUserLog: 1000004
08-30 12:31:44.484  1582  1582 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 12:31:44.484  3841  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 12:31:44.484  2011  2011 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-30 12:31:44.489  3841  4484 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:31:44.495  1582  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:31:44.495  1582  1638 D KeyguardModel: createShortcutInfo...
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , expire_time: 0
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , display: false
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , animation: false }
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , expire_time: 0
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , display: false
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , animation: false }
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , expire_time: 0
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , display: false
08-30 12:31:44.506  2011  2011 I GBoardWebViewUtils: , animation: false }
,08-30 12:31:44.513  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 12:31:44.516  1582  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:31:44.517  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:31:44.517  2011  8838 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 12:31:44.518  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:31:44.519  1582  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:31:44.519  1582  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-30 12:31:44.525  1582  1582 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 12:31:44.525  1582  1582 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 12:31:44.526  1582  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:31:44.526  1028  1028 I art     : Explicit concurrent mark sweep GC freed 47320(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.853ms total 166.621ms
08-30 12:31:44.526  1582  1638 D KeyguardModel: createShortcutInfo...
08-30 12:31:44.528  1028  2010 I art     : WaitForGcToComplete blocked for 42.444ms for cause Explicit
08-30 12:31:44.530  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 12:31:44.530  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:31:44.536  1582  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:31:44.536  1582  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 12:31:44.543  1582  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:31:44.543  1582  1638 D KeyguardModel: createShortcutInfo...
,08-30 12:31:44.545  1846  1846 D SplitUIManager: split_name #11 / not available #0
08-30 12:31:44.546  1846  1846 D SplitUIService: removed split : 
08-30 12:31:44.560  1582  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:31:44.560  1582  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:31:44.560  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:31:44.560  1582  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:31:44.567  1582  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:31:44.567  1582  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:31:44.576  1582  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:31:44.576  1582  1638 D KeyguardModel: createShortcutInfo...
,08-30 12:31:44.589  1028  1028 D administrator: Handling package changes for user 0
,08-30 12:31:44.592  1582  1582 D KeyguardModel: handleShortcutListChanged...
08-30 12:31:44.592  1582  1582 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 12:31:44.594  1846  1846 D SplitUIManager: split_name #11 / not available #0
08-30 12:31:44.594  1846  1846 I SplitUIService: split app #11
08-30 12:31:44.599  1582  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:31:44.599  1582  1638 D KeyguardModel: createShortcutInfo...
08-30 12:31:44.608  1582  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:31:44.609  1582  1638 D KeyguardModel: createShortcutInfo...
,08-30 12:31:44.612  1582  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:31:44.612  1582  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 12:31:44.614  1582  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:31:44.614  1582  1638 D KeyguardModel: createShortcutInfo...
08-30 12:31:44.616  1582  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:31:44.616  1582  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 12:31:44.618  1582  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:31:44.618  1582  1638 D KeyguardModel: createShortcutInfo...
08-30 12:31:44.621  1582  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:31:44.622  1582  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:31:44.640  1582  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:31:44.640  1582  1638 D KeyguardModel: createShortcutInfo...
,08-30 12:31:44.644  1582  1582 D KeyguardModel: handleShortcutListChanged...
,08-30 12:31:44.644  1582  1582 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 12:31:44.649  1028  1938 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:31:44.649  1028  1938 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:31:44.693  1028  2010 I art     : Explicit concurrent mark sweep GC freed 4341(245KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.909ms total 165.033ms
08-30 12:31:44.693  1028  1116 I art     : WaitForGcToComplete blocked for 189.361ms for cause Explicit
,08-30 12:31:44.708  2011  2011 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 12:31:44.715  1028  1043 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:31:44.726  2197  2197 I ConfigService: onCreate
08-30 12:31:44.726  2197  2197 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 12:31:44.727  1028  1578 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 12:31:44.727  1794  1794 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:31:44.727  7982  7982 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:31:44.732  2197  2197 I ConfigService: onBind returning update interface
08-30 12:31:44.733  2197  2197 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 12:31:44.733  2197  2197 I ConfigService: onBind returning config service
,08-30 12:31:44.749  2197  2197 I ConfigService: onDestroy
,08-30 12:31:44.753  1794  8844 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 12:31:44.766  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 12:31:44.769  2011  2011 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 12:31:44.778  5913  8849 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 12:31:44.790  1794  8851 I PeopleContactsSync: CP2 sync disabled
,08-30 12:31:44.792  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 12:31:44.792  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:31:44.792  1028  1028 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 12:31:44.794  1028  1555 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 12:31:44.796  1794  4775 I Icing   : doRemovePackageData com.test.thalitest
08-30 12:31:44.815  1794  8850 W GmsApplication: Using Auth Proxy for data requests.
,08-30 12:31:44.821  1794  8850 W GmsApplication: Using Auth Proxy for data requests.
08-30 12:31:44.837  7029  7029 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 12:31:44.854   329   400 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 12:31:44.855  3194  8854 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 12:31:44.864  2337  8855 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 12:31:44.881  1028  1116 I art     : Explicit concurrent mark sweep GC freed 10190(739KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.790ms total 184.907ms
,08-30 12:31:44.884  2011  2011 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 12:31:44.887  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:31:44.889  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 12:31:44.890  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 12:31:44.890  1028  1938 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8856 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 12:31:44.891  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 12:31:44.892  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 12:31:44.903   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 216us total 13.333ms
08-30 12:31:44.909  1028  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3adc9e6c u0 com.lge.launcher2/.Launcher t5} time:227742
,08-30 12:31:44.911  2011  2011 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 12:31:44.911  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:31:44.914   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.616ms
08-30 12:31:44.916  2011  2129 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 12:31:44.916  2011  2129 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-30 12:31:44.924   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.298ms
,08-30 12:31:44.929  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 12:31:44.930  2011  2011 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 12:31:44.930  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:31:44.934  8856  8856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:31:44.934  8856  8856 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:31:44.935  8856  8856 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:31:44.935  8856  8856 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:31:44.938  2011  2011 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 12:31:44.939  2558  2558 D [Concierge]Service: onStartCommand(). Type : 8
08-30 12:31:44.939  2558  2558 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 12:31:44.939  2558  2558 D [Concierge]Service: Update widget ID : 11
08-30 12:31:44.941  2011  2011 D [Concierge]WidgetView: change position of spinner
08-30 12:31:44.942  2558  2558 D [Concierge]Service: onStartCommand(). Type : 0
08-30 12:31:44.943  2011  2011 I [Concierge]WidgetView: initWebView(). Time : 1472553104942
08-30 12:31:44.954  2011  2011 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 215987692
08-30 12:31:44.954  2011  2011 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 12:31:44.954  2011  2011 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 12:31:44.957  2011  2011 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1e859679
08-30 12:31:44.957  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 12:31:44.960  2011  2011 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 12:31:44.960  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:31:44.963  1794  8846 I art     : Explicit concurrent mark sweep GC freed 38773(2MB) AllocSpace objects, 27(432KB) LOS objects, 51% free, 30MB/62MB, paused 923us total 29.755ms
08-30 12:31:44.965  1794  1806 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 12:31:44.965  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 12:31:44.965  2011  2011 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 12:31:44.965  1794  1806 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 12:31:44.965  2011  2011 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 12:31:44.965  2011  2011 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472552904534, New one : 1472553104942
08-30 12:31:44.966  2011  2011 D [Concierge]WidgetView: Unregister all receivers
08-30 12:31:44.966  1794  1806 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 12:31:44.966  2011  2011 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 12:31:44.967  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:31:44.969  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 12:31:44.970  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 12:31:44.971  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 12:31:44.972  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 12:31:44.973  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 12:31:44.976  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:31:44.977  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 12:31:44.988  1028  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:31:44.992  1028  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 12:31:45.009  8808  8808 D AndroidRuntime: Shutting down VM
,08-30 12:31:45.034  2011  2011 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 12:31:45.040  1028  1116 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8876 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 12:31:45.042  2011  2011 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 12:31:45.042  2011  2011 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 12:31:45.043  8856  8856 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 12:31:45.045  2011  2011 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 12:31:45.046  2011  2011 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 12:31:45.053  8856  8856 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 12:31:45.062  2011  2011 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11460661 time:227896
,08-30 12:31:45.082  8856  8856 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:31:45.093  1028  1578 I ActivityManager: Killing 8162:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 12:31:45.101  8856  8856 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:31:45.101  8856  8856 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:31:45.166  1028  1043 W libprocessgroup: failed to open /acct/uid_10026/pid_8162/cgroup.procs: No such file or directory
,08-30 12:31:45.173  2011  2011 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 12:31:45.197  8856  8856 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 12:31:45.206  1028  1900 I ActivityManager: Killing 8428:com.android.chrome/u0a57 (adj 15): empty #17
08-30 12:31:45.213  2011  2852 I GBoardtInterface: onReloaded()
,08-30 12:31:45.216  2011  2011 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-30 12:31:45.288  1973  1973 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 12:31:45.288  1973  1973 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-30 12:31:45.289  1973  1973 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-30 12:31:45.290  3841  4484 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:31:45.291  1028  1569 W libprocessgroup: failed to open /acct/uid_10057/pid_8428/cgroup.procs: No such file or directory
08-30 12:31:45.294  3841  3857 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:31:45.294  8233  8233 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 12:31:45.300  1028  1368 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-620677228] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:45.301  1028  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-620677227] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:31:45.301  1028  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:31:45.327  1028  1863 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8901 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 12:31:45.328  1882  1882 D ActionManagerService: notifyUserLog: 1000001
,08-30 12:31:45.330  3841  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 12:31:45.330  3841  4488 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 12:31:45.332  1882  1882 D ActionManagerService: notifyUserLog: 1000001
08-30 12:31:45.333  3841  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 12:31:45.333  3841  4488 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 12:31:45.333  3841  4488 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 12:31:45.333  3841  4488 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 12:31:45.334  3841  4484 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:31:45.336  2011  2011 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 12:31:45.336  2011  2011 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 12:31:45.338  2011  2011 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 12:31:45.338  2011  2011 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 12:31:45.339  2011  2011 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 12:31:45.339  2011  2011 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-30 12:31:45.379  8901  8901 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:31:45.379  8901  8901 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
