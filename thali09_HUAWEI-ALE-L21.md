#### Test 72145431eb52a3d_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-06 12:18:11.863  8280  8280 I appproc : CLASSPATH=/system/framework/am.jar
07-06 12:18:11.863  8280  8280 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-06 12:18:11.863  8280  8280 I appproc : app_process:number,5,0
07-06 12:18:11.863  8280  8280 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-06 12:18:12.003  8280  8280 I         : power log dlsym ok
07-06 12:18:12.053  8280  8280 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-06 12:18:12.053  8280  8280 I android_hardware_fm.cpp: ========64bit long size = 8
07-06 12:18:12.053  8280  8280 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-06 12:18:12.053  8280  8280 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-06 12:18:12.053  8280  8280 I fm_hisi : 
07-06 12:18:12.053  8280  8280 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-06 12:18:12.053  8280  8280 I fm_hisi : 
07-06 12:18:12.053  8280  8280 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-06 12:18:12.053  8280  8280 I fm_hisi : 
07-06 12:18:12.053  8280  8280 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-06 12:18:12.103  3171  3193 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-06 12:18:12.103  3171  3193 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-06 12:18:12.103  3171  3193 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-06 12:18:12.173  3171  3780 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-06 12:18:12.173  3732  4093 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-06 12:18:12.183  3994  4113 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 12:18:12.183  3994  4113 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 12:18:12.183  3849  3849 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-06 12:18:12.183  3849  3849 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-06 12:18:12.183  3849  3849 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-06 12:18:12.193  3994  4308 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-06 12:18:12.193  3849  3849 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-06 12:18:12.193  3849  3849 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-06 12:18:12.323  8300  8300 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
07-06 12:18:12.333  8300  8300 I LibraryLoader: Loading: webviewchromium
07-06 12:18:12.333  8300  8300 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1654-1657)
07-06 12:18:12.333  8300  8300 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-06 12:18:12.353  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.353  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.363  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.363  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.373  8300  8300 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 12:18:12.373  8300  8300 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 12:18:12.383  8300  8300 I BrowserStartupController: Initializing chromium process, renderers=0
07-06 12:18:12.383  8300  8300 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 12:18:12.393  8300  8300 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-06 12:18:12.393  8300  8300 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-06 12:18:12.393  8300  8300 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-06 12:18:12.483  8300  8336 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-06 12:18:12.483  8300  8300 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-06 12:18:12.493  8300  8336 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-06 12:18:12.543  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.543  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.553  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.553  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.553  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.553  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.553  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.553  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.563  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.563  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.563  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.563  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.573  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.573  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.573  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.573  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.583  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.583  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.583  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.583  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.583  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.583  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.593  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.593  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.593  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.593  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.593  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.593  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.603  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.603  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.603  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.603  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.613  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.613  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.613  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.613  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.613  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.613  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.623  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.623  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.623  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.623  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.623  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.623  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.633  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.643  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.653  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.663  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.663  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.663  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.663  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.663  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.663  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.673  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.673  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.673  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.673  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.683  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.683  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.683  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.683  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.683  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.693  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.693  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.693  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.693  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.693  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.703  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.703  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.703  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.703  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.713  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.713  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.713  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.713  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.713  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.713  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.723  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.723  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.723  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.723  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.723  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.723  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.733  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 E ZipFileCache: init failed when open zip file.
07-06 12:18:12.743  8300  8300 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 12:18:12.753  8300  8300 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-06 12:18:12.753  8300  8300 I art     : Can not find class: Landroid/widget/ViewStub;
07-06 12:18:12.753  8300  8300 I art     : Can not find class: Landroid/webkit/ViewStub;
07-06 12:18:12.753  8300  8300 I art     : Can not find class: Landroid/app/ViewStub;
07-06 12:18:12.783  8300  8300 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 12:18:12.783  8300  8300 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 12:18:12.963  3506  3506 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-06 12:18:12.973  3506  3506 I PhoneStatusBar: shouldTranslucent:true
07-06 12:18:12.973  3506  3506 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-06 12:18:13.063  8300  8353 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 12:18:13.133  3171  3230 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +956ms (total +1s27ms)
07-06 12:18:13.133  8300  8300 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-06 12:18:13.253  8300  8300 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-06 12:18:13.253  8300  8300 I chromium: 
,07-06 12:18:13.393  8300  8366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
,07-06 12:18:13.413  8300  8366 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-06 12:18:13.413  8300  8366 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-06 12:18:13.413  8300  8366 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-06 12:18:13.413  8300  8366 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,07-06 12:18:13.423  8300  8366 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-06 12:18:13.453  8300  8300 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-06 12:18:13.903  8300  8369 W jxcore-log: Initializing JXcore engine
07-06 12:18:13.903  8300  8369 W jxcore-log: JXcore engine is ready
07-06 12:18:13.963  8300  8369 W jxcore-log: Starting JXcore engine
07-06 12:18:14.073  8300  8369 W jxcore-log: Platform android
07-06 12:18:14.073  8300  8369 W jxcore-log: 
07-06 12:18:14.073  8300  8369 W jxcore-log: Process ARCH arm
07-06 12:18:14.073  8300  8369 W jxcore-log: 
07-06 12:18:14.283  8300  8369 I jxcore-log: JXcore Cordova bridge is ready!
07-06 12:18:14.283  8300  8369 I jxcore-log: 
07-06 12:18:14.283  8300  8369 W jxcore-log: JXcore engine is started
07-06 12:18:14.293  8300  8366 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-06 12:18:14.293  8300  8300 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-06 12:18:14.303  8300  8369 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-06 12:18:14.303  8300  8369 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
07-06 12:18:14.303  8300  8300 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-06 12:18:14.303  8300  8300 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-06 12:18:14.423  8300  8366 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 117ms. Plugin should use CordovaInterface.getThreadPool().
07-06 12:18:14.433  3994  4015 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 12:18:14.433  8300  8300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-06 12:18:14.433  8300  8300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-06 12:18:14.433  8300  8300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-06 12:18:14.433  8300  8300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-06 12:18:14.433  3994  4015 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-06 12:18:14.433  8300  8300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-06 12:18:14.433  3994  4556 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-06 12:18:14.433  3171  3782 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 12:18:14.433  3994  4556 I HwSystemManager: HoldService:uid:10084 pid:7438 died
07-06 12:18:14.433  3171  3782 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 7438
07-06 12:18:14.433  3171  3782 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 7438
07-06 12:18:14.433  3994  4556 I HwSystemManager: HoldService:oldVersionKey:10084,7438
07-06 12:18:14.433  3994  4308 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-06 12:18:14.443  8300  8300 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-06 12:18:14.443  8300  8300 W ScreenOrientationListener: Removing an inexistent observer!
,07-06 12:18:14.623  8371  8371 I appproc : CLASSPATH=/system/framework/pm.jar
07-06 12:18:14.623  8371  8371 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-06 12:18:14.623  8371  8371 I appproc : app_process:number,4,0
,07-06 12:18:14.633  8371  8371 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-06 12:18:14.763  8371  8371 I         : power log dlsym ok
,07-06 12:18:14.813  8371  8371 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-06 12:18:14.813  8371  8371 I android_hardware_fm.cpp: ========64bit long size = 8
07-06 12:18:14.813  8371  8371 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-06 12:18:14.813  8371  8371 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-06 12:18:14.813  8371  8371 I fm_hisi : 
07-06 12:18:14.813  8371  8371 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-06 12:18:14.813  8371  8371 I fm_hisi : 
07-06 12:18:14.813  8371  8371 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-06 12:18:14.813  8371  8371 I fm_hisi : 
07-06 12:18:14.813  8371  8371 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-06 12:18:14.853  3171  3192 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-06 12:18:14.853  3171  3192 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-06 12:18:15.093  3994  7467 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-06 12:18:15.093  3994  4113 I HwSystemManager: HoldService:uid:10072 pid:8300 died
07-06 12:18:15.093  3994  4113 I HwSystemManager: HoldService:oldVersionKey:10072,8300
07-06 12:18:15.093  3171  3418 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 12:18:15.093  3171  3418 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 8300
07-06 12:18:15.093  3171  3418 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 8300
,07-06 12:18:15.103  3171  3461 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-06 12:18:15.123  3171  3245 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-06 12:18:15.143  7004  7004 I art     : Explicit concurrent mark sweep GC freed 32552(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 670us total 46.373ms
,07-06 12:18:15.163  7400  7641 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@2d8734ff in the cache
,07-06 12:18:15.163  3924  4331 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-06 12:18:15.163  7400  7641 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-06 12:18:15.173  3171  3398 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-06 12:18:15.173  7004  7004 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-06 12:18:15.173  7004  7004 I HwSystemManager: HsmPackageManager:replacing:false
,07-06 12:18:15.173  7004  7004 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-06 12:18:15.173  7004  7004 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-06 12:18:15.173  7400  7641 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-06 12:18:15.173  3171  3245 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-06 12:18:15.183  3171  3245 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-06 12:18:15.183  7400  7641 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@10f172cc in the cache
,07-06 12:18:15.193  7569  7569 I art     : Explicit concurrent mark sweep GC freed 7927(599KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 420us total 96.196ms
,07-06 12:18:15.193  3171  3403 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-06 12:18:15.203  3994  4181 I HwSystemManager: aor:Network Stats Updated
07-06 12:18:15.203  3994  4181 I HwSystemManager: aoi:onNetworkStatsUpdated
,07-06 12:18:15.203  3994  4183 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-06 12:18:15.213  7400  7641 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
07-06 12:18:15.213  7400  7641 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-06 12:18:15.213  7400  7641 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-06 12:18:15.213  7400  7641 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-06 12:18:15.213  7400  7641 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@1d903915 in the cache
,07-06 12:18:15.213  7400  7641 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@30ae42a in the cache
07-06 12:18:15.213  3994  4183 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-06 12:18:15.223  7400  7641 E ExternalAccountType: Unsupported attribute readOnly
,07-06 12:18:15.223  3994  4183 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-06 12:18:15.223  3994  4183 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-06 12:18:15.223  3994  4183 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
07-06 12:18:15.223  3994  3994 I art     : Explicit concurrent mark sweep GC freed 108103(7MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/23MB, paused 4.125ms total 122.937ms
,07-06 12:18:15.223  3994  3994 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-06 12:18:15.223  3994  3994 I HwSystemManager: HsmPackageManager:replacing:false
07-06 12:18:15.223  3994  3994 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-06 12:18:15.233  3994  3994 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-06 12:18:15.233  3994  4183 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-06 12:18:15.233  3994  4183 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-06 12:18:15.233  7400  7641 I AccountTypeManager: AccountManager, account size is: 2
,07-06 12:18:15.233  3994  3994 I HwSystemManager: ww:deleteLockData:com.test.thalitest
,07-06 12:18:15.243  7400  7641 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 76ms(wall) 22ms(cpu)
,07-06 12:18:15.243  3994  4183 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-06 12:18:15.243  3994  4183 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-06 12:18:15.243  3994  4183 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-06 12:18:15.243  3994  4183 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-06 12:18:15.243  3994  4183 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-06 12:18:15.243  3994  4183 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-06 12:18:15.243  3994  4183 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-06 12:18:15.253  3994  4183 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-06 12:18:15.253  3994  4183 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-06 12:18:15.253  3994  4183 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-06 12:18:15.253  3994  4183 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-06 12:18:15.263  3171  3216 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,07-06 12:18:15.263  3783  3783 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-06 12:18:15.273  6208  6208 I art     : Explicit concurrent mark sweep GC freed 1901(73KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/31MB, paused 1.085ms total 175.532ms
,07-06 12:18:15.323  3849  3849 I art     : Explicit concurrent mark sweep GC freed 56562(3MB) AllocSpace objects, 73(4MB) LOS objects, 38% free, 25MB/41MB, paused 1.555ms total 211.264ms
,07-06 12:18:15.323  3849  3849 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-06 12:18:15.323  3849  3849 I HwLauncher: Model replacing = false package = com.test.thalitest
,07-06 12:18:15.333  3849  3849 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-06 12:18:15.333  3849  3849 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
,07-06 12:18:15.333  3849  3849 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
07-06 12:18:15.333  3849  3986 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
,07-06 12:18:15.333  3849  3991 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,07-06 12:18:15.333  3849  3991 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-06 12:18:15.333  3849  3991 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-06 12:18:15.333  3849  3991 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-06 12:18:15.333  3849  3991 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-06 12:18:15.333  3849  3991 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-06 12:18:15.333  3849  3849 I HwLauncher: Launcher onStart()
07-06 12:18:15.333  3849  3849 I HwLauncher: Launcher dynamicIconsRegister
,07-06 12:18:15.333  3849  3849 I HwLauncher: DynamicUpdater registerReceiver
,07-06 12:18:15.333  3849  3849 I HwLauncher: DynamicUpdater call updateFolder
,07-06 12:18:15.333  3849  3849 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-06 12:18:15.333  3849  3849 I HwLauncher: DynamicUpdater registerReceiver
,07-06 12:18:15.343  3849  3849 I HwLauncher: DynamicUpdater call updateFolder
,07-06 12:18:15.343  3849  3986 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,07-06 12:18:15.343  3849  3986 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-06 12:18:15.343  3849  3986 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-06 12:18:15.343  3849  3986 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-06 12:18:15.353  3849  3986 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,07-06 12:18:15.353  3849  3986 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-06 12:18:15.353  3849  3986 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicUpdater registerReceiver
,07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicUpdater call updateFolder
07-06 12:18:15.353  3849  3986 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
,07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
07-06 12:18:15.353  3849  3849 E HideAppsPagedView: removeItems begin 
07-06 12:18:15.353  3849  3849 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-06 12:18:15.353  3849  3849 E HideAppsPagedView: removeItems end 
07-06 12:18:15.353  3849  3849 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
,07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-06 12:18:15.353  3849  3849 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,07-06 12:18:15.383  3171  3216 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-06 12:18:15.383  3849  3849 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,07-06 12:18:15.393  3849  3849 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-06 12:18:15.393  3849  3849 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-06 12:18:15.393  3849  3849 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,07-06 12:18:15.393  3849  3849 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,07-06 12:18:15.393  3849  3849 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 12:18:15.393  3849  3849 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-06 12:18:15.393  3849  3849 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 12:18:15.393  3849  3849 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-06 12:18:15.393  3849  3849 W System.err: java.lang.NullPointerException: null receiver
,07-06 12:18:15.393  3849  3849 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-06 12:18:15.393  3849  3849 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-06 12:18:15.393  3849  3849 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-06 12:18:15.393  3849  3849 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-06 12:18:15.393  3849  3849 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 12:18:15.393  3849  3849 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-06 12:18:15.393  3849  3849 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 12:18:15.393  3849  3849 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-06 12:18:15.393  3849  3849 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-06 12:18:15.393  3849  3849 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
,07-06 12:18:15.393  3849  3849 E HideAppsPagedView: removeHideApps  begin 
07-06 12:18:15.393  3849  3849 E HideAppsPagedView: removeHideApps  end 
07-06 12:18:15.393  3849  3849 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-06 12:18:15.393  3849  3849 E ZipFileCache: init failed when open zip file.
,07-06 12:18:15.393  3849  3849 E ZipFileCache: init failed when open zip file.
,07-06 12:18:15.393  3849  3849 E ZipFileCache: init failed when open zip file.
,07-06 12:18:15.393  3849  3849 E ZipFileCache: init failed when open zip file.
,07-06 12:18:15.403  3849  3849 E ZipFileCache: init failed when open zip file.
,07-06 12:18:15.403  3849  3849 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
07-06 12:18:15.403  3849  3849 E HideAppsPagedView:  createAddIcon count = 0
,07-06 12:18:15.403  3849  3849 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,07-06 12:18:15.453  8416  8416 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-06 12:18:15.463  3171  3171 I art     : Explicit concurrent mark sweep GC freed 68216(4MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/42MB, paused 2.489ms total 356.660ms
,07-06 12:18:15.463  3171  3245 I art     : WaitForGcToComplete blocked for 259.739ms for cause Explicit
,07-06 12:18:15.483  8416  8436 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-06 12:18:15.493  8416  8416 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-06 12:18:15.503  8394  8394 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-06 12:18:15.503  3849  3849 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
07-06 12:18:15.503  8394  8394 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-06 12:18:15.513  3849  3986 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-06 12:18:15.513  3849  3986 I HwLauncher:  stringArray[] [unknown]
,07-06 12:18:15.583  3171  3388 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-06 12:18:15.583  3171  3388 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-06 12:18:15.583  3171  3388 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-06 12:18:15.583  3171  3388 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-06 12:18:15.583  3171  3388 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 12:18:15.583  3171  3388 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 12:18:15.583  3171  3388 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-06 12:18:15.633  3171  3171 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-06 12:18:15.643  3171  3171 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-06 12:18:15.643  3171  3171 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-06 12:18:15.643  3171  3171 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
07-06 12:18:15.643  3171  3171 E ReportTools: Can't find sReporterClazz
07-06 12:18:15.643  3171  3171 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
07-06 12:18:15.643  3171  3171 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
07-06 12:18:15.643  3171  3171 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-06 12:18:15.643  3171  3171 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-06 12:18:15.653  3171  3171 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-06 12:18:15.653  3171  3171 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-06 12:18:15.653  3171  3171 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-06 12:18:15.653  3171  3171 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-06 12:18:15.653  3171  3171 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-06 12:18:15.653  3171  3171 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-06 12:18:15.653  3171  3171 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-06 12:18:15.653  3171  3171 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 12:18:15.653  3171  3171 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-06 12:18:15.653  3171  3171 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-06 12:18:15.653  3171  3171 E ReportTools: This is not beta user build
,07-06 12:18:15.653  3506  3506 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-06 12:18:15.653  3506  3506 I PhoneStatusBar: shouldTranslucent:true
07-06 12:18:15.653  3506  3506 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-06 12:18:15.653  3994  4015 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-06 12:18:15.653  3994  4015 I HwSystemManager: HoldService:uid:10058 pid:6361 died
07-06 12:18:15.653  3994  4015 I HwSystemManager: HoldService:oldVersionKey:10058,6361
07-06 12:18:15.653  3171  3633 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 12:18:15.653  3171  3633 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 6361
07-06 12:18:15.653  3171  3633 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 6361
07-06 12:18:15.683  3171  3245 I art     : Explicit concurrent mark sweep GC freed 7544(369KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 4.262ms total 221.884ms
,07-06 12:18:15.833  3994  4113 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10010
07-06 12:18:15.833  3994  4113 I HwSystemManager: HoldService:uid:10010 pid:7598 died
07-06 12:18:15.833  3994  4113 I HwSystemManager: HoldService:oldVersionKey:10010,7598
07-06 12:18:15.833  3171  3826 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 12:18:15.833  3171  3826 I MediaProcessHandler: processOp opType: 1, uid: 10010, pid: 7598
07-06 12:18:15.833  3171  3826 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10010, pid: 7598
,07-06 12:18:15.863  3994  3994 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-06 12:18:15.863  3994  3994 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
,07-06 12:18:15.863  3994  3994 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@3ad285c3
,07-06 12:18:15.873  3994  3994 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
,07-06 12:18:15.873  3994  8489 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,07-06 12:18:15.873  7004  7004 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
,07-06 12:18:15.873  7004  7004 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@1c82175f
,07-06 12:18:15.873  7004  7004 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-06 12:18:15.873  7004  8490 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-06 12:18:15.883  7004  7004 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
07-06 12:18:15.883  7004  8491 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-06 12:18:15.883  7004  8491 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-06 12:18:15.883  7004  8491 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
07-06 12:18:15.883  7004  7875 I HwSystemManager: ProtectAppControl:handleMessage:7
07-06 12:18:15.883  7004  8491 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 12:18:15.883  7004  8491 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
,07-06 12:18:15.883  3994  4110 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
07-06 12:18:15.883  7004  7004 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
,07-06 12:18:15.883  7004  7875 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
,07-06 12:18:15.883  3994  3994 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-06 12:18:15.883  3994  3994 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-06 12:18:15.883  3994  3994 E HwSystemManager: AppCleanUpService:msg is 1
,07-06 12:18:15.893  7004  7004 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-06 12:18:15.893  7004  8492 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-06 12:18:15.893  7004  8492 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-06 12:18:15.893  7004  8492 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 12:18:15.893  7004  8492 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0
,07-06 12:18:15.893  7004  7004 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-06 12:18:15.893  7004  7004 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
,07-06 12:18:15.893  7004  7004 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
,07-06 12:18:15.943  7004  8490 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-06 12:18:15.943  7004  8490 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
07-06 12:18:15.943  3994  4556 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-06 12:18:15.943  3994  7467 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-06 12:18:15.943  3994  7467 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-06 12:18:15.943  3994  4556 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-06 12:18:15.943  3994  7467 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-06 12:18:15.943  7004  7004 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
07-06 12:18:15.943  7004  7004 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
07-06 12:18:15.943  7004  7004 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
07-06 12:18:15.943  7004  7004 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
07-06 12:18:15.943  3994  4389 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-06 12:18:15.943  3994  4389 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-06 12:18:15.943  3994  4389 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-06 12:18:15.953  3506  3506 I PhoneStatusBar: notification pkg =com.android.settings
07-06 12:18:15.953  3506  3506 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-06 12:18:15.953  3506  3506 I PhoneStatusBar: notification pkg =android
07-06 12:18:15.953  3506  3506 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,07-06 12:18:15.953  3994  8489 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED,
07-06 12:18:15.953  3994  8489 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
07-06 12:18:15.953  3994  8489 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-06 12:18:15.963  7004  8494 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
07-06 12:18:15.963  7004  8494 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
,07-06 12:18:15.963  3994  8493 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
,07-06 12:18:15.973  7004  8496 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
07-06 12:18:15.983  7004  7004 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
,07-06 12:18:15.983  7004  8497 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
,07-06 12:18:15.983  7004  7004 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
,07-06 12:18:15.993  7004  8497 I TrashManager: EngineManager not initialed, please EngineManager#init()
,07-06 12:18:16.033  3994  3994 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@3ad285c3
,07-06 12:18:16.093  7004  8490 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-06 12:18:16.093  3994  4110 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM history_table WHERE packageName=?] disk I/O error - SQLITE_IOERR_LOCK
,07-06 12:18:16.103  3994  4110 E DatabaseUtils: Writing exception to parcel
07-06 12:18:16.103  3994  4110 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at pf.delete(Unknown Source)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at com.huawei.permissionmanager.db.PermissionDataProvider.delete(Unknown Source)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
07-06 12:18:16.103  3994  4110 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,07-06 12:18:16.103  7004  8490 E HwSystemManager: HsmIntentService:invoke error, InvocationTargetException:java.lang.reflect.InvocationTargetException
07-06 12:18:16.103  7004  8490 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-06 12:18:16.103  7004  8490 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
07-06 12:18:16.103  7004  8490 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-06 12:18:16.153  7004  7004 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@1c82175f
,07-06 12:18:16.263  3994  4016 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10044
07-06 12:18:16.263  3994  4016 I HwSystemManager: HoldService:uid:10044 pid:7892 died
07-06 12:18:16.263  3994  4016 I HwSystemManager: HoldService:oldVersionKey:10044,7892
07-06 12:18:16.263  3171  3826 E HsmCoreServiceImpl: onTransact in code is: 102
07-06 12:18:16.263  3171  3826 I MediaProcessHandler: processOp opType: 1, uid: 10044, pid: 7892
07-06 12:18:16.263  3171  3826 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10044, pid: 7892

```
