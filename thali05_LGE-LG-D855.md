#### Test 75789268a387c77_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-28 12:17:56.381  5622  5622 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:17:56.382  5622  5622 W System.err: android.os.DeadObjectException
07-28 12:17:56.382  5622  5622 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:17:56.382  5622  5622 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:17:56.382  5622  5622 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:17:56.382  5622  5622 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:17:56.382  5622  5622 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:17:56.382  5622  5622 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:17:56.383  5622  5622 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:17:56.383  5622  5622 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:17:56.383  5622  5622 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 12:17:56.383  5622  5622 W System.err: android.os.DeadObjectException
07-28 12:17:56.383  5622  5622 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:17:56.383  5622  5622 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:17:56.383  5622  5622 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:17:56.383  5622  5622 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:17:56.383  5622  5622 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:17:56.384  5622  5622 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:17:56.384  5622  5622 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:17:56.384  5622  5622 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:17:56.384  5622  5622 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:17:56.384  5622  5622 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:17:56.384  5622  5622 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:17:56.384  5622  5622 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:17:56.384  5622  5622 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:17:56.384  5622  5622 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:17:56.384  5622  5622 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:17:56.384  5622  5622 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
--------- beginning of system
07-28 12:17:56.499  1037  1873 W libprocessgroup: failed to open /acct/uid_1000/pid_5644/cgroup.procs: No such file or directory
07-28 12:17:56.500  1037  1873 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-28 12:17:56.505  5622  5622 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:17:56.506  5622  5622 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:17:56.553  1037  2037 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6521 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:17:56.554  5622  5622 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:17:56.633  6521  6521 D UEI.SmartControl: Quickset Services start...
07-28 12:17:56.636  6521  6521 I UEI.SmartControl: Manufacture = LGE
07-28 12:17:56.637  6521  6521 D UEI.SmartControl: Id = LGNevo
07-28 12:17:56.638  6521  6521 D UEI.SmartControl: File observer start...
07-28 12:17:56.639  6521  6521 E UEI.SmartControl: IR Port is disabled: false
07-28 12:17:56.640  6521  6521 D UEI.SmartControl: Starting file observer...
07-28 12:17:56.640  6521  6521 D UEI.SmartControl: Extracting JNI libs...
07-28 12:17:56.641  6521  6521 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-28 12:17:56.720  6521  6521 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 12:17:56.720  6521  6521 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 12:17:56.720  6521  6521 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-28 12:17:56.748  6521  6521 I UEI.SmartControl: --- Selecting new region: 6
07-28 12:17:56.750  6521  6521 I UEI.SmartControl: Model = LG-D855
07-28 12:17:56.751  6521  6521 D UEI.SmartControl: QS Service created
07-28 12:17:56.763  6521  6521 I UEI.SmartControl: Service initServices...
07-28 12:17:56.766  6521  6521 D UEI.SmartControl: QS start get config
07-28 12:17:56.796  6521  6521 D UEI.SmartControl: Loading JNI Libs...
07-28 12:17:56.942   326   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 12:17:56.942  3175  6544 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:17:57.034  6521  6521 I UEI.SmartControl: Supports setup maps: true
07-28 12:17:57.037  6521  6521 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:17:57.037  6521  6521 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:17:57.037  6521  6521 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:17:57.037  6521  6521 I UEI.SmartControl: ### init IR Blaster...
07-28 12:17:57.044  6521  6521 D serial_port: Configuring serial port
07-28 12:17:57.064  6521  6521 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:17:57.064  6521  6521 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:17:57.065  6521  6521 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:17:57.065  6521  6521 I UEI.SmartControl: Get version...
07-28 12:17:57.083  6521  6545 D UEI.SmartControl: serial port data available: 21
07-28 12:17:57.114  6521  6521 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:17:57.114  6521  6521 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:17:57.114  6521  6521 I UEI.SmartControl: QS saving settings...
07-28 12:17:57.116  6521  6521 D UEI.SmartControl: IR Blaster version: 25672567
07-28 12:17:57.120  1803  4766 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-28 12:17:57.134  6521  6545 D UEI.SmartControl: serial port data available: 4
07-28 12:17:57.165  6521  6549 I UEI.SmartControl: Device manager: loading config....
07-28 12:17:57.165  6521  6549 D UEI.SmartControl: ----------- loading internal config...
07-28 12:17:57.165  6521  6521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:17:57.167  6521  6521 E UEI.SmartControl: Services init done
07-28 12:17:57.167  6521  6521 D UEI.SmartControl: QS Service init finished
07-28 12:17:57.169  6521  6521 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:17:57.169  6521  6521 D UEI.SmartControl: QS Service version code: 201091
07-28 12:17:57.170  6521  6521 D UEI.SmartControl: Service requested: Control
07-28 12:17:57.173  6521  6549 E UEI.SmartControl: Loading SETTINGS...
07-28 12:17:57.175  6521  6521 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:17:57.176  1803  4766 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-28 12:17:57.177  5622  5622 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:17:57.177  6521  6537 I UEI.SmartControl: ------ IControl API: 11
07-28 12:17:57.178  6521  6537 I UEI.SmartControl: Registering callback...
07-28 12:17:57.181  1037  1053 I ActivityManager: Killing 5470:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 12:17:57.181  6521  6537 I UEI.SmartControl: ------ IControl API: 19
07-28 12:17:57.182  6521  6537 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:17:57.185  6521  6549 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:17:57.203  6521  6548 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:17:57.204  5622  5638 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:17:57.204  5622  5641 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:17:57.204  5622  5641 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 12:17:57.205  5622  5622 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:17:57.205  6521  6548 D UEI.SmartControl: -----service ready thread exits
07-28 12:17:57.205  5622  5622 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 12:17:57.205  6521  6536 I UEI.SmartControl: ------ IControl API: 8
07-28 12:17:57.206  5622  5622 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:17:57.206  5622  5622 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:17:57.206  5622  5622 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:17:57.207  5622  5622 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:17:57.208  5622  5622 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 12:17:57.208  5622  5622 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 12:17:57.243  6521  6521 D UEI.SmartControl: Internal service binding...
07-28 12:17:57.246  1037  1891 W libprocessgroup: failed to open /acct/uid_10005/pid_5470/cgroup.procs: No such file or directory
07-28 12:17:57.252  5622  5622 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-28 12:17:57.275  1803  4766 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,07-28 12:17:57.714  6551  6551 D AndroidRuntime: 
07-28 12:17:57.714  6551  6551 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:17:57.719  6551  6551 D AndroidRuntime: CheckJNI is OFF
07-28 12:17:57.779  6495  6495 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:17:57.779  6495  6495 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:17:57.902  6109  6109 I LockScreenSettings: New app installed broadcast received ..
07-28 12:17:57.904  6109  6109 I LockScreenSettings: Number of installed packages  1
07-28 12:17:57.912  6551  6551 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:17:57.917  1037  2037 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:17:57.926  1929  2558 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-28 12:17:57.927  6495  6495 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-28 12:17:57.933  1037  2037 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-28 12:17:57.938  1037  2037 D ActivityManager: setTaskToReturnTo : TaskRecord{37e417fa #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:17:57.938  1037  2037 D ActivityManager: setTaskToReturnTo : TaskRecord{37e417fa #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:17:57.939  1037  2037 D WindowStateEx: AppWindowTokenEx init.. 
07-28 12:17:57.939   341   353 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:17:57.956  1037  1562 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:17:57.979  1037  2037 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6577 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:17:57.980  6551  6551 D AndroidRuntime: Shutting down VM
07-28 12:17:58.032  1037  1872 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6594 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:17:58.072  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-28 12:17:58.073  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13da08d8 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:17:58.074  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-28 12:17:58.075  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1197c431 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:17:58.132  6594  6594 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-28 12:17:58.132  6594  6594 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-28 12:17:58.185  1037  1872 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6615 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-28 12:17:58.186  1037  1872 I ActivityManager: Killing 5622:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 12:17:58.242  1037  1685 W libprocessgroup: failed to open /acct/uid_10112/pid_5622/cgroup.procs: No such file or directory
07-28 12:17:58.249  6577  6577 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-28 12:17:58.294  6615  6615 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-28 12:17:58.312  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-28 12:17:58.312  6615  6615 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:17:58.330  6371  6371 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-28 12:17:58.366  1037  1983 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6635 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-28 12:17:58.367  1037  1983 I ActivityManager: Killing 5848:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 12:17:58.387  6577  6577 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-28 12:17:58.473  1037  1872 W libprocessgroup: failed to open /acct/uid_10072/pid_5848/cgroup.procs: No such file or directory
07-28 12:17:58.484  6577  6577 I LibraryLoader: Loading: webviewchromium
07-28 12:17:58.488  6577  6577 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 871-876)
07-28 12:17:58.488  6577  6577 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:17:58.514  6635  6635 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:17:58.526  6577  6577 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e3c7c46}
07-28 12:17:58.530  6577  6577 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:17:58.531  6577  6577 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:17:58.538  6635  6635 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 12:17:58.555  6577  6577 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:17:58.556  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:17:58.563  6635  6635 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-28 12:17:58.563  6635  6635 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:17:58.563  6635  6635 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:17:58.563  6635  6635 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:17:58.564  6635  6635 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 12:17:58.565  6635  6635 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 12:17:58.566  1037  1100 W ActivityManager: Activity pause timeout for ActivityRecord{10c891ab u0 com.test.thalitest/.MainActivity t40}
07-28 12:17:58.568  6635  6635 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 12:17:58.574   316  2125 V AudioPolicyService: registerClient() client 0xb0410180, uid 10118
07-28 12:17:58.575  6577  6577 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:17:58.576  6635  6635 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:17:58.576  6577  6577 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-28 12:17:58.577  6577  6577 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-28 12:17:58.578  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:17:58.578  6635  6635 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 12:17:58.586  1037  1119 D BluetoothManagerService: Message: 20
07-28 12:17:58.586  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1871b67f:true
07-28 12:17:58.616  6577  6577 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:17:58.616  6577  6577 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:17:58.616  6577  6577 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:17:58.616  6577  6577 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:17:58.616  6577  6577 I Adreno-EGL: Remote Branch: 
07-28 12:17:58.616  6577  6577 I Adreno-EGL: Local Patches: 
07-28 12:17:58.616  6577  6577 I Adreno-EGL: Reconstruct Branch: 
07-28 12:17:58.619  6635  6635 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:17:58.619  6635  6635 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:17:58.625  6635  6635 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:17:58.626  6635  6635 V SoundPool: load: fd=27, offset=10857164, length=17813, priority=1
07-28 12:17:58.626  6635  6635 V SoundPool: create sampleID=1, fd=28, offset=17813 length=10857164
07-28 12:17:58.626  6635  6635 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:17:58.626  6635  6635 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:17:58.629  6635  6668 V SoundPool: Start decode
07-28 12:17:58.629  6635  6668 V MediaPlayer[Native]: decode(28, 10857164, 17813)
07-28 12:17:58.629  6635  6635 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:17:58.631   316   316 V MediaPlayerService: decode(23, 10857164, 17813)
07-28 12:17:58.631   316   316 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 12:17:58.631   316   316 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:17:58.631   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 12:17:58.631   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:17:58.631   316   316 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:17:58.631   316   316 V MediaPlayerService: player type = 3
07-28 12:17:58.631   316   316 V AwesomePlayer: AwesomePlayer create()
07-28 12:17:58.632   316   316 V AwesomePlayer: reset_l() 
07-28 12:17:58.632   316   316 V AwesomePlayer: cancelPlayerEvents
07-28 12:17:58.632   316   316 V AwesomePlayer: setAudioSink() 
07-28 12:17:58.632   316   316 V AwesomePlayer: reset_l() 
07-28 12:17:58.632   316   316 V AudioCache: notify(0xb1432340, 8, 0, 0)
07-28 12:17:58.632   316   316 V AudioCache: ignored
07-28 12:17:58.632   316   316 V AwesomePlayer: cancelPlayerEvents
07-28 12:17:58.632   316   316 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 12:17:58.632   316   316 V AwesomePlayer: setDataSource_l dataSource
07-28 12:17:58.632   316   316 V LGParserOSAL: SniffLGParser start
07-28 12:17:58.632   316   316 V LGParserOSAL: MainType:5, SubType=0
07-28 12:17:58.632   316   316 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:17:58.632   316   316 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 12:17:58.632   316   316 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:17:58.637  1590  1590 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 12:17:58.637  1590  1590 I [SystemUI]LGPowerUI: On Skip Timer : true
07-28 12:17:58.638  6635  6635 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:17:58.639  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:17:58.649  1590  1590 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
07-28 12:17:58.649  1590  1590 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:17:58.650  1929  2059 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-28 12:17:58.650  1929  2059 D LEDHandler: Battery Level Remaining: 100%
07-28 12:17:58.650  1929  2059 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
07-28 12:17:58.650  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:17:58.650  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:17:58.651  1037  1531 D WifiController: battery changed pluggedType: 2
07-28 12:17:58.651  1590  1590 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:17:58.654  6615  6615 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:17:58.655  3893  4013 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:17:58.660  6635  6635 V LGMDMManager: Create singleton instance
07-28 12:17:58.670   316   316 V LGParserOSAL: supported mime: application/ogg
07-28 12:17:58.670   316   316 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:17:58.671   316   316 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:17:58.671   316   316 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:17:58.671   316   316 V AwesomePlayer: AudioTrack Setting
07-28 12:17:58.671   316   316 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:17:58.671   316   316 V AwesomePlayer: setAudioSource() 
07-28 12:17:58.671   316   316 V MediaPlayerService: prepare
07-28 12:17:58.671   316   316 V AwesomePlayer: prepareAsync_l() 
07-28 12:17:58.671   316   316 V MediaPlayerService: wait for prepare
07-28 12:17:58.671   316  6669 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:17:58.671   316  6669 V AwesomePlayer: initAudioDecoder() 
07-28 12:17:58.671   316  6669 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:17:58.671   316  6669 V AudioSystem: isOffloadSupported()
07-28 12:17:58.671   316  6669 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:17:58.671   316  6669 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:17:58.671   316  6669 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:17:58.671   316  6669 V AwesomePlayer: getUseOffload() = 0 
07-28 12:17:58.671   316  6669 V OMXCodec: OMXCodec::Create
07-28 12:17:58.671   316  6669 V OMXCodec: findMatchingCodecs()
07-28 12:17:58.671   316  6669 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:17:58.671   316  6669 V OMXCodec: matchingCodecs.size()=1
07-28 12:17:58.671   316  6669 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 12:17:58.673   316  6669 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 12:17:58.673   316  6669 V LGCodecAdapter: LG Codec Adapter start
07-28 12:17:58.673   316  6669 V OMXCodec: OMXCodec Createtor
07-28 12:17:58.673   316  6669 V OMXCodec: setComponentRole
07-28 12:17:58.673   316  6669 V OMXCodec: configureCodec protected=0
07-28 12:17:58.673   316  6669 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:17:58.673   316  6669 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:17:58.673   316  6669 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:17:58.673   316  6669 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:17:58.673   316  6669 V LGCodecOSAL: Not support LGCodec
07-28 12:17:58.673   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:17:58.673   316  6669 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:17:58.673   316  6669 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 12:17:58.673   316  6669 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:17:58.674   316  6669 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:17:58.674   316  6669 V AudioSystem: isOffloadSupported()
07-28 12:17:58.674   316  6669 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:17:58.674   316  6669 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:17:58.674   316  6669 V OMXCodec: init()
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 12:17:58.674   316  6669 V OMXCodec: allocateBuffers
07-28 12:17:58.674   316  6669 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
07-28 12:17:58.674   316  6669 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd30 on output port
07-28 12:17:58.674   316  6669 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1787330 on output port
07-28 12:17:58.674   316  6669 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:17:58.674   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:17:58.674   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:17:58.674   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 12:17:58.674   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 12:17:58.674   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:17:58.674   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:17:58.674   316  6669 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 12:17:58.674   316  6669 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:17:58.674   316  6669 V AudioCache: notify(0xb1432340, 5, 0, 0)
07-28 12:17:58.674   316  6669 V AudioCache: ignored
07-28 12:17:58.674   316  6669 V AudioCache: notify(0xb1432340, 1, 0, 0)
07-28 12:17:58.674   316  6669 V AudioCache: prepared
07-28 12:17:58.674   316   316 V AudioCache: wait - success
07-28 12:17:58.674   316   316 V MediaPlayerService: start
07-28 12:17:58.674   316   316 V AwesomePlayer: play_l() 
07-28 12:17:58.674   316   316 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:17:58.674   316   316 V AwesomePlayer: createAudioPlayer_l
07-28 12:17:58.675   316   316 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:17:58.675   316   316 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:17:58.675   316   316 D AudioPlayer: start of Playback, useOffload 0
07-28 12:17:58.675   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:17:58.675   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049136
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977461040
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 12:17:58.676   316  6671 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:17:58.676   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:17:58.677   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd30 on output port
07-28 12:17:58.677   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:17:58.677   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
07-28 12:17:58.677   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on output port
07-28 12:17:58.677   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 12:17:58.677   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 12:17:58.677   316   316 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:17:58.677   316   316 V AudioCache: notify(0xb1432340, 6, 0, 0)
07-28 12:17:58.677   316   316 V AudioCache: ignored
07-28 12:17:58.677   316   316 V MediaPlayerService: wait for playback complete
07-28 12:17:58.678   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.678   316  6672 V AudioCache: memcpy(0xaf004000, 0xb57be000, 4096)
07-28 12:17:58.678   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.678   316  6672 V AudioCache: memcpy(0xaf005000, 0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: memcpy(0xaf006000, 0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: memcpy(0xaf007000, 0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: memcpy(0xaf008000, 0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: memcpy(0xaf009000, 0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.679   316  6672 V AudioCache: memcpy(0xaf00a000, 0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: memcpy(0xaf00b000, 0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: memcpy(0xaf00c000, 0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: memcpy(0xaf00d000, 0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.680   316  6672 V AudioCache: memcpy(0xaf00e000, 0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: memcpy(0xaf00f000, 0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: memcpy(0xaf010000, 0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: memcpy(0xaf011000, 0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: memcpy(0xaf012000, 0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.681   316  6672 V AudioCache: memcpy(0xaf013000, 0xb57be000, 4096)
07-28 12:17:58.682   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.682   316  6672 V AudioCache: memcpy(0xaf014000, 0xb57be000, 4096)
07-28 12:17:58.682   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.682   316  6672 V AudioCache: memcpy(0xaf015000, 0xb57be000, 4096)
07-28 12:17:58.683   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.683   316  6672 V AudioCache: memcpy(0xaf016000, 0xb57be000, 4096)
07-28 12:17:58.683   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.683   316  6672 V AudioCache: memcpy(0xaf017000, 0xb57be000, 4096)
07-28 12:17:58.684   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.684   316  6672 V AudioCache: memcpy(0xaf018000, 0xb57be000, 4096)
07-28 12:17:58.684   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.684   316  6672 V AudioCache: memcpy(0xaf019000, 0xb57be000, 4096)
07-28 12:17:58.685   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.685   316  6672 V AudioCache: memcpy(0xaf01a000, 0xb57be000, 4096)
07-28 12:17:58.685   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.685   316  6672 V AudioCache: memcpy(0xaf01b000, 0xb57be000, 4096)
07-28 12:17:58.685   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.686   316  6672 V AudioCache: memcpy(0xaf01c000, 0xb57be000, 4096)
07-28 12:17:58.686   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.686   316  6672 V AudioCache: memcpy(0xaf01d000, 0xb57be000, 4096)
07-28 12:17:58.687   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.687   316  6672 V AudioCache: memcpy(0xaf01e000, 0xb57be000, 4096)
07-28 12:17:58.687   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.687   316  6672 V AudioCache: memcpy(0xaf01f000, 0xb57be000, 4096)
07-28 12:17:58.687   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.687   316  6672 V AudioCache: memcpy(0xaf020000, 0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: memcpy(0xaf021000, 0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: memcpy(0xaf022000, 0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: memcpy(0xaf023000, 0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.688   316  6672 V AudioCache: memcpy(0xaf024000, 0xb57be000, 4096)
07-28 12:17:58.689   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.689   316  6672 V AudioCache: memcpy(0xaf025000, 0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: memcpy(0xaf026000, 0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: memcpy(0xaf027000, 0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: memcpy(0xaf028000, 0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.690   316  6672 V AudioCache: memcpy(0xaf029000, 0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: memcpy(0xaf02a000, 0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: memcpy(0xaf02b000, 0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: memcpy(0xaf02c000, 0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.692   316  6672 V AudioCache: memcpy(0xaf02d000, 0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: memcpy(0xaf02e000, 0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: memcpy(0xaf02f000, 0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: memcpy(0xaf030000, 0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.694   316  6672 V AudioCache: memcpy(0xaf031000, 0xb57be000, 4096)
07-28 12:17:58.695   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.695   316  6672 V AudioCache: memcpy(0xaf032000, 0xb57be000, 4096)
07-28 12:17:58.695   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.695   316  6672 V AudioCache: memcpy(0xaf033000, 0xb57be000, 4096)
07-28 12:17:58.695   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.695   316  6672 V AudioCache: memcpy(0xaf034000, 0xb57be000, 4096)
07-28 12:17:58.696   316  6672 V AudioCache: write(0xb57be000, 4096)
07-28 12:17:58.696   316  6672 V AudioCache: memcpy(0xaf035000, 0xb57be000, 4096)
07-28 12:17:58.696   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:17:58.696   316  6672 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:17:58.696   316  6672 V AwesomePlayer: postAudioEOS() 
07-28 12:17:58.696   316  6672 V AudioCache: write(0xb57be000, 280)
07-28 12:17:58.696   316  6672 V AudioCache: memcpy(0xaf036000, 0xb57be000, 280)
07-28 12:17:58.698   316  6669 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:17:58.698   316  6669 V AwesomePlayer: onStreamDone
07-28 12:17:58.698   316  6669 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:17:58.698   316  6669 V AudioCache: notify(0xb1432340, 2, 0, 0)
07-28 12:17:58.698   316  6669 V AudioCache: playback complete
07-28 12:17:58.698   316  6669 V AwesomePlayer: pause_l() 
07-28 12:17:58.698   316  6669 V AudioCache: notify(0xb1432340, 7, 0, 0)
07-28 12:17:58.698   316  6669 V AudioCache: ignored
07-28 12:17:58.698   316  6669 V AwesomePlayer: cancelPlayerEvents
07-28 12:17:58.698   316   316 V AudioCache: wait - success
07-28 12:17:58.698   316   316 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:17:58.698   316  6669 D AudioPlayer: Pause Playback at 1068125
07-28 12:17:58.699   316   316 V AwesomePlayer: reset_l() 
07-28 12:17:58.699   316   316 V AudioCache: notify(0xb1432340, 8, 0, 0)
07-28 12:17:58.699   316   316 V AudioCache: ignored
07-28 12:17:58.699   316   316 V AwesomePlayer: cancelPlayerEvents
07-28 12:17:58.699   316   316 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:17:58.699   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:17:58.699   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:17:58.699   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:17:58.699   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:17:58.699   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:17:58.699   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:17:58.699   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:17:58.699   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
07-28 12:17:58.699   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fd30 on port 1
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:17:58.700   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:17:58.701   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:17:58.701   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:17:58.701   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:17:58.701   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:17:58.701   316  6671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:17:58.701   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:17:58.701   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:17:58.701   316   316 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:17:58.702   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:17:58.702   316   316 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:17:58.702   316   316 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:17:58.702   316   316 V AwesomePlayer: reset_l() 
07-28 12:17:58.702   316   316 V AwesomePlayer: cancelPlayerEvents
07-28 12:17:58.702   316   316 V AwesomePlayer: ~AwesomePlayer call
07-28 12:17:58.702   316   316 V AwesomePlayer: reset_l() 
07-28 12:17:58.702   316   316 V AwesomePlayer: cancelPlayerEvents
07-28 12:17:58.703  6635  6668 V SoundPool: close(28)
07-28 12:17:58.703  6635  6668 V SoundPool: pointer = 0xaf202000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 12:17:58.720  6577  6664 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-28 12:17:58.722  6577  6577 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-28 12:17:58.735  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:17:58.739  6577  6577 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-28 12:17:58.742  6577  6577 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-28 12:17:58.744  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:17:58.745  6577  6577 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-28 12:17:58.745  6577  6577 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-28 12:17:58.745  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:17:58.746  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:920
07-28 12:17:58.748  6635  6635 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 12:17:58.751  6635  6635 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 12:17:58.752  6635  6635 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:17:58.752  6521  6537 I UEI.SmartControl: ------ IControl API: 11
07-28 12:17:58.752  6521  6537 I UEI.SmartControl: Registering callback...
07-28 12:17:58.753  6521  6536 I UEI.SmartControl: ------ IControl API: 19
07-28 12:17:58.753  6521  6536 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:17:58.753  6521  6536 I UEI.SmartControl: Notify client services are ready...
07-28 12:17:58.753  6635  6651 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:17:58.753  6635  6635 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:17:58.754  6635  6666 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:17:58.754  6635  6666 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 12:17:58.754  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:17:58.755  6635  6635 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:17:58.755  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:17:58.755  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:17:58.756  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:17:58.756  6577  6577 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-28 12:17:58.757  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7217
07-28 12:17:58.762  6635  6635 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:17:58.762  6635  6635 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 12:17:58.763  6521  6537 I UEI.SmartControl: ------ IControl API: 8
07-28 12:17:58.763  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:17:58.763  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:17:58.764  6635  6635 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:17:58.764  6635  6635 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:17:58.764  6635  6635 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:17:58.764  6635  6635 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:17:58.765  6635  6635 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 12:17:58.765  6635  6635 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 12:17:58.769  6635  6635 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-28 12:17:58.770  6635  6635 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:17:58.770  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:17:58.770  6635  6635 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:17:58.771  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:17:58.771  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:17:58.772  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-28 12:17:58.772  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-28 12:17:58.773  6635  6635 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469701078773]
07-28 12:17:58.776  6635  6635 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-28 12:17:58.777  1037  1928 I ActivityManager: Killing 6220:com.android.calendar/u0a13 (adj 15): empty #17
07-28 12:17:58.791  6635  6684 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
07-28 12:17:58.830  6577  6682 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:17:58.830  6577  6682 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:17:58.833  1037  1919 W libprocessgroup: failed to open /acct/uid_10013/pid_6220/cgroup.procs: No such file or directory
07-28 12:17:58.842  6635  6635 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-28 12:17:58.842  6635  6635 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:17:58.842  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-28 12:17:58.843  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-28 12:17:58.843  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-28 12:17:58.843  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-28 12:17:58.843  6577  6689 D OpenGLRenderer: Render dirty regions requested: true
07-28 12:17:58.843  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-28 12:17:58.843  6577  6689 I OpenGLRenderer: Initialized EGL, version 1.4
07-28 12:17:58.849  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
07-28 12:17:58.854  6577  6689 D OpenGLRenderer: Enabling debug mode 0
07-28 12:17:58.860  6577  6577 D Atlas   : Validating map...
07-28 12:17:58.863  1037  1919 D SplitWindow: check instance of lgWin Window{288c4d14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:17:58.946  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +880ms (total +1s6ms)
07-28 12:17:58.947  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10c891ab u0 com.test.thalitest/.MainActivity t40} time:121335
,07-28 12:17:58.951  6577  6577 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f5567cd time:121339
07-28 12:17:59.051  6577  6577 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-28 12:17:59.051  6577  6577 I chromium: 
,07-28 12:17:59.085  6577  6577 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-28 12:17:59.160  6577  6682 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-28 12:17:59.160  6577  6682 I chromium: 
,07-28 12:17:59.282  6577  6701 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,07-28 12:17:59.295  6577  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:17:59.295  6577  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:17:59.295  6577  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:17:59.295  6577  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:17:59.295  6577  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-28 12:17:59.295  6577  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22531301 added. We now have 1 listener(s)
07-28 12:17:59.300  1037  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:17:59.303  6577  6701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-28 12:17:59.305  6577  6701 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:17:59.306  6577  6701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:17:59.307  6577  6701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:17:59.314  6577  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35325394 added. We now have 1 listener(s)
,07-28 12:17:59.314  6577  6701 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:17:59.321  1037  1531 D WifiService: New client listening to asynchronous messages
07-28 12:17:59.325  6577  6701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:17:59.325  6577  6701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-28 12:17:59.325  6577  6701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-28 12:17:59.325  6577  6701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-28 12:17:59.330  6577  6701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:17:59.333  1037  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:17:59.334  6577  6701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-28 12:17:59.343  6577  6701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:17:59.344  6577  6701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:17:59.344  6577  6701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 12:17:59.344  6577  6701 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:17:59.345  6577  6701 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:17:59.347  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:17:59.349  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:17:59.379   341   355 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:17:59.379   341   355 E GBMv2   : Set value is all cleared set the max
07-28 12:17:59.379   341   355 I GBMv2   : DFP Enabled. Ignore VFP set
,07-28 12:17:59.391  6577  6577 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:17:59.937  6577  6704 W jxcore-log: Initializing JXcore engine
,07-28 12:17:59.937  6577  6704 W jxcore-log: JXcore engine is ready
,07-28 12:17:59.965  6704  6704 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8592]" dev="sockfs" ino=8592 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-28 12:17:59.965  6704  6704 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-28 12:17:59.965  6704  6704 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8813]" dev="sockfs" ino=8813 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-28 12:17:59.965  6704  6704 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-28 12:17:59.965  6704  6704 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31337]" dev="sockfs" ino=31337 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-28 12:17:59.987  6577  6704 W jxcore-log: Starting JXcore engine
07-28 12:18:00.000  1037  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=381158702, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,07-28 12:18:00.028  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
07-28 12:18:00.040  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-28 12:18:00.040  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
07-28 12:18:00.040  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-28 12:18:00.041  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
,07-28 12:18:00.045  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
07-28 12:18:00.045  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
07-28 12:18:00.046  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
07-28 12:18:00.046  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
07-28 12:18:00.068  4500  6705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-28 12:18:00.094  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=381158702 [*alarm*], flags=0x0
,07-28 12:18:00.153  6577  6704 W jxcore-log: Platform android
07-28 12:18:00.153  6577  6704 W jxcore-log: 
07-28 12:18:00.153  6577  6704 W jxcore-log: Process ARCH arm
07-28 12:18:00.153  6577  6704 W jxcore-log: 
,07-28 12:18:00.403  6577  6704 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:18:00.403  6577  6704 I jxcore-log: 
07-28 12:18:00.404  6577  6704 W jxcore-log: JXcore engine is started
,07-28 12:18:00.417  6577  6701 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:18:00.423  6577  6577 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-28 12:18:01.851  6495  6495 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-28 12:18:01.855  1037  1891 I ActivityManager: Killing 6185:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-28 12:18:01.944  1037  1052 W libprocessgroup: failed to open /acct/uid_10014/pid_6185/cgroup.procs: No such file or directory
,07-28 12:18:02.166  6521  6550 D UEI.SmartControl: Internal timer expired: 1
,07-28 12:18:02.166  6521  6550 D UEI.SmartControl: unbind internal service
,07-28 12:18:02.205  6521  6547 D serial_port: close(fd = 25)
,07-28 12:18:02.214  6521  6547 I UEI.SmartControl: Serial port is closed.
,07-28 12:18:02.960  1037  1949 I art     : Explicit concurrent mark sweep GC freed 19857(1064KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.772ms total 131.141ms
,07-28 12:18:02.987  6495  6563 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:18:05.376  1803  6404 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 12:18:05.382   310  6735 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-28 12:18:05.382   310  6735 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-28 12:18:05.382   310  6735 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-28 12:18:05.604  1803  1803 I ConfigFetchService: fetch service done; releasing wakelock
,07-28 12:18:05.612  1803  1803 I ConfigFetchService: stopping self
07-28 12:18:05.623  2094  2094 I ConfigService: onDestroy
,07-28 12:18:10.507  1037  1100 I ActivityManager: Waited long enough for: ServiceRecord{8ebb2bf u0 com.google.android.gms/.wearable.service.WearableService}
,07-28 12:18:10.989  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:18:10.989  6577  6704 I jxcore-log: 
,07-28 12:18:10.993  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:18:10.993  6577  6704 I jxcore-log: 
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:10.998  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:11.001  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.004  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:18:11.004  6577  6704 I jxcore-log: 
,07-28 12:18:11.006  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:18:11.006  6577  6704 I jxcore-log: 
,07-28 12:18:11.353  6577  6704 D ExecuteNativeTests: Running unit tests
,07-28 12:18:11.437  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:11.437  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 added. We now have 2 listener(s)
,07-28 12:18:11.438  1037  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:18:11.441  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-28 12:18:11.441  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:11.441  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:11.441  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:11.441  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 added. We now have 2 listener(s)
07-28 12:18:11.441  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:11.441  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:18:11.443  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:11.446  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:11.447  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.447  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:11.449  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.450  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.454  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:18:11.455  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:18:11.455  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:18:11.457  6577  6704 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-28 12:18:11.458  6577  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:18:11.458  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:18:11.458  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:18:11.458  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:18:11.459  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.459  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.459  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.460  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.460  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.460  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:11.460  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:11.460  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 removed from the list
07-28 12:18:11.460  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.460  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 removed from the list
07-28 12:18:11.460  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.460  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.461  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.461  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.461  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.461  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.461  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.461  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.463  6577  6704 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:18:11.463  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.463  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.463  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.463  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.463  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.463  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.463  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.464  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.464  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.464  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.464  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.464  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.464  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.464  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.466  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.466  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.466  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.466  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:18:11.470  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:18:11.472  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:18:11.473  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:18:11.473  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:18:11.473  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:18:11.473  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:18:11.473  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:18:11.473  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.473  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.473  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.473  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.473  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.473  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.473  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.473  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.473  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.473  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.473  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.473  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.473  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.473  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.474  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.474  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.475  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.475  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.475  6577  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:18:11.478  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:11.480  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:11.480  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.481  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:11.482  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.483  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.483  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:11.483  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:18:11.483  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.483  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:18:11.486  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:18:11.486  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:11.489  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:18:11.493  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:18:11.494  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:18:11.495  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:18:11.496  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:11.497  6577  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:18:11.497  6577  6704 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:18:11.499  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.499  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.499  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.499  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.499  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.499  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:11.499  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.499  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.499  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.499  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.499  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.500  6577  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:18:11.500  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:11.503  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:11.504  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.504  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:11.505  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:11.505  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:18:11.505  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.505  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:18:11.505  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.507  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:,11.508  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:18:11.508  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:18:11.512  6577  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:18:11.512  6577  6704 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:18:11.513  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.513  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.513  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.514  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.514  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.514  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:11.514  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.514  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.514  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.514  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.514  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.514  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.514  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.514  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.514  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.515  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.516  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.516  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.516  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.516  6577  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:18:11.517  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:11.519  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:18:11.520  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:11.520  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:11.521  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.522  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:11.522  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:18:11.522  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.522  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:18:11.523  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.525  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:18:11.525  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:11.526  6577  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:18:11.526  6577  6704 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:18:11.526  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.526  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.526  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.527  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.528  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.528  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.528  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.528  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.528  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:11.528  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.528  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.528  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.528  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.528  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.528  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.528  6577,  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.529  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.529  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.529  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.529  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.529  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.529  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.530  6577  6704 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:18:11.530  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.530  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.530  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.531  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:18:11.531  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.531  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.531  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.531  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.531  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.531  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.531  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.531  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-28 12:18:11.531  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.531  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.531  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.531  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:18:11.534  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.534  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.534  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.534  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.535  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:18:11.535  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.535  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.535  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.535  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.535  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.535  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.535  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.535  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.536  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.536  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:18:11.536  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.536  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.536  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.536  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.537  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.537  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.538  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.538  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.538  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.538  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.538  6577  6704 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:18:11.539  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:18:11.539  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.539  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.539  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.539  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.539  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.539  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.539  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:18:11.539  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.539  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.539  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.539  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.539  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.539  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.540  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:18:11.540  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.540  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.540  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.540  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.540  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.541  6577  6704 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:18:11.541  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
07-28 12:18:11.541  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.541  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.541  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.541  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.541  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.541  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list,
07-28 12:18:11.541  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.541  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.541  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.541  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-28 12:18:11.541  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.541  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.541  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.542  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.542  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:18:11.542  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.542  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.542  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:18:11.542  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.543  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:18:11.544  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:18:11.544  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:18:11.544  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:18:11.544  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:18:11.544  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:18:11.544  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:18:11.544  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
07-28 12:18:11.544  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.545  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.545  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-28 12:18:11.545  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.545  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.545  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.545  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.545  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop,
07-28 12:18:11.545  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.545  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.545  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.545  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-28 12:18:11.546  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.546  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.546  6577  6704 D BluetoothLeScanner: could not find callback wrapper
,07-28 12:18:11.546  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.546  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.546  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.547  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-28 12:18:11.547  6577  6704 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:18:11.547  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:18:11.548  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:18:11.548  6577  6704 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:18:11.549  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:18:11.549  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:18:11.549  6577  6704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,07-28 12:18:11.549  6577  6704 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:18:11.550  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:18:11.550  6577  6704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:18:11.550  6577  6704 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:18:11.550  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:18:11.550  6577  6704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,07-28 12:18:11.550  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:18:11.552  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:18:11.553  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:18:11.553  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,07-28 12:18:11.553  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,07-28 12:18:11.553  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:18:11.553  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:18:11.555  6577  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:18:11.555  6577  6704 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:18:11.556  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.556  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.556  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.556  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.556  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.556  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.556  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:18:11.557  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.557  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.557  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.557  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:18:11.557  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.557  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.557  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.557  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.559  6577  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
07-28 12:18:11.561  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.561  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.562  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.562  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.562  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.562  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.564  6577  6704 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:18:11.564  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.564  6577  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
07-28 12:18:11.564  6577  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
07-28 12:18:11.564  6577  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
07-28 12:18:11.565  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.565  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.565  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.565  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.565  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.565  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.565  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.565  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.565  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.565  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.565  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.565  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.565  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.566  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.566  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.567  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.567  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.567  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.567  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.572  6577  6704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:18:11.573  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.573  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.573  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:18:11.573  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.573  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.573  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.573  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.573  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.573  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.573  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.573  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.573  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.573  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.573  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.574  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.574  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.574  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.574  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.575  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.575  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.575  6577  6704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:18:11.575  6577  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:18:11.575  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:18:11.575  6577  6704 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:18:11.575  6577  6704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:18:11.575  6577  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:18:11.575  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:18:11.576  6577  6704 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:18:11.576  6577  6704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:18:11.576  6577  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:18:11.576  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:18:11.5,76  6577  6704 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:18:11.576  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.576  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.576  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.577  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.577  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.577  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.577  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.577  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.577  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.577  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.577  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.577  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.577  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:18:11.577  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.578  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.578  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.579  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.579  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.579  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.579  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.579  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.579  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.579  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:18:11.579  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.579  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.579  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.579  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.579  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.579  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.579  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.579  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.579  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:18:11.579  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.580  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.580  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.580  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.580  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.580  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.580  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.580  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.580  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.580  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list,
07-28 12:18:11.580  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.580  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.580  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.580  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.580  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.580  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.580  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.581  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.581  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.582  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.582  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
07-28 12:18:11.582  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.582  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.583  6577  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:18:11.583  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.584  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:18:11.584  6577  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:18:11.584  6577  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:18:11.584  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:18:11.584  6577  6577 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-28 12:18:11.584  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:18:11.585  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.585  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:18:11.585  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:18:11.585  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:18:11.585  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.585  6577  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:18:11.585  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.585  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.585  6577  6577 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-28 12:18:11.585  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:18:11.585  6577  6704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:18:11.586  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:18:11.586  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:18:11.586  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:11.586  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:11.586  6577  6704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:18:11.586  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:18:11.587  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.587  6577  6704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:18:11.588  6577  6577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:18:11.588  6577  6577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:18:11.588  6577  6577 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:18:11.588  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.588  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:18:11.588  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.588  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:18:11.588  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.588  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.588  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.600  6577  6738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:18:11.600  6577  6738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:18:11.601  6577  6577 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:18:11.588  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.602  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.602  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.602  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.602  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.602  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.602  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.602  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:18:11.604  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.604  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.604  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.605  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.606  6577  6704 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:18:11.606  6577  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:18:11.606  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:18:11.608  6577  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:18:11.608  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.608  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.608  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.608  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.608  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.608  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.608  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.608  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.608  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.608  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.608  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.608  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.608  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.608  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.609  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.609  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.609  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.609  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.610  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:11.610  1037  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroun,dUser=0
07-28 12:18:11.611  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:11.611  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.611  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.611  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.611  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.612  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.612  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.612  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.612  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.612  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.612  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.612  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.612  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.612  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.612  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.612  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.612  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.612  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.612  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.613  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:11.613  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:11.613  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:11.613  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:11.613  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.613  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:18:11.613  6577  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ccf683 not in the list
07-28 12:18:11.613  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.613  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.613  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:11.613  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.614  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.614  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:11.614  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:11.615  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:11.615  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:11.615  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:11.615  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b31000 not in the list
07-28 12:18:11.616  6577  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:18:11.616  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:18:11.617  6577  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:18:11.617  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
07-28 12:18:11.617  6577  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:18:11.617  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:18:11.619  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:18:11.619  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 12:18:11.619  6577  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 12:18:11.620  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:18:11.620  6577  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1,
07-28 12:18:11.620  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:18:11.620  6577  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:18:11.620  6577  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 12:18:11.620  6577  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:18:11.620  6577  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:18:11.621  6577  6704 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-28 12:18:11.621  6577  6704 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:18:11.621  6577  6704 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:18:11.621  6577  6704 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:18:11.621  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:11.622  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68e0756 added. We now have 2 listener(s)
07-28 12:18:11.622  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:11.623  6577  6704 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:18:11.624  1037  2000 D WifiServiceImplEx: setWifiEnabled: true pid=6577, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:18:11.624  1037  2000 D WifiService: setWifiEnabled: true pid=6577, uid=10118
07-28 12:18:11.624  1037  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:18:11.625  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:11.625  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@133983d7 added. We now have 3 listener(s)
07-28 12:18:11.625  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:18:11.629  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:11.629  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f2d4c4 added. We now have 4 listener(s)
07-28 12:18:11.629  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:11.630  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:11.630  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bd07fad added. We now have 5 listener(s)
07-28 12:18:11.630  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:11.631  1037  2000 D WifiServiceImplEx: setWifiEnabled: false pid=6577, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:18:11.632  1037  2000 D WifiService: setWifiEnabled: false pid=6577, uid=10118
07-28 12:18:11.632  1037  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:18:11.649  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:18:11.650  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:11.650  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-28 12:18:11.651  1037  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:11.651  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:11.652  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:11.652  1037  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:11.652  1037  2019 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1f817a3f mBinding = false
07-28 12:18:11.652  1037  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:11.652  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:11.652  1037  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:18:11.652  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:18:11.652  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,07-28 12:18:11.653  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:18:11.653  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:18:11.662  6577  6736 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
07-28 12:18:11.662  6577  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
07-28 12:18:11.663  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:18:11.663  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.664  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.664  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:18:11.664  2730  2730 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:18:11.664  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:18:11.664  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:11.665  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:11.665  1037  2847 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:18:11.669   310   895 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:18:11.674  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:18:11.675  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:11.675  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-28 12:18:11.675  1037  1119 D BluetoothManagerService: Message: 2
07-28 12:18:11.676  1037  1119 D BluetoothManagerService: Sending off request.
07-28 12:18:11.676  3893  3911 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:18:11.677  3893  3982 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:18:11.677  3893  3982 D BluetoothAdapterProperties: Setting state to 13
07-28 12:18:11.677  3893  3982 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:18:11.678  3893  3982 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:18:11.678  3893  3982 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:18:11.682  3893  3985 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:18:11.682  3893  3982 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:18:11.686  3893  4264 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:18:11.686  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:18:11.686  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-28 12:18:11.686  3893  4266 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:11.687  3893  4319 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:11.687  3893  4323 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:11.687  3893  4334 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:11.687  3893  3982 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:18:11.689  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:18:11.689  3893  4088 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:18:11.692  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:18:11.692  3893  4088 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:18:11.694  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.694  6577  6577 V io.jxcore.node.Conne,ctivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:11.694  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:11.695  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.695  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:11.697  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:11.698  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:18:11.698  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-28 12:18:11.700  1037  2019 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
07-28 12:18:11.700  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.701  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.701  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-28 12:18:11.701  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.701  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-28 12:18:11.721  1037  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,07-28 12:18:11.721  1037  1532 D DSQN    : disableDataServiceNotify
07-28 12:18:11.721  1037  1532 D DSQN    : stop dsqn bin
07-28 12:18:11.721   310  6759 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:18:11.722  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-28 12:18:11.722  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:18:11.725  1037  1100 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6758 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-28 12:18:11.726  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-28 12:18:11.727  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:11.727  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:11.728  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 12:18:11.728  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.728  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.728  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:11.729  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.730  1037  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 12:18:11.730  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:11.730  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:11.730  1037  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:11.731  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 12:18:11.731  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.731  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.731  1037  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:18:11.732  1037  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 12:18:11.732  1037  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 12:18:11.732  1037  1363 V AlarmManager: RTC_WAKEUP set : Ala,rm{3418da6a type 0 when 1469701090943 com.android.vending} when 1469701090943
07-28 12:18:11.732  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:18:11.734  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:18:11.735  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.735  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.735  1037  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@7b60254
07-28 12:18:11.735  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.735  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:11.736  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.736  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.737  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.737  1037  1524 D LGWifiP2pService: P2pDisablingState
07-28 12:18:11.737  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.737  1037  1524 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.737  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:11.737  1037  1524 D LGWifiP2pService: p2p socket connection lost
07-28 12:18:11.737  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:18:11.737  1037  1524 D LGWifiP2pService: P2pDisabledState
07-28 12:18:11.737  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:11.737  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.737  1037  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:11.737  1037  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:11.738  1037  1532 D NetworkManagementService: Removing idletimer
07-28 12:18:11.738  1037  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.738  1037  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:18:11.738  1037  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 12:18:11.738  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.739  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:11.739  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:18:11.740  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:18:11.740  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:18:11.740  2730  2730 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:18:11.741  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.741  1037  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.741  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-28 12:18:11.741  1838  1838 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:11.741  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.741  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:18:11.741  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.741  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:11.741  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:18:11.741  1037  1037 D RttService: SCAN_AVAILABLE : 1
07-28 12:18:11.741  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:18:11.741  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:18:11.741  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:18:11.741  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:18:11.742  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:18:11.742  1037  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.742  1037  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.742  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:18:11.742  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:11.742  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:18:11.742  1929  1929 D WfdsService: WifiP2pState is changed : false
07-28 12:18:11.742  1929  2242 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:18:11.742  1929  2242 D WfdsService: Set the WFDS Monitor: false
07-28 12:18:11.742  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:11.743  1929  2242 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:18:11.743  1929  2242 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:18:11.743  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:11.743  1929  2761 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:18:11.743  1929  2244 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:18:11.743  1929  2761 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:18:11.743  1929  2761 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:18:11.743  1929  2761 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:18:11.743  1929  2242 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 12:18:11.744  3893  3893 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:11.744  3893  3893 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:18:11,.744  3893  3893 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:18:11.744  3893  3893 V BluetoothMapService: Handler(): got msg=4
07-28 12:18:11.744  3893  3893 D BluetoothMapService: MAP Service closeService in
07-28 12:18:11.744   310   895 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:18:11.744  3893  3893 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:18:11.744  3893  3893 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:18:11.744  3893  3893 V BluetoothMapService: MAP Service closeService out
07-28 12:18:11.745  3893  3893 I BtOppRfcommListener: stopping Accept Thread
07-28 12:18:11.745  3893  3893 V BtOppRfcommListener: close mBtServerSocket
07-28 12:18:11.745  3893  3893 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:18:11.745  3893  4319 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:18:11.746  3893  3893 V BtOppRfcommListener: done waiting for thread to terminate
,07-28 12:18:11.749  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:18:11.749  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:18:11.749  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:18:11.749  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:18:11.749  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:18:11.751  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:11.752  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:11.752  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.767  1037  1100 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6776 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:18:11.768  3893  3893 V BtOppService: onDestroy
07-28 12:18:11.769  1037  1526 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:18:11.769  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-28 12:18:11.769  1037  1526 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:18:11.769  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:11.769  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:11.769  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:18:11.770  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.770  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:11.770  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:11.774  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:11.774  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:11.774  3893  3893 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:18:11.775  1037  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:11.775  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:11.776  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:18:11.776  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:18:11.777  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.777  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:11.777  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:11.780  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:11.780  6577  6577 V, io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:11.780  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:18:11.781  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:18:11.783  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:11.783  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:11.783  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:11.783  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:18:11.783  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:11.783  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:11.785  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.786  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.787  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:11.796  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-28 12:18:11.797  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.798  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.818  6776  6776 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:11.818  6776  6776 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-28 12:18:11.818  6776  6776 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:11.819  6776  6776 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,07-28 12:18:11.819  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:11.819  6776  6776 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:18:11.820  6776  6776 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:18:11.820  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.821  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.821  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:11.837  1037  2000 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:18:11.841  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:18:11.842  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:11.842  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:11.855  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:11.863  6758  6758 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 12:18:11.863  6758  6758 W LG Account v2.2: No ProfileInfo entries
07-28 12:18:11.863  6758  6758 I LG Account v2.2: isEnabled: false
07-28 12:18:11.863  6758  6758 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:18:11.863  6758  6758 I Feature : [Lifetracker]Country: EU
07-28 12:18:11.863  6758  6758 I Feature : [Lifetracker]Operator: OPEN
07-28 12:18:11.863  6758  6758 I Feature : [Lifetracker]Ranking support: false
07-28 12:18:11.863  6758  6758 I Feature : [Lifetracker]Comfort support: false
07-28 12:18:11.863  6758  6758 I Feature : [Lifetracker]Accessory: true
07-28 12:18:11.864  6758  6758 I Feature : [Lifetracker]Health device: true
07-28 12:18:11.864  6758  6758 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:18:11.864  6758  6758 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:18:11.864  6758  6758 I Feature : [Lifetracker]Device Number: 3
07-28 12:18:11.870  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:11.873  2730  2730 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:18:11.873  2730  2730 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:18:11.873  2730  2730 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-2\x00 that cannot receive messages
07-28 12:18:11.874  1037  2759 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:18:11.874  1037  2759 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:18:11.874  1037  2847 D DhcpStateMachine: StoppedState
07-28 12:18:11.874  1037  2847 D DhcpStateMachine: StoppedState{ when=-131ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:11.899  1037  1053 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6795 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:18:11.901  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 12:18:11.901  1037  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 12:18:11.906  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:18:11.907   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.193ms
07-28 12:18:11.908  3893  3893 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:18:11.908  3893  3893 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:11.908  3893  3893 V BluetoothPbapReceiver: ***********state = 13
07-28 12:18:11.909  3893  3893 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,07-28 12:18:11.910  2730  2730 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:18:11.910  2730  2730 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:18:11.911  1037  1119 D Tethering: InitialState.processMessage what=4
07-28 12:18:11.911  1037  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:18:11.911  1037  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:18:11.911  1037  2759 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:18:11.912  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:18:11.913  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:11.913  1037  2759 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:18:11.913  1037  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:11.913  1037  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:11.913  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:11.913  1037  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=134287
07-28 12:18:11.913  1037  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=134287
07-28 12:18:11.914  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=134287  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:18:11.914  1037  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=134288  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:18:11.916  3893  3893 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:11.916  3893  3893 V BluetoothPbapService: state: 13
07-28 12:18:11.916  3893  3893 V BluetoothPbapService: Pbap Service closeService in
07-28 12:18:11.918  3893  3893 V BluetoothPbapService: successfully stopped pbap service
07-28 12:18:11.918  3893  3893 V BluetoothPbapService: Pbap Service closeService out
07-28 12:18:11.918  3893  3893 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:18:11.918  3893  3893 V BluetoothPbapService: Pbap Service closeService in
07-28 12:18:11.918  3893  3893 V BluetoothPbapService: Pbap Service closeService out
07-28 12:18:11.918  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:18:11.918  3893  3893 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:18:11.918  1037  1119 D BluetoothManagerService: Message: 20
07-28 12:18:11.918   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 10.701ms
07-28 12:18:11.919  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@319d93a4:true
07-28 12:18:11.928   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.210ms
,07-28 12:18:11.929  1037  1119 D BluetoothManagerService: Message: 30
07-28 12:18:11.934  1037  1119 D BluetoothManagerService: Message: 30
07-28 12:18:11.935  6776  6776 D LocalBluetoothProfileManager: Adding local MAP profile
07-28 12:18:11.936  6776  6776 D BluetoothMap: Create BluetoothMap proxy object
07-28 12:18:11.936  1037  1119 D BluetoothManagerService: Message: 30
07-28 12:18:11.939  1037  1119 D BluetoothManagerService: Message: 30
07-28 12:18:11.940  6776  6776 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-28 12:18:11.940  6776  6776 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,07-28 12:18:11.948  6776  6776 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
07-28 12:18:11.949  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-28 12:18:11.954  6776  6776 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:18:11.960  6776  6776 D BluetoothInputDevice: Proxy object connected
07-28 12:18:11.960  6776  6776 D HidProfile: Bluetooth service connected
07-28 12:18:11.961  6776  6776 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:18:11.961  6776  6776 D PanProfile: Bluetooth service connected
07-28 12:18:11.961  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:18:11.961  6776  6776 D BluetoothMap: Proxy object connected
07-28 12:18:11.962  6776  6776 D MapProfile: Bluetooth service connected
07-28 12:18:11.962  6776  6776 D BluetoothMap: getConnectedDevices()
07-28 12:18:11.962  6776  6776 D BluetoothMap: Bluetooth is Not enabled
07-28 12:18:11.962  6776  6776 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:18:11.963  6776  6776 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:18:11.965  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:11.965  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:11.966  6776  6776 D BluetoothPermissionRequest: onReceive
,07-28 12:18:11.966  1037  1053 I ActivityManager: Killing 2116:com.lge.music/u0a34 (adj 15): empty #17
07-28 12:18:11.967  6776  6776 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:18:11.976   316  2125 V AudioFlinger: 2116 died, releasing its sessions
,07-28 12:18:11.977   316  2125 V AudioFlinger:  pid 1838 @ 0
07-28 12:18:11.977   316  2125 V AudioFlinger:  pid 3442 @ 1
07-28 12:18:11.977   316  2125 V AudioFlinger:  pid 3442 @ 2
07-28 12:18:11.982  6071  6071 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
07-28 12:18:11.992  2730  2730 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:18:11.992  1037  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:18:11.992  1037  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:18:11.992  1037  2759 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:18:11.993  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,07-28 12:18:11.996  1037  2037 W libprocessgroup: failed to open /acct/uid_10034/pid_2116/cgroup.procs: No such file or directory
,07-28 12:18:11.999  1037  1053 I ActivityManager: Killing 6422:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-28 12:18:12.004  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:18:12.033  6776  6776 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:12.033  6776  6776 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:12.045  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:12.054  1037  1685 W libprocessgroup: failed to open /acct/uid_10008/pid_6422/cgroup.procs: No such file or directory
,07-28 12:18:12.061  1037  1053 I ActivityManager: Killing 6001:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-28 12:18:12.065  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-28 12:18:12.106  3893  3893 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-28 12:18:12.106  3893  3893 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 12:18:12.106  1037  1919 W libprocessgroup: failed to open /acct/uid_10011/pid_6001/cgroup.procs: No such file or directory
07-28 12:18:12.107  3893  3893 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-28 12:18:12.113  1929  1929 D WfdsService: Supplicant Connection state is changed : false
07-28 12:18:12.114  1929  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:18:12.114  1929  2242 D WfdsService: Set the WFDS Monitor: false
07-28 12:18:12.114  1929  2242 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:18:12.133  1037  1526 D WifiOffDelayIfNotUsed: stopMonitoring
,07-28 12:18:12.133  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:12.133  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:12.133  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:18:12.136  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:18:12.136  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:12.137  3893  3893 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:12.137  3893  3893 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:18:12.138  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:18:12.138  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:18:12.138  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:18:12.140  2435  2435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:12.141  3893  3893 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:18:12.141  3893  3893 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:12.142  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:12.142  3893  3893 V BluetoothFtpService: Ftp Service closeService
07-28 12:18:12.143  3893  3893 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:18:12.145  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:12.153  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:12.153  3893  3893 V BluetoothFtpService: successfully stopped ftp service
07-28 12:18:12.154  3893  3893 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:18:12.154  3893  3893 V BluetoothFtpService: Ftp Service closeService
,07-28 12:18:12.160  3893  3893 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:12.160  3893  3893 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:12.160  3893  3893 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:12.161  3893  3893 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:12.161  3893  3893 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:18:12.161  3893  3893 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:18:12.162  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:12.163  3893  3893 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:12.163  3893  3893 V BluetoothSapService: state: 13
07-28 12:18:12.163  3893  3893 V BluetoothSapService: Stopping SAP server process
07-28 12:18:12.165  3893  3893 V BluetoothSapService: Sap Service closeSapService in
,07-28 12:18:12.165  3893  3893 V BluetoothSapService: Close listen Socket : 
07-28 12:18:12.165  3893  3893 V BluetoothSapService: Close rfcomm Socket : 
,07-28 12:18:12.166  3893  3893 V BluetoothSapService: Close sapd  Socket : 
07-28 12:18:12.205  1037  1983 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:18:12.209  3893  3893 V BluetoothSapService: Sap Service closeSapService out
07-28 12:18:12.209  3893  3893 V BluetoothSapService: Sap Service onDestroy
07-28 12:18:12.209  3893  3893 V BluetoothSapService: Sap Service closeSapService in
07-28 12:18:12.209  3893  3893 V BluetoothSapService: Close listen Socket : 
07-28 12:18:12.209  3893  3893 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:18:12.209  3893  3893 V BluetoothSapService: Close sapd  Socket : 
07-28 12:18:12.209  6635  6635 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:12.210  3893  3893 V BluetoothSapService: Sap Service closeSapService out
07-28 12:18:12.213  6635  6635 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-28 12:18:12.213  6635  6635 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7217
07-28 12:18:12.216  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:12.221  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:18:12.221  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:12.221  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:12.224  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:12.230  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:12.237  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:18:12.237  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:12.240  6635  6635 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:12.244  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:12.248  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:18:12.248  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:12.248  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:12.252  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:12.260  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:18:12.272  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:18:12.272  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:12.274  6827  6827 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:12.275  6635  6635 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:12.345  1037  2019 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6844 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-28 12:18:12.352  1037  2019 I ActivityManager: Killing 6022:com.android.contacts/u0a19 (adj 15): empty #17
07-28 12:18:12.426  1037  2037 W libprocessgroup: failed to open /acct/uid_10019/pid_6022/cgroup.procs: No such file or directory
,07-28 12:18:12.490  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:12.495  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:18:12.501  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:12.523  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:18:12.523  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:18:12.523  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:18:12.523  6776  6776 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:18:12.525  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:18:12.529  6844  6866 W FormManager: Network not available. Please check & try again.
07-28 12:18:12.537  6776  6776 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:18:12.537  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:18:12.537  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:18:12.537  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:18:12.537  6776  6776 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:18:12.538  6776  6776 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-28 12:18:12.542  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:18:12.543  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:18:12.544  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:12.549  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:12.549  6844  6868 V FormManager: Network unavailable.
07-28 12:18:12.558  4324  6870 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:18:12.558  6844  6868 V FormManager: Network unavailable.
07-28 12:18:12.559  6795  6795 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:18:12.559  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:12.559  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:12.561  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:18:12.568  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:12.572  4324  6871 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:18:12.573  4324  6871 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:12.585  6844  6872 W FormManager: Network not available. Please check & try again.
,07-28 12:18:12.589  6844  6873 V FormManager: Network unavailable.
07-28 12:18:12.591  6844  6873 V FormManager: Network unavailable.
07-28 12:18:12.596  1037  1052 I ActivityManager: Killing 6457:com.lge.email/u0a23 (adj 15): empty #17
07-28 12:18:12.624  1037  1891 W libprocessgroup: failed to open /acct/uid_10023/pid_6457/cgroup.procs: No such file or directory
,07-28 12:18:12.695  3893  4088 W bt-btif : ag scb idx 1 not allocated
07-28 12:18:12.695  3893  3985 D bt_hci_bdroid: cleanup
07-28 12:18:12.695  3893  4088 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:12.696  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:12.697  3893  4088 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:12.697  3893  4091 I bt_lpm  : LPM is already off!!!
07-28 12:18:12.697  3893  4088 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:12.697  3893  4088 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:12.697  3893  4251 I bt_userial_mct: exiting userial_read_thread
07-28 12:18:12.697  3893  4088 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:18:12.697  3893  4251 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:18:12.698  3893  3985 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:18:12.698  3893  4091 I bt_vendor: hw_epilog_process
07-28 12:18:12.699  3893  3985 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:18:12.699  3893  3985 D bt_userial_mct: userial_close
07-28 12:18:12.699  3893  3985 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:18:12.699  3893  3985 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:18:12.732  3893  3985 D bt_hci_bdroid: set_power 0
07-28 12:18:12.732  3893  3985 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 12:18:12.732  3893  3985 I bt_vendor: bluetooth satus is on
07-28 12:18:12.732  3893  3985 I bt_vendor: bt-vendor : resetting BT status
07-28 12:18:12.732  3893  3985 I bt_vendor: Starting hciattach daemon
07-28 12:18:12.732  3893  3985 I bt_vendor: try to set false
07-28 12:18:12.734  3893  3985 I bt_vendor: Starting hciattach daemon
07-28 12:18:12.734  3893  3985 I bt_vendor: try to set false
07-28 12:18:12.734  3893  3985 I bt_vendor: cleanup
,07-28 12:18:12.735  3893  4088 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:18:12.736  3893  3985 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:18:12.736  3893  3985 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:18:12.739  3893  3982 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:18:12.743  3893  3893 D HeadsetService: Received stop request...Stopping profile...
07-28 12:18:12.744  3893  3893 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:18:12.745  3893  4013 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:18:12.745  3893  3893 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:18:12.745  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.747  1037  1037 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:12.747  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-28 12:18:12.750  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:12.750  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:12.751  3893  3893 D A2dpService: Received stop request...Stopping profile...
07-28 12:18:12.751  3893  4070 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:18:12.752  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 12:18:12.753  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:12.754  3893  3982 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:18:12.754  3893  3893 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:18:12.754  3893  3893 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:18:12.754  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.755  1037  1037 D BluetoothA2dp: Proxy object disconnected
07-28 12:18:12.755  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:18:12.756  3893  3893 D HidService: Received stop request...Stopping profile...
07-28 12:18:12.756  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.757  6776  6776 D BluetoothInputDevice: Proxy object disconnected
07-28 12:18:12.757  6776  6776 D HidProfile: Bluetooth service disconnected
07-28 12:18:12.757  3893  3893 D HealthService: Received stop request...Stopping profile...
07-28 12:18:12.757  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.759  3893  3893 D PanService: Received stop request...Stopping profile...
,07-28 12:18:12.759  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.761  6776  6776 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:18:12.761  6776  6776 D PanProfile: Bluetooth service disconnected
07-28 12:18:12.762  3893  3893 D HeadsetStateMachine: Unbinding service...
07-28 12:18:12.763  3893  3893 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:18:12.763  3893  3893 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:18:12.763  3893  3893 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:18:12.763  3893  3893 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:18:12.763  3893  3893 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:18:12.763  3893  3893 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:18:12.763  3893  3893 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:18:12.763  3893  3893 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:18:12.764  3893  3893 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:18:12.764  3893  3893 D BtGatt.GattService: stop()
07-28 12:18:12.764  3893  3893 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:18:12.765  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.766  3893  3893 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:18:12.766  3893  3893 D BluetoothMapService: stop()
07-28 12:18:12.767  3893  3893 D BluetoothMapEmailAppObserver: deinitObservers()
,07-28 12:18:12.767  3893  3893 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:18:12.767  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c26e07
07-28 12:18:12.768  3893  3893 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:18:12.768  3893  4071 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:18:12.768  6776  6776 D BluetoothMap: Proxy object disconnected
07-28 12:18:12.768  6776  6776 D MapProfile: Bluetooth service disconnected
07-28 12:18:12.769  3893  3893 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:18:12.769  3893  3893 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:18:12.769  3893  3893 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:18:12.769  3893  3893 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:18:12.769  3893  3893 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:18:12.769  3893  3893 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:18:12.769  3893  3893 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:18:12.770  3893  3893 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:18:12.770  3893  3893 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:18:12.770  3893  3893 V BluetoothMapService: Handler(): got msg=4
07-28 12:18:12.770  3893  3893 D BluetoothMapService: MAP Service closeService in
07-28 12:18:12.770  3893  3893 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:18:12.771  3893  3893 V BluetoothMapService: MAP Service closeService out
07-28 12:18:12.771  3893  3982 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:18:12.771  3893  3982 D BluetoothAdapterProperties: Setting state to 10
07-28 12:18:12.771  3893  3982 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:18:12.772  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:12.772  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:18:12.772  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-28 12:18:12.772  3893  3982 I BluetoothAdapterState: Entering OffState
07-28 12:18:12.772  6776  6875 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:18:12.772  3893  3893 D BluetoothMapService: cleanup()
07-28 12:18:12.772  3893  3893 D BluetoothMapService: MAP Service closeService in
07-28 12:18:12.772  3893  3893 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:18:12.772  3893  3893 V BluetoothMapService: MAP Service closeService out
07-28 12:18:12.773  6776  6791 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:18:12.773  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:18:12.773  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:12.774  1838  4011 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 12:18:12.775  6776  6792 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:18:12.775  1838  2480 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:12.776  6776  6791 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:18:12.776  1838  4014 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:12.778  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:18:12.778  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:18:12.780  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:18:12.780  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 12:18:12.780  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1f817a3f mBinding = false
07-28 12:18:12.780  1037  1119 D BluetoothManagerService: Sending unbind request.
07-28 12:18:12.783  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 12:18:12.789  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:12.790  1929  2078 D LGBluetoothAPIService: Message: 2
07-28 12:18:12.790  1929  2078 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2a4ba716 mBinding = false
07-28 12:18:12.791  1929  2078 D LGBluetoothAPIService: Sending unbind request.
,07-28 12:18:12.791  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:12.793  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:12.793  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:12.796  3893  3985 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:18:12.796  3893  3893 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:18:12.796  3893  3893 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:18:12.797  3893  3893 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:18:12.797  3893  3893 I art     : --- WEIRD: removing null entry 246
07-28 12:18:12.797  3893  3893 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-28 12:18:12.797  3893  3893 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 12:18:12.798  6776  6776 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:18:12.798  1590  1590 D BluetoothAdapter: 599584127: getState() :  mService = null. Returning STATE_OFF
07-28 12:18:12.799  3893  3893 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:18:12.799  1590  1590 D BluetoothAdapter: 599584127: getState() :  mService = null. Returning STATE_OFF
07-28 12:18:12.799  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:18:12.799  6776  6776 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 12:18:12.802  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:18:12.802  3893  3893 I art     : System.exit called, status: 0
07-28 12:18:12.802  3893  3893 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:18:12.808  6776  6776 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:18:12.826   316  1372 V AudioFlinger: 3893 died, releasing its sessions
07-28 12:18:12.827   316  1372 V AudioFlinger:  pid 1838 @ 0
07-28 12:18:12.827   316  1372 V AudioFlinger:  pid 3442 @ 1
07-28 12:18:12.827   316  1372 V AudioFlinger:  pid 3442 @ 2
07-28 12:18:12.827  6776  6776 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-28 12:18:12.882  1037  1685 I ActivityManager: Process com.android.bluetooth (pid 3893) has died
07-28 12:18:12.882  1037  1685 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-28 12:18:12.893  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:18:12.911  6776  6776 D BluetoothPermissionRequest: onReceive
,07-28 12:18:12.915  6776  6776 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:18:12.916  6776  6776 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 12:18:12.920  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:12.994  1037  1562 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6878 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:18:13.087  6878  6878 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:18:13.088  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:18:13.088  6878  6878 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:18:13.089  6878  6878 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:18:13.110  6878  6878 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:18:13.147  6878  6878 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3aeee49c Instance Count = 1
,07-28 12:18:13.153  6878  6878 D BluetoothAdapterApp: onCreate
07-28 12:18:13.203  6878  6878 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 12:18:13.203  6878  6878 D ProfileConfigQcom: Adding HeadsetService
07-28 12:18:13.203  6878  6878 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:18:13.203  6878  6878 D ProfileConfigQcom: Adding A2dpService
07-28 12:18:13.204  6878  6878 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:18:13.204  6878  6878 D ProfileConfigQcom: Adding HidService
07-28 12:18:13.204  6878  6878 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:18:13.204  6878  6878 D ProfileConfigQcom: Adding HealthService
07-28 12:18:13.205  6878  6878 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:18:13.206  6878  6878 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:18:13.206  6878  6878 D ProfileConfigQcom: Adding PanService
07-28 12:18:13.206  6878  6878 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:18:13.206  6878  6878 D ProfileConfigQcom: Adding GattService
07-28 12:18:13.207  6878  6878 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:18:13.207  6878  6878 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:18:13.208  6878  6878 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:18:13.209  6878  6878 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-28 12:18:13.218  6776  6776 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-28 12:18:13.220  6878  6878 V LGMDMManagerInternal: Create singleton instance
,07-28 12:18:13.314  6878  6878 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:18:13.322  6878  6878 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:13.322  6878  6878 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:13.323  6878  6878 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:13.324  6878  6878 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:18:13.324  6878  6878 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 12:18:13.338  6827  6827 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-28 12:18:13.339  1037  1919 I ActivityManager: Killing 6049:com.android.gallery3d/u0a27 (adj 15): empty #17
,07-28 12:18:13.435  1037  2019 W libprocessgroup: failed to open /acct/uid_10027/pid_6049/cgroup.procs: No such file or directory
,07-28 12:18:14.741  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:14.754  1037  1119 D Tethering: MasterInitialState.processMessage what=3
07-28 12:18:14.764  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:18:14.768  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:14.772  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:14.774  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:14.777  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:18:14.784  6371  6398 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:18:14.788  1037  1119 D Tethering: MasterInitialState.processMessage what=3
07-28 12:18:14.792  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:18:14.800  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:14.801  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:18:14.813  1037  1983 D WifiServiceImplEx: setWifiEnabled: true pid=6577, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:18:14.814  1037  1983 D WifiService: setWifiEnabled: true pid=6577, uid=10118
07-28 12:18:14.814  1037  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:18:14.821  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:18:14.828  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:18:14.828  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:14.828  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-28 12:18:14.829  1037  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 12:18:14.829  1037  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:18:14.830  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:18:14.830  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:18:14.830  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:18:14.830  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:18:14.830  1037  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:18:14.830  1037  1526 E WifiHW  : unknown target_country: EU , set to default
07-28 12:18:14.830  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 12:18:14.830  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 12:18:14.830  1037  1526 I WifiUtil: gEnableBmps=1
,07-28 12:18:14.860  2094  2094 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:14.909  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:14.935  1037  1052 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6917 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-28 12:18:14.940  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:14.941  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:18:15.025  6917  6917 I AppUp4:AppBoxCP: onCreate
,07-28 12:18:15.026  6917  6917 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-28 12:18:15.036  6917  6917 I AppUp4:DB:  setFingerPrint start
07-28 12:18:15.036  6917  6917 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,07-28 12:18:15.045  6917  6917 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,07-28 12:18:15.045  6917  6917 I AppUp4:DB:  SDK version = 21
,07-28 12:18:15.045  6917  6917 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-28 12:18:15.047  6917  6917 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-28 12:18:15.049  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:18:15.049  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:15.051  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:18:15.052  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 12:18:15.063  6917  6917 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:18:15.102  6917  6917 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:15.102  6917  6917 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:15.115  6917  6917 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e3c7c46
,07-28 12:18:15.115  6917  6917 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:18:15.116  6917  6917 D AppUp4:CustFacade: isPhone : true
07-28 12:18:15.116  6917  6917 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:18:15.117  6917  6917 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-28 12:18:15.117  6917  6917 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-28 12:18:15.119  6917  6938 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-28 12:18:15.119  6917  6938 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-28 12:18:15.120  6917  6938 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,07-28 12:18:15.125  1037  1053 I ActivityManager: Killing 6310:com.android.defcontainer/u0a4 (adj 15): empty #17
07-28 12:18:15.164  1037  1891 W libprocessgroup: failed to open /acct/uid_10004/pid_6310/cgroup.procs: No such file or directory
07-28 12:18:15.167  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:15.167  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:18:15.171  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:15.176  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:15.187  4324  6940 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:18:15.198  4324  6941 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:15.199  4324  6941 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:15.247  1037  1919 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6945 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 12:18:15.326  6945  6945 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:15.327  6945  6945 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:15.328  6945  6945 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:18:15.329  6945  6945 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 12:18:15.432  6945  6945 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-28 12:18:15.461  6945  6945 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-28 12:18:15.515  6945  6945 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-28 12:18:15.554  6945  6945 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:15.554  6945  6945 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:15.644  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:18:15.647   310   895 D SoftapController: Softap fwReload - Ok
07-28 12:18:15.650  1037  1526 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (813ms)
07-28 12:18:15.653   310   895 D CommandListener: Setting iface cfg
07-28 12:18:15.653   310   895 D CommandListener: Trying to bring down wlan0
07-28 12:18:15.656   310   895 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:18:15.661  1037  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-28 12:18:15.663  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:15.663  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:15.663  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:18:15.664  1037  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:18:15.664  1037  1526 D WifiMonitor: connecting to supplicant
07-28 12:18:15.665  1037  1526 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-28 12:18:15.668  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:15.669  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:15.655  6973  6973 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:15.655  6973  6973 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:15.670  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 12:18:15.676  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 12:18:15.679  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:18:15.693  6973  6973 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:18:15.719  6945  6945 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:18:15.727  6973  6973 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:18:15.727  6973  6973 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-28 12:18:15.730  1037  1119 D Tethering: InitialState.processMessage what=4
07-28 12:18:15.731  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:18:15.756  6945  6945 I HubEmail: JNI_OnLoad()
07-28 12:18:15.756  6945  6945 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:18:15.756  3442  3442 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,07-28 12:18:15.756  6945  6945 I HubEmail: registerNatives()
07-28 12:18:15.756  6945  6945 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:18:15.756  3442  3442 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:15.756  6945  6945 I HubEmail: registerNativeMethods()
07-28 12:18:15.756  6945  6945 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:18:15.756  3442  3442 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:18:15.756  6945  6945 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,07-28 12:18:15.800  1037  1949 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6984 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-28 12:18:15.806  6844  6981 W FormManager: Network not available. Please check & try again.
07-28 12:18:15.809  6844  6982 V FormManager: Network unavailable.
07-28 12:18:15.810  6973  6973 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:18:15.813  6844  6982 V FormManager: Network unavailable.
,07-28 12:18:15.817  6945  6983 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:15.821  1037  2000 I ActivityManager: Killing 6495:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-28 12:18:15.845  6973  6973 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-28 12:18:15.848  6973  6973 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,07-28 12:18:15.851  1037  1891 W libprocessgroup: failed to open /acct/uid_10061/pid_6495/cgroup.procs: No such file or directory
,07-28 12:18:15.871  6973  6973 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,07-28 12:18:15.897  6984  6984 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:15.897  6984  6984 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:15.899  6984  6984 D PhoneMonitor: Register our PhoneStateListener
,07-28 12:18:15.913  6984  6984 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-28 12:18:15.919  6984  6984 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 12:18:15.942  6984  6984 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-28 12:18:15.944  6984  6984 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-28 12:18:15.946  6984  6984 D TelephonyAutoProfiling: [parse] Load xml
07-28 12:18:15.954  6984  6984 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-28 12:18:15.954  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,07-28 12:18:15.955  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-28 12:18:15.958  6984  6984 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-28 12:18:15.958  6984  6984 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
07-28 12:18:15.964  1037  1891 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7003 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:18:15.965  6984  6984 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-28 12:18:15.966  1037  1891 I ActivityManager: Killing 6109:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-28 12:18:16.013  1037  1919 W libprocessgroup: failed to open /acct/uid_10080/pid_6109/cgroup.procs: No such file or directory
,07-28 12:18:16.263  1037  2019 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7028 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,07-28 12:18:16.267  1037  2019 I ActivityManager: Killing 6139:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-28 12:18:16.322  1037  1873 W libprocessgroup: failed to open /acct/uid_10097/pid_6139/cgroup.procs: No such file or directory
,07-28 12:18:16.435  1037  1872 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7045 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:18:16.438  1037  1872 I ActivityManager: Killing 6594:com.lge.eula/1000 (adj 15): empty #17
,07-28 12:18:16.493  1037  1873 W libprocessgroup: failed to open /acct/uid_1000/pid_6594/cgroup.procs: No such file or directory
,07-28 12:18:16.494  6973  6973 E wpa_supplicant: USIM:  scard_init function
,07-28 12:18:16.495  6973  6973 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:18:16.527  7045  7045 I art     : Almond Protected OAT
,07-28 12:18:16.588  7045  7045 D WeatherApplication: removeAccount
,07-28 12:18:16.590  7045  7045 D WeatherApplication: Account.length = 0
,07-28 12:18:16.590  7045  7045 E WeatherApplication: OPERATOR:OPEN
07-28 12:18:16.597  7045  7045 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:16
07-28 12:18:16.600  7045  7045 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:18:16.600  7045  7045 D Weather.Utils: 2 : All the weather widget is gone.
,07-28 12:18:16.603  7045  7045 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:18:16.607  7045  7045 D WeatherAncestor: connectivity changed - connection : true
07-28 12:18:16.608  7045  7045 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-28 12:18:16.620  7045  7045 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,07-28 12:18:16.622  7045  7045 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:18:16.622  7045  7045 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
07-28 12:18:16.644  6973  6973 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:18:16.646  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:18:16.658  7045  7045 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:18:16.659  7045  7045 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:16
07-28 12:18:16.670  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:16.670  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-28 12:18:16.671  6973  6973 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:18:16.671  6973  6973 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:18:16.672  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:18:16.672  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:18:16.672  1037  7063 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:18:16.672  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,07-28 12:18:16.673  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-28 12:18:16.673  1037  7063 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:18:16.676  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:18:16.676  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:18:16.677  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:18:16.677  1037  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:18:16.678  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:16.678  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:16.679  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:16.679  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:16.680  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:16.680  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:16.680  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:16.681  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:16.681  1037  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:18:16.681  1037  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:18:16.682  1037  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:18:16.682  1037  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:18:16.683  1037  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:18:16.706  1037  1928 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7064 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:18:16.707  1037  1928 I ActivityManager: Killing 6615:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:18:16.742  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.742  1037  1524 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:18:16.844  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:16.844  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:16.844  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:18:16.844  1037  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6615/cgroup.procs: No such file or directory
,07-28 12:18:16.852  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.852  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.852  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.852  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.852  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:16.863  1037  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
,07-28 12:18:16.867  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:16.868  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:16.868  1929  1929 D WfdService: Waiting for WifiP2p enabling
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:16.868  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:16.868  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:16.868  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:16.869  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:18:16.869  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:18:16.869  1037  1526 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:18:16.869  1037  1526 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:18:16.869  1037  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:18:16.870  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:16.870  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:16.870  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:16.870  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:16.870  1037  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
07-28 12:18:16.878  1037  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-28 12:18:16.889  1037  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:18:16.889  1037  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:18:16.890  1037  1526 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:18:16.890  1037  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:18:16.891  1037  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:18:16.891  1037  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:18:16.891  1037  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
,07-28 12:18:16.891  1037  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:18:16.892  1037  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:18:16.892  1037  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:18:16.892  1037  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:18:16.892  1037  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:18:16.893  1037  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:18:16.893  1037  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:18:16.893  1037  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:18:16.893  1037  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:18:16.893  1037  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:18:16.895  1929  1929 D WfdsService: Supplicant Connection state is changed : true
07-28 12:18:16.895  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:18:16.895  1037  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:18:16.895  1929  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:18:16.895  1929  2242 D WfdsService: Set the WFDS Monitor: true
07-28 12:18:16.895  1929  2242 D WfdsMonitor: WfdsMonitorThread create
07-28 12:18:16.896  1037  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:18:16.896  1037  1526 D WifiNative-HAL: Setting external_sim to 1
07-28 12:18:16.896  1037  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:18:16.896  1929  2242 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:18:16.896  1037  1526 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:18:16.896  1929  2242 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:18:16.896  1037  1526 I WifiNative-HAL: startHal
07-28 12:18:16.896  1037  1526 D wifi    : setting scan oui 0x9576d260
07-28 12:18:16.897  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:18:16.897  1037  1526 I WifiNative-HAL: startHal
07-28 12:18:16.897  1037  1526 D wifi    : setting scan oui 0x9576d260
07-28 12:18:16.897  1037  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:18:16.897  1929  7093 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:18:16.897  1037  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:18:16.897  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:18:16.898  1929  7093 E CtrlSupplicant: Succeed to open control connection
07-28 12:18:16.898  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:18:16.898  1929  7093 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:18:16.898  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:18:16.898  1929  7093 D WfdsMonitor: Supplicant connection established
07-28 12:18:16.898  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:18:16.898  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:18:16.898  1929  2242 D WfdsService: Connected to the supplicant for wfds
07-28 12:18:16.899  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:18:16.899  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:18:16.899  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:18:16.899  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:18:16.899  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:18:16.899  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:18:16.899  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:18:16.900  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:18:16.900  6,973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:18:16.900  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:18:16.900  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:18:16.900  6973  6973 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:18:16.900  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:18:16.900  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:18:16.901  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:18:16.901  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:18:16.902  1037  1526 E WifiNative: : [139,275,213 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:18:16.902  1037  1526 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:18:16.902  1037  1526 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:18:16.903  1037  1526 D WifiNative-wlan0: doString: [STATUS]
07-28 12:18:16.903  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:16.903  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:16.903  1037  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:18:16.903  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:16.904  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:16.904  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.906  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:18:16.906  1037  1037 D RttService: SCAN_AVAILABLE : 3
07-28 12:18:16.906  1037  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.906  1037  1543 I WifiNative-HAL: startHal
07-28 12:18:16.906  1037  1543 D wifi    : getting scan capabilities on interface[1] = 0x9576d260
07-28 12:18:16.906  1037  1543 D wifi    : failed to get capabilities : -3
07-28 12:18:16.906  1037  1543 E WifiScanningService: could not get scan capabilities
,07-28 12:18:16.907  1037  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.907   310   895 D CommandListener: Setting iface cfg
07-28 12:18:16.907   310   895 D CommandListener: Trying to bring up p2p0
07-28 12:18:16.907  1037  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:18:16.907  1037  1524 D LGWifiP2pService: P2pEnablingState
07-28 12:18:16.908  1037  1524 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:18:16.908  1037  1524 D LGWifiP2pService: P2p socket connection successful
07-28 12:18:16.908  1037  1524 D LGWifiP2pService: P2pEnabledState
07-28 12:18:16.908  1037  1524 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 12:18:16.908  1037  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:18:16.911  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:18:16.911  1929  1929 D WfdsService: WifiP2pState is changed : true
07-28 12:18:16.912  1929  2242 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:18:16.912  1929  2242 D WfdsService: Set the WFDS Monitor: true
07-28 12:18:16.912  1037  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:18:16.912  1929  2242 D WfdsService: Connected to the supplicant for wfds
07-28 12:18:16.912  1929  2242 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:18:16.912  1037  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:18:16.912  6973  6973 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:18:16.912  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:18:16.913  1929  2242 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
07-28 12:18:16.913  6973  6973 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
07-28 12:18:16.913  1929  2242 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
07-28 12:18:16.913  1929  2242 D WfdsService: selectPreferredScanChannel [36]
07-28 12:18:16.913  1929  2242 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:18:16.913  1929  1929 D WfdsService: isConnected: false
07-28 12:18:16.913  1037  1524 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:18:16.913  1037  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:18:16.913  1037  1524 D LGWifiP2pService: before postfix = G3
07-28 12:18:16.914  1037  1524 D WifiServerServiceExt: postfix byte check : 2
07-28 12:18:16.914  1037  1524 D LGWifiP2pService: after postfix = G3
07-28 12:18:16.914  1037  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:18:16.914  1037  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:18:16.914  1037  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:18:16.915  1037  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:18:16.915  1037  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:18:16.915  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:18:16.915  1037  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:18:16.915  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:18:16.916  1037  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:18:16.916  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:18:16.916  1037  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:18:16.916  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:18:16.917  1037  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:18:16.917  1037  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:18:16.917  1037  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:18:16.917  1037  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:18:16.918  1037  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:18:16.918  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=139291  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:18:16.918  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:18:16.918  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:18:16.918  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_,ATCION
07-28 12:18:16.918  1929  1929 D WfdsService: Update P2p Interface State: 3
07-28 12:18:16.918  1037  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:18:16.919  1037  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:18:16.919  1037  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,07-28 12:18:16.919  1037  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:18:16.924  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:16.924  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:16.928  1037  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 12:18:16.928  1037  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:18:16.928  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:16.928  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.928  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.928  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:18:16.929  1037  1524 D LGWifiP2pService: InactiveState
07-28 12:18:16.929  1037  1524 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:18:16.929  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.929  1037  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:18:16.931  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:18:16.932  6973  6973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:16.936  6973  6973 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:18:16.937  6973  6973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.937  1037  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:18:16.937  6973  6973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.938  1037  1524 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.938  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.938  1037  1524 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.938  1929  7093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:18:16.938  1929  7093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:16.938  1929  7093 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:16.938  1037  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:18:16.938  1037  1524 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.938  1037  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:16.938  1037  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:16.939  1037  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:16.939  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.939  1037  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:16.939  1037  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.939  1037  1524 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.939  1037  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.939  1037  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.939  1037  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:16.939  1037  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.939  1037  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.939  1037  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:16.939  1037  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.939  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.939  1037  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.939  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STA,TE_CHANGE_EVENT 22 0 rt=139313  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:18:16.940  1929  2242 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:18:16.940  1037  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139314
07-28 12:18:16.941  1037  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139315
07-28 12:18:16.941  1037  1524 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.941  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.941  1037  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.941  1037  1526 D WifiNative-wlan0: doString: [STATUS]
07-28 12:18:16.942  1037  1037 E WifiServerServiceExt: No p2p device connected
07-28 12:18:16.942  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:16.942  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:16.942  1037  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:18:16.944  1037  1526 I WifiServiceExtension: setVHTCapabilityType  : false
,07-28 12:18:16.951  1037  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:18:16.951  1037  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 12:18:16.955  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:16.955  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:16.956  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.956  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.956  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:18:16.956  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:16.962  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:18:16.962  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.962  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:18:16.964  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.964  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:16.965  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:18:16.970  1037  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:18:16.971  1037  1532 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:18:16.971  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:18:16.971  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:18:16.971  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:18:16.971  1037  1532 D ConnectivityService: NetworkAgent connected
,07-28 12:18:16.972  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:18:16.972  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:18:16.976  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:18:16.976  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:18:16.976  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:18:16.976  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:18:16.976  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:18:16.978  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:16.979  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:16.979  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:18:16.980  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:16.981   310   895 D CommandListener: Setting iface cfg
07-28 12:18:16.982  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:16.982  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:16.983  1037  1526 E WifiStateMachine: Start Dhcp Watchdog 2
07-28 12:18:16.983  1037  7098 D DhcpStateMachine: StoppedState
07-28 12:18:16.983  1037  7098 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:16.983  1037  7098 D DhcpStateMachine: WaitBeforeStartState
,07-28 12:18:16.984  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=139358  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:16.984  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=139358  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:16.985  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=139359  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:16.986  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:18:16.986  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:18:16.986  1037  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:18:16.987  1037  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:18:16.987  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:18:16.988  1037  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:18:16.988  1037  1526 E WifiStateMachine:  ObtainingIpState what:132106 1 0
07-28 12:18:16.989  1037  1526 E WifiStateMachine:  L2ConnectedState what:132106 1 0
07-28 12:18:16.989  1037  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:18:16.989  1037  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:18:16.989  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:16.989  1037  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:18:16.990  6973  6973 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:18:16.990   281   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:18:16.990   281   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:18:16.990   281   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:18:16.991  1037  1526 E WifiStateMachine:  ObtainingIpState what:132096 -100 0
07-28 12:18:16.991  1037  1526 E WifiStateMachine:  L2ConnectedState what:132096 -100 0
07-28 12:18:16.992  7064  7097 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 12:18:16.992  1037  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:18:16.993  1037  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:18:16.993  1037  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:18:16.993  6973  6973 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:18:16.994  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:18:16.994  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:18:16.994   281   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:18:16.994  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:16.994   281   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:18:16.994   281   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:18:16.995  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:16.995  7064  7097 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:18:16.995  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:16.996  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:16.996  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:18:16.996  6973  ,6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:18:16.996  6973  6973 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:16.996  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:18:16.996  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:16.996  1037  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:16.996  1037  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:16.997  1037  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:18:16.997  1037  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,07-28 12:18:16.997  1037  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:18:16.997  1037  1526 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:18:16.998  6973  6973 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 12:18:16.999  1037  1526 D WifiNative-wlan0: SCAN: returned true
07-28 12:18:16.999  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:18:16.999  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:18:16.999  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=139373  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:16.999  1037  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:18:16.999  1037  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,07-28 12:18:17.000  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=139373  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:17.000  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=139374  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:17.001  1037  1526 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-28 12:18:17.001  1037  1526 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:17.002  1037  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE,
07-28 12:18:17.002  1037  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-28 12:18:17.003  1037  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:17.003  1037  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-28 12:18:17.004  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:17.004  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,07-28 12:18:17.005  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=139379  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,07-28 12:18:17.006  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=139380  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:17.006   281   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,07-28 12:18:17.006   281   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:18:17.006   281   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:18:17.006  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=139380  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:17.006  7064  7101 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-28 12:18:17.008  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:93773] from screen [on:0 period:822281775] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-28 12:18:17.008   281   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,07-28 12:18:17.008   281   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:18:17.008   281   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:18:17.008  7064  7101 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:18:17.008  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:822281776] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-28 12:18:17.008  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:18:17.097  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.099  1037  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-28 12:18:17.100  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.101  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:18:17.102  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.103  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.104  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.105  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.106  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:18:17.107  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
07-28 12:18:17.109  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
07-28 12:18:17.109  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:18:17.110  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:18:17.111  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:18:17.111  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:18:17.112  1037  1526 D WifiNative-wlan0: SET ps 0: returned true
,07-28 12:18:17.112  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:18:17.113  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:18:17.117  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:18:17.117  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cf8285c target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.118  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2cf8285c target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.118  1037  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,07-28 12:18:17.118  1037  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:18:17.118  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:18:17.118  1037  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:18:17.118  1037  7063 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:18:17.119  1929  7093 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
07-28 12:18:17.119  1037  7098 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.119  1037  7098 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:18:17.119  1929  7093 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
07-28 12:18:17.119  1037  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:18:17.119  1037  7063 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:18:17.119  1037  7063 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
07-28 12:18:17.119  1037  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:18:17.120  1037  7063 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:18:17.120  1037  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.120  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.120  1037  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.122   310   895 D CommandListener: Setting iface cfg
07-28 12:18:17.123   310   895 D CommandListener: Trying to bring up wlan0
07-28 12:18:17.125  1037  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:18:17.125  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:17.126  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:18:17.127  1037  1526 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:18:17.127  1037  1526 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:18:17.128  1037  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:18:17.128  1037  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:18:17.129  1037  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-28 12:18:17.129  1037  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 12:18:17.129  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:17.129  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:18:17.146  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:18:17.147  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.147  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.148  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.149  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.150  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.150  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:18:17.151  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:18:17.152  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:18:17.152  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:18:17.153  1037  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.153  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.153  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:18:17.154  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:18:17.154  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:18:17.155  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:18:17.156  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:18:17.156  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:17.170  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
,07-28 12:18:17.174  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:18:17.175  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:18:17.175  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:18:17.176  1037  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:18:17.177  1037  1532 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:18:17.179  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:17.179  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:17.180  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.180  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.180  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:18:17.181  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.182  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:18:17.183  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.183  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.183  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:18:17.184  1037  1532 D ConnectivityService: Adding iface wlan0 to network 101
07-28 12:18:17.186  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:18:17.186  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:18:17.186  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.186  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:18:17.186  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:18:17.188  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:18:17.189  1037  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:18:17.195  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.195  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.195  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:18:17.201  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:17.201  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:17.202  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.205  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:18:17.205  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:18:17.205  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.209  1037  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:18:17.209  1037  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-28 12:18:17.210  1037  1526 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,07-28 12:18:17.210  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:18:17.211  1037  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-28 12:18:17.212   310   895 E Netd    : netlink response contains error (File exists)
07-28 12:18:17.212  1037  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-28 12:18:17.213  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:17.213  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:18:17.213  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.213  1037  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:18:17.213  1037  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-28 12:18:17.213  1037  1532 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-28 12:18:17.219  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:18:17.219  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.220  1037  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.220  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.220  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:17.220  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.220  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:18:17.220  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.220  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:18:17.220  1037  1532 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:18:17.220  1037  1532 D ConnectivityService:    accepting network in place of null
07-28 12:18:17.220  1037  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.221  1037  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:18:17.221  1037  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:18:17.221  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:18:17.221  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.co,nn.CONNECTIVITY_CHANGE
07-28 12:18:17.222  1037  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:18:17.222  1037  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,07-28 12:18:17.222  1838  1838 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.223  1037  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.223  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:17.223  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:18:17.223  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:18:17.223  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:18:17.224  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:18:17.224  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:18:17.225  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.225  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:18:17.225  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.226  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:18:17.227  1037  1532 D ConnectivityService: validation of new default Network = false
07-28 12:18:17.227  1037  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:18:17.227  1037  1532 D DSQN    : enableDataServiceNotify 
07-28 12:18:17.227  1037  1532 D DSQN    : start dsqn bin
07-28 12:18:17.229   310  7119 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-28 12:18:17.230   310  7119 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-28 12:18:17.215  7120  7120 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:17.215  7120  7120 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:17.232  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.232  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.232  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.232  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.234  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:18:17.241  7120  7120 E DSQN    : DSQN ssw
07-28 12:18:17.250  1037  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-28 12:18:17.256  1803  7124 I CheckinService: active receiver: enabled
,07-28 12:18:17.265  7064  7064 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-28 12:18:17.266  1803  7124 I CheckinService: Preparing to send checkin request
07-28 12:18:17.266  1803  7124 I EventLogService: Accumulating logs since 1469701015183
07-28 12:18:17.268  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:17.268  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.269  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.277  7064  7064 I LibraryLoader: Loading: webviewchromium
07-28 12:18:17.279  7064  7064 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9664-9667)
07-28 12:18:17.279  7064  7064 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:18:17.281   310  7119 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-28 12:18:17.283  7064  7064 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {380efb93}
07-28 12:18:17.284  7064  7064 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:18:17.284  7064  7064 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:18:17.292  7064  7064 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:18:17.293  7064  7064 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:18:17.302  7064  7064 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:18:17.303  7064  7064 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-28 12:18:17.303  7064  7064 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,07-28 12:18:17.305   316  2125 V AudioPolicyService: registerClient() client 0xb558ad40, uid 10093
07-28 12:18:17.307  7064  7131 W AudioManagerAndroid: Requires BLUETOOTH permission
07-28 12:18:17.307  1803  7124 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-28 12:18:17.311   310   894 D LGDataListener: argv[0]=dsqncommand
07-28 12:18:17.311   310   894 D LGDataListener: argv[1]=wlan0
,07-28 12:18:17.311   310   894 D LGDataListener: argv[2]=1
07-28 12:18:17.311   310   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 12:18:17.312  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 12:18:17.312  1037  1117 D DSQN    : start to monitor internet connection
07-28 12:18:17.315  7064  7064 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:18:17.315  7064  7064 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:18:17.315  7064  7064 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:18:17.315  7064  7064 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:18:17.315  7064  7064 I Adreno-EGL: Remote Branch: 
07-28 12:18:17.315  7064  7064 I Adreno-EGL: Local Patches: 
07-28 12:18:17.315  7064  7064 I Adreno-EGL: Reconstruct Branch: 
07-28 12:18:17.320  1037  7098 D DhcpStateMachine: DHCPV4 request on wlan0
07-28 12:18:17.321  1037  7098 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:18:17.321  1037  7098 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-28 12:18:17.315  7141  7141 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:17.315  7141  7141 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:17.331  7141  7141 I dhcpcd  : version 5.5.6 starting
07-28 12:18:17.333  7141  7141 E dhcpcd  : get_duid: m
07-28 12:18:17.333  7141  7141 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:18:17.333  7141  7141 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-28 12:18:17.336  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:18:17 GMT], X-Android-Received-Millis=[1469701097336], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469701097310]}
07-28 12:18:17.336  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:18:17.336  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 12:18:17.336  1037  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.336  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.336  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:17.336  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.336  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:18:17.336  1037  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-28 12:18:17.336  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:18:17.336  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.336  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.337  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.337  1037  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:18:17.337  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:18:17.338  1037  1526 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.338  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:17.338  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:18:17.339  1838  1838 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.339  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:18:17.358  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:17.359  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.359  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:17.380  7141  7141 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:18:17.380  7141  7141 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:18:17.380  7141  7141 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:18:17.380  7141  7141 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,07-28 12:18:17.381  7064  7064 I NSApplication: Starting up...
,07-28 12:18:17.381  7141  7141 D dhcpcd  : wlan0: sending REQUEST (xid 0x9d5677be), next in 4.40 seconds
07-28 12:18:17.401  7141  7141 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-28 12:18:17.416  1037  1891 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7153 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-28 12:18:17.422  7141  7141 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:18:17.422  7141  7141 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:18:17.422  7141  7141 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:18:17.422  7141  7141 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:18:17.422  7141  7141 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:18:17.423  7141  7141 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:18:17.423  7141  7141 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:18:17.423  7141  7141 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:18:17.428   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 243us total 12.153ms
,07-28 12:18:17.442   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 11.655ms
,07-28 12:18:17.453   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.067ms
07-28 12:18:17.483  1037  1053 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7178 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-28 12:18:17.484  1037  1053 I ActivityManager: Killing 6071:com.android.vending/u0a44 (adj 15): empty #17
,07-28 12:18:17.550  1037  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_6071/cgroup.procs: No such file or directory
07-28 12:18:17.577  7153  7153 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-28 12:18:17.577  7153  7153 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-28 12:18:17.596  7178  7178 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:18:17.610  7153  7153 I MultiDex: VM with version 2.1.0 has multidex support
07-28 12:18:17.610  7153  7153 I MultiDex: install
,07-28 12:18:17.610  7153  7153 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-28 12:18:17.620  7153  7153 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-28 12:18:17.724  1037  7098 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-28 12:18:17.726  1037  7098 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:18:17.726  1037  7098 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:18:17.727  1037  7098 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:18:17.727  1037  7098 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 12:18:17.727  1037  7098 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:18:17.727  1037  7098 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:18:17.727  1037  7098 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:18:17.727  1037  7098 D DhcpStateMachine: RunningState
07-28 12:18:17.817  1037  2037 I art     : Explicit concurrent mark sweep GC freed 102523(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.566ms total 122.650ms
,07-28 12:18:17.830  1037  2019 D WifiServiceImplEx: setWifiEnabled: false pid=6577, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:18:17.830  1037  2019 D WifiService: setWifiEnabled: false pid=6577, uid=10118
07-28 12:18:17.830  1037  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:18:17.837  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:18:17.837  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:17.837  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-28 12:18:17.838  1037  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:17.838  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:17.839  1037  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:17.839  1037  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:17.839  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:18:17.840  1037  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:18:17.840  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:18:17.840  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:18:17.840  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:18:17.840  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:18:17.844  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:18:17.844  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.844  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.845  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:18:17.845  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:18:17.845  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:18:17.845  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:17.845  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:17.846  1037  7098 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.846   310   895 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:18:17.863  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:18:17.863  1037  1532 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:18:17.863  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
07-28 12:18:17.866  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:18:17.866  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.866  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.866  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:17.866  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.866  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:17.866  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.867  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.867  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 12:18:17.867  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:17.867  1037  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:18:17.867  1037  1524 D LGWifiP2pService: InactiveState{ when=-2ms, what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.867  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.867  1037  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@7b60254
07-28 12:18:17.868  1037  1524 D LGWifiP2pService: P2pDisablingState
07-28 12:18:17.868  1037  1524 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.868  1037  1524 D LGWifiP2pService: p2p socket connection lost
07-28 12:18:17.868  1037  1524 D LGWifiP2pService: P2pDisabledState
07-28 12:18:17.868  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.870  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:18:17.870  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:18:17.870  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:18:17.870  1929  1929 D WfdsService: WifiP2pState is changed : false
07-28 12:18:17.870  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.870  1929  2242 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:18:17.870  1037  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.870  1929  2242 D WfdsService: Set the WFDS Monitor: false
07-28 12:18:17.871  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-28 12:18:17.871  1929  2242 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:18:17.871  1929  2242 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:18:17.871  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.871  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.871  1929  7093 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:18:17.871  1929  7093 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:18:17.871  1929  7093 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:18:17.871  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:17.871  1929  7093 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:18:17.871  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-28 12:18:17.871  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.872  1929  2244 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:18:17.872  1929  2242 W WfdsService: DefaultState - msg [9445378] is not handled
,07-28 12:18:17.873  6973  6973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:18:17.874  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.874  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:17.874  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:18:17.874  1037  1037 D RttService: SCAN_AVAILABLE : 1
07-28 12:18:17.875  1037  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.875  1037  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.875  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:18:17.875  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:17.876  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:17.890  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:17.890  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:18:17.891  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:17.897   310   895 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:18:17.897  1037  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 12:18:17.897  1037  1532 D DSQN    : disableDataServiceNotify
07-28 12:18:17.897  1037  1532 D DSQN    : stop dsqn bin
07-28 12:18:17.898  1037  1526 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:18:17.899  1037  1526 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:18:17.899  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:17.899  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:17.899  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:18:17.899  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-28 12:18:17.901  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.901  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.901  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:17.901  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
,07-28 12:18:17.903  1037  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-28 12:18:17.903  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.903  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.903  1037  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:17.903  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 12:18:17.904  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.904  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:17.904  1037  7094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:18:17.904  1037  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 12:18:17.904  1037  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:18:17.904  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:18:17.904  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:17.904  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:18:17.905  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:17.905  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:18:17.905  1037  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.905  1037  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.905  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:18:17.905  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:18:17.906  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:18:17.906  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: fals,e
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:17.906  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:17.906  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:17.906  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:17.906  1838  1838 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.906  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:18:17.906  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:18:17.906  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:18:17.906  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:18:17.906  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:18:17.907  1037  1532 D NetworkManagementService: Removing idletimer
07-28 12:18:17.907  1037  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:17.909  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:18:17.909  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:18:17.909  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:18:17.909  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:18:17.909  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:18:17.911  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:18:17.911  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:17.912  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:17.912  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - act,ive network type is Wi-Fi: true
07-28 12:18:17.912  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:17.912  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:17.912  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.913  1037  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:17.913  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:17.917  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:17.917  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:18:17.918  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:17.936  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:17.937  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.937  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:17.948  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:17.949  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.949  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:17.962  6973  6973 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:18:17.962  6973  6973 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:18:17.962  6973  6973 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1929-4\x00 that cannot receive messages
07-28 12:18:17.964  1037  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:18:17.964  1037  7063 D WifiMonitor: Dropping event because (p2p0) is stopped
,07-28 12:18:17.967  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:18:17.969  6371  6398 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:18:17.979  2094  2094 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:17.984  6973  6973 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:18:17.985  6973  6973 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:18:17.985  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:18:17.985  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:18:17.985  1037  7063 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:18:17.985  1037  7063 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:18:17.985  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:17.985  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:17.986  1037  1119 D Tethering: InitialState.processMessage what=4
07-28 12:18:17.986  1037  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=140359
07-28 12:18:17.986  1037  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=140360
07-28 12:18:17.986  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=140360  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:18:17.986  1037  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=140360  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:18:17.988  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:18:17.988  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:17.988  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:18:17.988  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:18:17.988  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:18:17.989  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:17.989  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:17.989  6917  6917 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:18:17.994  6917  6917 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e3c7c46
07-28 12:18:17.994  6917  6917 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:18:17.994  6917  6917 D AppUp4:CustFacade: isPhone : true
07-28 12:18:17.994  6917  6917 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:18:17.994  6917  6917 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:18:17.997  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:17.997  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:18:17.998  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:17.999  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:18.001  7153  7169 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:18.002  7153  7169 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:18:18.002  4324  7225 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:18:18.003  6945  6945 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:18:18.012  4324  7226 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:18.012  4324  7226 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:18.020  6844  7230 W FormManager: Network not available. Please check & try again.
,07-28 12:18:18.022  6945  7228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:18:18.026  3442  3442 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:18:18.026  3442  3442 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:18.026  3442  3442 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:18:18.028  6984  6984 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:18:18.028  6984  6984 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:18:18.032  6844  7231 V FormManager: Network unavailable.
,07-28 12:18:18.036  7045  7045 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:18
07-28 12:18:18.037  6844  7231 V FormManager: Network unavailable.
07-28 12:18:18.038  7045  7045 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:18:18.038  7045  7045 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:18:18.042  7045  7045 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:18:18.042  7045  7045 D WeatherAncestor: connectivity changed - connection : true
07-28 12:18:18.042  7045  7045 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3db92b34
07-28 12:18:18.042  7045  7045 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:18:18.042  7045  7045 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:18:18.043  7045  7045 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:18:18.043  7045  7045 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:18:18.043  7045  7045 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:18
,07-28 12:18:18.051  1037  7098 D DhcpStateMachine: StoppedState
,07-28 12:18:18.051  1037  7098 D DhcpStateMachine: StoppedState{ when=-175ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:18.053  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 12:18:18.053  1037  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 12:18:18.062  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:18:18.062  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:18:18.062  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:18:18.062  6776  6776 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 12:18:18.063  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:18:18.064  6776  6776 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:18:18.064  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:18:18.064  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:18:18.064  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:18:18.064  6776  6776 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:18:18.064  6776  6776 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:18:18.070  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:18.072  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:18:18.075  7235  7235 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-28 12:18:18.076  6844  7238 W FormManager: Network not available. Please check & try again.
07-28 12:18:18.077  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.088  6844  7240 V FormManager: Network unavailable.
,07-28 12:18:18.091  6844  7240 V FormManager: Network unavailable.
07-28 12:18:18.099  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:18.102  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:18:18.106  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.113  6844  7245 W FormManager: Network not available. Please check & try again.
,07-28 12:18:18.116  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:18:18.116  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:18:18.116  7235  7235 I dex2oat : dex2oat took 40.881ms (threads: 4)
07-28 12:18:18.117  6844  7246 V FormManager: Network unavailable.
07-28 12:18:18.118  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:18.119  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:18.120  6844  7246 V FormManager: Network unavailable.
07-28 12:18:18.122  6973  6973 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:18:18.123  1037  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:18:18.123  1037  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:18:18.123  1037  7063 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:18:18.123  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 38 0
07-28 12:18:18.125  4324  7248 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:18:18.125  4324  7247 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:18:18.127  7153  7169 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:18:18.127  7153  7169 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:18:18.127  7153  7169 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:18:18.127  7153  7169 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:18:18.127  7153  7169 I Adreno-EGL: Remote Branch: 
07-28 12:18:18.127  7153  7169 I Adreno-EGL: Local Patches: 
07-28 12:18:18.127  7153  7169 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:18:18.125  4324  7248 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:18.155  1037  1949 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7250 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:18:18.194  7153  7169 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:18:18.194  7153  7169 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:18:18.194  7153  7169 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:18:18.194  7153  7169 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:18:18.194  7153  7169 I Adreno-EGL: Remote Branch: 
07-28 12:18:18.194  7153  7169 I Adreno-EGL: Local Patches: 
07-28 12:18:18.194  7153  7169 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:18:18.224  1037  1526 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:18:18.224  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:18.224  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:18.224  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:18:18.226  1929  1929 D WfdsService: Supplicant Connection state is changed : false
07-28 12:18:18.226  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:18:18.226  1929  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:18:18.226  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:18:18.226  1929  2242 D WfdsService: Set the WFDS Monitor: false
07-28 12:18:18.226  1929  2242 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:18:18.226  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:18:18.226  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:18:18.226  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:18.226  2435  2435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:18.226  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:18.226  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:18.227  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:18.227  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:18.229  7250  7250 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:18:18.229  7250  7250 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-28 12:18:18.230  1037  1532 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
07-28 12:18:18.235  7250  7250 V [BNRBootReceiver]: Boot Receiver Return
07-28 12:18:18.237  7250  7250 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-28 12:18:18.242  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:18.249  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.256  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.266  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.266  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:18.268  6635  6635 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:18.270  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:18.277  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.284  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.290  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:18:18.291  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:18.292  6635  6635 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:18.296  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:18.300  7153  7169 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:18:18.300  7153  7169 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:18:18.300  7153  7169 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:18:18.300  7153  7169 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:18:18.300  7153  7169 I Adreno-EGL: Remote Branch: 
07-28 12:18:18.300  7153  7169 I Adreno-EGL: Local Patches: 
07-28 12:18:18.300  7153  7169 I Adreno-EGL: Reconstruct Branch: 
07-28 12:18:18.304  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.311  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.326  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.326  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:18.327  6635  6635 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:18:18.331  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:18.340  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.348  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.357  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.357  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:18.358  6635  6635 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:18.364  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-28 12:18:18.368  6776  6776 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:18:18.375  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:18.393  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.401  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:18:18.410  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.410  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:18.418  6635  6635 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:18.425  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:18.426  1037  1526 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:18:18.427  1037  1526 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
,07-28 12:18:18.439  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.454  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.460  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.461  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:18.463  6635  6635 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:18.475  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:18.481  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-28 12:18:18.496  1037  1531 D WifiService: New client listening to asynchronous messages
,07-28 12:18:18.498  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:18.503  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.513  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.522  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.523  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:18.524  6635  6635 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:18:18.526  6635  6635 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:18:18.527  6635  6635 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,07-28 12:18:18.532  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:18.537  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:18:18.538  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:18.542  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.555  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.563  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.564  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:18.565  6635  6635 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-28 12:18:18.567  6635  6635 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:18:18.568  6635  6635 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,07-28 12:18:18.572  1037  2019 I ActivityManager: Killing 6758:com.lge.lifetracker/u0a37 (adj 15): empty #17
,07-28 12:18:18.669  1037  2037 W libprocessgroup: failed to open /acct/uid_10037/pid_6758/cgroup.procs: No such file or directory
,07-28 12:18:18.682  2094  2094 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
07-28 12:18:18.690  2094  2094 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-28 12:18:18.691  2094  2094 D c       : Getting all permits...
07-28 12:18:18.691  2094  2094 D a       : Opening database...
07-28 12:18:18.701  2094  2094 D a       : Opening database auth.proximity.permit_store...
07-28 12:18:18.702  2094  2094 D a       : Closing database...
,07-28 12:18:18.713  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:18.717  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:18:18.717  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:18.717  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:18.721  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.736  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.743  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.743  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:18.745  6635  6635 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:18.747  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:18.751  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:18:18.752  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:18.752  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:18.754  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.768  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.773  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.774  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:18.775  6635  6635 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:18.780  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:18.784  6795  6795 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:18:18.784  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:18.784  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:18.788  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:18.803  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.810  6635  6635 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:18.810  6635  6635 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:18.811  6635  6635 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:18.820  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:18.824  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:18:18.831  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:18:18.842  6844  7275 W FormManager: Network not available. Please check & try again.
07-28 12:18:18.852  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:18:18.852  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:18:18.854  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:18:18.857  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:18.857  6844  7276 V FormManager: Network unavailable.
07-28 12:18:18.865  6795  6795 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:18:18.865  6795  6795 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:18:18.865  6795  6795 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:18.866  6844  7276 V FormManager: Network unavailable.
,07-28 12:18:18.871  4324  7277 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:18:18.873  4324  7278 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:18:18.873  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:18:18.873  4324  7278 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:18:18.882  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:18.891  6844  7280 V FormManager: Network unavailable.
,07-28 12:18:18.892   310  7282 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-28 12:18:18.893  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:18:18.893  6844  7279 W FormManager: Network not available. Please check & try again.
07-28 12:18:18.896  6844  7280 V FormManager: Network unavailable.
07-28 12:18:18.900  1803  7124 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-28 12:18:18.912  1803  7124 I CheckinService: active receiver: disabled
,07-28 12:18:18.936  2094  2094 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-28 12:18:20.104  1037  1526 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:822284872] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:18:20.106  1037  1526 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:822284874] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-28 12:18:20.224  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:20.235  1037  1119 D Tethering: MasterInitialState.processMessage what=3
07-28 12:18:20.256  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:18:20.260  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:20.265  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:18:20.268  6371  6398 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 12:18:20.276  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:20.282  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:18:20.314  2094  2094 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:20.340  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:18:20.341  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:20.341  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:18:20.341  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 12:18:20.347  6917  6917 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:18:20.350  6917  6917 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e3c7c46
07-28 12:18:20.350  6917  6917 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:18:20.350  6917  6917 D AppUp4:CustFacade: isPhone : true
07-28 12:18:20.351  6917  6917 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:18:20.352  6917  6917 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:18:20.360  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:20.360  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:18:20.365  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:20.368  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:20.384  4324  7298 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:18:20.394  4324  7299 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:20.394  4324  7299 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:20.413  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:18:20.431  6945  6945 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:18:20.460  6945  7310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:18:20.470  3442  3442 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:18:20.470  3442  3442 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:20.470  3442  3442 I LgeMiscReceiver: networkInfo.isConnected() = true
07-28 12:18:20.470  3442  3442 D PhoneState: setPdpRejectCasuse : false
07-28 12:18:20.472  6844  7313 W FormManager: Network not available. Please check & try again.
07-28 12:18:20.473  6984  6984 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-28 12:18:20.474  6984  6984 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 12:18:20.489  6844  7314 V FormManager: Network unavailable.
07-28 12:18:20.489  7045  7045 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:20
,07-28 12:18:20.492  7045  7045 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-28 12:18:20.492  7045  7045 D Weather.Utils: 2 : All the weather widget is gone.
,07-28 12:18:20.492  7045  7045 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-28 12:18:20.492  7045  7045 D WeatherAncestor: connectivity changed - connection : true
,07-28 12:18:20.493  7045  7045 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3db92b34
07-28 12:18:20.493  7045  7045 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,07-28 12:18:20.493  7045  7045 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,07-28 12:18:20.493  7045  7045 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:18:20.493  7045  7045 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:18:20.493  7045  7045 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:20
,07-28 12:18:20.495  6844  7314 V FormManager: Network unavailable.
07-28 12:18:20.839  1037  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:18:20.840  1037  1891 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:18:20.877  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-28 12:18:20.878  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:20.878  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:18:20.882  1037  1119 D BluetoothManagerService: Message: 1
,07-28 12:18:20.882  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:18:20.905  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:20.910  1037  1119 D Tethering: MasterInitialState.processMessage what=3
07-28 12:18:20.916  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:20.917  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:20.920  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:20.927  1037  1119 D Tethering: MasterInitialState.processMessage what=3
07-28 12:18:20.937  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:20.942  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:20.943  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:20.945  1037  1119 D BluetoothManagerService: Message: 20
07-28 12:18:20.945  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22daaa16:true
07-28 12:18:20.946  6878  6878 D BluetoothAdapterState: make
07-28 12:18:20.951  6878  6878 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:18:20.951  6878  6878 I bluedroid-qcom: init
,07-28 12:18:20.954  6878  7323 I BluetoothAdapterState: Entering OffState
07-28 12:18:20.955  6878  6878 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:18:20.955  6878  6878 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:18:20.955  6878  6878 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:18:20.956  6878  6878 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:18:20.956  6878  6878 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:18:20.957  6878  6878 I bluedroid-qcom: get_profile_interface socket
07-28 12:18:20.957  6878  6878 I bluedroid-qcom: get_profile_interface map_client
07-28 12:18:20.959  6878  7327 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:18:20.961  6878  7327 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:18:20.955  7326  7326 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:20.955  7326  7326 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:18:20.973  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:18:20.974  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:18:20.975  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,07-28 12:18:20.977  1037  1119 D BluetoothManagerService: Message: 40
07-28 12:18:20.977  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:18:20.980  7326  7326 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:18:20.980  7326  7326 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:18:20.980  7326  7326 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-28 12:18:20.981  6878  6893 I bluedroid-qcom: config_hci_snoop_log
07-28 12:18:20.983  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:18:20.983  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-28 12:18:20.985  7326  7326 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:18:20.989  7326  7326 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:18:20.989  7326  7326 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-28 12:18:20.998  6878  7327 D BluetoothAdapterProperties: Name is: G3
07-28 12:18:21.000  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:18:21.001  6878  7323 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:18:21.002  6878  7323 D BluetoothAdapterProperties: Setting state to 11
07-28 12:18:21.002  6878  7323 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-28 12:18:21.007  6371  6398 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:18:21.009  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:21.009  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:18:21.009  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:18:21.011  6878  7323 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:18:21.015  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:21.016  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-28 12:18:21.020  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:21.022  1037  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.023  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:18:21.023  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:21.025  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:18:21.030  6878  6878 V BluetoothPbapReceiver: PbapReceiver onReceive 
,07-28 12:18:21.036  6878  6878 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:21.036  6878  6878 V BluetoothPbapReceiver: ***********state = 11
07-28 12:18:21.038  6878  7323 D BluetoothBondStateMachine: make
07-28 12:18:21.041  6878  7323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
,07-28 12:18:21.042  6878  7345 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 12:18:21.042  6878  7323 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:18:21.042  6878  7323 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.042  6878  7323 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:18:21.043  6878  7323 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:18:21.044  5750  5750 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:18:21.046  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:21.047  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:18:21.053  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:18:21.055  6878  6878 D HeadsetService: Received start request. Starting profile...
07-28 12:18:21.055  6878  6878 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:18:21.056  6878  6878 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:18:21.059  6878  6878 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:18:21.060  6878  6878 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:18:21.060  6878  6878 D HeadsetStateMachine: make
07-28 12:18:21.097  6878  6878 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:21.097  6878  6878 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:21.101  1037  1983 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7349 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-28 12:18:21.104  6878  6878 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:18:21.104  6878  6878 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:18:21.105  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:21.105  1037  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:21.106  6878  6878 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:18:21.106  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:21.107   316   316 V AudioPolicyService: registerClient() client 0xb0410280, uid 1002
07-28 12:18:21.107   316  2125 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:18:21.107   316  2125 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:18:21.107   316  2125 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:18:21.107  6878  6878 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:18:21.107   316  1372 V AudioFlinger: registerClient() client 0xb57d3220, pid 6878
07-28 12:18:21.108   316  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:21.108  6878  6878 V ToneGenerator: Create Track: 0xb4928080
07-28 12:18:21.108  6878  6878 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:18:21.108  6878  6878 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:18:21.108   316  2125 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:18:21.108   316  2125 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:18:21.108   316  2125 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:18:21.108   316  2125 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:18:21.108  6878  6878 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:18:21.108   316  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:21.108  1037  1928 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:21.108  1037  1928 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:21.108   316  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:21.108   316  2125 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:18:21.108   316  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:21.108  3442  3457 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:21.108  3442  3457 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:21.109  6878  7343 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:21.109  6878  7343 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:18:21.109   316  1371 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:18:21.109  6878  7343 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:21.109   316  1371 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:18:21.109  6878  7343 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:18:21.109  1590  2171 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:21.109  3442  3458 ,V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:21.109   316  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:18:21.109  1590  2171 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:21.109  3442  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:21.109   316  1371 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:18:21.109  1037  1964 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:21.109  1590  2171 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:21.109  1590  2171 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:21.109  1037  1964 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:21.109  6878  6878 V AudioSystem: getLatency() output 2, latency 50
07-28 12:18:21.109  6878  6878 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:18:21.109  6878  6878 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:18:21.109   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:18:21.109   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:18:21.109   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:18:21.109   316  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:18:21.109   316  1371 V AudioFlinger: createTrack() lSessionId: 22
07-28 12:18:21.109  1838  4014 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:21.109  1838  4014 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:21.110  1838  4014 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:21.110  1838  4014 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:21.111  6878  6878 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:18:21.111   316   316 V AudioFlinger: acquiring 22 from 6878, for 6878
07-28 12:18:21.111   316   316 V AudioFlinger:  added new entry for 22
07-28 12:18:21.112  6878  6878 V ToneGenerator: ToneGenerator INIT OK, time: 143500
07-28 12:18:21.112  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.112  6878  7348 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:18:21.112  6878  7348 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:18:21.112  6878  7348 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:18:21.112  6878  7348 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:18:21.113   316  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6878
07-28 12:18:21.113   316  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:18:21.113   316  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:18:21.113   316  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:18:21.113   316  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:18:21.113   316  1371 V voice   : voice_set_parameters: exit with code(0)
07-28 12:18:21.113   316  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:18:21.113   316  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:18:21.113   316  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:18:21.113   316  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:18:21.113   316  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:18:21.113   316  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:18:21.114  6878  7348 V ToneGenerator: ToneGenerator destructor
07-28 12:18:21.114  6878  7348 V ToneGenerator: stopTone
07-28 12:18:21.114  6878  7348 V ToneGenerator: Delete Track: 0xb4928080
07-28 12:18:21.119  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.119  6878  6878 D HeadsetStateMachine: Proxy object connected
07-28 12:18:21.120  6878  6878 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:18:21.120  6878  6878 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-28 12:18:21.120  6878  7348 V AudioTrack: ~AudioTrack, releasing session id from 6878 on behalf of 6878
07-28 12:18:21.120   316  2125 V AudioFlinger: releasing 22 from 6878 for 6878
07-28 12:18:21.120   316  2125 V AudioFlinger:  decremented refcount to 0
07-28 12:18:21.120   316  2125 V AudioFlinger: purging stale effects
07-28 12:18:21.121   316  2125 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:18:21.121   316  2125 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:18:21.121   316  2125 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:18:21.121   316  1274 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:18:21.121   316  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:18:21.121   316  2125 V AudioFlinger: removeClient_l() pid 6878, calling pid 316
07-28 12:18:21.121   316  1274 V AudioPolicyManager: releaseOutput() 2
07-28 12:18:21.121   316  1274 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:18:21.123  6878  6878 D A2dpService: Received start request. Starting profile...
07-28 12:18:21.124  6878  6878 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:18:21.124  6878  6878 V Avrcp   : make
07-28 12:18:21.125  6878  6878 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:18:21.125  6878  6878 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:18:21.126  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:21.132  2094  2094 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.132  6878  6878 V AudioManager: registerRemoteController: size of Media player list: 0
07-28 12:18:21.133  6878  6878 E AudioManager: No RCC entry present to update
07-28 12:18:21.133  6878  6878 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:18:21.134  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:18:21.136  6878  6878 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:18:21.137  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:18:21.137  6878  6878 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:18:21.143  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:18:21.145  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:18:21.201  6878  7323 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:21.214  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,07-28 12:18:21.214  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.215  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:18:21.215  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:18:21.223  6878  7323 V LGMDMManager: Create singleton instance
07-28 12:18:21.225  6878  7323 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:18:21.225  6917  6917 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:18:21.233  6917  6917 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e3c7c46
07-28 12:18:21.233  6917  6917 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:18:21.233  6917  6917 D AppUp4:CustFacade: isPhone : true
07-28 12:18:21.240  6917  6917 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:18:21.241  6917  6917 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:18:21.245  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.245  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:18:21.246  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:18:21.249  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:21.257  6945  6945 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:18:21.259  4324  7369 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:18:21.260  4324  7370 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.260  4324  7370 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:21.265  1037  1919 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:18:21.265  1037  1919 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:18:21.266  7349  7349 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 12:18:21.267  7349  7349 W LG Account v2.2: No ProfileInfo entries
07-28 12:18:21.267  7349  7349 I LG Account v2.2: isEnabled: false
07-28 12:18:21.267  7349  7349 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:18:21.267  7349  7349 I Feature : [Lifetracker]Country: EU
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Operator: OPEN
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Ranking support: false
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Comfort support: false
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Accessory: true
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Health device: true
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:18:21.268  7349  7349 I Feature : [Lifetracker]Device Number: 3
07-28 12:18:21.277  6945  7373 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:18:21.282  3442  3442 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:18:21.282  3442  3442 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.282  3442  3442 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:18:21.283  6776  6776 D BluetoothPermissionRequest: onReceive
07-28 12:18:21.288  6984  6984 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:18:21.288  6984  6984 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:18:21.288  6844  7375 W FormManager: Network not available. Please check & try again.
,07-28 12:18:21.294  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:21.300  7045  7045 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:21
,07-28 12:18:21.301  7045  7045 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:18:21.301  7045  7045 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:18:21.302  6844  7376 V FormManager: Network unavailable.
07-28 12:18:21.303  7045  7045 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:18:21.303  7045  7045 D WeatherAncestor: connectivity changed - connection : true
07-28 12:18:21.303  7045  7045 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3db92b34
07-28 12:18:21.303  6844  7376 V FormManager: Network unavailable.
07-28 12:18:21.303  7045  7045 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:18:21.303  7045  7045 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:18:21.303  7045  7045 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:18:21.303  7045  7045 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:18:21.304  7045  7045 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:21
07-28 12:18:21.317  6371  6371 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:18:21.320  6371  6398 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:18:21.329  2094  2094 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:21.335  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:18:21.335  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.336  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:18:21.336  6917  6917 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:18:21.337  6917  6917 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:18:21.339  6917  6917 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e3c7c46
07-28 12:18:21.339  6917  6917 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:18:21.339  6917  6917 D AppUp4:CustFacade: isPhone : true
07-28 12:18:21.339  6917  6917 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:18:21.339  6917  6917 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:18:21.342  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.342  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:18:21.343  1037  2000 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:18:21.343  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:21.345  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:21.348  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:18:21.349  4324  7378 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:18:21.350  4324  7379 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:18:21.350  4324  7379 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:21.350  6945  6945 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:18:21.352  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:18:21.352  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,07-28 12:18:21.352  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:18:21.352  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:18:21.353  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:18:21.353  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:18:21.353  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:18:21.353  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:18:21.353  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:18:21.353  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:18:21.353  6878  6878 I BluetoothA2dpServiceJni: classInitNative
07-28 12:18:21.353  6878  6878 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:18:21.353  6878  6878 D A2dpStateMachine: make
07-28 12:18:21.355  6878  6878 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:18:21.355  6878  7381 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:18:21.356  6878  6878 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:18:21.356  6878  6878 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:18:21.357  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.357  6878  7380 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:18:21.360  6878  6878 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:21.361  6878  6878 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:18:21.362  6878  6878 D HidService: Received start request. Starting profile...
07-28 12:18:21.362  6878  6878 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:18:21.362  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.363  6878  6878 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:18:21.364  6945  7383 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:21.364  6878  7348 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:18:21.364  3442  3442 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:18:21.364  3442  3442 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:21.364  6878  7348 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:18:21.364  3442  3442 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:18:21.365  6984  6984 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:18:21.366  6984  6984 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 12:18:21.367  6878  6878 D HealthService: Received start request. Starting profile...
07-28 12:18:21.368  6878  7348 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-28 12:18:21.368  6878  6878 I bluedroid-qcom: get_profile_interface health
07-28 12:18:21.368  6878  6878 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:18:21.368  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.369  6878  6878 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:18:21.370  6878  6878 D PanService: Received start request. Starting profile...
07-28 12:18:21.370  6878  6878 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:18:21.370  6878  6878 I bluedroid-qcom: get_profile_interface pan
07-28 12:18:21.371  6844  7386 W FormManager: Network not available. Please check & try again.
07-28 12:18:21.373  7045  7045 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:21
07-28 12:18:21.374  6878  6878 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:18:21.374  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.375  7045  7045 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:18:21.375  7045  7045 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:18:21.375  6844  7387 V FormManager: Network unavailable.
07-28 12:18:21.375  7045  7045 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:18:21.375  6878  6878 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 12:18:21.375  7045  7045 D WeatherAncestor: connectivity changed - connection : true
07-28 12:18:21.375  7045  7045 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3db92b34
07-28 12:18:21.376  7045  7045 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:18:21.376  7045  7045 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:18:21.376  7045  7045 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:18:21.376  7045  7045 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:18:21.376  7045  7045 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:18:21
07-28 12:18:21.378  6878  6878 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:18:21.378  6844  7387 V FormManager: Network unavailable.
07-28 12:18:21.379  6878  6878 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:18:21.379  6878  6878 D BtGatt.GattService: start()
07-28 12:18:21.379  6878  6878 I bluedroid-qcom: get_profile_interface gatt
07-28 12:18:21.380  6878  6878 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:18:21.384  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.385  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.385  6878  6878 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:18:21.386  6878  6878 V BluetoothMapService: BluetoothMapBinder()
07-28 12:18:21.387  6878  6878 D BluetoothMapService: Received start request. Starting profile...
07-28 12:18:21.387  6878  6878 D BluetoothMapService: start()
07-28 12:18:21.388  6878  6878 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:18:21.389  6878  6878 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:18:21.389  6878  6878 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:18:21.390  6878  6878 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-28 12:18:21.395  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:21.397  6878  6878 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:21.399  6878  6878 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:21.401  6878  6878 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:21.401  6878  6878 V PanService: [BTUI] SIM Extra State :ABSENT
07-28 12:18:21.403  6878  6878 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:18:21.405  6878  6878 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,07-28 12:18:21.405  6878  6878 V BluetoothMapService: Handler(): got msg=1
07-28 12:18:21.405  6878  7323 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:18:21.405  6878  7323 I bluedroid-qcom: enable
07-28 12:18:21.405  6878  7393 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:18:21.405  6878  7393 I bt-btu  : btu_task pending for preload complete event
07-28 12:18:21.406  6878  7323 I bt_hci_bdroid: init
07-28 12:18:21.406  6878  6878 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:21.406  6878  7323 I bt_vendor: bt-vendor : init
07-28 12:18:21.406  6878  7323 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:18:21.406  6878  7323 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:18:21.406  6878  7323 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:18:21.406  6878  7323 D bt_userial_mct: userial_init
07-28 12:18:21.407  6878  6878 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:21.407  6878  7323 D bt_hci_bdroid: set_power 1
07-28 12:18:21.407  6878  6878 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:21.407  6878  7323 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:18:21.407  6878  6878 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:21.407  6878  7323 I bt_vendor: Starting hciattach daemon
07-28 12:18:21.407  6878  7323 I bt_vendor: try to set true
07-28 12:18:21.407  6878  6878 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:21.407  6878  6878 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:18:21.395  7396  7396 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:21.395  7396  7396 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:21.420  7397  7397 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:18:21.476  7403  7403 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:18:21.498  7404  7404 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:18:21.534  7406  7406 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:18:21.549  7407  7407 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 12:18:21.572  7408  7408 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:18:21.585  7409  7409 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 12:18:21.609  7411  7411 I libmdmdetect: ESOC framework not supported
07-28 12:18:21.611  7411  7411 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:18:21.623  7411  7411 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-28 12:18:21.623  7411  7411 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:18:21.623  7411  7411 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:18:21.623  7411  7411 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:18:21.623  7411  7411 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:18:21.623  7411  7411 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:18:21.623  7411  7411 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:18:21.673  7411  7412 E QC-QMI  : qmi_client [7411] 14: failed to locate client data
07-28 12:18:21.674   487   487 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:18:21.674   487   487 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-28 12:18:21.730  7419  7419 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:18:21.744  7420  7420 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:18:21.761  6878  7323 I bt_vendor: bluetooth satus is on
,07-28 12:18:21.761  6878  7323 D bt_hci_bdroid: preload
07-28 12:18:21.763  6878  7395 D bt_userial_mct: userial_open(port:0)
07-28 12:18:21.763  6878  7395 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 12:18:21.767  6878  7395 I bt_vendor: Done intiailizing UART
,07-28 12:18:21.768  6878  7395 I bt_vendor: Done intiailizing UART
07-28 12:18:21.768  6878  7395 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:18:21.768  6878  7395 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,07-28 12:18:21.768  6878  7422 D bt_userial_mct: Entering userial_read_thread()
07-28 12:18:21.768  6878  7393 I bt-btu  : btu_task received preload complete event
07-28 12:18:21.769  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:18:21.769  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 12:18:21.771  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:18:21.774  6878  7393 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:18:21.886  6878  7393 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-28 12:18:21.886  6878  7393 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e8061 
07-28 12:18:21.887  6878  7393 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e8061 
,07-28 12:18:21.913  6878  7327 E bt-btif : Calling BTA_HhEnable
07-28 12:18:21.913  6878  7327 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 12:18:21.913  6878  7327 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:18:21.916  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:18:21.917  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:18:21.917  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:18:21.918  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:18:21.919  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
,07-28 12:18:21.919  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:18:21.919  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:18:21.919  6878  7327 D BluetoothAdapterProperties: Name is: G3
,07-28 12:18:21.920  6878  7327 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:18:21.920  6878  7327 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:18:21.921  6878  7327 D bt_hci_bdroid: postload
07-28 12:18:21.921  6878  7395 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:18:21.923  6878  7395 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:18:21.924  6878  7393 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:18:21.926  6878  7395 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:18:21.926  6878  7395 D bt_hci_bdroid: Used up Tx Cmd credits
,07-28 12:18:21.932  6878  7393 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:21.932  6878  7393 W bt-smp  : Plain text(LSB ~ MSB) = 62 0d 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:21.932  6878  7393 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f 4a 58 9f ef 7c c6 22 a9 f1 73 72 91 58 4e 5f 
07-28 12:18:21.933  6878  7395 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:18:21.933  6878  7393 W bt-btm  : Stopping oneshot timer
07-28 12:18:21.933  6878  7327 D bte_conf: Device ID record 1 : primary
07-28 12:18:21.933  6878  7327 D bte_conf:   vendorId            = 00c4
07-28 12:18:21.933  6878  7327 D bte_conf:   vendorIdSource      = 0001
07-28 12:18:21.933  6878  7327 D bte_conf:   product             = 13a1
07-28 12:18:21.933  6878  7327 D bte_conf:   version             = 1000
07-28 12:18:21.933  6878  7327 D bte_conf:   clientExecutableURL = 
07-28 12:18:21.933  6878  7327 D bte_conf:   serviceDescription  = 
07-28 12:18:21.933  6878  7327 D bte_conf:   documentationURL    = 
07-28 12:18:21.933  6878  7327 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:18:21.936  6878  7422 E bt_mct  : hci lib postload completed
07-28 12:18:21.937  6878  7323 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:18:21.937  6878  7327 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:18:21.938  6878  7323 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:18:21.938  6878  7323 D BluetoothAdapterProperties: State =  11
07-28 12:18:21.938  6878  7323 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:18:21.939  6878  7323 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:18:21.939  6878  7323 D BluetoothAdapterProperties: Setting state to 12
07-28 12:18:21.939  6878  7323 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:18:21.935  7427  7427 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:21.935  7427  7427 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:21.952  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:21.953  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:18:21.953  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,07-28 12:18:21.956  6878  7327 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:18:21.969  6878  7327 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:18:21.969  6878  7327 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,07-28 12:18:21.971  6878  7323 I BluetoothAdapterState: Entering On State
07-28 12:18:21.983  6878  7393 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:21.983  6878  7393 W bt-smp  : Plain text(LSB ~ MSB) = c4 b1 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:21.983  6878  7393 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a 25 37 38 30 61 70 e0 eb fb e0 33 5a 0d be 5c 
,07-28 12:18:21.985  6878  7393 W bt-btm  : Stopping oneshot timer
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:21.989  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:21.994  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:22.003  6878  7393 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:22.003  6878  7393 W bt-smp  : Plain text(LSB ~ MSB) = f5 7e 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:22.003  6878  7393 W bt-smp  : Encrypted text(LSB ~ MSB) = 73 c0 38 ae cd 3d ff 0a cf 60 85 2e 70 0a cd 67 
,07-28 12:18:22.005  6878  7393 W bt-btm  : Stopping oneshot timer
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:22.005  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:22.012  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:22.017  6878  7393 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:22.017  6878  7393 W bt-smp  : Plain text(LSB ~ MSB) = 87 e6 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:22.017  6878  7393 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 63 b6 0a bc 6e 7a d2 15 8a 50 4f fe e7 2c 44 
,07-28 12:18:22.020  6878  7393 W bt-btm  : Stopping oneshot timer
,07-28 12:18:22.024  6878  7323 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:18:22.024  6878  7323 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:18:22.024  6878  7323 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 12:18:22.025  6878  7323 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 12:18:22.025  6878  7323 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:18:22.026  6776  6791 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:18:22.055  6776  6792 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:18:22.056  6776  6792 D BluetoothPan: onBluetoothStateChange call bindService
,07-28 12:18:22.062  6878  7393 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:22.062  6878  7393 W bt-smp  : Plain text(LSB ~ MSB) = f2 7a 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:22.062  6878  7393 W bt-smp  : Encrypted text(LSB ~ MSB) = cf 02 be 07 3c e1 21 be d6 62 b1 01 fa 37 cf 8e 
07-28 12:18:22.062  6878  7393 W bt-btm  : Stopping oneshot timer
07-28 12:18:22.064  7432  7432 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-28 12:18:22.069  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:18:22.073  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:22.077  1037  1037 D BluetoothA2dp: Proxy object connected
07-28 12:18:22.078  1037  1037 D BluetoothHeadset: Proxy object connected
07-28 12:18:22.080  1838  4019 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:18:22.084  6776  6776 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:18:22.084  1838  1838 D BluetoothHeadset: Proxy object connected
07-28 12:18:22.084  6776  6776 D PanProfile: Bluetooth service connected
07-28 12:18:22.084  6776  6791 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:18:22.086  1838  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:22.087  6776  6776 D BluetoothMap: Proxy object connected
07-28 12:18:22.087  6776  6776 D MapProfile: Bluetooth service connected
07-28 12:18:22.087  6776  6776 D BluetoothMap: getConnectedDevices()
07-28 12:18:22.088  6878  6894 V BluetoothMapService: getConnectedDevices()
07-28 12:18:22.088  1838  1838 D BluetoothHeadset: Proxy object connected
07-28 12:18:22.088  6776  6875 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:18:22.090  1838  2480 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:22.092  1838  1838 D BluetoothHeadset: Proxy object connected
07-28 12:18:22.094  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:18:22.094  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:18:22.094  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:18:22.095  1037  1119 D BluetoothManagerService: Message: 40
07-28 12:18:22.095  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,07-28 12:18:22.097  6776  6776 D BluetoothInputDevice: Proxy object connected
07-28 12:18:22.097  6776  6776 D HidProfile: Bluetooth service connected
07-28 12:18:22.098  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.098  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:22.101  1929  2078 D LGBluetoothAPIService: Message: 1
07-28 12:18:22.101  1929  2078 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:18:22.113  1929  2078 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-28 12:18:22.114  6878  6878 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.115  6878  6878 D BluetoothMapService: STATE_ON
07-28 12:18:22.118  7064  7099 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
07-28 12:18:22.119  6878  6878 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:18:22.121  6878  6878 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:18:22.122  6577  6577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:18:22.123  6878  6878 V BluetoothMapService: Handler(): got msg=1
07-28 12:18:22.124  6776  6776 D LocalBluetoothProfileManager: Adding local A2DP profile
07-28 12:18:22.126  1037  1119 D BluetoothManagerService: Message: 30
,07-28 12:18:22.127  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:18:22.127  1929  2078 D LGBluetoothAPIService: Message: 100
07-28 12:18:22.127  1929  2078 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:18:22.128  6878  6878 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:18:22.129  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:22.131  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:22.133  6878  7452 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:18:22.133  6878  7452 D BluetoothMapMasInstance:   masId = 00
07-28 12:18:22.133  6878  7452 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:18:22.133  6878  7452 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:18:22.133  6878  7452 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:18:22.134  1037  1705 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:22.135  6878  7452 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:22.136  6776  6776 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-28 12:18:22.138  1037  1119 D BluetoothManagerService: Message: 30
07-28 12:18:22.139  6878  7452 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:18:22.139  6878  7452 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:18:22.139  6878  7327 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:18:22.139  6878  7452 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:18:22.139  6878  7327 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:18:22.144  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:22.144  6878  6878 V BluetoothPbapService: Pbap Service onCreate
07-28 12:18:22.144  6878  6878 V BluetoothPbapService: Starting PBAP service
07-28 12:18:22.145  6878  6878 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 12:18:22.145  6878  6878 V BluetoothPbapService: Pbap Service onBind
,07-28 12:18:22.147  6878  6878 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.147  6878  6878 V BluetoothPbapService: state: 12
07-28 12:18:22.147  6878  6878 V BluetoothPbapService: Handler(): got msg=1
07-28 12:18:22.147  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:18:22.148  6878  6878 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:18:22.149  6878  7454 V BluetoothPbapService: Pbap Service initSocket
07-28 12:18:22.149  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:18:22.149  1037  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:22.150  6878  7454 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:22.151  6878  7454 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:18:22.151  6878  7454 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:18:22.151  6878  7454 V BluetoothPbapService: Accepting socket connection...
07-28 12:18:22.151  6776  6776 D BluetoothA2dp: Proxy object connected
07-28 12:18:22.152  6776  6776 D A2dpProfile: Bluetooth service connected
07-28 12:18:22.152  6878  6878 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:18:22.152  6878  6878 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.153  6878  6878 V BluetoothPbapReceiver: ***********state = 12
07-28 12:18:22.153  6776  6776 D BluetoothHeadset: Proxy object connected
07-28 12:18:22.154  6776  6776 D HeadsetProfile: Bluetooth service connected
07-28 12:18:22.157  6776  6776 D BluetoothPbap: Proxy object connected
07-28 12:18:22.157  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:18:22.157  2094  2094 D c       : Getting all permits...
07-28 12:18:22.157  2094  2094 D a       : Opening database...
07-28 12:18:22.158  6776  6776 D PbapServerProfile: Bluetooth service connected
07-28 12:18:22.161  6776  6776 D DockEventReceiver: finishStartingService: stopping service
07-28 12:18:22.161  2094  2094 D a       : Opening database auth.proximity.permit_store...
07-28 12:18:22.162  2094  2094 D a       : Closing database...
,07-28 12:18:22.169  6776  6776 D BluetoothPermissionRequest: onReceive
07-28 12:18:22.171  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:22.172  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:22.175  6776  6776 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:18:22.178  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:22.181  6878  6878 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:18:22.182  6878  6878 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:18:22.187  6878  6878 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-28 12:18:22.203  6878  6878 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:18:22.203  6878  6878 V BtOppService: onCreate
07-28 12:18:22.207  6878  6878 V BluetoothOppNotification: send message
07-28 12:18:22.209  6878  6878 V BtOppService: Starting RfcommListener
07-28 12:18:22.213  6878  6878 D BluetoothOppPreference: Dumping Names:  
07-28 12:18:22.213  6878  6878 D BluetoothOppPreference: {}
07-28 12:18:22.213  6878  6878 D BluetoothOppPreference: Dumping Channels:  
07-28 12:18:22.213  6878  6878 D BluetoothOppPreference: {}
07-28 12:18:22.213  6878  6878 V BtOppService: onStartCommand
07-28 12:18:22.215  6878  7463 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 12:18:22.216  6878  7460 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:18:22.217  6878  7463 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:18:22.219  6878  7460 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:18:22.219  6878  7463 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@48ccaa9 on behalf of 
07-28 12:18:22.219  6878  7460 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,07-28 12:18:22.219  6878  6878 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.220  6878  6878 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:18:22.221  6878  7463 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:18:22.222  6878  7460 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d67f82e on behalf of 
07-28 12:18:22.224  6878  6878 V BluetoothOppNotification: new notify threadi!
07-28 12:18:22.225  6878  6878 V BluetoothOppNotification: send delay message
07-28 12:18:22.225  6878  6878 V BtOppService: start RfcommListener
07-28 12:18:22.226  6878  7464 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:18:22.227  6878  7464 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3476dfcf on behalf of 
07-28 12:18:22.228  6878  7463 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:18:22.228  6878  7463 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:18:22.228  6878  7464 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 12:18:22.229  6878  6878 V BtOppService: RfcommListener started
07-28 12:18:22.230  6878  6878 V BtOppService: ContentObserver received notification
07-28 12:18:22.230  6878  7463 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37e88d5c on behalf of 
07-28 12:18:22.230  6878  6878 V BtOppService: ContentObserver received notification
07-28 12:18:22.231  6878  7465 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:18:22.231  1037  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:22.232  6878  7464 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:18:22.232  6878  7463 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:18:22.232  6878  7463 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:18:22.233  6878  7465 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:22.234  6878  7465 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
07-28 12:18:22.234  6878  7463 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a3e6865 on behalf of 
07-28 12:18:22.234  6878  7465 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:18:22.234  6878  7465 I BtOppRfcommListener: Accept thread started.
07-28 12:18:22.235  6878  7465 V BtOppRfcommListener: Accepting connection...
07-28 12:18:22.235  6878  7463 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:18:22.235  6878  7464 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@137f693a on behalf of 
07-28 12:18:22.236  6878  7464 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:18:22.236  6878  7463 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:18:22.238  6878  7464 V BluetoothOppNotification: outbound notification was removed.
07-28 12:18:22.238  6878  7464 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:18:22.239  6878  7464 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c2ba9eb on behalf of 
07-28 12:18:22.240  6878  7464 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-28 12:18:22.244  6878  7464 V BluetoothOppNotification: inbound notification was removed.
07-28 12:18:22.244  6878  7464 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:18:22.244  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:22.244  6878  6878 V BluetoothFtpService: Ftp Service onCreate
07-28 12:18:22.244  6878  6878 I BluetoothFtpService: Ftp Service onCreate
07-28 12:18:22.245  6878  6878 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:18:22.245  6878  6878 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.245  6878  6878 V BluetoothFtpService: Starting Listening on sockets
07-28 12:18:22.245  6878  7464 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b225e1 on behalf of 
07-28 12:18:22.245  6878  6878 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:22.245  6878  6878 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:22.245  6878  6878 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:22.246  6878  6878 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:22.246  6878  6878 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:18:22.246  6878  6878 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:18:22.248  6878  6878 V BluetoothFtpService: Handler(): got msg=1
07-28 12:18:22.248  6878  6878 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:18:22.248  6878  6878 V BluetoothFtpService: Ftp Service initSocket
07-28 12:18:22.254  1037  1685 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:22.255  6878  6878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:18:22.256  6878  6878 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
07-28 12:18:22.256  6878  6878 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:18:22.257  6878  7466 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:18:22.271  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:22.271  6878  6878 V BluetoothSapService: Sap Service onCreate
,07-28 12:18:22.273  6878  6878 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:18:22.273  6878  6878 V BluetoothSapService: state: 12
07-28 12:18:22.274  6878  6878 V BluetoothSapService: Starting SAP server process
07-28 12:18:22.265  7467  7467 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:22.265  7467  7467 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:22.277  6878  6878 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:18:22.278  6878  7468 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:18:22.278  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:22.279  6878  7468 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:22.280  6878  7468 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 12:18:22.280  6878  7468 V BluetoothSapService: Succeed to create listening socket 
07-28 12:18:22.280  6878  7468 V BluetoothSapService: Accepting socket connection...
07-28 12:18:22.287  7467  7467 V BT_SAP  : Event pipe created
07-28 12:18:22.287  7467  7467 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:18:22.287  7467  7467 V BT_SAP  : created socket fd 6
,07-28 12:18:22.820  1037  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3447c7c2 type 2 when 145173 com.google.android.gms} when 145173
,07-28 12:18:22.830   310  7479 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:18:22.830  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 12:18:22.871  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:18:22.871  1037  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:18:22.903  1037  1526 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 12:18:22.904  1037  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 12:18:22.990  1037  1685 I ActivityManager: Killing 7250:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:18:23.033  1037  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_7250/cgroup.procs: No such file or directory
,07-28 12:18:23.226  6878  6878 V BluetoothOppNotification: new notify threadi!
,07-28 12:18:23.227  6878  6878 V BluetoothOppNotification: send delay message
,07-28 12:18:23.241  6878  7480 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:18:23.244  6878  7480 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@164a3f1d on behalf of 
07-28 12:18:23.245  6878  7480 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:18:23.246  6878  7480 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-28 12:18:23.251  6878  7480 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a45e592 on behalf of 
07-28 12:18:23.252  6878  7480 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:18:23.254  6878  7480 V BluetoothOppNotification: outbound notification was removed.
07-28 12:18:23.254  6878  7480 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:18:23.255  6878  7480 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ca16b63 on behalf of 
07-28 12:18:23.256  6878  7480 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:18:23.257  6878  7480 V BluetoothOppNotification: inbound notification was removed.
07-28 12:18:23.257  6878  7480 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:18:23.258  6878  7480 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1051360 on behalf of 
,07-28 12:18:23.884  1037  2000 I ActivityManager: Killing 6521:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-28 12:18:23.908  6635  6635 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:18:23.908  6635  6635 W System.err: android.os.DeadObjectException
07-28 12:18:23.908  6635  6635 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:18:23.908  6635  6635 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:18:23.908  6635  6635 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:18:23.908  6635  6635 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:18:23.909  6635  6635 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:18:23.909  6635  6635 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:18:23.909  6635  6635 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:18:23.909  6635  6635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:18:23.909  6635  6635 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:18:23.909  6635  6635 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:18:23.909  6635  6635 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:18:23.909  6635  6635 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:18:23.909  6635  6635 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:18:23.909  6635  6635 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:18:23.909  6635  6635 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 12:18:23.909  6635  6635 W System.err: android.os.DeadObjectException
07-28 12:18:23.910  6635  6635 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:18:23.910  6635  6635 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:18:23.910  6635  6635 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:18:23.910  6635  6635 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:18:23.910  6635  6635 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:18:23.910  6635  6635 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:18:23.910  6635  6635 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:18:23.910  6635  6635 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:18:23.910  6635  6635 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:18:23.911  6635  6635 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-28 12:18:23.947  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:18:23.953  1037  1919 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@237959d3 mBinding = false
07-28 12:18:23.961  1037  1872 W libprocessgroup: failed to open /acct/uid_1000/pid_6521/cgroup.procs: No such file or directory
07-28 12:18:23.964  1037  1872 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-28 12:18:23.971  6635  6635 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:18:23.972  6635  6635 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:18:23.977  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:18:23.977  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:23.977  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:18:23.981  1037  1119 D BluetoothManagerService: Message: 2
07-28 12:18:23.987  1037  1119 D BluetoothManagerService: Sending off request.
07-28 12:18:23.987  6878  7343 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:18:23.988  6878  7323 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:18:23.988  6878  7323 D BluetoothAdapterProperties: Setting state to 13
07-28 12:18:23.988  6878  7323 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:18:23.989  6878  7323 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:18:23.989  6878  7323 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:18:23.991  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:23.991  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:18:23.991  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-28 12:18:24.045  1037  1919 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7482 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:18:24.049  6878  7327 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:18:24.049  6878  7323 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:18:24.050  6878  7323 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:18:24.052  6878  7452 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,07-28 12:18:24.054  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:18:24.055  6878  7393 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:18:24.056  6878  7465 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:24.057  6878  7454 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:18:24.067  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:18:24.067  6878  7393 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:18:24.071  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:24.071  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:18:24.076  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:24.076  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:24.078  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:24.078  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:24.079  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:18:24.079  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:24.084  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:18:24.087  6878  7466 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:24.088  6878  7468 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:18:24.104  6878  6878 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.104  6878  6878 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:18:24.104  6878  6878 V BluetoothMapService: Handler(): got msg=4
07-28 12:18:24.104  6878  6878 D BluetoothMapService: MAP Service closeService in
07-28 12:18:24.104  6878  6878 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:18:24.104  6878  6878 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:18:24.105  6878  6878 V BluetoothMapService: MAP Service closeService out
,07-28 12:18:24.108  6878  6878 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:18:24.108  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:24.110  6878  6878 I BtOppRfcommListener: stopping Accept Thread
07-28 12:18:24.110  6878  6878 V BtOppRfcommListener: close mBtServerSocket
07-28 12:18:24.111  6878  7465 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:18:24.112  6878  6878 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:18:24.112  6878  6878 V BtOppRfcommListener: done waiting for thread to terminate
07-28 12:18:24.137  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:18:24.138  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-28 12:18:24.140  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:24.142  6635  6635 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:18:24.149  6878  6878 V BtOppService: onDestroy
,07-28 12:18:24.150  6878  6878 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:18:24.151  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:18:24.155  6776  6776 D DockEventReceiver: finishStartingService: stopping service
07-28 12:18:24.155  6878  6878 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:18:24.155  6878  6878 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.156  6878  6878 V BluetoothPbapReceiver: ***********state = 13
07-28 12:18:24.157  6878  6878 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-28 12:18:24.158  6878  6878 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.158  6878  6878 V BluetoothPbapService: state: 13
07-28 12:18:24.158  6878  6878 V BluetoothPbapService: Pbap Service closeService in
07-28 12:18:24.160  6878  6878 V BluetoothPbapService: successfully stopped pbap service
07-28 12:18:24.160  6878  6878 V BluetoothPbapService: Pbap Service closeService out
07-28 12:18:24.161  6878  6878 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:18:24.161  6878  6878 V BluetoothPbapService: Pbap Service closeService in
07-28 12:18:24.161  6878  6878 V BluetoothPbapService: Pbap Service closeService out
07-28 12:18:24.161  6878  6878 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:18:24.161  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:18:24.168  6776  6776 D BluetoothPbap: Proxy object disconnected
,07-28 12:18:24.168  6776  6776 D PbapServerProfile: Bluetooth service disconnected
,07-28 12:18:24.289  1037  1872 I art     : Explicit concurrent mark sweep GC freed 93567(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.129ms total 114.591ms
,07-28 12:18:24.297  1590  1590 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 12:18:24.297  1590  1590 I [SystemUI]LGPowerUI: On Skip Timer : true
07-28 12:18:24.298  6776  6776 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:18:24.301  1590  1590 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-28 12:18:24.301  1590  1590 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:18:24.302  1929  2059 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-28 12:18:24.302  1929  2059 D LEDHandler: Battery Level Remaining: 100%
07-28 12:18:24.302  1929  2059 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-28 12:18:24.303  1037  1531 D WifiController: battery changed pluggedType: 2
,07-28 12:18:24.310  1590  1590 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:18:24.315  6878  7348 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:18:24.317  6776  6776 D BluetoothPermissionRequest: onReceive
,07-28 12:18:24.317  6776  6776 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:18:24.321  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:24.324  7482  7482 D UEI.SmartControl: Quickset Services start...
07-28 12:18:24.326  6878  6878 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-28 12:18:24.326  6878  6878 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 12:18:24.326  6878  6878 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-28 12:18:24.327  7482  7482 I UEI.SmartControl: Manufacture = LGE
07-28 12:18:24.327  7482  7482 D UEI.SmartControl: Id = LGNevo
,07-28 12:18:24.329  6878  6878 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.329  6878  6878 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:18:24.329  6878  6878 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:18:24.329  7482  7482 D UEI.SmartControl: File observer start...
07-28 12:18:24.329  6878  6878 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.330  6878  6878 V BluetoothFtpService: Ftp Service closeService
07-28 12:18:24.330  6878  6878 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:18:24.330  7482  7482 E UEI.SmartControl: IR Port is disabled: false
07-28 12:18:24.330  7482  7482 D UEI.SmartControl: Starting file observer...
,07-28 12:18:24.330  7482  7482 D UEI.SmartControl: Extracting JNI libs...
07-28 12:18:24.331  7482  7482 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-28 12:18:24.331  6878  6878 V BluetoothFtpService: successfully stopped ftp service
07-28 12:18:24.332  6878  6878 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:24.332  6878  6878 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:24.332  6878  6878 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:24.332  6878  6878 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.332  6878  6878 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:18:24.332  6878  6878 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:18:24.333  6878  6878 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:18:24.333  6878  6878 V BluetoothFtpService: Ftp Service closeService
07-28 12:18:24.336  6878  6878 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:24.336  6878  6878 V BluetoothSapService: state: 13
07-28 12:18:24.336  6878  6878 V BluetoothSapService: Stopping SAP server process
07-28 12:18:24.337  6878  6878 V BluetoothSapService: Sap Service closeSapService in
07-28 12:18:24.337  6878  6878 V BluetoothSapService: Close listen Socket : 
07-28 12:18:24.337  6878  6878 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:18:24.337  6878  6878 V BluetoothSapService: Close sapd  Socket : 
07-28 12:18:24.342  6878  6878 V BluetoothSapService: Sap Service closeSapService out
07-28 12:18:24.342  6878  6878 V BluetoothSapService: Sap Service onDestroy
07-28 12:18:24.342  6878  6878 V BluetoothSapService: Sap Service closeSapService in
07-28 12:18:24.342  6878  6878 V BluetoothSapService: Close listen Socket : 
07-28 12:18:24.343  6878  6878 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:18:24.343  6878  6878 V BluetoothSapService: Close sapd  Socket : 
07-28 12:18:24.343  6878  6878 V BluetoothSapService: Sap Service closeSapService out
07-28 12:18:24.429  7482  7482 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 12:18:24.429  7482  7482 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,07-28 12:18:24.429  7482  7482 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-28 12:18:24.459  7482  7482 I UEI.SmartControl: --- Selecting new region: 6
,07-28 12:18:24.461  7482  7482 I UEI.SmartControl: Model = LG-D855
,07-28 12:18:24.463  7482  7482 D UEI.SmartControl: QS Service created
,07-28 12:18:24.475  7482  7482 I UEI.SmartControl: Service initServices...
07-28 12:18:24.479  7482  7482 D UEI.SmartControl: QS start get config
,07-28 12:18:24.514  7482  7482 D UEI.SmartControl: Loading JNI Libs...
,07-28 12:18:24.754  7482  7482 I UEI.SmartControl: Supports setup maps: true
,07-28 12:18:24.757  7482  7482 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:18:24.757  7482  7482 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:18:24.757  7482  7482 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:18:24.757  7482  7482 I UEI.SmartControl: ### init IR Blaster...
,07-28 12:18:24.764  7482  7482 D serial_port: Configuring serial port
07-28 12:18:24.767  7482  7482 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:18:24.767  7482  7482 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:18:24.768  7482  7482 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:18:24.768  7482  7482 I UEI.SmartControl: Get version...
07-28 12:18:24.787  7482  7524 D UEI.SmartControl: serial port data available: 21
,07-28 12:18:24.818  7482  7482 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:18:24.818  7482  7482 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:18:24.819  7482  7482 I UEI.SmartControl: QS saving settings...
07-28 12:18:24.821  7482  7482 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:18:24.840  7482  7524 D UEI.SmartControl: serial port data available: 4
,07-28 12:18:24.878  7482  7527 I UEI.SmartControl: Device manager: loading config....
07-28 12:18:24.880  7482  7527 D UEI.SmartControl: ----------- loading internal config...
,07-28 12:18:24.886  7482  7482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-28 12:18:24.892  7482  7482 E UEI.SmartControl: Services init done
07-28 12:18:24.897  7482  7482 D UEI.SmartControl: QS Service init finished
07-28 12:18:24.898  7482  7482 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:18:24.898  7482  7482 D UEI.SmartControl: QS Service version code: 201091
07-28 12:18:24.899  7482  7482 D UEI.SmartControl: Service requested: Control
,07-28 12:18:24.901  7482  7527 E UEI.SmartControl: Loading SETTINGS...
07-28 12:18:24.905  7482  7482 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:18:24.906  1037  2019 I ActivityManager: Killing 6635:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 12:18:24.908  7482  7527 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-28 12:18:24.913  7482  7526 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:18:24.913  7482  7526 D UEI.SmartControl: -----service ready thread exits
07-28 12:18:24.938  1037  1685 W libprocessgroup: failed to open /acct/uid_10112/pid_6635/cgroup.procs: No such file or directory
,07-28 12:18:24.940  7482  7482 D UEI.SmartControl: Internal service binding...
,07-28 12:18:24.961  6878  7327 D bt_hci_bdroid: cleanup
07-28 12:18:24.962  6878  7395 I bt_lpm  : LPM is already off!!!
07-28 12:18:24.962  6878  7393 W bt-btif : ag scb idx 1 not allocated
07-28 12:18:24.963  6878  7393 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:18:24.963  6878  7393 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:18:24.964  6878  7393 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:18:24.964  6878  7393 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:18:24.964  6878  7393 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:18:24.965  6878  7422 I bt_userial_mct: exiting userial_read_thread
07-28 12:18:24.965  6878  7422 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:18:24.968  6878  7327 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:18:24.969  6878  7395 I bt_vendor: hw_epilog_process
07-28 12:18:24.970  6878  7327 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:18:24.970  6878  7327 D bt_userial_mct: userial_close
07-28 12:18:24.971  6878  7327 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:18:24.971  6878  7327 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:18:24.993  6878  7327 D bt_hci_bdroid: set_power 0
07-28 12:18:24.993  6878  7327 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,07-28 12:18:24.994  6878  7327 I bt_vendor: bluetooth satus is on
07-28 12:18:24.994  6878  7327 I bt_vendor: bt-vendor : resetting BT status
07-28 12:18:24.994  6878  7327 I bt_vendor: Starting hciattach daemon
07-28 12:18:24.994  6878  7327 I bt_vendor: try to set false
07-28 12:18:24.998  6878  7327 I bt_vendor: Starting hciattach daemon
07-28 12:18:24.998  6878  7327 I bt_vendor: try to set false
07-28 12:18:24.999  6878  7327 I bt_vendor: cleanup
07-28 12:18:24.999  6878  7393 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:18:24.999  6878  7327 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:18:25.000  6878  7327 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:18:25.001  6878  7323 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:18:25.006  6878  6878 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:18:25.010  6878  7348 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:18:25.009  6878  6878 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:18:25.012  6878  6878 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:18:25.012  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.014  6878  7323 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:18:25.014  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:25.015  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:25.015  1838  1838 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:25.016  1037  1037 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:25.016  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:18:25.017  6776  6776 D BluetoothHeadset: Proxy object disconnected
07-28 12:18:25.017  6878  6878 D A2dpService: Received stop request...Stopping profile...
07-28 12:18:25.017  6776  6776 D HeadsetProfile: Bluetooth service disconnected
07-28 12:18:25.017  6878  7380 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:18:25.018  6878  6878 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,07-28 12:18:25.020  6878  6878 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
,07-28 12:18:25.021  6878  6878 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:18:25.021  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.022  1037  1037 D BluetoothA2dp: Proxy object disconnected
07-28 12:18:25.022  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:18:25.023  6776  6776 D BluetoothA2dp: Proxy object disconnected
07-28 12:18:25.023  6776  6776 D A2dpProfile: Bluetooth service disconnected
07-28 12:18:25.025  6878  6878 D HidService: Received stop request...Stopping profile...
07-28 12:18:25.025  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.026  6776  6776 D BluetoothInputDevice: Proxy object disconnected
07-28 12:18:25.026  6776  6776 D HidProfile: Bluetooth service disconnected
07-28 12:18:25.027  6878  6878 D HealthService: Received stop request...Stopping profile...
07-28 12:18:25.027  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.028  6878  6878 D PanService: Received stop request...Stopping profile...
07-28 12:18:25.029  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.030  6776  6776 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:18:25.030  6776  6776 D PanProfile: Bluetooth service disconnected
07-28 12:18:25.030  6878  6878 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:18:25.032  6878  6878 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:18:25.033  6878  6878 D BtGatt.GattService: stop()
07-28 12:18:25.033  6878  6878 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:18:25.034  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.036  6878  6878 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:18:25.036  6878  6878 D BluetoothMapService: stop()
07-28 12:18:25.037  6878  6878 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:18:25.037  6878  6878 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:18:25.037  6878  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:25.038  6878  6878 D HeadsetStateMachine: Unbinding service...
07-28 12:18:25.039  6776  6776 D BluetoothMap: Proxy object disconnected
07-28 12:18:25.039  6776  6776 D MapProfile: Bluetooth service disconnected
07-28 12:18:25.039  6878  6878 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:18:25.039  6878  6878 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:18:25.039  6878  6878 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:18:25.039  6878  6878 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:18:25.039  6878  6878 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:18:25.039  6878  6878 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:18:25.039  6878  6878 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:18:25.040  6878  6878 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:18:25.040  6878  7381 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:18:25.040  6878  6878 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:18:25.041  6878  6878 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:18:25.041  6878  6878 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:18:25.041  6878  6878 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:18:25.041  6878  6878 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:18:25.042  6878  6878 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:18:25.042  6878  6878 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:18:25.042  6878  6878 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:18:25.042  6878  6878 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:18:25.044  6878  6878 V BluetoothMapService: Handler(): got msg=4
07-28 12:18:25.044  6878  6878 D BluetoothMapService: MAP Service closeService in
07-28 12:18:25.044  6878  6878 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:18:25.044  6878  6878 V BluetoothMapService: MAP Service closeService out
07-28 12:18:25.045  6878  7323 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:18:25.045  6878  7323 D BluetoothAdapterProperties: Setting state to 10
07-28 12:18:25.045  6878  7323 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:18:25.049  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:25.049  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:18:25.049  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-28 12:18:25.050  6878  7323 I BluetoothAdapterState: Entering OffState
07-28 12:18:25.051  6776  6792 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:18:25.052  6878  6878 D BluetoothMapService: cleanup()
07-28 12:18:25.052  6878  6878 D BluetoothMapService: MAP Service closeService in
07-28 12:18:25.053  6878  6878 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:18:25.053  6878  6878 V BluetoothMapService: MAP Service closeService out
07-28 12:18:25.054  6776  6875 D BluetoothPan: onBluetoothStateChange on: false
,07-28 12:18:25.055  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:18:25.055  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:25.056  1838  4014 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:25.058  6776  6791 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:18:25.058  6776  6792 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:18:25.059  1838  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:25.060  6776  6875 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:18:25.060  1838  2480 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:25.061  6776  6791 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:18:25.062  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:18:25.062  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:18:25.065  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:18:25.065  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,07-28 12:18:25.065  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@237959d3 mBinding = false
07-28 12:18:25.066  1037  1119 D BluetoothManagerService: Sending unbind request.
07-28 12:18:25.070  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 12:18:25.070  6878  7327 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:18:25.070  6878  6878 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:18:25.070  6878  6878 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:18:25.071  6878  6878 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:18:25.071  6878  6878 I art     : --- WEIRD: removing null entry 248
07-28 12:18:25.071  6878  6878 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-28 12:18:25.071  6878  6878 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,07-28 12:18:25.073  6878  6878 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:18:25.074  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:25.075  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:25.075  1929  2078 D LGBluetoothAPIService: Message: 2
07-28 12:18:25.075  1929  2078 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@20230897 mBinding = false
07-28 12:18:25.075  1929  2078 D LGBluetoothAPIService: Sending unbind request.
07-28 12:18:25.080  1590  1590 D BluetoothAdapter: 599584127: getState() :  mService = null. Returning STATE_OFF
07-28 12:18:25.080  1590  1590 D BluetoothAdapter: 599584127: getState() :  mService = null. Returning STATE_OFF
07-28 12:18:25.081  6878  6878 I art     : System.exit called, status: 0
07-28 12:18:25.081  6878  6878 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:18:25.084  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:25.084  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:18:25.084  6776  6776 D LGBluetoothEventManager: [BTUI] clear device connection state
,07-28 12:18:25.085  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:25.086  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:18:25.093  6776  6776 D DockEventReceiver: finishStartingService: stopping service
07-28 12:18:25.101   316  2125 V AudioFlinger: 6878 died, releasing its sessions
07-28 12:18:25.101   316  2125 V AudioFlinger:  pid 1838 @ 0
07-28 12:18:25.101   316  2125 V AudioFlinger:  pid 3442 @ 1
,07-28 12:18:25.101   316  2125 V AudioFlinger:  pid 3442 @ 2
07-28 12:18:25.102  6776  6776 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-28 12:18:25.132  1037  1919 I ActivityManager: Process com.android.bluetooth (pid 6878) has died
07-28 12:18:25.132  1037  1919 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,07-28 12:18:25.140  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:18:25.160  6776  6776 D BluetoothPermissionRequest: onReceive
,07-28 12:18:25.164  6776  6776 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:18:25.164  6776  6776 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,07-28 12:18:25.168  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:25.235  1037  1705 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7543 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:18:25.326  7543  7543 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-28 12:18:25.327  7543  7543 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:25.327  7543  7543 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:18:25.328  7543  7543 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:18:25.349  7543  7543 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:18:25.389  7543  7543 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3aeee49c Instance Count = 1
,07-28 12:18:25.396  7543  7543 D BluetoothAdapterApp: onCreate
07-28 12:18:25.430  7543  7543 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 12:18:25.431  7543  7543 D ProfileConfigQcom: Adding HeadsetService
07-28 12:18:25.431  7543  7543 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:18:25.434  7543  7543 D ProfileConfigQcom: Adding A2dpService
07-28 12:18:25.435  7543  7543 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:18:25.436  7543  7543 D ProfileConfigQcom: Adding HidService
07-28 12:18:25.436  7543  7543 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:18:25.437  7543  7543 D ProfileConfigQcom: Adding HealthService
07-28 12:18:25.437  7543  7543 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:18:25.439  7543  7543 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:18:25.439  7543  7543 D ProfileConfigQcom: Adding PanService
07-28 12:18:25.440  7543  7543 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:18:25.441  7543  7543 D ProfileConfigQcom: Adding GattService
07-28 12:18:25.441  7543  7543 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:18:25.442  7543  7543 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:18:25.443  7543  7543 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:18:25.446  7543  7543 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-28 12:18:25.453  6776  6776 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-28 12:18:25.456  7543  7543 V LGMDMManagerInternal: Create singleton instance
,07-28 12:18:25.545  7543  7543 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:25.550  7543  7543 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-28 12:18:25.551  7543  7543 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:25.551  7543  7543 V BluetoothSapReceiver: SapReceiver onReceive 
,07-28 12:18:25.553  7543  7543 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:18:25.553  7543  7543 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,07-28 12:18:25.558  6827  6827 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-28 12:18:25.560  1037  1872 I ActivityManager: Killing 6795:com.lge.sync/1000 (adj 15): empty #17
07-28 12:18:25.579  1037  1531 D WifiService: Client connection lost with reason: 4
,07-28 12:18:25.656  1037  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_6795/cgroup.procs: No such file or directory
,07-28 12:18:25.768  1037  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c8460e6 type 2 when 148139 com.google.android.gms} when 148139
,07-28 12:18:25.788   310  7572 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:18:25.789  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 12:18:26.987  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:18:26.987  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:18:27.320  1037  1415 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:18:27.366  1590  1590 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-28 12:18:27.436  1037  1100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7573 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:18:27.442  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-28 12:18:27.443  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-28 12:18:27.462  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-28 12:18:27.462  1037  1037 D administrator: Handling package changes for user 0
,07-28 12:18:27.489  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:18:27.534  7573  7573 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:18:27.577  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-28 12:18:27.578  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-28 12:18:27.598  7573  7573 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:27.598  7573  7573 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:27.626  1037  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:18:27.635  1037  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 12:18:27.643  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 12:18:27.644  2435  2435 V GmsNetworkLocationProvi: DISABLE
,07-28 12:18:27.676  1037  1099 D LocationProviderProxy: applying state to connected service
07-28 12:18:27.677  2435  2435 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-28 12:18:27.710  7573  7618 I Babel   : MmsConfig: mnc/mcc: 0/0
07-28 12:18:27.710  7573  7618 I Babel   : MmsConfig.loadMmsSettings
07-28 12:18:27.713  7573  7618 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 12:18:27.713  7573  7618 I Babel   : MmsConfig.loadFromDatabase
,07-28 12:18:27.724  7573  7618 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-28 12:18:27.725  7573  7618 I Babel   : MmsConfig.loadFromResources
07-28 12:18:27.726  7573  7618 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-28 12:18:27.726  7573  7618 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 12:18:27.729  7573  7573 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:27.739  7573  7616 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:18:27.743  7573  7616 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:18:27.745  7573  7616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-28 12:18:27.755  1803  7620 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-28 12:18:27.755  1803  7620 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-28 12:18:27.756  6917  6917 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:18:27.760  6917  6917 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e3c7c46
07-28 12:18:27.760  6917  6917 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:18:27.760  6917  6917 D AppUp4:CustFacade: isPhone : true
07-28 12:18:27.760  6917  6917 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:18:27.761  6917  6917 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-28 12:18:27.765  7573  7616 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-28 12:18:27.767  7573  7616 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:18:27.767  1803  4766 I Icing   : updateResources: need to parse e{com.google.android.gms}
,07-28 12:18:27.777  7573  7616 W AudioCapabilities: Unsupported mime audio/evrc
07-28 12:18:27.786  1037  1053 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7623 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-28 12:18:27.789  1037  2019 I ActivityManager: Killing 6945:com.lge.email/u0a23 (adj 15): empty #17
,07-28 12:18:27.796  7573  7616 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-28 12:18:27.798  7573  7616 W VideoCapabilities: Unsupported mime video/divx
07-28 12:18:27.800  7573  7616 W VideoCapabilities: Unsupported mime video/divx311
07-28 12:18:27.802  7573  7616 W VideoCapabilities: Unsupported mime video/divx4
07-28 12:18:27.806  7573  7616 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-28 12:18:27.818  7573  7616 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-28 12:18:27.823  7573  7616 W AudioCapabilities: Unsupported mime audio/eac3
,07-28 12:18:27.823  7573  7616 W AudioCapabilities: Unsupported mime audio/ac3
,07-28 12:18:27.824  7573  7616 W AudioCapabilities: Unsupported mime audio/g726
07-28 12:18:27.825  7573  7616 W AudioCapabilities: Unsupported mime audio/wma-voice
07-28 12:18:27.826  7573  7616 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-28 12:18:27.826  7573  7616 W AudioCapabilities: Unsupported mime audio/adpcm
07-28 12:18:27.828  7573  7616 W VideoCapabilities: Unsupported mime video/theora
07-28 12:18:27.829  7573  7616 W VideoCapabilities: Unsupported mime video/mjpg
,07-28 12:18:27.968  1037  2037 W libprocessgroup: failed to open /acct/uid_10023/pid_6945/cgroup.procs: No such file or directory
,07-28 12:18:28.008  7623  7623 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:28.009  7623  7623 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:28.010  7623  7623 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-28 12:18:28.015  7623  7623 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,07-28 12:18:28.015  7623  7623 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:18:28.101  7623  7623 I SystemConfig: BUILD Country: EU
07-28 12:18:28.101  7623  7623 I SystemConfig: BUILD Operator: OPEN
,07-28 12:18:28.153  1037  1705 I ActivityManager: Killing 6844:com.lge.formmanager/u0a26 (adj 15): empty #17
,07-28 12:18:28.270  1037  1052 W libprocessgroup: failed to open /acct/uid_10026/pid_6844/cgroup.procs: No such file or directory
,07-28 12:18:28.339  1037  1705 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7647 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-28 12:18:28.344  7623  7642 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-28 12:18:28.344  7623  7642 I SystemConfig: existFile = false
07-28 12:18:28.344  7623  7642 I SystemConfig: canReadFile = false
07-28 12:18:28.344  7623  7642 I SystemConfig: systemFeature RCS result false
07-28 12:18:28.345  7623  7642 D SystemConfig: refreshRcsSupport() :false
,07-28 12:18:28.399  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:28.400  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 12:18:28.400  7647  7647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:18:28.400  7647  7647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 12:18:28.533  7647  7647 I AppConfig: Total System Memory = 2995761152
,07-28 12:18:28.544  7647  7647 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-28 12:18:28.650  1037  2019 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7667 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:18:28.653  1037  2019 I ActivityManager: Killing 6371:com.wsandroid.suite.lge/1000 (adj 15): empty #17
07-28 12:18:28.693  1037  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_6371/cgroup.procs: No such file or directory
,07-28 12:18:28.881  7667  7667 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-28 12:18:28.976  7667  7667 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:28.976  7667  7667 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:29.032  7667  7667 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-28 12:18:29.052  7667  7667 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-28 12:18:29.053  7667  7667 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-28 12:18:29.071  7667  7667 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-28 12:18:29.071  7667  7667 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-28 12:18:29.098  1037  1891 I ActivityManager: Killing 6984:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-28 12:18:29.202  1037  1872 W libprocessgroup: failed to open /acct/uid_10046/pid_6984/cgroup.procs: No such file or directory
,07-28 12:18:29.208  3516  3532 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-28 12:18:29.211  3516  3532 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@205697f5 on behalf of 7667
07-28 12:18:29.229  4612  7704 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-28 12:18:29.305  1037  1052 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7705 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-28 12:18:29.322  7667  7667 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-28 12:18:29.354  7667  7667 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-28 12:18:29.413  7705  7705 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-28 12:18:29.440  7705  7705 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-28 12:18:29.440  7705  7705 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-28 12:18:29.440  7705  7705 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-28 12:18:29.440  7705  7705 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-28 12:18:29.441  7705  7705 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-28 12:18:29.441  7705  7705 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-28 12:18:29.466  1037  1562 I ActivityManager: Killing 7003:com.android.chrome/u0a57 (adj 15): empty #17
,07-28 12:18:29.503  1037  2019 W libprocessgroup: failed to open /acct/uid_10057/pid_7003/cgroup.procs: No such file or directory
,07-28 12:18:29.619  1037  1705 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:18:29.655  4612  7704 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 426 ms] updated apps [took 426 ms] 
,07-28 12:18:29.882  7482  7528 D UEI.SmartControl: Internal timer expired: 1
,07-28 12:18:29.882  7482  7528 D UEI.SmartControl: unbind internal service
,07-28 12:18:29.901  7482  7482 D UEI.SmartControl: Service.onUnbind: IControl
,07-28 12:18:29.904  7482  7482 D UEI.SmartControl: Service.onDestroy
07-28 12:18:29.904  7482  7482 D UEI.SmartControl: Lock is in USE false
07-28 12:18:29.904  7482  7482 D UEI.SmartControl: unbind internal service
07-28 12:18:29.905  7482  7482 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7b416d2
07-28 12:18:29.905  7482  7482 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-28 12:18:29.905  7482  7482 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-28 12:18:29.905  7482  7482 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:18:29.905  7482  7482 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:18:29.906  7482  7482 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:18:29.906  7482  7482 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:18:29.906  7482  7482 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:18:29.906  7482  7482 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:18:29.906  7482  7482 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7b416d2
07-28 12:18:29.908  7482  7482 D serial_port: close(fd = 25)
07-28 12:18:29.912  7482  7482 I UEI.SmartControl: Serial port is closed.
07-28 12:18:29.912  7482  7482 I UEI.SmartControl: Serial port is closed.
07-28 12:18:29.912  7482  7482 D UEI.SmartControl: Blaster closed
07-28 12:18:29.912  7482  7482 D UEI.SmartControl: Shut down QS...
07-28 12:18:29.912  7482  7482 D UEI.SmartControl: Stopping QS lib
07-28 12:18:29.912  7482  7482 D UEI.SmartControl: QS lib stop result = true
07-28 12:18:29.913  7482  7482 D UEI.SmartControl: Stopped QS lib
07-28 12:18:29.913  7482  7482 D UEI.SmartControl: Stopped file observer...
07-28 12:18:29.913  7482  7482 D UEI.SmartControl: QS shutdown complete
,07-28 12:18:30.002  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:18:30.002  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ea88673 added. We now have 6 listener(s)
07-28 12:18:30.003  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:18:30.014  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:30.014  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16aa7930 added. We now have 7 listener(s)
07-28 12:18:30.014  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:30.016  6577  6704 I System.out: IsBluetoothEnabled
07-28 12:18:30.019  1037  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:30.019  1037  1949 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-28 12:18:30.023  1037  1119 D BluetoothManagerService: Message: 2
,07-28 12:18:30.028  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:30.029  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:30.029  1037  2019 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:18:30.047  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:18:30.047  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:18:30.048  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-28 12:18:30.048  1037  1119 D BluetoothManagerService: Message: 1
07-28 12:18:30.048  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:18:30.076  1037  1119 D BluetoothManagerService: Message: 20
07-28 12:18:30.076  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@313883a8:true
,07-28 12:18:30.080  7543  7543 D BluetoothAdapterState: make
07-28 12:18:30.085  7543  7543 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:18:30.086  7543  7543 I bluedroid-qcom: init
07-28 12:18:30.087  7543  7735 I BluetoothAdapterState: Entering OffState
07-28 12:18:30.087  7543  7543 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:18:30.087  7543  7543 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:18:30.087  7543  7543 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:18:30.087  7543  7543 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:18:30.087  7543  7543 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:18:30.089  7543  7543 I bluedroid-qcom: get_profile_interface socket
07-28 12:18:30.089  7543  7543 I bluedroid-qcom: get_profile_interface map_client
,07-28 12:18:30.093  7543  7739 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:18:30.085  7738  7738 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:30.085  7738  7738 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:30.103  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,07-28 12:18:30.106  1037  1119 D BluetoothManagerService: Message: 40
07-28 12:18:30.106  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:18:30.107  7543  7559 I bluedroid-qcom: config_hci_snoop_log
07-28 12:18:30.108  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:18:30.108  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-28 12:18:30.114  7738  7738 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:18:30.114  7738  7738 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:18:30.114  7738  7738 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-28 12:18:30.117  7738  7738 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,07-28 12:18:30.122  7543  7735 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:18:30.123  7738  7738 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:18:30.123  7738  7738 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-28 12:18:30.125  7543  7735 D BluetoothAdapterProperties: Setting state to 11
07-28 12:18:30.126  7543  7735 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:18:30.127  7543  7735 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:18:30.127  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:30.128  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:18:30.128  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:18:30.132  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:18:30.135  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:30.138  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:30.140  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:18:30.151  7543  7739 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:18:30.155  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:18:30.155  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:18:30.156  7543  7739 D BluetoothAdapterProperties: Name is: G3
07-28 12:18:30.159  7543  7543 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:18:30.160  7543  7543 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:30.160  7543  7543 V BluetoothPbapReceiver: ***********state = 11
07-28 12:18:30.164  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:18:30.186  6776  6776 D BluetoothPermissionRequest: onReceive
,07-28 12:18:30.196  7543  7735 D BluetoothBondStateMachine: make
07-28 12:18:30.200  7543  7754 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:18:30.200  7543  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.201  7543  7735 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:18:30.201  7543  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.201  7543  7735 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:18:30.201  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:30.203  7543  7735 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:18:30.206  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:30.215  7543  7543 D HeadsetService: Received start request. Starting profile...
07-28 12:18:30.215  7543  7543 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:18:30.215  7543  7543 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:18:30.216  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:18:30.218  7543  7543 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:18:30.219  7543  7543 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:18:30.220  7543  7543 D HeadsetStateMachine: make
07-28 12:18:30.222  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:30.226  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:30.231  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:18:30.237  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:30.242  7543  7735 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:18:30.248  7543  7543 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:30.248  7543  7543 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:30.252  7543  7543 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:18:30.252  7543  7543 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:18:30.254  7543  7543 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:18:30.254   316  1371 V AudioPolicyService: registerClient() client 0xb04108e0, uid 1002
07-28 12:18:30.255   316  2125 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:18:30.255   316  2125 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:18:30.255   316  2125 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:18:30.255  7543  7543 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:18:30.255   316   316 V AudioFlinger: registerClient() client 0xb1433178, pid 7543
07-28 12:18:30.255   316  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:30.255   316  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:30.256  7543  7559 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:30.256  1590  3095 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:30.256  1590  3095 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:30.256  1838  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:30.256  1838  1854 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:30.256  1037  2019 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:30.256  1037  2019 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:30.256  3442  3457 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:18:30.256  3442  3457 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:18:30.256   316  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:30.256   316  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:30.256  1037  1685 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:30.256  1037  1685 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:30.256  1590  2171 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:30.256  1590  2171 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:30.256  1838  2480 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:30.256  1838  2480 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:30.257  7543  7559 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:18:30.257  3442  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:30.257  7543  7543 V ToneGenerator: Create Track: 0xb4928080
07-28 12:18:30.257  3442  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:18:30.257  7543  7543 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:18:30.257  7543  7543 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:18:30.257  7543  7559 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:18:30.257  7543  7559 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:18:30.257   316  1371 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:18:30.257   316  1371 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:18:30.257   316  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:18:30.257   316  1371 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:18:30.257   316  2125 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 ,12:18:30.257   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:18:30.257   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:18:30.257   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:18:30.257   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:18:30.257  7543  7543 V AudioSystem: getLatency() output 2, latency 50
07-28 12:18:30.257  7543  7543 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:18:30.257  7543  7543 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:18:30.258   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:18:30.258   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:18:30.258   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:18:30.258   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:18:30.258   316  1372 V AudioFlinger: createTrack() lSessionId: 23
07-28 12:18:30.258  7543  7543 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:18:30.258   316  1371 V AudioFlinger: acquiring 23 from 7543, for 7543
07-28 12:18:30.258   316  1371 V AudioFlinger:  added new entry for 23
07-28 12:18:30.259  7543  7543 V ToneGenerator: ToneGenerator INIT OK, time: 152647
07-28 12:18:30.259  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.259  7543  7758 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:18:30.259  7543  7758 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:18:30.259  7543  7758 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:18:30.260  7543  7758 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:18:30.260  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.260   316  2125 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7543
07-28 12:18:30.261   316  2125 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:18:30.261   316  2125 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:18:30.261   316  2125 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:18:30.261   316  2125 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:18:30.261   316  2125 V voice   : voice_set_parameters: exit with code(0)
07-28 12:18:30.261   316  2125 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:18:30.261   316  2125 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:18:30.261   316  2125 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:18:30.261   316  2125 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:18:30.261   316  2125 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:18:30.261   316  2125 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:18:30.261  7543  7543 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:30.262  7543  7758 V ToneGenerator: ToneGenerator destructor
07-28 12:18:30.262  7543  7758 V ToneGenerator: stopTone
07-28 12:18:30.262  7543  7758 V ToneGenerator: Delete Track: 0xb4928080
07-28 12:18:30.262  7543  7758 V AudioTrack: ~AudioTrack, releasing session id from 7543 on behalf of 7543
07-28 12:18:30.263   316  1372 V AudioFlinger: releasing 23 from 7543 for 7543
07-28 12:18:30.263   316  1372 V AudioFlinger:  decremented refcount to 0
07-28 12:18:30.263   316  1372 V AudioFlinger: purging stale effects
07-28 12:18:30.263   316  1372 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:18:30.263   316  1372 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:18:30.263   316  1274 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:18:30.263   316  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:18:30.263   316  1274 V AudioPolicyManager: releaseOutput() 2
07-28 12:18:30.263   316  1274 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:18:30.263   316  1372 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:18:30.263   316  1372 V AudioFlinger: removeClient_l() pid 7543, calling pid 316
07-28 12:18:30.264  7543  7543 D A2dpService: Received start request. Starting profile...
07-28 12:18:30.265  7543  7543 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:18:30.265  7543  7543 V Avrcp   : make
07-28 12:18:30.265  7543  7735 V LGMDMManager: Create singleton instance
07-28 12:18:30.266  7543  7543 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:18:30.266  7543  7543 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:18:30.266  1037  2019 W Process : Unable to open /proc/7760/status
07-28 12:18:30.268  7543  7735 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:18:30.273  7543  7543 V AudioManager: registerRemoteController: size of Media player list: 0
,07-28 12:18:30.274  7543  7543 E AudioManager: No RCC entry present to update
07-28 12:18:30.274  7543  7543 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:18:30.277  7543  7543 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:18:30.277  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:18:30.277  7543  7543 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:18:30.280  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:18:30.366  1037  2037 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:18:30.366  1037  2037 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:18:30.441  1037  1949 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-28 12:18:30.457  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-28 12:18:30.463  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:18:30.464  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:18:30.464  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:18:30.464  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:18:30.465  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:18:30.465  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:18:30.465  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:18:30.465  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:18:30.465  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:18:30.465  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:18:30.465  7543  7543 I BluetoothA2dpServiceJni: classInitNative
07-28 12:18:30.466  7543  7543 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:18:30.466  7543  7543 D A2dpStateMachine: make
07-28 12:18:30.469  7543  7543 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:18:30.469  7543  7764 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-28 12:18:30.472  7543  7543 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:18:30.473  7543  7543 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:18:30.474  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.474  7543  7763 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:18:30.475  7543  7543 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:18:30.478  7543  7543 D HidService: Received start request. Starting profile...
07-28 12:18:30.478  7543  7543 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:18:30.478  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.479  7543  7543 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:18:30.480  7543  7543 D HealthService: Received start request. Starting profile...
07-28 12:18:30.486  7543  7543 I bluedroid-qcom: get_profile_interface health
,07-28 12:18:30.487  7543  7543 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:18:30.487  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.490  7543  7543 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:18:30.494  7543  7543 D PanService: Received start request. Starting profile...
07-28 12:18:30.495  7543  7543 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:18:30.495  7543  7543 I bluedroid-qcom: get_profile_interface pan
07-28 12:18:30.508  7543  7543 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:18:30.508  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
,07-28 12:18:30.509  7543  7543 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 12:18:30.516  7543  7543 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:18:30.516  7543  7543 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:18:30.516  7543  7543 D BtGatt.GattService: start()
07-28 12:18:30.516  7543  7543 I bluedroid-qcom: get_profile_interface gatt
07-28 12:18:30.517  7543  7543 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:18:30.526  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
,07-28 12:18:30.527  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.528  7543  7543 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:18:30.529  7543  7543 V BluetoothMapService: BluetoothMapBinder()
07-28 12:18:30.529  7543  7543 D BluetoothMapService: Received start request. Starting profile...
07-28 12:18:30.529  7543  7543 D BluetoothMapService: start()
07-28 12:18:30.533  7543  7543 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:18:30.533  7543  7543 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:18:30.534  7543  7543 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:18:30.534  7543  7543 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-28 12:18:30.559  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:30.561  7543  7543 D HeadsetStateMachine: Proxy object connected
,07-28 12:18:30.563  7543  7543 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:18:30.563  7543  7543 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-28 12:18:30.572  7543  7543 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:30.572  7543  7543 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:30.573  7543  7543 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:30.573  7543  7543 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:30.573  7543  7758 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:18:30.573  7543  7543 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:30.573  7543  7543 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:18:30.573  7543  7758 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:18:30.574  7543  7758 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-28 12:18:30.578  7543  7543 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:18:30.583  7543  7543 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:30.588  7543  7543 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:18:30.588  7543  7543 V PanService: [BTUI] SIM Extra State :ABSENT
,07-28 12:18:30.592  7543  7543 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:18:30.595  7543  7543 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:18:30.596  7543  7543 V BluetoothMapService: Handler(): got msg=1
07-28 12:18:30.597  7543  7735 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:18:30.597  7543  7735 I bluedroid-qcom: enable
07-28 12:18:30.597  7543  7777 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:18:30.597  7543  7735 I bt_hci_bdroid: init
07-28 12:18:30.599  7543  7735 I bt_vendor: bt-vendor : init
07-28 12:18:30.599  7543  7735 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:18:30.599  7543  7735 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:18:30.599  7543  7735 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:18:30.599  7543  7735 D bt_userial_mct: userial_init
07-28 12:18:30.599  7543  7735 D bt_hci_bdroid: set_power 1
07-28 12:18:30.599  7543  7735 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:18:30.599  7543  7735 I bt_vendor: Starting hciattach daemon
07-28 12:18:30.599  7543  7735 I bt_vendor: try to set true
07-28 12:18:30.601  7543  7777 I bt-btu  : btu_task pending for preload complete event
,07-28 12:18:30.595  7780  7780 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:18:30.595  7780  7780 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:30.632  7781  7781 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:18:30.703  7787  7787 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:18:30.728  7788  7788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:18:30.756  7790  7790 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:18:30.769  7791  7791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-28 12:18:30.780  7792  7792 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:18:30.793  7793  7793 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-28 12:18:30.817  7795  7795 I libmdmdetect: ESOC framework not supported
,07-28 12:18:30.818  7795  7795 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:18:30.826  7795  7795 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-28 12:18:30.826  7795  7795 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:18:30.826  7795  7795 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:18:30.826  7795  7795 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:18:30.826  7795  7795 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:18:30.826  7795  7795 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:18:30.826  7795  7795 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:18:30.867  7795  7796 E QC-QMI  : qmi_client [7795] 15: failed to locate client data
07-28 12:18:30.868   487   487 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:18:30.868   487   487 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-28 12:18:30.922  7797  7797 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:18:30.937  7798  7798 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:18:30.954  7543  7735 I bt_vendor: bluetooth satus is on
07-28 12:18:30.954  7543  7735 D bt_hci_bdroid: preload
,07-28 12:18:30.954  7543  7779 D bt_userial_mct: userial_open(port:0)
07-28 12:18:30.954  7543  7779 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-28 12:18:30.958  7543  7779 I bt_vendor: Done intiailizing UART
07-28 12:18:30.959  7543  7779 I bt_vendor: Done intiailizing UART
07-28 12:18:30.959  7543  7779 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:18:30.959  7543  7779 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:18:30.959  7543  7800 D bt_userial_mct: Entering userial_read_thread()
07-28 12:18:30.960  7543  7777 I bt-btu  : btu_task received preload complete event
07-28 12:18:30.960  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:18:30.960  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 12:18:30.962  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-28 12:18:30.965  7543  7777 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:18:30.966  7543  7777 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:18:31.040  7543  7777 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,07-28 12:18:31.041  7543  7777 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e8061 
07-28 12:18:31.041  7543  7777 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e8061 
,07-28 12:18:31.109  7543  7739 E bt-btif : Calling BTA_HhEnable
,07-28 12:18:31.119  7543  7739 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 12:18:31.120  7543  7739 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:18:31.123  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:18:31.124  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:18:31.125  7543  7739 D BluetoothAdapterProperties: Name is: G3
07-28 12:18:31.128  7543  7739 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:18:31.129  7543  7739 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:18:31.134  7543  7739 D bt_hci_bdroid: postload
07-28 12:18:31.135  7543  7739 D bte_conf: Device ID record 1 : primary
07-28 12:18:31.135  7543  7739 D bte_conf:   vendorId            = 00c4
07-28 12:18:31.136  7543  7739 D bte_conf:   vendorIdSource      = 0001
07-28 12:18:31.136  7543  7739 D bte_conf:   product             = 13a1
07-28 12:18:31.136  7543  7739 D bte_conf:   version             = 1000
07-28 12:18:31.136  7543  7739 D bte_conf:   clientExecutableURL = 
07-28 12:18:31.136  7543  7739 D bte_conf:   serviceDescription  = 
07-28 12:18:31.136  7543  7739 D bte_conf:   documentationURL    = 
07-28 12:18:31.136  7543  7779 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:18:31.136  7543  7739 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:18:31.125  7805  7805 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:31.125  7805  7805 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:31.145  7543  7735 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:18:31.145  7543  7735 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:18:31.145  7543  7735 D BluetoothAdapterProperties: State =  11
07-28 12:18:31.146  7543  7735 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:18:31.146  7543  7735 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:18:31.146  7543  7735 D BluetoothAdapterProperties: Setting state to 12
07-28 12:18:31.146  7543  7735 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:18:31.151  7543  7739 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:18:31.155  1037  1119 D BluetoothManagerService: Message: 60
07-28 12:18:31.155  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:18:31.155  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-28 12:18:31.171  7543  7735 I BluetoothAdapterState: Entering On State
,07-28 12:18:31.183  7543  7735 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:18:31.183  7543  7735 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:18:31.183  7543  7735 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-28 12:18:31.185  7543  7735 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 12:18:31.195  7543  7739 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:18:31.197  7543  7739 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-28 12:18:31.208  7543  7779 D bt_hci_bdroid: Used up Tx Cmd credits
,07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:31.210  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:31.216  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:31.217  7543  7779 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:18:31.217  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:18:31.217  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:18:31.217  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:18:31.218  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:18:31.218  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:18:31.218  7543  7777 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:18:31.218  7543  7739 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:18:31.220  7543  7800 E bt_mct  : hci lib postload completed
,07-28 12:18:31.224  7543  7735 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:18:31.264  7810  7810 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-28 12:18:31.276  6776  6875 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:18:31.277  7543  7777 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:31.277  7543  7777 W bt-smp  : Plain text(LSB ~ MSB) = 92 55 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:31.277  7543  7777 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 9a 13 66 be ac 43 ae 25 ee f4 93 46 93 c7 05 
07-28 12:18:31.277  7543  7777 W bt-btm  : Stopping oneshot timer
07-28 12:18:31.278  6776  6791 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:18:31.278  6776  6791 D BluetoothPan: onBluetoothStateChange call bindService
07-28 12:18:31.281  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:18:31.282  6776  6776 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:18:31.283  6776  6776 D PanProfile: Bluetooth service connected
,07-28 12:18:31.283  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:31.284  1838  4011 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:31.286  1037  1037 D BluetoothA2dp: Proxy object connected
07-28 12:18:31.289  1037  1037 D BluetoothHeadset: Proxy object connected
07-28 12:18:31.290  1838  1838 D BluetoothHeadset: Proxy object connected
07-28 12:18:31.291  6776  6875 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:18:31.294  6776  6791 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:18:31.294  6776  6776 D BluetoothMap: Proxy object connected
07-28 12:18:31.295  6776  6776 D MapProfile: Bluetooth service connected
07-28 12:18:31.295  6776  6776 D BluetoothMap: getConnectedDevices()
,07-28 12:18:31.297  7543  7559 V BluetoothMapService: getConnectedDevices()
07-28 12:18:31.298  1838  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:31.299  6776  6776 D BluetoothA2dp: Proxy object connected
07-28 12:18:31.299  6776  6776 D A2dpProfile: Bluetooth service connected
07-28 12:18:31.300  1838  1838 D BluetoothHeadset: Proxy object connected
07-28 12:18:31.301  7543  7777 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:31.301  7543  7777 W bt-smp  : Plain text(LSB ~ MSB) = b9 8c 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:31.301  7543  7777 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 1d 67 c1 1b 87 fc a1 14 a7 93 8d 64 10 94 de 
07-28 12:18:31.301  7543  7777 W bt-btm  : Stopping oneshot timer
07-28 12:18:31.301  6776  6791 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:18:31.304  1838  2480 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:18:31.305  6776  6776 D BluetoothInputDevice: Proxy object connected
07-28 12:18:31.305  6776  6776 D HidProfile: Bluetooth service connected
07-28 12:18:31.306  1838  1838 D BluetoothHeadset: Proxy object connected
07-28 12:18:31.306  6776  6792 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:18:31.309  6776  6776 D BluetoothHeadset: Proxy object connected
07-28 12:18:31.309  6776  6776 D HeadsetProfile: Bluetooth service connected
07-28 12:18:31.309  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:18:31.310  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:18:31.312  1929  1929 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.312  1929  2078 D LGBluetoothAPIService: Message: 1
07-28 12:18:31.312  1929  2078 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:18:31.313  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:18:31.313  7543  7777 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:31.313  7543  7777 W bt-smp  : Plain text(LSB ~ MSB) = a2 31 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:31.313  7543  7777 W bt-smp  : Encrypted text(LSB ~ MSB) = 0e 27 1d ff 94 90 2c 0c 2f d4 40 96 a1 54 43 9c 
07-28 12:18:31.314  7543  7777 W bt-btm  : Stopping oneshot timer
07-28 12:18:31.317  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:31.318  1929  2078 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-28 12:18:31.320  7543  7543 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.320  7543  7543 D BluetoothMapService: STATE_ON
,07-28 12:18:31.320  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:18:31.320  1037  1119 D BluetoothManagerService: Message: 40
07-28 12:18:31.320  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 12:18:31.321  7543  7543 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:18:31.322  7543  7543 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:18:31.323  1929  1929 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:18:31.323  1929  2078 D LGBluetoothAPIService: Message: 100
07-28 12:18:31.323  1929  2078 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:18:31.325  7543  7777 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:31.325  7543  7777 W bt-smp  : Plain text(LSB ~ MSB) = c1 ae 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:31.325  7543  7777 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 44 76 c5 56 4c 99 f0 00 69 50 06 39 0d fd 7f 
07-28 12:18:31.325  7543  7777 W bt-btm  : Stopping oneshot timer
07-28 12:18:31.326  6776  6776 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:18:31.327  6776  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:18:31.334  6776  6776 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:18:31.335  7543  7777 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:18:31.335  7543  7777 W bt-smp  : Plain text(LSB ~ MSB) = 6c d7 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:18:31.335  7543  7777 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 36 70 07 ef ae 72 70 6c 23 fd f1 de 2b 89 d4 
07-28 12:18:31.335  7543  7777 W bt-btm  : Stopping oneshot timer
07-28 12:18:31.339  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
07-28 12:18:31.339  7543  7543 V BluetoothPbapService: Pbap Service onCreate
07-28 12:18:31.339  7543  7543 V BluetoothPbapService: Starting PBAP service
07-28 12:18:31.340  7543  7543 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 12:18:31.340  7543  7543 V BluetoothMapService: Handler(): got msg=1
07-28 12:18:31.341  7543  7543 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:18:31.342  7543  7543 V BluetoothPbapService: Pbap Service onBind
07-28 12:18:31.343  7543  7828 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:18:31.343  7543  7828 D BluetoothMapMasInstance:   masId = 00
07-28 12:18:31.343  7543  7828 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:18:31.343  7543  7828 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:18:31.343  7543  7828 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:18:31.343  7543  7543 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.343  7543  7543 V BluetoothPbapService: state: 12
07-28 12:18:31.344  7543  7543 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:18:31.344  7543  7543 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.344  7543  7543 V BluetoothPbapReceiver: ***********state = 12
07-28 12:18:31.345  6776  6776 D BluetoothPbap: Proxy object connected
07-28 12:18:31.345  6776  6776 D PbapServerProfile: Bluetooth service connected
07-28 12:18:31.345  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:18:31.345  7543  7543 V BluetoothPbapService: Handler(): got msg=1
07-28 12:18:31.347  7543  7543 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:18:31.348  2094  2094 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:18:31.349  2094  2094 D c       : Getting all permits...
07-28 12:18:31.349  2094  2094 D a       : Opening database...
07-28 12:18:31.350  7543  7828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:31.351  7543  7828 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:18:31.351  7543  7828 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:18:31.351  7543  7828 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:18:31.351  7543  7829 V BluetoothPbapService: Pbap Service initSocket
07-28 12:18:31.352  7543  7739 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:18:31.352  7543  7739 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:18:31.353  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:31.354  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:31.356  2094  2094 D a       : Opening database auth.proximity.permit_store...
07-28 12:18:31.357  7543  7829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:31.357  2094  2094 D a       : Closing database...
,07-28 12:18:31.364  7543  7829 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:18:31.364  7543  7829 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:18:31.364  7543  7829 V BluetoothPbapService: Accepting socket connection...
07-28 12:18:31.370  6776  6776 D BluetoothPermissionRequest: onReceive
,07-28 12:18:31.371  6776  6776 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:18:31.374  6776  6776 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:18:31.377  7543  7543 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:18:31.379  7543  7543 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:18:31.385  7543  7543 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-28 12:18:31.410  7543  7543 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-28 12:18:31.410  7543  7543 V BtOppService: onCreate
07-28 12:18:31.415  7543  7543 V BluetoothOppNotification: send message
07-28 12:18:31.419  7543  7543 V BtOppService: Starting RfcommListener
07-28 12:18:31.426  7543  7543 D BluetoothOppPreference: Dumping Names:  
07-28 12:18:31.426  7543  7543 D BluetoothOppPreference: {}
07-28 12:18:31.426  7543  7543 D BluetoothOppPreference: Dumping Channels:  
07-28 12:18:31.426  7543  7543 D BluetoothOppPreference: {}
07-28 12:18:31.428  7543  7543 V BtOppService: onStartCommand
07-28 12:18:31.429  7543  7837 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 12:18:31.435  7543  7543 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.436  7543  7543 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:18:31.437  7543  7837 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:18:31.439  7543  7834 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:18:31.440  7543  7837 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@48ccaa9 on behalf of 
,07-28 12:18:31.443  7543  7543 V BluetoothOppNotification: new notify threadi!
07-28 12:18:31.444  7543  7834 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:18:31.446  7543  7834 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 12:18:31.448  7543  7543 V BluetoothOppNotification: send delay message
07-28 12:18:31.448  7543  7543 V BtOppService: start RfcommListener
07-28 12:18:31.448  7543  7838 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:18:31.452  7543  7543 V BtOppService: RfcommListener started
,07-28 12:18:31.452  7543  7543 V BtOppService: ContentObserver received notification
07-28 12:18:31.452  7543  7543 V BtOppService: ContentObserver received notification
07-28 12:18:31.456  7543  7839 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:18:31.456  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:31.457  7543  7839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:31.458  7543  7839 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-28 12:18:31.459  7543  7839 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:18:31.459  7543  7839 I BtOppRfcommListener: Accept thread started.
07-28 12:18:31.459  7543  7839 V BtOppRfcommListener: Accepting connection...
07-28 12:18:31.486  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
,07-28 12:18:31.487  7543  7543 V BluetoothFtpService: Ftp Service onCreate
07-28 12:18:31.487  7543  7543 I BluetoothFtpService: Ftp Service onCreate
07-28 12:18:31.487  7543  7543 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:18:31.487  7543  7543 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.487  7543  7543 V BluetoothFtpService: Starting Listening on sockets
07-28 12:18:31.488  7543  7543 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:18:31.488  7543  7543 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:18:31.488  7543  7543 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:18:31.488  7543  7543 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.488  7543  7543 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:18:31.488  7543  7543 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:18:31.491  7543  7543 V BluetoothFtpService: Handler(): got msg=1
07-28 12:18:31.492  7543  7543 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:18:31.492  7543  7543 V BluetoothFtpService: Ftp Service initSocket
07-28 12:18:31.497  1037  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:31.498  7543  7543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:18:31.500  7543  7543 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
07-28 12:18:31.501  7543  7543 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:18:31.503  7543  7840 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:18:31.527  7543  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3db92b34
,07-28 12:18:31.527  7543  7543 V BluetoothSapService: Sap Service onCreate
07-28 12:18:31.530  7543  7543 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:18:31.530  7543  7543 V BluetoothSapService: state: 12
07-28 12:18:31.530  7543  7543 V BluetoothSapService: Starting SAP server process
07-28 12:18:31.533  7543  7543 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:18:31.525  7841  7841 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:31.525  7841  7841 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:31.534  7543  7842 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:18:31.535  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:31.535  7543  7842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:18:31.539  7543  7842 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
07-28 12:18:31.539  7543  7842 V BluetoothSapService: Succeed to create listening socket 
07-28 12:18:31.539  7543  7842 V BluetoothSapService: Accepting socket connection...
,07-28 12:18:31.545  7841  7841 V BT_SAP  : Event pipe created
07-28 12:18:31.545  7841  7841 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:18:31.545  7841  7841 V BT_SAP  : created socket fd 6
07-28 12:18:31.573  1037  1685 I art     : Explicit concurrent mark sweep GC freed 25934(1276KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.651ms total 125.541ms
07-28 12:18:31.574  7543  7838 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@137f693a on behalf of 
07-28 12:18:31.574  7543  7834 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c2ba9eb on behalf of 
,07-28 12:18:31.576  7543  7838 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 12:18:31.576  7543  7837 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:18:31.576  7543  7837 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:18:31.579  7543  7838 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:18:31.579  7543  7837 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31f2348 on behalf of 
07-28 12:18:31.583  7543  7837 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:18:31.585  7543  7837 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,07-28 12:18:31.585  7543  7838 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b225e1 on behalf of 
07-28 12:18:31.589  7543  7838 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:18:31.590  7543  7838 V BluetoothOppNotification: outbound notification was removed.
07-28 12:18:31.590  7543  7838 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:18:31.593  7543  7838 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a6adf06 on behalf of 
07-28 12:18:31.594  7543  7838 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:18:31.596  7543  7838 V BluetoothOppNotification: inbound notification was removed.
07-28 12:18:31.596  7543  7838 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:18:31.598  7543  7838 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3418f9c7 on behalf of 
,07-28 12:18:31.658  1037  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{388c6b98 type 2 when 154031 com.google.android.gms} when 154031
,07-28 12:18:31.668   310  7844 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-28 12:18:31.670  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:32.082  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:18:32.095  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:32.097  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:32.097  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a269a9 added. We now have 8 listener(s)
07-28 12:18:32.097  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:32.100  1037  1053 D WifiServiceImplEx: setWifiEnabled: false pid=6577, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:18:32.100  1037  1053 D WifiService: setWifiEnabled: false pid=6577, uid=10118
07-28 12:18:32.100  1037  1053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:18:32.108  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:32.110  1037  1949 D WifiServiceImplEx: setWifiEnabled: true pid=6577, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:18:32.110  1037  1949 D WifiService: setWifiEnabled: true pid=6577, uid=10118
07-28 12:18:32.110  1037  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:18:32.128  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-28 12:18:32.128  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-28 12:18:32.128  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:18:32.130  1037  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,07-28 12:18:32.130  1037  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:18:32.132  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:18:32.132  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:18:32.132  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:18:32.132  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,07-28 12:18:32.132  1037  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
07-28 12:18:32.132  1037  1526 E WifiHW  : unknown target_country: EU , set to default,
,07-28 12:18:32.132  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,07-28 12:18:32.133  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,07-28 12:18:32.133  1037  1526 I WifiUtil: gEnableBmps=1
,07-28 12:18:32.450  7543  7543 V BluetoothOppNotification: new notify threadi!,
07-28 12:18:32.451  7543  7543 V BluetoothOppNotification: send delay message
,07-28 12:18:32.475  7543  7857 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:18:32.478  7543  7857 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a72bf4 on behalf of 
07-28 12:18:32.479  7543  7857 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:18:32.480  7543  7857 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-28 12:18:32.483  7543  7857 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@164a3f1d on behalf of 
07-28 12:18:32.484  7543  7857 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:18:32.486  7543  7857 V BluetoothOppNotification: outbound notification was removed.
07-28 12:18:32.486  7543  7857 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:18:32.489  7543  7857 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a45e592 on behalf of 
07-28 12:18:32.490  7543  7857 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-28 12:18:32.495  7543  7857 V BluetoothOppNotification: inbound notification was removed.
07-28 12:18:32.495  7543  7857 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:18:32.496  7543  7857 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ca16b63 on behalf of 
07-28 12:18:32.699   310   895 D SoftapController: Softap fwReload - Ok
,07-28 12:18:32.703  1037  1526 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (567ms)
07-28 12:18:32.706  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:18:32.707  1037  1119 D Tethering: InitialState.processMessage what=4
07-28 12:18:32.707  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:18:32.712   310   895 D CommandListener: Setting iface cfg
07-28 12:18:32.712   310   895 D CommandListener: Trying to bring down wlan0
,07-28 12:18:32.715   310   895 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:18:32.716  1037  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-28 12:18:32.715  7865  7865 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:18:32.725  7865  7865 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:32.756  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:32.756  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:32.756  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:18:32.756  1037  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:18:32.756  1037  1526 D WifiMonitor: connecting to supplicant
,07-28 12:18:32.767  7865  7865 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:18:32.788  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:32.789  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 12:18:32.792  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:32.796  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 12:18:32.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:18:32.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:18:32.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:18:32.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:18:32.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:18:32.802  6776  6776 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:18:32.803  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,07-28 12:18:32.803  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:18:32.803  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:18:32.803  6776  6776 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:18:32.803  6776  6776 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:18:32.805  7865  7865 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:18:32.805  7865  7865 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-28 12:18:32.808  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:18:32.808  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:18:32.808  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:18:32.808  6776  6776 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:18:32.809  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:18:32.810  6776  6776 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:18:32.810  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:18:32.810  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:18:32.810  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:18:32.810  6776  6776 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:18:32.810  6776  6776 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:18:32.861  7865  7865 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:18:32.863  1037  1873 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7883 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
07-28 12:18:32.881   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 19.907ms
,07-28 12:18:32.899   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 17.451ms
,07-28 12:18:32.916   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 16.357ms
,07-28 12:18:32.928  7865  7865 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-28 12:18:32.934  7865  7865 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 12:18:32.935  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:18:32.935  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:18:32.936  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:18:32.936  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:18:32.936  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:18:32.936  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:18:32.936  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:18:32.936  1037  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:18:32.937  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:32.937  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:32.938  1037  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:18:32.938  1037  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:18:32.938  1037  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:18:32.938  1037  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:18:32.938  1037  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:18:32.940  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:18:32.940  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:18:32.940  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:18:32.940  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:32.940  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:32.940  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:32.940  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:32.940  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:18:32.940  1037  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 12:18:32.941  1037  1526 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:18:32.941  1037  1526 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:18:32.941  1037  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:18:32.941  1037  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 12:18:32.945  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:32.946  1037  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-28 12:18:32.947  1929  1929 D WfdService: Waiting for WifiP2p enabling
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:32.950  6577  6577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:32.953  6577  6577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:32.953  1037  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:18:32.953  1037  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:18:32.986  1037  1983 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7906 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:18:32.987  1037  1526 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:18:32.987  1037  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,07-28 12:18:32.988  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:18:32.989  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:18:32.989  1037  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:18:32.989  1037  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:18:32.989  1037  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 12:18:32.989  1037  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:18:32.990  7883  7904 W FormManager: Network not available. Please check & try again.
07-28 12:18:32.990  1037  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:18:32.990  1037  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:18:32.990  1037  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:18:32.990  1037  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:18:32.990  1037  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:18:32.990  1037  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:18:32.991  1037  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:18:32.991  1037  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:18:32.991  1037  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:18:32.991  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:18:32.991  1037  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:18:32.992  1037  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:18:32.992  1037  1526 D WifiNative-HAL: Setting external_sim to 1
07-28 12:18:32.992  1037  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:18:32.992  1929  1929 D WfdsService: Supplicant Connection state is changed : true
07-28 12:18:32.992  1929  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:18:32.992  1037  1526 D WifiNative-wlan0: SET external_sim 1: returned true
,07-28 12:18:32.992  1037  1526 I WifiNative-HAL: startHal
07-28 12:18:32.992  1929  2242 D WfdsService: Set the WFDS Monitor: true
07-28 12:18:32.992  1037  1526 D wifi    : setting scan oui 0x9576d260
07-28 12:18:32.992  1929  2242 D WfdsMonitor: WfdsMonitorThread create
07-28 12:18:32.993  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:18:32.993  1037  1526 I WifiNative-HAL: startHal
07-28 12:18:32.993  1037  1526 D wifi    : setting scan oui 0x9576d260
07-28 12:18:32.993  1929  2242 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:18:32.993  1929  2242 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:18:32.993  1037  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:18:32.993  7573  7573 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:32.993  1037  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:18:32.993  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:18:32.993  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,07-28 12:18:32.993  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:18:32.994  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:18:32.994  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:18:32.994  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:18:32.994  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:18:32.994  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:18:32.994  1929  7915 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:18:32.994  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:18:32.994  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:18:32.994  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:18:32.995  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:18:32.995  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:18:32.995  1929  7915 E CtrlSupplicant: Succeed to open control connection
07-28 12:18:32.995  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:18:32.995  1929  7915 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:18:32.995  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:18:32.995  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:18:32.995  7865  7865 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:18:32.996  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:18:32.996  1929  7915 D WfdsMonitor: Supplicant connection established
07-28 12:18:32.996  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:18:32.996  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:18:32.996  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:18:32.997  1037  1526 E WifiNative: : [155,370,626 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:18:32.997  1037  1526 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:18:32.998  1929  2242 D WfdsService: Connected to the supplicant for wfds
07-28 12:18:32.998  1037  1526 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:18:32.998  1037  1526 D WifiNative-wlan0: doString: [STATUS]
07-28 12:18:32.999  1037  1526 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,07-28 12:18:32.999  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:33.000  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:18:33.000  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:33.000  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:18:33.000  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.003   310   895 D CommandListener: Setting iface cfg
07-28 12:18:33.003   310   895 D CommandListener: Trying to bring up p2p0
,07-28 12:18:33.003  1037  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:18:33.003  1037  1524 D LGWifiP2pService: P2pEnablingState
07-28 12:18:33.004  1037  1524 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.004  1037  1524 D LGWifiP2pService: P2p socket connection successful
07-28 12:18:33.004  1037  1524 D LGWifiP2pService: P2pEnabledState
07-28 12:18:33.006  1929  1929 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:18:33.006  1929  1929 D WfdsService: WifiP2pState is changed : true
07-28 12:18:33.006  1929  2242 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:18:33.006  1929  2242 D WfdsService: Set the WFDS Monitor: true
07-28 12:18:33.006  1929  2242 D WfdsService: Connected to the supplicant for wfds
07-28 12:18:33.006  1929  2242 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:18:33.006  7865  7865 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:18:33.006  1929  2242 D WfdsService: selectPreferredScanChannel [36]
07-28 12:18:33.006  1929  2242 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:18:33.007  1037  1524 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 12:18:33.008  1037  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:18:33.008  1037  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:18:33.008  1037  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:18:33.008  1037  1524 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:18:33.008  1037  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:18:33.008  1037  1524 D LGWifiP2pService: before postfix = G3
07-28 12:18:33.009  1037  1524 D WifiServerServiceExt: postfix byte check : 2
07-28 12:18:33.009  1037  1524 D LGWifiP2pService: after postfix = G3
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:18:33.009  1929  1929 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:18:33.009  1929  1929 D WfdsService: isConnected: false
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:18:33.009  1037  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:18:33.010  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:18:33.010  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:18:33.010  1037  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:18:33.010  1037  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:18:33.010  1037  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:18:33.010  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:18:33.010  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:18:33.010  1037  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:18:33.010  1037  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:18:33.011  1037  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:18:33.011  1037  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 12:18:33.011  1037  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:18:33.011  1037  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:18:33.011  1037  1526 E WifiStateMachine:  DriverS,tartedState CMD_START_DRIVER 0 0
07-28 12:18:33.012  7883  7905 V FormManager: Network unavailable.
07-28 12:18:33.012  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:18:33.012  1037  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.012  1037  1543 I WifiNative-HAL: startHal
07-28 12:18:33.012  1037  1037 D RttService: SCAN_AVAILABLE : 3
07-28 12:18:33.012  1037  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.013  1929  1929 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:18:33.013  1929  1929 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:18:33.013  1929  1929 D WfdsService: Update P2p Interface State: 3
07-28 12:18:33.014  1037  1526 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:18:33.015  1037  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
,07-28 12:18:33.017  7883  7905 V FormManager: Network unavailable.
07-28 12:18:33.018  1037  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:18:33.018  1037  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 12:18:33.018  1037  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:18:33.018  1037  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:18:33.018  1037  1524 D LGWifiP2pService: InactiveState
07-28 12:18:33.018  7865  7865 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:18:33.018  1037  1524 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.018  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.019  1037  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:18:33.019  1037  1526 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:18:33.019  1037  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:18:33.020  1037  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:18:33.020  1037  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:18:33.020  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:18:33.021  7865  7865 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.022  1037  7901 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:18:33.022  1037  7901 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.022  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.022  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.022  1929  7915 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:18:33.022  7865  7865 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:18:33.022  7865  7865 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:18:33.022  1037  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:18:33.022  7865  7865 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.022  1037  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.023  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.023  1037  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.023  1037  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.023  1037  1524 D LGWif,iP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.023  1037  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.023  7865  7865 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1037  1037 E WifiServerServiceExt: No p2p device connected
07-28 12:18:33.023  1037  1543 D wifi    : getting scan capabilities on interface[1] = 0x9576d260
07-28 12:18:33.023  1037  1543 D wifi    : failed to get capabilities : -3
07-28 12:18:33.023  1037  1543 E WifiScanningService: could not get scan capabilities
07-28 12:18:33.023  1929  7915 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.023  1929  7915 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.023  1037  7901 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.023  1037  7901 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1037  7901 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.023  1037  7901 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.023  1929  2242 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:18:33.024  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:18:33.024  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:18:33.025  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:18:33.025  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:18:33.025  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:18:33.026  7865  7865 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.026  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:18:33.026  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.027  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.027  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:18:33.027  7865  7865 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:18:33.027  7865  7865 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-28 12:18:33.027  1037  1526 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:18:33.028  7865  7865 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.028  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:33.029  1929  7915 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.029  1929  7915 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.029  1037  7901 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.029  1037  7901 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.029  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-28 12:18:33.029  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.029  1037  7901 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:18:33.029  1037  7901 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.029  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.029  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:18:33.029  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:33.030  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:18:33.030  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:18:33.030  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:18:33.030  7865  7865 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:33.031  1037  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.031  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.031  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:18:33.031  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:33.031  1037  7901 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:33.031  1037  7901 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:18:33.032  1037  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:18:33.032  1037  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:18:33.033  1037  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:18:33.033  1037  1526 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:18:33.033  1037  1526 D WifiNative-wlan0: SCAN: returned false
07-28 12:18:33.034  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=155408  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:18:33.035  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=155409  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:18:33.036  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.036  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:33.036  1037  1526 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:33.037  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.037  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.037  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.037  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:18:33.037  1037  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:33.037  1037  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:33.038  1037  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:33.038  1037  ,1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:18:33.039  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.039  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:18:33.058  7906  7906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:18:33.060  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:18:33.065  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:33.066  1037  2019 I ActivityManager: Killing 7028:com.lge.drmservice/u0a62 (adj 15): empty #17
07-28 12:18:33.103  1037  1052 W libprocessgroup: failed to open /acct/uid_10062/pid_7028/cgroup.procs: No such file or directory
,07-28 12:18:33.127  7906  7906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:33.132  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:18:33.137  7883  7928 W FormManager: Network not available. Please check & try again.
07-28 12:18:33.142  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:18:33.147  7883  7929 V FormManager: Network unavailable.
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:18:33.148  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:18:33.151  7883  7929 V FormManager: Network unavailable.
,07-28 12:18:33.151  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:18:33.160  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:18:33.161  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:18:33.164  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-28 12:18:33.165  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:33.165  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-28 12:18:33.168  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:18:33.169  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d93c9b8 Bundle[{}]
07-28 12:18:33.172  6577  6704 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:18:33.172  6577  6704 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 12:18:33.174  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-28 12:18:33.176  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 12:18:33.177  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-28 12:18:33.178  6577  6704 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-28 12:18:33.185  4324  7930 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:18:33.190  6577  6704 I System.out: Running OutgoingSocketThread
07-28 12:18:33.191  4324  7931 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:18:33.191  4324  7931 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:18:33.193  6577  7932 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
07-28 12:18:33.194  6577  7932 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60763
07-28 12:18:33.195  6577  7932 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-28 12:18:33.215  1037  1685 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7933 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:18:33.353  7933  7933 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:18:33.353  7933  7933 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-28 12:18:33.370  7933  7933 V [BNRBootReceiver]: Boot Receiver Return
07-28 12:18:33.371  7933  7933 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-28 12:18:33.416  1037  1919 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:18:33.419  1037  1919 I ActivityManager: Killing 7045:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-28 12:18:33.494  1037  1053 W libprocessgroup: failed to open /acct/uid_10085/pid_7045/cgroup.procs: No such file or directory
,07-28 12:18:33.529  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:18:33.529  1037  7901 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:18:33.529  7865  7865 E wpa_supplicant: USIM:  scard_init function
07-28 12:18:33.530  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:18:33.530  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:18:33.530  1037  7901 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:18:33.530  7865  7865 I wpa_supplicant: Trying to associate with SSID 'NG700'
,07-28 12:18:33.533  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:18:33.533  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-28 12:18:33.535  1037  1526 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:18:33.536  7951  7951 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:33.536  1037  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:18:33.538  1037  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:18:33.539  1037  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:18:33.539  1037  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 12:18:33.556  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=155930  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 12:18:33.560  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.560  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:33.562  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.562  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.562  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.562  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:18:33.564  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=155938  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:18:33.568  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.568  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.568  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:18:33.568  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.568  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 12:18:33.572  7951  7951 D PluginManager: init()
,07-28 12:18:33.583  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.583  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:18:33.584  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.637  7865  7865 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:18:33.638  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:18:33.638  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,07-28 12:18:33.639  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:18:33.639  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 12:18:33.639  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:33.640  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:33.642  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=156015  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:18:33.643  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:18:33.643  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=156017  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:18:33.646  7865  7865 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:18:33.646  7865  7865 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:18:33.647  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:33.647  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:33.648  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:18:33.648  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:18:33.648  1037  7901 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:18:33.648  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:18:33.648  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:18:33.649  1037  7901 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:18:33.649  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:33.649  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:33.652  1037  1526 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156026
07-28 12:18:33.652  1037  1526 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156026
07-28 12:18:33.653  1037  1526 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156027
07-28 12:18:33.653  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156027
,07-28 12:18:33.654  1037  1526 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156028
07-28 12:18:33.654  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=156028  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:18:33.658  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.658  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.658  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:18:33.660  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.660  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:18:33.662  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.664  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.664  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.664  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:18:33.665  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=156038  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:18:33.666  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.666  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:33.666  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.666  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-28 12:18:33.667  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:33.669  1037  1526 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:33.670  1037  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:33.670  1037  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:33.671  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:33.672  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:18:33.672  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=156046  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:18:33.673  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=156047  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:18:33.674  1037  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156047
07-28 12:18:33.674  1037  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156048
07-28 12:18:33.675  1037  1526 D WifiNative-wlan0: doString: [STATUS]
07-28 12:18:33.675  1037  7901 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:18:33.675  1037  7901 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:18:33.676  1037  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:18:33.677  1037  1526 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:18:33.683  1037  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:18:33.683  1037  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-28 12:18:33.689  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.689  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.689  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:18:33.694  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.694  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.694  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:18:33.702  1037  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:18:33.702  1037  1532 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:18:33.702  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:18:33.702  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:18:33.702  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:18:33.703  1037  1532 D ConnectivityService: NetworkAgent connected
07-28 12:18:33.703  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:18:33.703  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:18:33.705  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.705  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:18:33.706  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.708  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.708  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:18:33.708  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:33.708  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:18:33.708  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:18:33.708  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:18:33.708  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:18:33.709  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.712  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:18:33.714   310   895 D CommandListener: Setting iface cfg
07-28 12:18:33.717  1037  1526 E WifiStateMachine: Start Dhcp Watchdog 3
07-28 12:18:33.718  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=156091  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:33.718  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=156092  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:33.719  1037  7978 D DhcpStateMachine: StoppedState
07-28 12:18:33.719  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=156092  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:33.719  1037  7978 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.719  1037  7978 D DhcpStateMachine: WaitBeforeStartState
,07-28 12:18:33.720  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.720  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-28 12:18:33.721  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.721  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-28 12:18:33.722  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=156096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:33.723  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=156096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:33.723  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=156097  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:18:33.724  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13617] from screen [on:0 period:822298492] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:18:33.725  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:822298493] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:18:33.726  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:18:33.729  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.730  1037  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-28 12:18:33.730  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.731  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.731  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.732  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.733  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.733  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.733  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:18:33.734  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.734  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:18:33.735  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
07-28 12:18:33.735  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
07-28 12:18:33.735  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:18:33.736  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:18:33.736  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:18:33.736  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:18:33.737  1037  1526 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:18:33.737  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:18:33.737  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:18:33.737  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:18:33.737  1037  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:18:33.737  1037  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:18:33.737  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ed696c5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.738  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ed696c5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.738  1037  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:18:33.738  1037  7978 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.738  1037  7978 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:18:33.739   310   895 D CommandListener: Setting iface cfg
07-28 12:18:33.739   310   895 D CommandListener: Trying to bring up wlan0
07-28 12:18:33.740  1037  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:18:33.740  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:18:33.740  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:18:33.741  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:18:33.742  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.743  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.744  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.744  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.745  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:18:33.745  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:18:33.746  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:18:33.746  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:18:33.746  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:18:33.746  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.746  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.747  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:18:33.747  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:18:33.747  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:18:33.747  7865  7865 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:18:33.747  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:18:33.748  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:18:33.764  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:18:33.764  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:18:33.764  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:18:33.765  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:18:33.765  1037  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-28 12:18:33.765  1037  1532 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:18:33.767  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.767  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:33.769  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.769  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.769  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.770  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:18:33.770  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:18:33.771  1037  1532 D ConnectivityService: Adding iface wlan0 to network 102
07-28 12:18:33.775  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.775  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.775  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:18:33.776  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:18:33.778  1929  1929 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:18:33.781  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.781  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.781  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:18:33.782  1037  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:18:33.784  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-28 12:18:33.788  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.788  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:18:33.789  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.791  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.792  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:18:33.792  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.792  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.792  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:18:33.792  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:18:33.794  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:18:33.794  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:18:33.794  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.794  1037  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:18:33.794  1037  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-28 12:18:33.795  1037  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-28 12:18:33.796   310   895 E Netd    : netlink response contains error (File exists)
,07-28 12:18:33.796  1037  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-28 12:18:33.797  1037  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:18:33.797  1037  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-28 12:18:33.797  1037  1532 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-28 12:18:33.798  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:18:33.798  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:18:33.798  1037  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-28 12:18:33.798  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 12:18:33.798  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.798  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:18:33.799  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:18:33.799  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:33.799  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:18:33.799  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:33.799  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:18:33.799  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.799  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:18:33.799  1037  1532 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:18:33.799  1037  1532 D ConnectivityService:    accepting network in place of null
07-28 12:18:33.799  1037  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.800  1037  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.800  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:33.801  1037  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:18:33.801  1037  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-28 12:18:33.802  1037  1532 D ConnectivityService: send,StickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:18:33.802   310  7982 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 12:18:33.802  1838  1838 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.802  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:18:33.803  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:18:33.803  1037  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:18:33.803  1037  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 12:18:33.804  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:18:33.804  1037  1532 D ConnectivityService: validation of new default Network = false
07-28 12:18:33.804  1037  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:18:33.804  1037  1532 D DSQN    : enableDataServiceNotify 
07-28 12:18:33.805  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:18:33.805  1037  1532 D DSQN    : start dsqn bin
07-28 12:18:33.805  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:18:33.805  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:18:33.810  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-28 12:18:33.810  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.811  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:33.811  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:33.795  7983  7983 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:33.811  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:18:33.795  7983  7983 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:33.814  1037  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 12:18:33.822  7983  7983 E DSQN    : DSQN ssw
07-28 12:18:33.829  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:33.830  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.830  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.853   310  7982 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-28 12:18:33.886   310  7982 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-28 12:18:33.917   310   894 D LGDataListener: argv[0]=dsqncommand
07-28 12:18:33.917   310   894 D LGDataListener: argv[1]=wlan0
07-28 12:18:33.917   310   894 D LGDataListener: argv[2]=1
07-28 12:18:33.917   310   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 12:18:33.918  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 12:18:33.918  1037  1117 D DSQN    : start to monitor internet connection
,07-28 12:18:33.941  1037  7978 D DhcpStateMachine: DHCPV4 request on wlan0
,07-28 12:18:33.942  1037  7978 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:18:33.943  1037  7978 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 12:18:33.935  7989  7989 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:33.935  7989  7989 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:18:33.955  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:18:33 GMT], X-Android-Received-Millis=[1469701113953], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469701113916]}
07-28 12:18:33.955  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:18:33.955  1037  7977 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 12:18:33.956  1037  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
07-28 12:18:33.956  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 12:18:33.956  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:33.956  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:33.957  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:18:33.957  1037  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,07-28 12:18:33.957  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,07-28 12:18:33.957  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.957  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:33.958  7989  7989 I dhcpcd  : version 5.5.6 starting
07-28 12:18:33.958  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:33.960  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:18:33.961  7989  7989 E dhcpcd  : get_duid: m
07-28 12:18:33.961  7989  7989 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:18:33.961  7989  7989 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-28 12:18:33.962  1037  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.963  1838  1838 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.964  1838  1838 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:18:33.965  1037  1526 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:33.965  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:18:33.966  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:18:33.986  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:18:33.987  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:18:33.989  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:18:34.016  7951  7951 W ExternalStrings: load override strings
07-28 12:18:34.016  7951  7951 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:18:34.016  7951  7951 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,07-28 12:18:34.018  7951  7951 D StatusProvider: onCreate
,07-28 12:18:34.023  7989  7989 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,07-28 12:18:34.023  7989  7989 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:18:34.023  7989  7989 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:18:34.023  7989  7989 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 12:18:34.023  7989  7989 D dhcpcd  : wlan0: sending REQUEST (xid 0x2b2a65ab), next in 4.07 seconds
07-28 12:18:34.071  7951  7951 V Signer  : override build config not found
07-28 12:18:34.071  7951  7951 D Signer  : value of property debug is false
,07-28 12:18:34.092  7989  7989 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1,
,07-28 12:18:34.128  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,07-28 12:18:34.128  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,07-28 12:18:34.128  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-28 12:18:34.129  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-28 12:18:34.129  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-28 12:18:34.129  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-28 12:18:34.129  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-28 12:18:34.130  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-28 12:18:34.130  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-28 12:18:34.130  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-28 12:18:34.130  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-28 12:18:34.130  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-28 12:18:34.131  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-28 12:18:34.132  7989  7989 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:18:34.132  7989  7989 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:18:34.133  7989  7989 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:18:34.134  7989  7989 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:18:34.134  7989  7989 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:18:34.134  7989  7989 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:18:34.135  7989  7989 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:18:34.135  7989  7989 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:18:34.144  7951  7951 V LGMDMManager: Create singleton instance
07-28 12:18:34.192  6577  6704 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
07-28 12:18:34.192  6577  6704 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 857)
07-28 12:18:34.193  6577  6704 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 857)
07-28 12:18:34.193  6577  6704 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
,07-28 12:18:34.196  6577  6704 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 862)
,07-28 12:18:34.196  6577  6704 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 862)
07-28 12:18:34.196  6577  6704 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
07-28 12:18:34.197  6577  6704 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 863)
07-28 12:18:34.199  6577  6704 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 865)
07-28 12:18:34.201  7951  7951 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
07-28 12:18:34.202  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.202  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0eab2e added. We now have 2 listener(s)
07-28 12:18:34.202  1037  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.205  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.205  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.205  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.206  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.206  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afb16cf added. We now have 9 listener(s)
07-28 12:18:34.206  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.206  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:18:34.209  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:34.213  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:34.216  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.216  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:34.216  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.216  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8ef765 added. We now have 3 listener(s)
07-28 12:18:34.217  1037  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.218  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.219  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.222  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-28 12:18:34.222  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.222  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.223  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.223  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325e4c3a added. We now have 10 listener(s)
07-28 12:18:34.223  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.225  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:34.225  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:34.225  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:34.225  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.225  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.225  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.225  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.225  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0eab2e removed from the list
07-28 12:18:34.225  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.225  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afb16cf removed from the list
07-28 12:18:34.225  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:34.225  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.225  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.225  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.226  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.226  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.226  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.226  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afb16cf not in the list
07-28 12:18:34.226  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.226  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.227  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.227  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.227  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:18:34.227  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325e4c3a removed from the list
07-28 12:18:34.227  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.227  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.227  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.227  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.227  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8ef765 removed from the list
07-28 12:18:34.228  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.228  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3c50eb added. We now have 2 listener(s)
07-28 12:18:34.228  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.230  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.230  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.230  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.230  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.230  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27183e48 added. We now have 9 listener(s)
07-28 12:18:34.230  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.231  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:18:34.232  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:34.234  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:18:34.237  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.238  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:34.239  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.239  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd4f206 added. We now have 3 listener(s)
07-28 12:18:34.239  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.239  1037  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.240  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.241  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.241  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.241  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.241  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.241  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d10c7 added. We now have 10 listener(s)
07-28 12:18:34.241  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.241  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:34.241  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:18:34.241  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:34.241  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:18:34.243  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:18:34.243  1037  1685 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.246  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:18:34.251  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:18:34.252  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:18:34.253  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.254  6577  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:18:34.254  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:34.254  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:34.255  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:34.255  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:34.255  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:34.255  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.255  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.255  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.255  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.255  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3c50eb removed from the list
07-28 12:18:34.255  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.255  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27183e48 removed from the list
07-28 12:18:34.255  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:34.256  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.256  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.256  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.257  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.257  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.257  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.257  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27183e48 not in the list
07-28 12:18:34.257  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.257  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.257  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:18:34.260  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:34.260  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:34.260  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.260  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.260  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d10c7 removed from the list
07-28 12:18:34.260  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.260  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.260  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.260  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.260  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd4f206 removed from the list
07-28 12:18:34.261  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.261  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23be2892 added. We now have 2 listener(s)
07-28 12:18:34.261  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.263  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.263  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.263  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.263  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.263  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3ff263 added. We now have 9 listener(s)
07-28 12:18:34.263  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.264  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:18:34.266  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:34.268  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network t,ype is Wi-Fi: true
07-28 12:18:34.269  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.269  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:18:34.271  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.271  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218c0f19 added. We now have 3 listener(s)
07-28 12:18:34.271  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.272  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.273  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.274  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.274  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.274  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.275  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.275  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b923bde added. We now have 10 listener(s)
07-28 12:18:34.275  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.275  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:34.275  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:34.275  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:18:34.276  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:34.276  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:18:34.278  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:18:34.279  1037  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.282  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:18:34.283  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:18:34.284  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:18:34.284  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.285  6577  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:18:34.285  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:34.285  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:34.285  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:34.286  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.286  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.286  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.286  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.286  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23be2892 removed from the list
07-28 12:18:34.286  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.286  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3ff263 removed from the list
07-28 12:18:34.286  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:34.286  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.286  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.286  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.287  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.287  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.287  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.287  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3ff263 not in the list
07-28 12:18:34.287  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.287  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.287  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.288  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:34.288  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:34.288  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.288  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.288  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b923bde removed from the list,
07-28 12:18:34.288  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.288  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.288  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.288  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.288  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.288  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218c0f19 removed from the list
07-28 12:18:34.289  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.289  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c583d5 added. We now have 2 listener(s)
07-28 12:18:34.289  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.291  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.291  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.292  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.292  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.292  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220237ea added. We now have 9 listener(s)
07-28 12:18:34.292  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.292  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.292  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:18:34.295  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:34.297  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:34.298  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.299  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:34.299  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.299  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127bc978 added. We now have 3 listener(s)
07-28 12:18:34.299  1037  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.301  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.302  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.302  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.302  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.302  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.302  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20e78851 added. We now have 10 listener(s)
07-28 12:18:34.302  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:18:34.302  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:18:34.302  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:18:34.302  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:18:34.302  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:18:34.304  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.305  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:18:34.305  1037  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.309  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeo,ut: 0, is connectable: false
,07-28 12:18:34.310  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:18:34.310  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:18:34.312  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:18:34.312  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.314  6577  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:18:34.316  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:34.316  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:34.316  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:34.316  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.316  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.316  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.316  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.316  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.316  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c583d5 removed from the list
07-28 12:18:34.316  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.316  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220237ea removed from the list
07-28 12:18:34.316  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:34.316  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.317  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.317  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.318  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.318  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.318  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.318  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220237ea not in the list
07-28 12:18:34.318  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.318  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.318  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.318  6577  6704 D BluetoothLeScanner: could not find callback wrapper
07-28 12:18:34.318  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:18:34.318  6577  67,04 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.319  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.319  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20e78851 removed from the list
07-28 12:18:34.319  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.319  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.319  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.319  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.319  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127bc978 removed from the list
07-28 12:18:34.319  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.319  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2600524 added. We now have 2 listener(s)
07-28 12:18:34.319  1037  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.321  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.321  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.322  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.322  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.322  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224b588d added. We now have 9 listener(s)
07-28 12:18:34.322  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:18:34.326  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:18:34.348  1037  7978 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-28 12:18:34.349  1037  7978 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:18:34.349  1037  7978 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,07-28 12:18:34.349  1037  7978 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:18:34.349  1037  7978 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 12:18:34.349  1037  7978 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:18:34.349  1037  7978 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:18:34.349  1037  7978 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:18:34.349  1037  7978 D DhcpStateMachine: RunningState
07-28 12:18:34.364  1037  1983 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8021 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-28 12:18:34.366  1037  1983 I ActivityManager: Killing 7064:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,07-28 12:18:34.444  7951  8008 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-28 12:18:34.579  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:18:34.590  6577  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:18:34.594  6577  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:18:34.595  6577  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:18:34.595  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:18:34.595  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b423a53 added. We now have 3 listener(s)
07-28 12:18:34.597  1037  2019 W libprocessgroup: failed to open /acct/uid_10093/pid_7064/cgroup.procs: No such file or directory
,07-28 12:18:34.612  1037  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:18:34.616  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.618  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:18:34.618  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:18:34.618  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:18:34.618  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:18:34.619  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@382a4f90 added. We now have 10 listener(s)
07-28 12:18:34.619  6577  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:18:34.620  6577  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:18:34.620  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:18:34.620  6577  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:18:34.620  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.620  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.620  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:18:34.620  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.620  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2600524 removed from the list
07-28 12:18:34.620  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.620  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224b588d removed from the list
07-28 12:18:34.623  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:18:34.624  6577  6704 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:18:34.624  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.625  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.625  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.626  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.626  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.626  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.627  6577  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224b588d not in the list
07-28 12:18:34.627  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.627  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.628  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:18:34.629  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:18:34.629  6577  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:18:34.629  6577  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@382a4f90 removed from the list
07-28 12:18:34.629  6577  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:18:34.629  6577  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:18:34.629  6577  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:18:34.629  6577  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth,.BluetoothConnector: shutdown: Shutting down...
07-28 12:18:34.629  6577  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b423a53 removed from the list
07-28 12:18:34.632  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:18:34.632  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:18:34.633  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:18:34.633  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:18:34.633  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:18:34.633  6577  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:18:34.647  6577  8043 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
07-28 12:18:34.648  6577  8043 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 871, thread name: My test thread name)
07-28 12:18:34.648  6577  8043 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name)
07-28 12:18:34.652  8021  8021 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:34.653  6577  8044 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: My test thread name)
07-28 12:18:34.653  6577  8044 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 873, thread name: My test thread name)
07-28 12:18:34.653  6577  8044 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 873, name: My test thread name)
,07-28 12:18:34.656  6577  6704 E com.test.thalitest.ThaliTestRunner: ConnectionHelper is properly instantiated
07-28 12:18:34.656  6577  6704 E com.test.thalitest.ThaliTestRunner: Expected: is null
07-28 12:18:34.656  6577  6704 E com.test.thalitest.ThaliTestRunner:      but: was <io.jxcore.node.ConnectionModel@34627d71>
07-28 12:18:34.656  6577  6704 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:18:34.656  6577  6704 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 79
07-28 12:18:34.656  6577  6704 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
07-28 12:18:34.657  6577  6704 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 12:18:34.657  6577  6704 D com.test.thalitest.ThaliTestRunner: Total duration: 23221 ms
07-28 12:18:34.658  6577  6704 I jxcore-log: Total number of executed tests:  80
07-28 12:18:34.658  6577  6704 I jxcore-log: 
07-28 12:18:34.658  6577  6704 I jxcore-log: Number of passed tests:  79
07-28 12:18:34.658  6577  6704 I jxcore-log: 
07-28 12:18:34.658  6577  6704 I jxcore-log: Number of failed tests:  1
07-28 12:18:34.658  6577  6704 I jxcore-log: 
07-28 12:18:34.659  6577  6704 I jxcore-log: Number of ignored tests:  0
07-28 12:18:34.659  6577  6704 I jxcore-log: 
07-28 12:18:34.659  6577  6704 I jxcore-log: Total duration:  23221
07-28 12:18:34.659  6577  6704 I jxcore-log: 
07-28 12:18:34.659  6577  6704 I jxcore-log: Failed to execute UT.
07-28 12:18:34.659  6577  6704 I jxcore-log: 
07-28 12:18:34.660  6577  6704 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
07-28 12:18:34.660  6577  6704 I jxcore-log: 
07-28 12:18:34.664  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.664  6577  6704 I jxcore-log: 
07-28 12:18:34.668  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.668  6577  6704 I jxcore-log: 
,07-28 12:18:34.670  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.670  6577  6704 I jxcore-log: 
07-28 12:18:34.671  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.671  6577  6704 I jxcore-log: 
07-28 12:18:34.672  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.672  6577  6704 I jxcore-log: 
07-28 12:18:34.674  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-28 12:18:34.674  6577  6704 I jxcore-log: 
07-28 12:18:34.678  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:18:34.678  6577  6704 I jxcore-log: 
07-28 12:18:34.680  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:18:34.680  6577  6704 I jxcore-log: 
07-28 12:18:34.682  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.682  6577  6704 I jxcore-log: 
07-28 12:18:34.683  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.683  6577  6704 I jxcore-log: 
07-28 12:18:34.684  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:18:34.684  6577  6704 I jxcore-log: 
07-28 12:18:34.685  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:18:34.685  6577  6704 I jxcore-log: 
07-28 12:18:34.686  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.686  6577  6704 I jxcore-log: 
,07-28 12:18:34.686  6577  6577 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-28 12:18:34.688  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.688  6577  6704 I jxcore-log: 
07-28 12:18:34.688  8021  8021 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 12:18:34.688  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.688  6577  6704 I jxcore-log: 
07-28 12:18:34.689  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.689  6577  6704 I jxcore-log: 
07-28 12:18:34.690  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.690  6577  6704 I jxcore-log: 
07-28 12:18:34.691  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.691  6577  6704 I jxcore-log: 
07-28 12:18:34.692  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.692  6577  6704 I jxcore-log: 
07-28 12:18:34.693  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:18:34.693  6577  6704 I jxcore-log: 
07-28 12:18:34.694  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:18:34.694  6577  6704 I jxcore-log: 
07-28 12:18:34.695  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:18:34.695  6577  6704 I jxcore-log: 
07-28 12:18:34.696  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.696  6577  6704 I jxcore-log: 
07-28 12:18:34.697  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.697  6577  6704 I jxcore-log: 
07-28 12:18:34.697  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.697  6577  6704 I jxcore-log: 
07-28 12:18:34.698  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.698  6577  6704 I jxcore-log: 
07-28 12:18:34.699  6577  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:18:34.699  6577  6704 I jxcore-log: 
07-28 12:18:34.718  8021  8021 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-28 12:18:34.718  8021  8021 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:18:34.719  8021  8021 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:18:34.719  8021  8021 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:18:34.719  8021  8021 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,07-28 12:18:34.721  8021  8021 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 12:18:34.724  8021  8021 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 12:18:34.729  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.732  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:34.743  8021  8021 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:18:34.745  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-28 12:18:34.747  6776  6776 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:18:34.750  8021  8021 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,07-28 12:18:34.752  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.752  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.754  8021  8021 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 12:18:34.758  7951  8008 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:34.758  7951  8008 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:18:34.760  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:34.766  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.772  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.772  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.773  8021  8021 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:18:34.775  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.775  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.780  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:34.794  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.798  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.798  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.799  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:18:34.800  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:18:34.800  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:18:34.800  6776  6776 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:18:34.800  6776  6776 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:18:34.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:18:34.801  6776  6776 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:18:34.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 12:18:34.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:18:34.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:18:34.801  6776  6776 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,07-28 12:18:34.801  6776  6776 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 12:18:34.802  6776  6776 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:18:34.805  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.805  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.813  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:34.819  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.825  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.825  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.825  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:34.828  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.828  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 12:18:34.833  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:18:34.838  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.845  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.845  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.845  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:18:34.848  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.848  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.854  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:34.858  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.863  7951  8008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-28 12:18:34.865  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.865  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.866  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:34.868  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.871  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 12:18:34.878  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:18:34.879  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,07-28 12:18:34.883  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.885  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
07-28 12:18:34.885  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 12:18:34.885  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 12:18:34.886  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-28 12:18:34.886  7951  8008 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-28 12:18:34.890  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.890  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.890  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:34.891  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-28 12:18:34.895  7951  8008 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,07-28 12:18:34.900  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.900  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 12:18:34.911  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:34.915  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.920  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.920  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:34.923  8050  8050 D AndroidRuntime: 
07-28 12:18:34.923  8050  8050 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:18:34.923  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:34.925  8050  8050 D AndroidRuntime: CheckJNI is OFF
07-28 12:18:34.926  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.927  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.932  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:18:34.938  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:18:34.946  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:34.947  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:18:34.948  8021  8021 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:18:34.950  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.951  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.953  7906  7906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:18:34.958  7906  7906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:34.961  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:18:34.968  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:34.975  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:18:34.976  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:34.977  8021  8021 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:18:34.978  8021  8021 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:18:34.978  8021  8021 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:18:34.982  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:34.983  7951  8010 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:18:34.986  7906  7906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:18:34.987  7906  7906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:18:34.991  6776  6776 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:18:34.996  6776  6776 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:18:35.002  8021  8021 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:18:35.002  8021  8021 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:18:35.003  8021  8021 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:18:35.004  8021  8021 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:18:35.005  8021  8021 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:18:35.008  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.030  8050  8050 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:18:35.034  8021  8021 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:18:35.035  8021  8021 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,07-28 12:18:35.036  8021  8021 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 12:18:35.043  1037  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-28 12:18:35.044  1037  1100 I ActivityManager: Killing 6577:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,07-28 12:18:35.074  8021  8021 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:35.074  8021  8021 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:18:35.090  1037  1053 I WindowState: WIN DEATH: Window{288c4d14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 12:18:35.091  1037  1531 D WifiService: Client connection lost with reason: 4
07-28 12:18:35.098  1037  1053 D InputDispatcher: Window went away: Window{288c4d14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:18:35.104  1037  1526 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-28 12:18:35.104  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:18:35.105  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:18:35.105  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:18:35.105  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:18:35.106  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:18:35.107  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-28 12:18:35.107  1037  1532 D ConnectivityService: identical MTU - not setting
07-28 12:18:35.107  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:18:35.107  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:18:35.107  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:18:35.107  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:35.108  1037  1532 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:18:35.108  1590  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-28 12:18:35.128  8021  8021 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:18:35.129  8021  8021 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 12:18:35.129  8021  8021 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 12:18:35.129  8021  8021 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:18:35.130  8021  8021 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,07-28 12:18:35.131  8021  8073 V SoundPool: Start decode
07-28 12:18:35.131  8021  8073 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-28 12:18:35.132   316  1372 V MediaPlayerService: decode(23, 10857164, 17813)
07-28 12:18:35.132   316  1372 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 12:18:35.132   316  1372 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:18:35.132   316  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,07-28 12:18:35.132   316  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:18:35.132   316  1372 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:18:35.132   316  1372 V MediaPlayerService: player type = 3
07-28 12:18:35.132   316  1372 V AwesomePlayer: AwesomePlayer create()
07-28 12:18:35.133   316  1372 V AwesomePlayer: reset_l() 
07-28 12:18:35.133   316  1372 V AwesomePlayer: cancelPlayerEvents
07-28 12:18:35.133   316  1372 V AwesomePlayer: setAudioSink() 
07-28 12:18:35.133   316  1372 V AwesomePlayer: reset_l() 
07-28 12:18:35.133   316  1372 V AudioCache: notify(0xb14322c0, 8, 0, 0)
07-28 12:18:35.133   316  1372 V AudioCache: ignored
07-28 12:18:35.133   316  1372 V AwesomePlayer: cancelPlayerEvents
07-28 12:18:35.133   316  1372 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 12:18:35.133   316  1372 V AwesomePlayer: setDataSource_l dataSource
07-28 12:18:35.133   316  1372 V LGParserOSAL: SniffLGParser start
07-28 12:18:35.133   316  1372 V LGParserOSAL: MainType:5, SubType=0
07-28 12:18:35.133   316  1372 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:18:35.133   316  1372 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,07-28 12:18:35.133   316  1372 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:18:35.168   316  1372 V LGParserOSAL: supported mime: application/ogg
07-28 12:18:35.168   316  1372 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:18:35.168   316  1372 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:18:35.168   316  1372 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:18:35.168   316  1372 V AwesomePlayer: AudioTrack Setting
07-28 12:18:35.168   316  1372 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:18:35.168   316  1372 V AwesomePlayer: setAudioSource() 
07-28 12:18:35.168   316  1372 V MediaPlayerService: prepare
07-28 12:18:35.168   316  1372 V AwesomePlayer: prepareAsync_l() 
07-28 12:18:35.168   316  1372 V MediaPlayerService: wait for prepare
07-28 12:18:35.168   316  8074 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:18:35.168   316  8074 V AwesomePlayer: initAudioDecoder() 
07-28 12:18:35.168   316  8074 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:18:35.168   316  8074 V AudioSystem: isOffloadSupported()
07-28 12:18:35.168   316  8074 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,07-28 12:18:35.168   316  8074 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:18:35.168   316  8074 I AudioFlinger: isAudioPlaybackHookOn() false
,07-28 12:18:35.168   316  8074 V AwesomePlayer: getUseOffload() = 0 
07-28 12:18:35.168   316  8074 V OMXCodec: OMXCodec::Create
07-28 12:18:35.168   316  8074 V OMXCodec: findMatchingCodecs()
07-28 12:18:35.169   316  8074 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:18:35.169   316  8074 V OMXCodec: matchingCodecs.size()=1
07-28 12:18:35.169   316  8074 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 12:18:35.170   316  8074 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 12:18:35.170   316  8074 V LGCodecAdapter: LG Codec Adapter start
07-28 12:18:35.170   316  8074 V OMXCodec: OMXCodec Createtor
07-28 12:18:35.170   316  8074 V OMXCodec: setComponentRole
07-28 12:18:35.170   316  8074 V OMXCodec: configureCodec protected=0
07-28 12:18:35.170   316  8074 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:18:35.170   316  8074 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:18:35.170   316  8074 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:18:35.170   316  8074 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:18:35.170   316  8074 V LGCodecOSAL: Not support LGCodec
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:18:35.171   316  8074 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:18:35.171   316  8074 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
,07-28 12:18:35.171   316  8074 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:18:35.171   316  8074 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:18:35.171   316  8074 V AudioSystem: isOffloadSupported()
07-28 12:18:35.171   316  8074 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:18:35.171   316  8074 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:18:35.171   316  8074 V OMXCodec: init()
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 12:18:35.171   316  8074 V OMXCodec: allocateBuffers
07-28 12:18:35.171   316  8074 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
07-28 12:18:35.171   316  8074 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:18:35.171   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
07-28 12:18:35.172   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
,07-28 12:18:35.172   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
07-28 12:18:35.172   316  8074 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
07-28 12:18:35.172   316  8074 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:18:35.172   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:18:35.172   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:18:35.172   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,07-28 12:18:35.172   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 12:18:35.172   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:18:35.172   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:18:35.172   316  8074 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 12:18:35.172   316  8074 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:18:35.173   316  8074 V AudioCache: notify(0xb14322c0, 5, 0, 0)
07-28 12:18:35.173   316  8074 V AudioCache: ignored
07-28 12:18:35.173   316  8074 V AudioCache: notify(0xb14322c0, 1, 0, 0)
07-28 12:18:35.173   316  8074 V AudioCache: prepared
07-28 12:18:35.173   316  1372 V AudioCache: wait - success
07-28 12:18:35.173   316  1372 V MediaPlayerService: start
07-28 12:18:35.173   316  1372 V AwesomePlayer: play_l() 
07-28 12:18:35.173   316  1372 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:18:35.173   316  1372 V AwesomePlayer: createAudioPlayer_l
07-28 12:18:35.173   316  1372 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:18:35.173   316  1372 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:18:35.173   316  1372 D AudioPlayer: start of Playback, useOffload 0
,07-28 12:18:35.173   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:18:35.174   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:18:35.181   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
,07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 12:18:35.182   316  8076 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 12:18:35.182   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,07-28 12:18:35.183   316  1372 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:18:35.183   316  1372 V AudioCache: notify(0xb14322c0, 6, 0, 0)
07-28 12:18:35.183   316  1372 V AudioCache: ignored
07-28 12:18:35.183   316  1372 V MediaPlayerService: wait for playback complete
07-28 12:18:35.184   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.184   316  8077 V AudioCache: memcpy(0xac102000, 0xb57c7000, 4096)
,07-28 12:18:35.188   316  8077 V AudioCache: write(0xb57c7000, 4096)
,07-28 12:18:35.188   316  8077 V AudioCache: memcpy(0xac103000, 0xb57c7000, 4096)
07-28 12:18:35.190   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.190   316  8077 V AudioCache: memcpy(0xac104000, 0xb57c7000, 4096)
,07-28 12:18:35.192   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.192   316  8077 V AudioCache: memcpy(0xac105000, 0xb57c7000, 4096),
07-28 12:18:35.193   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.193   316  8077 V AudioCache: memcpy(0xac106000, 0xb57c7000, 4096)
07-28 12:18:35.193   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.193   316  8077 V AudioCache: memcpy(0xac107000, 0xb57c7000, 4096)
07-28 12:18:35.194   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.194   316  8077 V AudioCache: memcpy(0xac108000, 0xb57c7000, 4096)
07-28 12:18:35.195   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.195   316  8077 V AudioCache: memcpy(0xac109000, 0xb57c7000, 4096)
,07-28 12:18:35.195   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.196   316  8077 V AudioCache: memcpy(0xac10a000, 0xb57c7000, 4096)
07-28 12:18:35.196   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.196   316  8077 V AudioCache: memcpy(0xac10b000, 0xb57c7000, 4096)
07-28 12:18:35.197   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.197   316  8077 V AudioCache: memcpy(0xac10c000, 0xb57c7000, 4096)
07-28 12:18:35.198   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.198   316  8077 V AudioCache: memcpy(0xac10d000, 0xb57c7000, 4096)
,07-28 12:18:35.198   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.198   316  8077 V AudioCache: memcpy(0xac10e000, 0xb57c7000, 4096)
07-28 12:18:35.199   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.199   316  8077 V AudioCache: memcpy(0xac10f000, 0xb57c7000, 4096)
07-28 12:18:35.200   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.200   316  8077 V AudioCache: memcpy(0xac110000, 0xb57c7000, 4096)
07-28 12:18:35.200   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.200   316  8077 V AudioCache: memcpy(0xac111000, 0xb57c7000, 4096)
,07-28 12:18:35.201   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.201   316  8077 V AudioCache: memcpy(0xac112000, 0xb57c7000, 4096)
07-28 12:18:35.202   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.202   316  8077 V AudioCache: memcpy(0xac113000, 0xb57c7000, 4096)
07-28 12:18:35.202   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.202   316  8077 V AudioCache: memcpy(0xac114000, 0xb57c7000, 4096)
07-28 12:18:35.203   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.203   316  8077 V AudioCache: memcpy(0xac115000, 0xb57c7000, 4096)
07-28 12:18:35.204   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.204   316  8077 V AudioCache: memcpy(0xac116000, 0xb57c7000, 4096)
07-28 12:18:35.204   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.204   316  8077 V AudioCache: memcpy(0xac117000, 0xb57c7000, 4096)
07-28 12:18:35.205   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.205   316  8077 V AudioCache: memcpy(0xac118000, 0xb57c7000, 4096)
07-28 12:18:35.206   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.206   316  8077 V AudioCache: memcpy(0xac119000, 0xb57c7000, 4096)
07-28 12:18:35.206   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.206   316  8077 V AudioCache: memcpy(0xac11a000, 0xb57c7000, 4096)
07-28 12:18:35.207   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.207   316  8077 V AudioCache: memcpy(0xac11b000, 0xb57c7000, 4096)
07-28 12:18:35.208   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.208   316  8077 V AudioCache: memcpy(0xac11c000, 0xb57c7000, 4096)
07-28 12:18:35.208   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.208   316  8077 V AudioCache: memcpy(0xac11d000, 0xb57c7000, 4096)
07-28 12:18:35.209   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.209   316  8077 V AudioCache: memcpy(0xac11e000, 0xb57c7000, 4096)
07-28 12:18:35.210   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.210   316  8077 V AudioCache: memcpy(0xac11f000, 0xb57c7000, 4096)
07-28 12:18:35.211   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.211   316  8077 V AudioCache: memcpy(0xac120000, 0xb57c7000, 4096)
07-28 12:18:35.211   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.211   316  8077 V AudioCache: memcpy(0xac121000, 0xb57c7000, 4096)
07-28 12:18:35.212   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.212   316  8077 V AudioCache: memcpy(0xac122000, 0xb57c7000, 4096)
07-28 12:18:35.213   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.213   316  8077 V AudioCache: memcpy(0xac123000, 0xb57c7000, 4096)
07-28 12:18:35.213   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.213   316  8077 V AudioCache: memcpy(0xac124000, 0xb57c7000, 4096)
07-28 12:18:35.214   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.214   316  8077 V AudioCache: memcpy(0xac125000, 0xb57c7000, 4096)
07-28 12:18:35.215   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.215   316  8077 V AudioCache: memcpy(0xac126000, 0xb57c7000, 4096)
07-28 12:18:35.215   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.215   316  8077 V AudioCache: memcpy(0xac127000, 0xb57c7000, 4096)
07-28 12:18:35.216   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.216   316  8077 V AudioCache: memcpy(0xac128000, 0xb57c7000, 4096)
07-28 12:18:35.217   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.217   316  8077 V AudioCache: memcpy(0xac129000, 0xb57c7000, 4096)
07-28 12:18:35.218   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.218   316  8077 V AudioCache: memcpy(0xac12a000, 0xb57c7000, 4096)
07-28 12:18:35.218   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.218   316  8077 V AudioCache: memcpy(0xac12b000, 0xb57c7000, 4096)
07-28 12:18:35.219   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.219   316  8077 V AudioCache: memcpy(0xac12c000, 0xb57c7000, 4096)
07-28 12:18:35.220   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.220   316  8077 V AudioCache: memcpy(0xac12d000, 0xb57c7000, 4096)
07-28 12:18:35.220   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.220   316  8077 V AudioCache: memcpy(0xac12e000, 0xb57c7000, 4096)
07-28 12:18:35.221   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.221   316  8077 V AudioCache: memcpy(0xac12f000, 0xb57c7000, 4096)
07-28 12:18:35.222   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.222   316  8077 V AudioCache: memcpy(0xac130000, 0xb57c7000, 4096)
07-28 12:18:35.222   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.222   316  8077 V AudioCache: memcpy(0xac131000, 0xb57c7000, 4096)
07-28 12:18:35.223   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.223   316  8077 V AudioCache: memcpy(0xac132000, 0xb57c7000, 4096)
07-28 12:18:35.223   316  8077 V AudioCache: write(0xb57c7000, 4096)
07-28 12:18:35.223   316  8077 V AudioCache: memcpy(0xac133000, 0xb57c7000, 4096)
07-28 12:18:35.224   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:18:35.224   316  8077 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:18:35.224   316  8077 V AwesomePlayer: postAudioEOS() 
07-28 12:18:35.224   316  8077 V AudioCache: write(0xb57c7000, 280)
07-28 12:18:35.224   316  8077 V AudioCache: memcpy(0xac134000, 0xb57c7000, 280)
07-28 12:18:35.225   316  8074 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:18:35.225   316  8074 V AwesomePlayer: onStreamDone
07-28 12:18:35.226   316  8074 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:18:35.226   316  8074 V AudioCache: notify(0xb14322c0, 2, 0, 0)
07-28 12:18:35.226   316  8074 V AudioCache: playback complete
07-28 12:18:35.226   316  1372 V AudioCache: wait - success
,07-28 12:18:35.226   316  8074 V AwesomePlayer: pause_l() 
07-28 12:18:35.226   316  1372 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:18:35.226   316  8074 V AudioCache: notify(0xb14322c0, 7, 0, 0)
07-28 12:18:35.226   316  8074 V AudioCache: ignored
07-28 12:18:35.226   316  8074 V AwesomePlayer: cancelPlayerEvents
07-28 12:18:35.226   316  8074 D AudioPlayer: Pause Playback at 1068125
07-28 12:18:35.228   316  1372 V AwesomePlayer: reset_l() 
07-28 12:18:35.228   316  1372 V AudioCache: notify(0xb14322c0, 8, 0, 0)
07-28 12:18:35.228   316  1372 V AudioCache: ignored
07-28 12:18:35.228   316  1372 V AwesomePlayer: cancelPlayerEvents
07-28 12:18:35.228   316  1372 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:18:35.229   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:18:35.229   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:18:35.229   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:18:35.229   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
07-28 12:18:35.229   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:18:35.230   316  8076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:18:35.230   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:18:35.230   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:18:35.230   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:18:35.231   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:18:35.232   316  1372 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:18:35.232   316  1372 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:18:35.232   316  1372 V AwesomePlayer: reset_l() 
07-28 12:18:35.232   316  1372 V AwesomePlayer: cancelPlayerEvents
07-28 12:18:35.232   316  1372 V AwesomePlayer: ~AwesomePlayer call
07-28 12:18:35.232   316  1372 V AwesomePlayer: reset_l() 
07-28 12:18:35.232   316  1372 V AwesomePlayer: cancelPlayerEvents
07-28 12:18:35.233  8021  8073 V SoundPool: close(31)
07-28 12:18:35.233  8021  8073 V SoundPool: pointer = 0x9ffda000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 12:18:35.260  1037  1100 I ActivityManager:   Force finishing activity ActivityRecord{10c891ab u0 com.test.thalitest/.MainActivity t40}
,07-28 12:18:35.295   341   353 E GBMv2   : DFP En is all cleared set to be enabled
,07-28 12:18:35.299  1037  1964 W ActivityManager: Spurious death for ProcessRecord{4c98a3 6577:com.test.thalitest/u0a118}, curProc for 6577: null
,07-28 12:18:35.305  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-28 12:18:35.312  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{10c891ab u0 com.test.thalitest/.MainActivity t40 f}
07-28 12:18:35.312  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{10c891ab u0 com.test.thalitest/.MainActivity t40 f}
,07-28 12:18:35.342  7482  7482 D UEI.SmartControl: QS Service created
07-28 12:18:35.342  2020  2020 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-28 12:18:35.344  1929  2558 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-28 12:18:35.345  1929  2558 D SplitWindowPolicy: topRunningActivity=ActivityInfo{bd31ea2 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:18:35.346  2020  2020 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-28 12:18:35.347  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,07-28 12:18:35.348  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f859733 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:18:35.349  8021  8021 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:18:35.351  8021  8021 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:18:35.351  8021  8021 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:18:35.356  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-28 12:18:35.357  2020  2088 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-28 12:18:35.358  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-28 12:18:35.378  7482  7482 I UEI.SmartControl: Service initServices...
07-28 12:18:35.378  7482  7482 D UEI.SmartControl: QS start get config
,07-28 12:18:35.382  4612  4612 I art     : Explicit concurrent mark sweep GC freed 8172(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 625us total 58.540ms
07-28 12:18:35.386  3833  3833 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-28 12:18:35.387  7543  7543 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-28 12:18:35.387  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:18:35.390  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-28 12:18:35.389  1037  1415 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:18:35.401  8021  8021 V LGMDMManager: Create singleton instance
07-28 12:18:35.429  1037  1873 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:18:35.452  2435  2601 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-28 12:18:35.456  4500  4500 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 12:18:35.458  4500  4500 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-28 12:18:35.458  4500  4500 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-28 12:18:35.458  4500  4500 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-28 12:18:35.458  4500  4500 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:18:35.458  4500  4500 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:18:35.458  4500  4500 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:18:35.458  4500  4500 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:18:35.458  4500  4500 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:18:35.458  4500  4500 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:18:35.458  4500  4500 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:18:35.458  4500  4500 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:18:35.459  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-28 12:18:35.460  2020  2020 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-28 12:18:35.461  2020  2020 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-28 12:18:35.462  1892  1892 D ActionManagerService: notifyUserLog: 1000003
07-28 12:18:35.463  3833  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-28 12:18:35.464  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-28 12:18:35.464  2020  2020 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-28 12:18:35.468  1590  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:18:35.468  1590  1648 D KeyguardModel: createShortcutInfo...
,07-28 12:18:35.470  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-28 12:18:35.470  1590  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:18:35.470  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.471  3833  3848 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:18:35.471  1892  1892 D ActionManagerService: notifyUserLog: 1000004
07-28 12:18:35.472  3833  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262123
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , expire_time: 0
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , display: false
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , animation: false }
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262287
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , expire_time: 0
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , display: false
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , animation: false }
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , create_time: 1469186101943
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , expire_time: 0
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , display: false
07-28 12:18:35.474  2020  2020 I GBoardWebViewUtils: , animation: false }
07-28 12:18:35.481  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:18:35.481  1590  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:35.481  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-28 12:18:35.483  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:18:35.484  1590  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.484  1590  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:18:35.485  1590  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:18:35.485  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.489  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:18:35.489  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:35.490  2020  8079 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-28 12:18:35.490  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-28 12:18:35.490  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-28 12:18:35.493  1590  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.493  1590  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:18:35.497  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:18:35.497  1855  1855 D SplitUIManager: split_name #11 / not available #0
07-28 12:18:35.497  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-28 12:18:35.498  1855  1855 D SplitUIService: removed split : 
07-28 12:18:35.499  1590  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:18:35.499  1590  1648 D KeyguardModel: createShortcutInfo...
,07-28 12:18:35.503  1590  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:35.503  1590  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 12:18:35.503  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:18:35.503  1590  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:18:35.512  1037  1949 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:18:35.512  1037  1949 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:18:35.514  1590  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.514  1590  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,07-28 12:18:35.518  1590  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:18:35.518  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.523  1590  1590 D KeyguardModel: handleShortcutListChanged...
07-28 12:18:35.523  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 12:18:35.527  1590  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:18:35.527  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.531  8021  8021 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:18:35.541  1590  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:18:35.541  1590  1648 D KeyguardModel: createShortcutInfo...
,07-28 12:18:35.543  1590  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.543  1590  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:18:35.549  1855  1855 D SplitUIManager: split_name #11 / not available #0
07-28 12:18:35.549  1590  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:18:35.549  1855  1855 I SplitUIService: split app #11
07-28 12:18:35.549  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.550  1590  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.550  1590  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:18:35.551  1590  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:18:35.551  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.552  1590  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.552  1590  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:18:35.553  1037  1037 D administrator: Handling package changes for user 0
,07-28 12:18:35.556  1590  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:18:35.556  1590  1648 D KeyguardModel: createShortcutInfo...
07-28 12:18:35.563  2020  2020 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-28 12:18:35.566  8021  8021 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:18:35.572  1037  1949 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-28 12:18:35.572  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:18:35.572  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:18:35.573  7543  7543 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:18:35.593  8021  8021 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3512
,07-28 12:18:35.593  1590  1590 D KeyguardModel: handleShortcutListChanged...
07-28 12:18:35.593  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 12:18:35.599  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.601  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.607  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:18:35.609  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.616  1037  2000 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:18:35.616  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.619  1037  1099 W InputMethodInfo: Duplicated subtype definition found: , voice
,07-28 12:18:35.619  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-28 12:18:35.619  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:18:35.620   326   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 12:18:35.620  3175  8082 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:18:35.620  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-28 12:18:35.622  1037  1564 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-28 12:18:35.624  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.626  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-28 12:18:35.629  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:18:35.630  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-28 12:18:35.631  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-28 12:18:35.632  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.632  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-28 12:18:35.634  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-28 12:18:35.634  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.639  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.642  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:18:35.644  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,07-28 12:18:35.647  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14e8cee u0 com.lge.launcher2/.Launcher t39} time:158035
07-28 12:18:35.647  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-28 12:18:35.652  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-28 12:18:35.652  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.654  2094  2094 I ConfigService: onCreate
07-28 12:18:35.654  2094  2094 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-28 12:18:35.656  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-28 12:18:35.656  2020  2156 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-28 12:18:35.656  2020  2156 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,07-28 12:18:35.661  2094  2094 I ConfigService: onBind returning update interface
07-28 12:18:35.662  2094  2094 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-28 12:18:35.662  2094  2094 I ConfigService: onBind returning config service
07-28 12:18:35.667  2094  2094 I ConfigService: onDestroy
,07-28 12:18:35.668  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-28 12:18:35.668  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:18:35.669  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.674  1803  8086 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-28 12:18:35.676  2020  2020 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-28 12:18:35.678  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
07-28 12:18:35.678  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-28 12:18:35.679  2581  2581 D [Concierge]Service: Update widget ID : 11
,07-28 12:18:35.680  2020  2020 D [Concierge]WidgetView: change position of spinner
07-28 12:18:35.685  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
07-28 12:18:35.685  2020  2020 I [Concierge]WidgetView: initWebView(). Time : 1469701115685
07-28 12:18:35.701  1803  8093 I PeopleContactsSync: CP2 sync disabled
,07-28 12:18:35.702  5928  8092 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
07-28 12:18:35.706  1803  4766 I Icing   : doRemovePackageData com.test.thalitest
07-28 12:18:35.709  2020  2020 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 15448409
07-28 12:18:35.710  2020  2020 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-28 12:18:35.710  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-28 12:18:35.714  2020  2020 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@137f6925
07-28 12:18:35.714  1803  8091 W GmsApplication: Using Auth Proxy for data requests.
07-28 12:18:35.714  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,07-28 12:18:35.715  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:18:35.715  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.721  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-28 12:18:35.721  2020  2020 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-28 12:18:35.721  2020  2020 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:18:35.722  2020  2020 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469700985549, New one : 1469701115685
07-28 12:18:35.722  2020  2020 D [Concierge]WidgetView: Unregister all receivers
07-28 12:18:35.722  2020  2020 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:18:35.723  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.725  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-28 12:18:35.726  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,07-28 12:18:35.726  1803  8091 W GmsApplication: Using Auth Proxy for data requests.
07-28 12:18:35.727  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-28 12:18:35.728  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-28 12:18:35.729  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-28 12:18:35.730  6917  6917 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-28 12:18:35.733  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.733  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.761  2364  8096 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-28 12:18:35.780  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-28 12:18:35.785  1037  2019 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8097 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-28 12:18:35.788  2020  2020 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-28 12:18:35.788  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-28 12:18:35.789  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:18:35.808  2020  2020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@82f15b6 time:158196
,07-28 12:18:35.837  8097  8097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:18:35.838  8097  8097 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:18:35.838  8097  8097 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:18:35.839  8097  8097 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:18:35.843  1037  1125 I art     : Explicit concurrent mark sweep GC freed 82963(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 5.331ms total 498.296ms
,07-28 12:18:35.845  2094  2273 I art     : Explicit concurrent mark sweep GC freed 5063(301KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 643us total 18.041ms
07-28 12:18:35.882  8050  8050 D AndroidRuntime: Shutting down VM
,07-28 12:18:35.918  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8115 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-28 12:18:35.933  8097  8097 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-28 12:18:35.944  8097  8097 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-28 12:18:35.951  2020  2020 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-28 12:18:35.971  7482  7482 I UEI.SmartControl: Supports setup maps: true
,07-28 12:18:35.974  7482  7482 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:18:35.974  7482  7482 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:18:35.974  7482  7482 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:18:35.974  7482  7482 I UEI.SmartControl: ### init IR Blaster...
07-28 12:18:35.977  7482  7482 D serial_port: Configuring serial port
07-28 12:18:35.977  7482  7482 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:18:35.977  7482  7482 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:18:35.977  7482  7482 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:18:35.978  7482  7482 I UEI.SmartControl: Get version...
07-28 12:18:35.978  8097  8097 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:18:35.991  2020  2942 I GBoardtInterface: onReloaded()
,07-28 12:18:35.993  2020  2020 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-28 12:18:35.994  7482  8134 D UEI.SmartControl: serial port data available: 21
07-28 12:18:35.994  3833  3848 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:18:35.996  3833  3850 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:18:35.996  8097  8097 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:18:35.996  8097  8097 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:18:36.001  1892  1892 D ActionManagerService: notifyUserLog: 1000001
07-28 12:18:36.002  3833  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 12:18:36.002  3833  4488 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 12:18:36.004  1892  1892 D ActionManagerService: notifyUserLog: 1000001
,07-28 12:18:36.006  3833  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 12:18:36.006  3833  4488 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 12:18:36.006  3833  3848 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:18:36.006  3833  4488 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-28 12:18:36.006  3833  4488 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-28 12:18:36.008  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-28 12:18:36.008  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-28 12:18:36.009  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-28 12:18:36.010  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:18:36.011  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-28 12:18:36.011  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 12:18:36.020  7482  7482 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:18:36.020  7482  7482 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:18:36.020  7482  7482 I UEI.SmartControl: QS saving settings...
07-28 12:18:36.021  7482  7482 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:18:36.034  1037  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:18:36.038  7482  8134 D UEI.SmartControl: serial port data available: 4
07-28 12:18:36.038  1037  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 12:18:36.040  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 12:18:36.051  8097  8097 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,07-28 12:18:36.060  1037  1983 I ActivityManager: Killing 7153:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 12:18:36.065  7482  8140 I UEI.SmartControl: Device manager: loading config....
,07-28 12:18:36.066  7482  7482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:18:36.067  7482  8140 D UEI.SmartControl: ----------- loading internal config...
07-28 12:18:36.069  7482  8140 E UEI.SmartControl: Loading SETTINGS...
07-28 12:18:36.072  7482  8140 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:18:36.085  7482  8139 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:18:36.085  7482  8139 D UEI.SmartControl: -----service ready thread exits
,07-28 12:18:36.143  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,07-28 12:18:36.143  1037  1052 W libprocessgroup: failed to open /acct/uid_10005/pid_7153/cgroup.procs: No such file or directory
07-28 12:18:36.143  7482  7482 E UEI.SmartControl: Services init done
07-28 12:18:36.143  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
07-28 12:18:36.143  7482  7482 D UEI.SmartControl: QS Service init finished
07-28 12:18:36.144  7482  7482 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:18:36.144  7482  7482 D UEI.SmartControl: QS Service version code: 201091
07-28 12:18:36.144  7482  7482 D UEI.SmartControl: Service requested: Control
,07-28 12:18:36.145  7482  7482 D UEI.SmartControl: Internal service binding...
07-28 12:18:36.145  8021  8021 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:18:36.145  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
07-28 12:18:36.146  7482  7511 I UEI.SmartControl: ------ IControl API: 11
07-28 12:18:36.146  7482  7511 D UEI.SmartControl: File observer start...
07-28 12:18:36.146  7482  7511 E UEI.SmartControl: IR Port is disabled: false
07-28 12:18:36.146  7482  7511 D UEI.SmartControl: Starting file observer...
07-28 12:18:36.147  7482  7511 I UEI.SmartControl: Registering callback...
07-28 12:18:36.147  7482  7497 I UEI.SmartControl: ------ IControl API: 19
07-28 12:18:36.147  7482  7497 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:18:36.147  7482  7497 I UEI.SmartControl: Notify client services are ready...
07-28 12:18:36.148  8021  8036 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:18:36.148  8021  8071 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:18:36.148  8021  8071 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 12:18:36.148  8021  8021 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:18:36.148  8021  8021 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 12:18:36.149  7482  7511 I UEI.SmartControl: ------ IControl API: 8
07-28 12:18:36.149  8021  8021 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:18:36.149  8021  8021 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:18:36.150  8021  8021 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:18:36.150  8021  8021 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:18:36.150  8021  8021 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 12:18:36.150  8021  8021 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 12:18:36.151  8021  8021 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-28 12:18:36.152  8021  8021 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-28 12:18:36.153  1037  1949 I ActivityManager: Killing 7573:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 12:18:36.222  1037  1872 W libprocessgroup: failed to open /acct/uid_10072/pid_7573/cgroup.procs: No such file or directory
,07-28 12:18:36.226  7951  7951 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-28 12:18:36.229  7349  7349 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
07-28 12:18:36.234  6776  6776 D PackageIntentReceiver: Not supported Hotkey customization function 
,07-28 12:18:36.241  6776  6776 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
07-28 12:18:36.241  6776  6776 D HideNavigationAppsReceiver: replacing : false
07-28 12:18:36.243  6776  6776 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
07-28 12:18:36.244  6776  6776 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
07-28 12:18:36.244  6776  6776 D ButtonCombinationReceiver: replacing : false
,07-28 12:18:36.250  1037  1949 I ActivityManager: Killing 7178:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-28 12:18:36.289  2020  2942 I GBoardtInterface: exportHTML()

```
