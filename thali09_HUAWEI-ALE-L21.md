#### Test 757892685041341_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-06 14:35:10.479  8148  8148 I appproc : CLASSPATH=/system/framework/am.jar
07-06 14:35:10.479  8148  8148 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-06 14:35:10.479  8148  8148 I appproc : app_process:number,5,0
07-06 14:35:10.479  8148  8148 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-06 14:35:10.629  8148  8148 I         : power log dlsym ok
07-06 14:35:10.669  8148  8148 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-06 14:35:10.669  8148  8148 I android_hardware_fm.cpp: ========64bit long size = 8
07-06 14:35:10.669  8148  8148 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-06 14:35:10.669  8148  8148 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-06 14:35:10.669  8148  8148 I fm_hisi : 
07-06 14:35:10.669  8148  8148 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-06 14:35:10.669  8148  8148 I fm_hisi : 
07-06 14:35:10.669  8148  8148 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-06 14:35:10.669  8148  8148 I fm_hisi : 
07-06 14:35:10.669  8148  8148 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-06 14:35:10.719  3172  3778 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-06 14:35:10.729  3172  3778 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-06 14:35:10.729  3172  3778 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-06 14:35:10.809  3172  3747 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-06 14:35:10.809  3669  3959 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-06 14:35:10.819  3997  4625 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 14:35:10.819  3997  4625 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 14:35:10.819  3779  3779 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-06 14:35:10.819  3779  3779 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-06 14:35:10.819  3779  3779 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-06 14:35:10.819  3997  4231 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-06 14:35:10.839  3779  3779 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-06 14:35:10.839  3779  3779 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-06 14:35:10.969  8172  8172 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
,07-06 14:35:10.989  8172  8172 I LibraryLoader: Loading: webviewchromium
07-06 14:35:11.039  8172  8172 I LibraryLoader: Time to load native libraries: 51 ms (timestamps 5336-5387)
07-06 14:35:11.039  8172  8172 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 14:35:11.079  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.079  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.079  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.089  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.099  8172  8172 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 14:35:11.099  8172  8172 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 14:35:11.109  8172  8172 I BrowserStartupController: Initializing chromium process, renderers=0
07-06 14:35:11.119  8172  8172 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 14:35:11.179  8172  8172 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-06 14:35:11.179  8172  8172 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-06 14:35:11.189  8172  8172 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-06 14:35:11.319  8172  8208 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-06 14:35:11.329  8172  8208 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-06 14:35:11.339  8172  8172 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-06 14:35:11.379  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.379  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.379  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.389  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.399  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.399  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.399  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.399  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.409  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.409  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.409  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.409  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.419  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.419  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.419  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.419  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.419  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.419  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.429  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.429  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.429  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.429  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.429  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.429  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.439  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.439  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.439  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.439  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.439  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.449  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.449  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.449  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.449  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.449  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.459  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.469  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.479  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.489  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.499  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.499  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.499  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.499  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.509  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.509  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.509  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.509  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.509  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.509  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.519  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.519  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.519  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.519  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.519  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.519  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.529  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.529  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.529  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.529  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.529  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.539  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.539  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.539  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.539  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.539  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.549  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.549  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.549  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.549  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.549  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.549  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.559  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 E ZipFileCache: init failed when open zip file.
07-06 14:35:11.569  8172  8172 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 14:35:11.579  8172  8172 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-06 14:35:11.579  8172  8172 I art     : Can not find class: Landroid/widget/ViewStub;
07-06 14:35:11.579  8172  8172 I art     : Can not find class: Landroid/webkit/ViewStub;
07-06 14:35:11.579  8172  8172 I art     : Can not find class: Landroid/app/ViewStub;
07-06 14:35:11.609  8172  8172 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 14:35:11.609  8172  8172 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:11.879  3440  3440 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-06 14:35:11.879  3440  3440 I PhoneStatusBar: shouldTranslucent:true
,07-06 14:35:11.879  3440  3440 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-06 14:35:11.909  8172  8226 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 14:35:11.939  3172  3233 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s128ms (total +1s211ms)
,07-06 14:35:11.949  8172  8172 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-06 14:35:11.979  3473  3473 I wpa_supplicant: wlan0: HEART-BEAT-ACK: 15
,07-06 14:35:11.979  3172  3890 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 15
07-06 14:35:11.979  3172  3324 E WifiStateMachine:  ConnectedState what:147506 0 0
07-06 14:35:11.979  3172  3324 E WifiStateMachine:  L2ConnectedState what:147506 0 0
,07-06 14:35:11.979  3172  3324 E WifiStateMachine:  ConnectModeState what:147506 0 0
07-06 14:35:11.979  3172  3324 E WifiStateMachine:  DriverStartedState what:147506 0 0
,07-06 14:35:11.979  3172  3324 E WifiStateMachine:  SupplicantStartedState what:147506 0 0
,07-06 14:35:12.049  8172  8172 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-06 14:35:12.049  8172  8172 I chromium: 
,07-06 14:35:12.119  8172  8172 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
07-06 14:35:12.219  8172  8234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
07-06 14:35:12.249  8172  8234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-06 14:35:12.249  8172  8234 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-06 14:35:12.249  8172  8234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-06 14:35:12.249  8172  8234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
07-06 14:35:12.259  8172  8234 I io.jxcore.node.LifeCycleMonitor: start: OK
07-06 14:35:12.279  8172  8172 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-06 14:35:12.709  8172  8237 W jxcore-log: Initializing JXcore engine
07-06 14:35:12.709  8172  8237 W jxcore-log: JXcore engine is ready
07-06 14:35:12.769  8172  8237 W jxcore-log: Starting JXcore engine
,07-06 14:35:12.869  8172  8237 W jxcore-log: Platform android
07-06 14:35:12.869  8172  8237 W jxcore-log: 
07-06 14:35:12.869  8172  8237 W jxcore-log: Process ARCH arm
07-06 14:35:12.869  8172  8237 W jxcore-log: 
,07-06 14:35:13.079  8172  8237 I jxcore-log: JXcore Cordova bridge is ready!
07-06 14:35:13.079  8172  8237 I jxcore-log: 
07-06 14:35:13.079  8172  8237 W jxcore-log: JXcore engine is started
,07-06 14:35:13.729  3172  3374 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-06 14:35:18.969  3997  4226 I HwSystemManager: BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
07-06 14:35:18.969  3997  4226 I HwSystemManager: BgPowerManagerService: mTimes = 180587 firstTime = 92729 firstmBatteryCapacity =2203
,07-06 14:35:26.989  3473  3473 I wpa_supplicant: wlan0: HEART-BEAT-ACK: 16
,07-06 14:35:26.989  3172  3890 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 16
,07-06 14:35:26.999  3172  3324 E WifiStateMachine:  ConnectedState what:147506 0 0
,07-06 14:35:26.999  3172  3324 E WifiStateMachine:  L2ConnectedState what:147506 0 0
,07-06 14:35:26.999  3172  3324 E WifiStateMachine:  ConnectModeState what:147506 0 0
,07-06 14:35:26.999  3172  3324 E WifiStateMachine:  DriverStartedState what:147506 0 0
,07-06 14:35:26.999  3172  3324 E WifiStateMachine:  SupplicantStartedState what:147506 0 0
,07-06 14:35:42.009  3473  3473 I wpa_supplicant: wlan0: HEART-BEAT-ACK: 17
,07-06 14:35:42.009  3172  3890 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: HEART-BEAT-ACK: 17
,07-06 14:35:42.009  3172  3324 E WifiStateMachine:  ConnectedState what:147506 0 0
,07-06 14:35:42.019  3172  3324 E WifiStateMachine:  L2ConnectedState what:147506 0 0
,07-06 14:35:42.019  3172  3324 E WifiStateMachine:  ConnectModeState what:147506 0 0
,07-06 14:35:42.019  3172  3324 E WifiStateMachine:  DriverStartedState what:147506 0 0
,07-06 14:35:42.019  3172  3324 E WifiStateMachine:  SupplicantStartedState what:147506 0 0

```
