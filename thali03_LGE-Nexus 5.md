#### Test 757892682551a10_thali03_LGE-Nexus 5 Logs


```
--------- beginning of main
06-30 13:51:56.047  2977  2977 W Quickoffice: Cleanup of storage: done
06-30 13:51:56.049  2977  2993 D com.google.android.apps.docs.quickoffice.X: Loading recent documents list
06-30 13:51:56.052  2977  2994 D Quickoffice: The number of lines present in  /proc/mount 22
06-30 13:51:56.058  2977  2994 D Quickoffice: Parsing the storagedefinition.xml.
06-30 13:51:56.063  2977  2994 D Quickoffice: # of Storagedefinitions - 35
06-30 13:51:56.063  2977  2994 D Quickoffice: The # of storage definitions available - 35
06-30 13:51:56.063  2977  2994 D Quickoffice: Processing mountline rootfs / rootfs ro,seclabel,relatime 0 0
06-30 13:51:56.063  2977  2994 D Quickoffice: Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
06-30 13:51:56.063  2977  2994 D Quickoffice: Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
06-30 13:51:56.063  2977  2994 D Quickoffice: Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
06-30 13:51:56.063  2977  2994 D Quickoffice: Processing mountline proc /proc proc rw,relatime 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline debugfs /sys/kernel/debug debugfs rw,seclabel,relatime 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline tmpfs /mnt tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
06-30 13:51:56.064  2977  2994 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/default/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 13:51:56.065  2977  2994 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/read/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 13:51:56.065  2977  2994 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/write/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 13:51:56.065  2977  2994 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,relatime 0 0
06-30 13:51:56.065  2977  2994 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
06-30 13:51:56.065  2977  2994 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
06-30 13:51:56.065  2977  2994 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
06-30 13:51:56.066  2977  2994 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,context=u:object_r:firmware_file:s0,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
06-30 13:51:56.066  2977  2994 D Quickoffice: Processing mountline tmpfs /storage tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
06-30 13:51:56.066  2977  2994 D Quickoffice: Processing mountline /dev/fuse /storage/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 13:51:56.066  2977  2994 D Quickoffice: Processing mountline tmpfs /storage/self tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
06-30 13:51:56.076  2977  2994 E Quickoffice: An excep,tion occured in getAllMountedStorages method.
06-30 13:51:56.076  2977  2994 E Quickoffice: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.qo.android.filesystem.h.a(com.qo.android.filesystem.StorageDefinition)' on a null object reference
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at com.quickoffice.mx.engine.a.e(AndroidLocalFileSystems.java:432)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at com.quickoffice.mx.engine.a.a(AndroidLocalFileSystems.java:92)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at com.quickoffice.mx.S.b(MxPlugin.java:59)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at com.quickoffice.mx.engine.q.f(MxEngine.java:1225)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at com.quickoffice.mx.engine.q.a(MxEngine.java:1219)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at com.qo.android.b.call(AsyncTask.java:217)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-30 13:51:56.076  2977  2994 E Quickoffice: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:51:56.076  2977  2994 D Quickoffice: The # of mounts identified -  0
06-30 13:51:56.077  2977  2994 D Quickoffice: Failed to get moto storage state.
06-30 13:51:56.079  2977  2994 D Quickoffice: Failed to get moto storage dir.
--------- beginning of system
06-30 13:51:56.092   790  1313 I ActivityManager: Killing 2391:com.google.android.apps.photos/u0a83 (adj 15): empty #17
06-30 13:51:56.096  1661  2339 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
06-30 13:51:56.102  2977  2999 D com.google.android.apps.docs.quickoffice.X: Checking validity of 0 items
06-30 13:51:56.111  2977  2998 W Quickoffice: Could not load clipboard.
06-30 13:51:56.122  2977  3000 W Quickoffice: Could not store clipboard.
06-30 13:51:56.124   790  1311 W ActivityManager: No permission grants found for com.quickoffice.android
06-30 13:51:56.124  2977  2999 D ContentResolverUtil: There are 0 persisted uri permissions.
06-30 13:51:56.124  2977  2999 D com.google.android.apps.docs.quickoffice.X: 0 items were valid
06-30 13:51:56.154  1661  2339 D Icing   : Loaded CLD2 Version V2.0 - 20141016
06-30 13:51:56.158   790  1242 I ActivityManager: Killing 2427:com.google.android.deskclock/u0a33 (adj 15): empty #17
06-30 13:51:56.164  1661  2339 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
06-30 13:51:56.680  3001  3001 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:51:56.683  3001  3001 D AndroidRuntime: CheckJNI is OFF
06-30 13:51:56.718  3001  3001 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:51:56.755  3001  3001 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:51:56.774  3001  3001 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:51:56.776   790   959 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:51:56.798  3001  3001 D AndroidRuntime: Shutting down VM
06-30 13:51:56.799  1376  1388 W SearchService: Abort, client detached.
06-30 13:51:56.811  1376  1376 I MicroDetector: Keeping mic open: false
06-30 13:51:56.811  1376  1376 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@e8b9796
06-30 13:51:56.811  1376  1477 E AudioRecord-JNI: Error -4 during AudioRecord native read
06-30 13:51:56.811  1376  1602 I DeviceStateChecker: DeviceStateChecker cancelled
06-30 13:51:56.816   790   800 I ActivityManager: Start proc 3011:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
06-30 13:51:56.864   197  1612 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 13:51:56.864   197  1612 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
06-30 13:51:56.870  1376  1610 I MicroRecognitionRunner: Detection finished
06-30 13:51:56.870  1376  1601 I MicroRecognitionRunner: Stopping hotword detection.
06-30 13:51:56.911  3011  3011 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108600)
06-30 13:51:56.938  3011  3011 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 6360-6361)
06-30 13:51:56.938  3011  3011 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-30 13:51:56.952  3011  3011 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a7aef3}
06-30 13:51:56.952  3011  3011 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-30 13:51:56.952  3011  3011 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:51:56.974   790   891 D WifiService: New client listening to asynchronous messages
06-30 13:51:56.982  3011  3011 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 13:51:56.991  1661  2339 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
06-30 13:51:56.992  3011  3011 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
06-30 13:51:56.992  3011  3011 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
06-30 13:51:57.003  3011  3011 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 13:51:57.041  1661  2339 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,06-30 13:51:57.088   790   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91d7a0a:true
,06-30 13:51:57.096   790   959 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3011 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:51:57.104  3011  3011 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,06-30 13:51:57.110  3011  3011 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:51:57.111  3011  3011 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,06-30 13:51:57.121  3011  3011 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-30 13:51:57.145  3011  3011 I cr_Ime  : ImeThread is not enabled.
,06-30 13:51:57.157  3011  3052 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:51:57.224  3011  3057 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-30 13:51:57.303   190   190 D SurfaceFlinger: shader cache generated - 24 shaders in 134.180206 ms
,06-30 13:51:57.320   790  1311 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3011 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:51:57.374  3011  3052 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:51:57.434   790   809 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +634ms
,06-30 13:51:57.487  3011  3011 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3011
,06-30 13:51:57.490  3011  3011 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,06-30 13:51:57.491  3011  3011 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,06-30 13:51:57.611   790   959 I ActivityManager: Killing 2446:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,06-30 13:51:57.717  3011  3011 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:51:57.718   790   892 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:51:57.817  3011  3066 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1744832208
,06-30 13:51:57.820  3011  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:51:57.820  3011  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:51:57.820  3011  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:51:57.820  3011  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:51:57.820  3011  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:51:57.820  3011  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed25ff added. We now have 1 listener(s)
,06-30 13:51:57.824  3011  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,06-30 13:51:57.825  3011  3066 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,06-30 13:51:57.825  3011  3066 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:51:57.825  3011  3066 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 13:51:57.829  3011  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a492a added. We now have 1 listener(s)
06-30 13:51:57.829  3011  3066 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:51:57.830  3011  3066 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:51:57.830  3011  3066 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 13:51:57.831  3011  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-30 13:51:57.831  3011  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 13:51:57.832  3011  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:51:57.832  3011  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 13:51:57.833  3011  3066 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:51:57.833  3011  3066 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,06-30 13:51:57.834  3011  3066 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:51:57.834  3011  3066 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:51:57.834  3011  3066 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-30 13:51:57.834  3011  3066 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:51:57.834  3011  3066 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:51:57.859  3011  3011 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:51:58.614  3011  3067 W jxcore-log: Initializing JXcore engine
06-30 13:51:58.614  3011  3067 W jxcore-log: JXcore engine is ready
,06-30 13:51:58.639  3067  3067 W Thread-254: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7912]" dev="sockfs" ino=7912 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-30 13:51:58.639  3067  3067 W Thread-254: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-30 13:51:58.639  3067  3067 W Thread-254: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18890]" dev="sockfs" ino=18890 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-30 13:51:58.660  3011  3067 W jxcore-log: Starting JXcore engine
,06-30 13:51:58.735  3011  3067 W jxcore-log: Platform android
06-30 13:51:58.735  3011  3067 W jxcore-log: 
,06-30 13:51:58.735  3011  3067 W jxcore-log: Process ARCH arm
06-30 13:51:58.735  3011  3067 W jxcore-log: 
,06-30 13:51:58.919  3011  3067 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:51:58.919  3011  3067 I jxcore-log: 
06-30 13:51:58.920  3011  3067 W jxcore-log: JXcore engine is started
06-30 13:51:58.926  3011  3066 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 13:51:58.927   790   959 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10026 on display 0
06-30 13:51:58.933  3011  3011 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 13:51:58.934  3011  3011 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-30 13:51:58.951   790  1313 I ActivityManager: Start proc 3072:com.android.packageinstaller/u0a60 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 13:51:58.996  3072  3072 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
06-30 13:51:59.121  3072  3084 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 13:51:59.158  3072  3084 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 13:51:59.159  3072  3084 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:51:59.227   790   809 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +289ms
06-30 13:51:59.404  3011  3011 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7db8fb1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7783c8c, 16908290=android.view.AbsSavedState$1@7783c8c}, android:focusedViewId=100}]}]
06-30 13:51:59.404  3011  3011 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 13:52:01.955   790   801 I ActivityManager: Killing 1824:com.google.android.apps.fitness/u0a82 (adj 15): empty #17
,06-30 13:52:07.510  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:52:07.511  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:52:07.550  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:52:07.693  2926  2949 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,06-30 13:52:07.705  2926  2949 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
06-30 13:52:07.705  2926  2949 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,06-30 13:52:07.709  2926  2949 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-30 13:52:07.738  2926  2949 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 13:52:20.613  1558  1642 I Finsky  : [110] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,06-30 13:52:20.762   790   799 I art     : Background partial concurrent mark sweep GC freed 26497(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 25MB/37MB, paused 776us total 120.072ms
,06-30 13:52:20.773   790  1242 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1661 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:52:20.806  1661  3142 W DriveInitializer: Background init thread started
,06-30 13:52:20.837  1558  1642 I Finsky  : [110] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,06-30 13:52:20.837  1558  1558 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,06-30 13:52:20.863  1661  3142 W DriveInitializer: Background init thread ended
,06-30 13:52:58.922   790   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
06-30 13:52:58.925   790   813 I PowerManagerService: Sleeping (uid 1000)...
,06-30 13:52:58.961   790   813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 13:52:58.980   190   252 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (4230 us)
,06-30 13:52:59.044  3011  3011 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-30 13:52:59.045  3011  3011 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 13:52:59.526   790   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 13:52:59.539   790   813 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 13:52:59.542   790   809 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,06-30 13:52:59.546   190   190 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
06-30 13:52:59.546   190   190 D qdhwcomposer: hwc_blank: Blanking display: 0
,06-30 13:52:59.827   190   190 D qdhwcomposer: hwc_blank: Done blanking display: 0
,06-30 13:52:59.827   790   907 D SurfaceControl: Excessive delay in setPowerMode(): 285ms
06-30 13:52:59.828  1740  1742 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,06-30 13:52:59.831   197   829 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
06-30 13:52:59.832   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
06-30 13:52:59.833   790   890 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 13:52:59.857   197   898 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,06-30 13:52:59.858   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
06-30 13:52:59.858   790   890 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 13:52:59.869  1224  1224 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,06-30 13:53:05.601  1261  1615 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:36.528  1261  1261 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=90ded416-3d0d-42d7-a6ab-7dd097c2afe2
,06-30 13:53:36.540  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:36.541  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:36.632  1661  3218 D UdcContextInitService: registered all accounts: true
,06-30 13:53:36.633  1261  1548 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:53:36.642  1261  1541 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 13:53:36.730  1261  1541 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 13:53:36.774  1261  1261 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 13:53:36.777  1261  3231 I VacuumService: Vacuum at: now=1467287616777 tag=VacuumService
,06-30 13:54:36.899  1261  1541 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:36.900  1261  1541 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 13:54:36.900  1261  1541 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 13:54:36.900  1261  1541 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 13:54:36.900  1261  1541 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 13:54:36.901  1261  1541 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 13:55:55.795  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:55:55.813  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:55:55.814  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:00:55.952  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 14:00:55.955  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 14:00:55.955  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:05:56.040  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:05:56.057  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:05:56.057  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:10:40.504   790   802 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:56.157  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:10:56.173  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:10:56.173  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms)
```
