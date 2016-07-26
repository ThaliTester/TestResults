#### Test 757892686f45c73_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-26 15:20:45.687  8100  8100 I appproc : CLASSPATH=/system/framework/am.jar
07-26 15:20:45.687  8100  8100 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-26 15:20:45.687  8100  8100 I appproc : app_process:number,5,0
07-26 15:20:45.687  8100  8100 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-26 15:20:45.837  8100  8100 I         : power log dlsym ok
07-26 15:20:45.877  8100  8100 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-26 15:20:45.877  8100  8100 I android_hardware_fm.cpp: ========64bit long size = 8
07-26 15:20:45.877  8100  8100 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-26 15:20:45.877  8100  8100 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-26 15:20:45.877  8100  8100 I fm_hisi : 
07-26 15:20:45.877  8100  8100 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-26 15:20:45.877  8100  8100 I fm_hisi : 
07-26 15:20:45.877  8100  8100 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-26 15:20:45.877  8100  8100 I fm_hisi : 
07-26 15:20:45.877  8100  8100 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-26 15:20:45.927  3062  3460 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-26 15:20:45.927  3062  3460 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-26 15:20:45.927  3062  3460 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-26 15:20:45.987  3062  3708 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-26 15:20:45.997  3665  4175 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-26 15:20:46.007  4084  4895 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-26 15:20:46.007  4084  4895 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-26 15:20:46.007  3783  3783 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-26 15:20:46.007  4084  4482 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-26 15:20:46.007  3783  3783 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-26 15:20:46.007  3783  3783 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-26 15:20:46.017  3783  3783 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-26 15:20:46.017  3783  3783 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-26 15:20:46.147  8122  8122 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
,07-26 15:20:46.177  8122  8122 I LibraryLoader: Loading: webviewchromium
07-26 15:20:46.237  8122  8122 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 6954-7011)
07-26 15:20:46.237  8122  8122 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:46.267  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.267  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.277  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.277  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.287  8122  8122 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:46.287  8122  8122 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:20:46.297  8122  8122 I BrowserStartupController: Initializing chromium process, renderers=0
07-26 15:20:46.307  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:46.357  8122  8122 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-26 15:20:46.367  8122  8122 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-26 15:20:46.367  8122  8122 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-26 15:20:46.507  8122  8158 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-26 15:20:46.517  8122  8122 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-26 15:20:46.517  8122  8158 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-26 15:20:46.557  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.557  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.567  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.567  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.567  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.567  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.567  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.567  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.577  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.577  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.577  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.577  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.587  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.587  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.587  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.587  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.597  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.597  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.597  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.597  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.597  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.597  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.607  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.607  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.607  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.607  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.607  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.607  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.617  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.617  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.617  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.617  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.627  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.627  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.627  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.627  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.627  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.627  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.637  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.637  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.637  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.637  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.637  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.637  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.647  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.657  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.667  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.677  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.677  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.677  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.677  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.687  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.687  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.687  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.687  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.687  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.687  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.697  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.697  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.697  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.697  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.707  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.707  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.707  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.707  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.707  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.707  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.717  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.717  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.717  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.717  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.717  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.717  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.727  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.727  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.727  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.727  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.727  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.737  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.747  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.757  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.757  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.757  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.757  8122  8122 E ZipFileCache: init failed when open zip file.
07-26 15:20:46.757  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:46.757  8122  8122 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-26 15:20:46.767  8122  8122 I art     : Can not find class: Landroid/widget/ViewStub;
07-26 15:20:46.767  8122  8122 I art     : Can not find class: Landroid/webkit/ViewStub;
07-26 15:20:46.767  8122  8122 I art     : Can not find class: Landroid/app/ViewStub;
07-26 15:20:46.787  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:46.787  8122  8122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:46.967  3062  3283 I ActivityManager: filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
07-26 15:20:46.987  3903  3903 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
07-26 15:20:47.037  3461  3461 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-26 15:20:47.037  3461  3461 I PhoneStatusBar: shouldTranslucent:true
07-26 15:20:47.037  3461  3461 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-26 15:20:47.067  8122  8176 I OpenGLRenderer: Initialized EGL, version 1.4
07-26 15:20:47.117  3062  3096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s115ms (total +1s187ms)
07-26 15:20:47.117  8122  8122 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-26 15:20:47.137  6386  8182 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.157  3903  3903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-26 15:20:47.177  3062  3085 I ActivityManager: filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
07-26 15:20:47.227  8122  8122 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-26 15:20:47.227  8122  8122 I chromium: 
07-26 15:20:47.347  6386  8186 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.377  6386  8186 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.387  3903  8188 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.427  8122  8187 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
07-26 15:20:47.447  3903  8188 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.467  3903  8188 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.467  8122  8187 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:47.467  8122  8187 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:47.467  8122  8187 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:47.467  8122  8187 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-26 15:20:47.467  8122  8187 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:47.477  8122  8187 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
07-26 15:20:47.487  8122  8187 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:20:47.527  8122  8122 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-26 15:20:47.577  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.607  8193  8193 I MultiDex: VM with version 2.1.0 has multidex support
07-26 15:20:47.607  8193  8193 I MultiDex: install
07-26 15:20:47.617  8193  8193 I MultiDex: MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
07-26 15:20:47.617  8193  8193 I MultiDex: loading existing secondary dex files
07-26 15:20:47.617  8193  8193 I MultiDex: load found 4 secondary dex files
07-26 15:20:47.627  8193  8193 I MultiDex: install done
07-26 15:20:47.687  8193  8193 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.747  8193  8193 I art     : Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,07-26 15:20:47.747  8193  8193 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8bffdb2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-26 15:20:47.747  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:47.747  8193  8193 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-26 15:20:47.887  3062  3778 I art     : Explicit concurrent mark sweep GC freed 39094(2MB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 28MB/43MB, paused 2.298ms total 216.515ms
,07-26 15:20:47.907  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.917  8122  8191 W jxcore-log: Initializing JXcore engine
07-26 15:20:47.917  8122  8191 W jxcore-log: JXcore engine is ready
,07-26 15:20:47.917  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.927  8193  8193 I art     : Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,07-26 15:20:47.937  8193  8193 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
07-26 15:20:47.937  8193  8193 I art     : Can not find class: Linz;
,07-26 15:20:47.937  8193  8193 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-26 15:20:47.947  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.957  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.957  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.967  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:47.977  8122  8191 W jxcore-log: Starting JXcore engine
,07-26 15:20:48.007  8193  8212 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:48.007  8193  8222 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.027  3903  6233 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.047  2612  3058 I WVCdm   : CdmEngine::OpenSession
07-26 15:20:48.047  2612  3058 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,07-26 15:20:48.057  2612  3058 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-26 15:20:48.077  2612  3058 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,07-26 15:20:48.077  8122  8191 W jxcore-log: Platform android
07-26 15:20:48.077  8122  8191 W jxcore-log: 
07-26 15:20:48.077  8122  8191 W jxcore-log: Process ARCH arm
07-26 15:20:48.077  8122  8191 W jxcore-log: 
,07-26 15:20:48.107  3903  3903 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=0f7e9060-64e7-4aac-af25-15952308279c
,07-26 15:20:48.117  8193  8212 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.127  8193  8213 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.127  3903  3903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:20:48.127  8193  8213 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.137  3903  3903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:20:48.137  2612  3058 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-26 15:20:48.137  2612  2612 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-26 15:20:48.137  2612  2612 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-26 15:20:48.137  2612  2612 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-26 15:20:48.217  8193  8213 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.227  3062  3089 W SyncManager: SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,07-26 15:20:48.247  8193  8213 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.257  8122  8191 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:48.257  8122  8191 I jxcore-log: 
,07-26 15:20:48.257  8122  8191 W jxcore-log: JXcore engine is started
,07-26 15:20:48.267  8122  8187 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:48.267  8193  8213 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.267  8122  8122 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:20:48.277  8193  8213 I System  : core_booster, getBoosterConfig = false
,07-26 15:20:48.287  8122  8191 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-26 15:20:48.287  8122  8191 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-26 15:20:48.287  8122  8122 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-26 15:20:48.287  8122  8122 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:20:48.307  3903  6233 I art     : Explicit concurrent mark sweep GC freed 66191(3MB) AllocSpace objects, 7(140KB) LOS objects, 40% free, 22MB/36MB, paused 1.683ms total 142.090ms
07-26 15:20:48.307  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:48.317  8122  8122 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:48.317  8122  8122 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:48.317  8122  8122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:48.317  8122  8122 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:48.317  8122  8122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-26 15:20:48.317  8122  8187 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
07-26 15:20:48.327  4084  4111 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-26 15:20:48.327  4084  4111 I HwSystemManager: AppLockService:applock password not initial or function is closed
,07-26 15:20:48.327  4084  4482 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-26 15:20:48.347  8122  8122 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 15:20:48.347  8122  8122 W ScreenOrientationListener: Removing an inexistent observer!
,07-26 15:20:48.347  4045  4197 I art     : Explicit concurrent mark sweep GC freed 1732(62KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 13MB/22MB, paused 730us total 34.618ms
,07-26 15:20:48.357  8193  8213 I System  : core_booster, getBoosterConfig = false
,07-26 15:20:48.357  8193  8213 I System  : core_booster, getBoosterConfig = false
,07-26 15:20:48.387  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.427  3903  4418 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:48.437  3903  4418 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.457  3903  4418 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.467  3903  4418 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.467  3903  4418 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.467  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.477  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:48.477  3903  4418 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.507  6386  8186 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.507  3903  4478 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:48.517  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.517  3903  4562 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-26 15:20:48.537  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.557  6386  8186 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.557  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.557  8232  8232 I appproc : CLASSPATH=/system/framework/pm.jar
07-26 15:20:48.557  8232  8232 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-26 15:20:48.557  8232  8232 I appproc : app_process:number,4,0
,07-26 15:20:48.567  8232  8232 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-26 15:20:48.657  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/DroidGuard;
,07-26 15:20:48.697  8232  8232 I         : power log dlsym ok
,07-26 15:20:48.727  3524  3524 I wpa_supplicant: wlan0: HEART-BEAT-ACK: 6
,07-26 15:20:48.727  3062  3961 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 6
07-26 15:20:48.727  3062  3338 E WifiStateMachine:  ConnectedState what:147506 0 0
07-26 15:20:48.727  3062  3338 E WifiStateMachine:  L2ConnectedState what:147506 0 0
07-26 15:20:48.727  3062  3338 E WifiStateMachine:  ConnectModeState what:147506 0 0
07-26 15:20:48.727  3062  3338 E WifiStateMachine:  DriverStartedState what:147506 0 0
07-26 15:20:48.727  3062  3338 E WifiStateMachine:  SupplicantStartedState what:147506 0 0
,07-26 15:20:48.747  8232  8232 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-26 15:20:48.747  8232  8232 I android_hardware_fm.cpp: ========64bit long size = 8
07-26 15:20:48.747  8232  8232 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-26 15:20:48.747  8232  8232 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-26 15:20:48.747  8232  8232 I fm_hisi : 
07-26 15:20:48.747  8232  8232 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-26 15:20:48.747  8232  8232 I fm_hisi : 
07-26 15:20:48.747  8232  8232 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-26 15:20:48.747  8232  8232 I fm_hisi : 
07-26 15:20:48.747  8232  8232 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-26 15:20:48.787  3062  3708 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-26 15:20:48.787  3062  3708 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-26 15:20:48.787  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:48.927  3062  3394 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-26 15:20:49.017  4084  4576 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10041
,07-26 15:20:49.017  4084  4192 I HwSystemManager: HoldService:uid:10041 pid:7506 died
07-26 15:20:49.017  4084  4192 I HwSystemManager: HoldService:oldVersionKey:10041,7506
07-26 15:20:49.017  4084  4895 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-26 15:20:49.017  4084  4192 I HwSystemManager: HoldService:uid:10072 pid:8122 died
07-26 15:20:49.017  4084  4192 I HwSystemManager: HoldService:oldVersionKey:10072,8122
07-26 15:20:49.017  3062  3084 E HsmCoreServiceImpl: onTransact in code is: 102
07-26 15:20:49.017  3062  3084 I MediaProcessHandler: processOp opType: 1, uid: 10041, pid: 7506
07-26 15:20:49.017  3062  3084 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10041, pid: 7506
07-26 15:20:49.017  3062  3708 E HsmCoreServiceImpl: onTransact in code is: 102
07-26 15:20:49.017  3062  3708 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 8122
07-26 15:20:49.017  3062  3708 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 8122
,07-26 15:20:49.047  3062  3102 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.067  3062  3297 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-26 15:20:49.077  7631  7631 I art     : Explicit concurrent mark sweep GC freed 7897(598KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 541us total 53.370ms
,07-26 15:20:49.087  7418  7628 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@9d25217 in the cache
,07-26 15:20:49.097  7418  7628 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-26 15:20:49.097  3062  3102 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-26 15:20:49.097  7418  7628 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-26 15:20:49.107  7418  7628 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@185a2604 in the cache
,07-26 15:20:49.107  3903  4478 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:49.127  3713  3713 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-26 15:20:49.127  7418  7628 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
07-26 15:20:49.127  7418  7628 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-26 15:20:49.127  7418  7628 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-26 15:20:49.127  7418  7628 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-26 15:20:49.127  7418  7628 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@10f97ed in the cache
,07-26 15:20:49.127  7418  7628 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@223c1622 in the cache
07-26 15:20:49.127  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:49.137  7418  7628 E ExternalAccountType: Unsupported attribute readOnly
,07-26 15:20:49.157  7418  7628 I AccountTypeManager: AccountManager, account size is: 2
,07-26 15:20:49.157  7013  7013 I art     : Explicit concurrent mark sweep GC freed 32684(2MB) AllocSpace objects, 10(160KB) LOS objects, 25% free, 13MB/18MB, paused 725us total 129.600ms
,07-26 15:20:49.157  7013  7013 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-26 15:20:49.157  7418  7628 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 104ms(wall) 20ms(cpu)
,07-26 15:20:49.157  7013  7013 I HwSystemManager: HsmPackageManager:replacing:false
07-26 15:20:49.157  7013  7013 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-26 15:20:49.157  7013  7013 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-26 15:20:49.187  3062  3102 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-26 15:20:49.197  3062  3318 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-26 15:20:49.217  3783  3783 I art     : Explicit concurrent mark sweep GC freed 71630(4MB) AllocSpace objects, 109(10MB) LOS objects, 38% free, 25MB/41MB, paused 11.262ms total 153.227ms
,07-26 15:20:49.217  3783  3783 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-26 15:20:49.217  3783  3783 I HwLauncher: Model replacing = false package = com.test.thalitest
,07-26 15:20:49.217  3783  3783 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-26 15:20:49.217  3783  3783 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
,07-26 15:20:49.217  3783  3932 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
,07-26 15:20:49.217  3783  3783 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
,07-26 15:20:49.217  3783  3936 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,07-26 15:20:49.217  3783  3783 E HideAppsPagedView: removeItems begin 
,07-26 15:20:49.217  3783  3783 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-26 15:20:49.217  3783  3783 E HideAppsPagedView: removeItems end 
,07-26 15:20:49.227  3783  3936 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
,07-26 15:20:49.227  3783  3936 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-26 15:20:49.227  3783  3936 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-26 15:20:49.227  3783  3936 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-26 15:20:49.227  3783  3936 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-26 15:20:49.227  3783  3783 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
07-26 15:20:49.227  3783  3783 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-26 15:20:49.227  3783  3783 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
,07-26 15:20:49.237  3783  3783 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
,07-26 15:20:49.237  3783  3783 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-26 15:20:49.237  3783  3783 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:49.237  3783  3783 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:49.237  3783  3783 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-26 15:20:49.237  3783  3783 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-26 15:20:49.237  3783  3783 W System.err: java.lang.NullPointerException: null receiver
07-26 15:20:49.237  3783  3783 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-26 15:20:49.237  3783  3783 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-26 15:20:49.237  3783  3783 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-26 15:20:49.237  3783  3783 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:20:49.237  3783  3783 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-26 15:20:49.237  3783  3783 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:49.237  3783  3783 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:49.237  3783  3783 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-26 15:20:49.237  3783  3783 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-26 15:20:49.237  3783  3783 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
07-26 15:20:49.237  3783  3783 I HwLauncher: Launcher Deferring update until onResume
07-26 15:20:49.247  4084  4084 I art     : Explicit concurrent mark sweep GC freed 98406(6MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/23MB, paused 1.800ms total 213.029ms
07-26 15:20:49.247  4084  4084 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-26 15:20:49.247  4084  4084 I HwSystemManager: HsmPackageManager:replacing:false
07-26 15:20:49.247  4084  4084 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-26 15:20:49.247  4084  4084 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-26 15:20:49.257  3783  3783 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
07-26 15:20:49.257  3783  3783 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
07-26 15:20:49.257  3783  3783 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
07-26 15:20:49.267  3783  3783 I HwLauncher: Launcher onStart()
07-26 15:20:49.267  3783  3783 I HwLauncher: Launcher dynamicIconsRegister
07-26 15:20:49.267  3783  3783 I HwLauncher: DynamicUpdater registerReceiver
07-26 15:20:49.267  3783  3783 I HwLauncher: DynamicUpdater call updateFolder
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicUpdater registerReceiver
07-26 15:20:49.277  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicUpdater call updateFolder
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicUpdater registerReceiver
,07-26 15:20:49.277  3783  3932 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicUpdater call updateFolder
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-26 15:20:49.277  3783  3783 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
07-26 15:20:49.277  3783  3783 E HideAppsPagedView: removeHideApps  begin 
07-26 15:20:49.277  3783  3783 E HideAppsPagedView: removeHideApps  end 
07-26 15:20:49.277  3783  3783 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-26 15:20:49.277  3783  3932 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-26 15:20:49.277  3783  3932 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-26 15:20:49.277  3783  3783 E ZipFileCache: init failed when open zip file.
,07-26 15:20:49.277  3783  3932 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-26 15:20:49.287  3783  3783 E ZipFileCache: init failed when open zip file.
07-26 15:20:49.287  3783  3783 E ZipFileCache: init failed when open zip file.
,07-26 15:20:49.287  3783  3783 E ZipFileCache: init failed when open zip file.
07-26 15:20:49.287  3783  3932 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
07-26 15:20:49.287  3783  3783 E ZipFileCache: init failed when open zip file.
,07-26 15:20:49.287  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
07-26 15:20:49.287  3783  3932 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-26 15:20:49.287  3783  3932 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-26 15:20:49.287  3783  3932 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
,07-26 15:20:49.287  3783  3783 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
07-26 15:20:49.287  3783  3783 E HideAppsPagedView:  createAddIcon count = 0
,07-26 15:20:49.297  3062  3280 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-26 15:20:49.297  3062  3280 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-26 15:20:49.297  3062  3280 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-26 15:20:49.297  3062  3280 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-26 15:20:49.297  3062  3280 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.297  3062  3280 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:20:49.297  3062  3280 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.297  4084  4084 I HwSystemManager: ww:deleteLockData:com.test.thalitest
,07-26 15:20:49.307  3783  3783 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,07-26 15:20:49.307  3783  3783 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
,07-26 15:20:49.307  3783  3783 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
,07-26 15:20:49.307  3783  3783 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,07-26 15:20:49.327  3783  3783 I HwLauncher: DynamicUpdater call updateFolder
,07-26 15:20:49.347  4084  4343 I HwSystemManager: aor:Network Stats Updated
07-26 15:20:49.347  4084  4343 I HwSystemManager: aoi:onNetworkStatsUpdated
07-26 15:20:49.347  4084  4346 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-26 15:20:49.357  4084  4346 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-26 15:20:49.357  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:49.357  4084  4346 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-26 15:20:49.357  4084  4346 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-26 15:20:49.357  4084  4346 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-26 15:20:49.357  4084  4346 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-26 15:20:49.357  4084  4346 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
07-26 15:20:49.367  4084  4346 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-26 15:20:49.377  4084  4346 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-26 15:20:49.377  4084  4346 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-26 15:20:49.377  4084  4346 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-26 15:20:49.377  4084  4346 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-26 15:20:49.377  4084  4346 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-26 15:20:49.377  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:49.387  4084  4346 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-26 15:20:49.387  4084  4346 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-26 15:20:49.387  4084  4346 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-26 15:20:49.387  4084  4346 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-26 15:20:49.387  4084  4346 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-26 15:20:49.397  8252  8252 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
07-26 15:20:49.397  8252  8252 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-26 15:20:49.397  8274  8274 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-26 15:20:49.407  3903  4562 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-26 15:20:49.417  3062  3062 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-26 15:20:49.457  3062  3062 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-26 15:20:49.457  3062  3062 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-26 15:20:49.457  3062  3062 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
07-26 15:20:49.457  3062  3062 E ReportTools: Can't find sReporterClazz
,07-26 15:20:49.457  3062  3062 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-26 15:20:49.457  3062  3062 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-26 15:20:49.457  3062  3062 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-26 15:20:49.467  3062  3062 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
,07-26 15:20:49.467  3062  3062 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-26 15:20:49.467  3062  3062 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-26 15:20:49.467  3062  3062 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-26 15:20:49.467  3062  3062 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-26 15:20:49.467  3062  3062 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:49.467  3062  3062 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:49.467  3062  3062 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-26 15:20:49.467  3062  3062 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:49.467  3062  3062 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-26 15:20:49.467  3062  3062 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-26 15:20:49.467  3062  3062 E ReportTools: This is not beta user build
,07-26 15:20:49.467  3461  3461 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-26 15:20:49.467  3461  3461 I PhoneStatusBar: shouldTranslucent:true
07-26 15:20:49.467  3461  3461 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-26 15:20:49.477  3062  3089 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,07-26 15:20:49.487  8274  8294 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-26 15:20:49.497  8274  8274 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-26 15:20:49.527  3062  3089 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-26 15:20:49.577  3062  3102 I art     : Explicit concurrent mark sweep GC freed 29675(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 2.326ms total 397.912ms
,07-26 15:20:49.657  3783  3783 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
07-26 15:20:49.657  3783  3932 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-26 15:20:49.657  3783  3932 I HwLauncher:  stringArray[] [unknown]
,07-26 15:20:49.677  4084  4192 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-26 15:20:49.677  4084  4895 I HwSystemManager: HoldService:uid:10084 pid:7454 died
07-26 15:20:49.677  4084  4895 I HwSystemManager: HoldService:oldVersionKey:10084,7454
07-26 15:20:49.677  3062  3708 E HsmCoreServiceImpl: onTransact in code is: 102
07-26 15:20:49.677  3062  3708 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 7454
07-26 15:20:49.677  3062  3708 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 7454
,07-26 15:20:49.677  2612  3058 I WVCdm   : CdmEngine::CloseSession
07-26 15:20:49.687  3903  4562 I System  : core_booster, getBoosterConfig = false
,07-26 15:20:49.687  4084  4084 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.687  4084  4084 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
,07-26 15:20:49.697  4084  4084 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@8bf653c
,07-26 15:20:49.697  4084  4084 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
,07-26 15:20:49.697  4084  8330 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,07-26 15:20:49.697  7013  7013 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.697  2612  3058 I WVCdm   : L3 Terminate.
,07-26 15:20:49.697  7013  7013 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@17100081
07-26 15:20:49.697  7013  7013 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-26 15:20:49.697  7013  8331 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-26 15:20:49.707  7013  7013 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,07-26 15:20:49.707  7013  8332 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-26 15:20:49.707  7013  8332 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.707  7013  8332 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
07-26 15:20:49.707  7013  8019 I HwSystemManager: ProtectAppControl:handleMessage:7
07-26 15:20:49.707  7013  8332 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.707  7013  8332 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
,07-26 15:20:49.707  7013  7013 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.717  4084  4084 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-26 15:20:49.717  4084  4084 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-26 15:20:49.717  4084  4084 E HwSystemManager: AppCleanUpService:msg is 1
07-26 15:20:49.717  4084  4111 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
,07-26 15:20:49.717  7013  7013 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-26 15:20:49.717  7013  8333 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-26 15:20:49.717  7013  8333 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.717  7013  8333 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.717  7013  8333 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0
,07-26 15:20:49.717  7013  7013 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.717  7013  7013 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
,07-26 15:20:49.717  7013  7013 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
,07-26 15:20:49.727  7013  8019 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
,07-26 15:20:49.787  3903  4562 I System  : core_booster, getBoosterConfig = false
07-26 15:20:49.787  3903  4562 I System  : core_booster, getBoosterConfig = false
,07-26 15:20:49.817  3062  3709 W System.err: java.lang.IllegalArgumentException: Unknown package: com.google.android.gms.unstable
07-26 15:20:49.817  3062  3709 W System.err: 	at com.android.server.pm.Settings.getInstallerPackageNameLPr(Settings.java:3220)
07-26 15:20:49.817  3062  3709 W System.err: 	at com.android.server.pm.PackageManagerService.getInstallerPackageName(PackageManagerService.java:12885)
07-26 15:20:49.817  3062  3709 W System.err: 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:935)
07-26 15:20:49.817  3062  3709 W System.err: 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1999)
07-26 15:20:49.817  3062  3709 W System.err: 	at com.android.server.pm.HwPackageManagerService.onTransact(HwPackageManagerService.java:461)
07-26 15:20:49.817  3062  3709 W System.err: 	at android.os.Binder.execTransact(Binder.java:446)
,07-26 15:20:49.867  4084  8330 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-26 15:20:49.867  4084  8330 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
07-26 15:20:49.867  4084  8330 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
07-26 15:20:49.867  4084  4107 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-26 15:20:49.867  4084  4107 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-26 15:20:49.867  4084  4107 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-26 15:20:49.867  7013  7013 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
,07-26 15:20:49.867  4084  4576 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-26 15:20:49.867  4084  4576 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-26 15:20:49.867  4084  4895 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-26 15:20:49.867  4084  4895 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-26 15:20:49.867  4084  4895 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-26 15:20:49.877  3461  3461 I PhoneStatusBar: notification pkg =com.android.settings
07-26 15:20:49.877  3461  3461 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-26 15:20:49.877  3461  3461 I PhoneStatusBar: notification pkg =android
07-26 15:20:49.877  3461  3461 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,07-26 15:20:49.877  7013  7013 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
,07-26 15:20:49.877  7013  7013 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
,07-26 15:20:49.877  7013  7013 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
,07-26 15:20:49.877  7013  8331 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-26 15:20:49.877  7013  8331 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-26 15:20:49.907  8334  8334 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=default --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=50 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-26 15:20:49.917  4084  4084 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@8bf653c
,07-26 15:20:49.927  7013  8338 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
,07-26 15:20:49.927  7013  8338 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
,07-26 15:20:49.927  4084  8337 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
,07-26 15:20:49.937  7013  8347 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
07-26 15:20:49.937  7013  7013 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
,07-26 15:20:49.947  7013  8348 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
07-26 15:20:49.947  7013  7013 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.957  7013  8348 I TrashManager: EngineManager not initialed, please EngineManager#init()
,07-26 15:20:49.987  8334  8334 I dex2oat : dex2oat took 85.275ms (threads: 8)
,07-26 15:20:49.997  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/Droidguasso;
,07-26 15:20:49.997  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/c;
,07-26 15:20:49.997  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/l;
,07-26 15:20:49.997  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/i;
,07-26 15:20:49.997  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/k;
,07-26 15:20:50.007  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/a;
,07-26 15:20:50.007  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/e;
,07-26 15:20:50.007  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/h;
,07-26 15:20:50.007  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/b;
,07-26 15:20:50.007  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/g;
,07-26 15:20:50.007  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/d;
,07-26 15:20:50.027  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/f;
,07-26 15:20:50.047  8193  8213 I art     : Can not find class: Lcom/google/ccc/abuse/droidguard/droidguasso/j;
,07-26 15:20:50.047  7013  8331 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-26 15:20:50.057  7013  8331 I HwSystemManager: PermissionDbVisitor:removeHistoryRecord,pkgName:com.test.thalitest, delete count:0
,07-26 15:20:50.057  7013  8331 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-26 15:20:50.057  7013  8331 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-26 15:20:50.067  3062  3636 I art     : Can not find class: Lcom/android/server/am/ActivityManagerService$20;
,07-26 15:20:50.067  3062  3636 E JavaBinder: *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
07-26 15:20:50.067  3062  3636 E JavaBinder: android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_WRITE(Sqlite code 778),(OS error - 9:Bad file number)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:535)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.saveAuthTokenToDatabase(AccountManagerService.java:1356)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.setAuthToken(AccountManagerService.java:1395)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.accounts.IAccountManager$Stub.onTransact(IAccountManager.java:268)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.onTransact(AccountManagerService.java:326)
07-26 15:20:50.067  3062  3636 E JavaBinder: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:20:50.067  3062  3090 I art     : Can not find class: Lcom/android/server/am/ActivityManagerService$21;
07-26 15:20:50.067  3062  3707 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error - SQLITE_IOERR_LOCK
07-26 15:20:50.067  3062  3707 E JavaBinder: *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
07-26 15:20:50.067  3062  3707 E JavaBinder: android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:518)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:429)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.setUserdataInternal(AccountManagerService.java:1495)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.setUserData(AccountManagerService.java:1482)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.accounts.IAccountManager$Stub.onTransact(IAccountManager.java:316)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.onTransact(AccountManagerService.java:326)
07-26 15:20:50.067  3062  3707 E JavaBinder: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:20:50.077  3062  3460 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error - SQLITE_IOERR_LOCK
,07-26 15:20:50.077  3062  3460 E JavaBinder: *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
07-26 15:20:50.077  3062  3460 E JavaBinder: android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:518)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:429)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.setUserdataInternal(AccountManagerService.java:1495)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.setUserData(AccountManagerService.java:1482)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.accounts.IAccountManager$Stub.onTransact(IAccountManager.java:316)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.onTransact(AccountManagerService.java:326)
07-26 15:20:50.077  3062  3460 E JavaBinder: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:20:50.077  3062  3084 E SQLiteLog: (3850) statement aborts at 17: [SELECT password FROM accounts WHERE name=? AND type=?] disk I/O error - SQLITE_IOERR_LOCK
07-26 15:20:50.077  3062  3084 E SQLiteQuery: exception: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number); query: SELECT password FROM accounts WHERE name=? AND type=?
07-26 15:20:50.077  3062  3084 E JavaBinder: *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
07-26 15:20:50.077  3062  3084 E JavaBinder: android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:845)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.AbstractCursor.moveToPosition(AbstractCursor.java:197)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.database.AbstractCursor.moveToNext(AbstractCursor.java:245)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.readPasswordInternal(AccountManagerService.java:567)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.getPassword(AccountManagerService.java:550)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.accounts.IAccountManager$Stub.onTransact(IAccountManager.java:59)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.onTransact(AccountManagerService.java:326)
07-26 15:20:50.077  3062  3084 E JavaBinder: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:20:50.087  3903  4562 E ZipFileCache: init failed when open zip file.
,07-26 15:20:50.187  7013  8331 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-26 15:20:50.237  7013  8331 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-26 15:20:50.237  7013  8331 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
07-26 15:20:50.237  7013  8331 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-26 15:20:50.247  4084  4111 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-26 15:20:50.247  4084  4895 I HwSystemManager: HoldService:uid:10058 pid:7587 died
07-26 15:20:50.247  4084  4895 I HwSystemManager: HoldService:oldVersionKey:10058,7587
07-26 15:20:50.247  3062  3609 E HsmCoreServiceImpl: onTransact in code is: 102
07-26 15:20:50.247  3062  3609 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 7587
07-26 15:20:50.247  3062  3609 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 7587
,07-26 15:20:50.287  7013  7013 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@17100081

```
