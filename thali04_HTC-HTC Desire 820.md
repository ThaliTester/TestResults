#### Test 721454317367600_thali04_HTC-HTC Desire 820 Logs


```
--------- beginning of main,
06-22 07:44:39.962  5259  5717 D osq     : Look up (com.test.thalitest:19) returned no result
06-22 07:44:39.962  5259  5717 D osz     : Starting Hash for package com.test.thalitest:0.0.1
06-22 07:44:39.972  1614  2692 I PackageManager: setEnabledSetting: pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, oldComponentState=2
06-22 07:44:40.032  5259  6481 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
06-22 07:44:40.072  5866  5866 D AlarmReceiver: ACTION_RESTART_INTENT
06-22 07:44:40.072  6216  6216 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
06-22 07:44:40.072  5866  5866 D LocalBluetoothProfile: getPriorityOnValue = 100
06-22 07:44:40.072  5866  5866 D LocalBluetoothProfile: getPriorityOffValue = 0
--------- beginning of system
06-22 07:44:40.072  1614  1614 D PMS     : releaseWL(22c1f9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10177}
06-22 07:44:40.072  5866  5866 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-22 07:44:40.072  5866  5866 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
06-22 07:44:40.082  6216  6216 I Finsky  : [1] com.google.android.finsky.utils.bh.run(2302): Package state data is missing for com.test.thalitest
06-22 07:44:40.092  1614  2692 D PMS     : acquireWL(58dc4c6): PARTIAL_WAKE_LOCK  Icing 0x1 5259 10029 WorkSource{10029 com.google.android.gms}
06-22 07:44:40.122  2750  3135 E Prism.WidgetManager: The same lists. No need to update. skip it.
06-22 07:44:40.122  2750  3135 I Prism.WidgetManager: onLoadItems() -
06-22 07:44:40.122  2750  3135 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1374195 -
06-22 07:44:40.142  5866  6493 D HtcModeClient: start the htcmodeservice thread
06-22 07:44:40.142  5866  6493 D HtcModeClient: initCanAgent
06-22 07:44:40.142  5866  6493 I CANMesgAgentLocalSocket: CANAgent Id = 0
06-22 07:44:40.152  5866  6493 D HtcModeClient: sense info: version = none, id = 2
06-22 07:44:40.152  5866  6493 D HtcModeClient: display info: width = 720, height = 1184
06-22 07:44:40.152  5866  6493 D HtcModeClient: display info: mode = 10
06-22 07:44:40.252  5866  5866 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = false
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: Force_AWAKE = false
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = true
06-22 07:44:40.252  5866  5866 D HtcModeClient: connectState: POWERCONNECTED_READY = true
06-22 07:44:40.582  6489  6489 E cutils-trace: Error opening trace file: No such file or directory (2)
06-22 07:44:40.592  6489  6489 W art     : 6f10f000-6ff31000 rw-p 00000000 103:0d 589826                            /data/dalvik-cache/arm64/system@framework@boot.art
06-22 07:44:40.592  6489  6489 W art     : 5572a21000-5572a26000 r-xp 00000000 103:0c 26                            /system/bin/app_process64
06-22 07:44:40.592  6489  6489 W art     : 5572a35000-5572a36000 r--p 00004000 103:0c 26                            /system/bin/app_process64
06-22 07:44:40.592  6489  6489 W art     : 5572a36000-5572a37000 rw-p 00005000 103:0c 26                            /system/bin/app_process64
06-22 07:44:40.592  6489  6489 W art     : 55a6d3d000-55a6d79000 rw-p 00000000 00:00 0                              [heap]
06-22 07:44:40.592  6489  6489 W art     : 7f87393000-7f89629000 r--p 00000000 103:0c 8544                          /system/framework/arm64/boot.oat
06-22 07:44:40.592  6489  6489 W art     : 7f89629000-7f8bb10000 r-xp 02296000 103:0c 8544                          /system/framework/arm64/boot.oat
06-22 07:44:40.592  6489  6489 W art     : 7f8bb10000-7f8bb11000 rw-p 0477d000 103:0c 8544                          /system/framework/arm64/boot.oat
06-22 07:44:40.592  6489  6489 W art     : 7f8bb11000-7f8bb3b000 r--p 00e22000 103:0d 589826                        /data/dalvik-cache/arm64/system@framework@boot.art
06-22 07:44:40.592  6489  6489 W art     : 7f8bb3b000-7f8bb3c000 r-xp 00000000 103:0c 188644                        /system/lib64/libsigchain.so
06-22 07:44:40.592  6489  6489 W art     : 7f8bb3c000-7f8bb4b000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8bb4b000-7f8bb4c000 r--p 00000000 103:0c 188644                        /system/lib64/libsigchain.so
06-22 07:44:40.592  6489  6489 W art     : 7f8bb4c000-7f8bb4d000 rw-p 00001000 103:0c 188644                        /system/lib64/libsigchain.so
06-22 07:44:40.592  6489  6489 W art     : 7f8bb4d000-7f8c13c000 r-xp 00000000 103:0c 188480                        /system/lib64/libart.so
06-22 07:44:40.592  6489  6489 W art     : 7f8c13c000-7f8c14b000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8c14b000-7f8c15e000 r--p 005f8000 103:0c 188480                        /system/lib64/libart.so
06-22 07:44:40.592  6489  6489 W art     : 7f8c15e000-7f8c160000 rw-p 0060b000 103:0c 188480                        /system/lib64/libart.so
06-22 07:44:40.592  6489  6489 W art     : 7f8c160000-7f8c163000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8c167000-7f8c16c000 r--p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8c16c000-7f8c18c000 r--s 00000000 00:0c 3769                           /dev/__properties__
06-22 07:44:40.592  6489  6489 W art     : 7f8c18c000-7f8c18d000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 07:44:40.592  6489  6489 W art     : 7f8c18d000-7f8c18e000 r--p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8c18e000-7f8c18f000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 07:44:40.592  6489  6489 W art     : 7f8c18f000-7f8d0a6000 r-xp 00000000 103:0c 188457                        /system/lib64/libLLVM.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d0a6000-7f8d0b6000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d0b6000-7f8d151000 r--p 00f24000 103:0c 188457                        /system/lib64/libLLVM.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d151000-7f8d155000 rw-p 00fbf000 103:0c 188457                        /system/lib64/libLLVM.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d155000-7f8d163000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d163000-7f8d1ae000 r-xp 00000000 103:0c 188473                        /system/lib64/libbcinfo.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d1ae000-7f8d1be000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d1be000-7f8d1bf000 r--p 0004b000 103:0c 188473                        /system/lib64/libbcinfo.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d1bf000-7f8d1c0000 rw-p 0004c000 103:0c 188473                        /system/lib64/libbcinfo.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d1c0000-7f8d221000 r-xp 00000000 103:0c 188500       
06-22 07:44:40.592  6489  6489 W art     :                  /system/lib64/libbcc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d221000-7f8d231000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d231000-7f8d233000 r--p 00062000 103:0c 188500                        /system/lib64/libbcc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d233000-7f8d234000 rw-p 00064000 103:0c 188500                        /system/lib64/libbcc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d234000-7f8d235000 r--p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d235000-7f8d236000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d236000-7f8d242000 r-xp 00000000 103:0c 188511                        /system/lib64/libcommon_time_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d242000-7f8d251000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d251000-7f8d255000 r--p 0000f000 103:0c 188511                        /system/lib64/libcommon_time_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d255000-7f8d256000 rw-p 00013000 103:0c 188511                        /system/lib64/libcommon_time_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d256000-7f8d279000 r-xp 00000000 103:0c 188751                        /system/lib64/libprotobuf-cpp-lite.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d279000-7f8d289000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d289000-7f8d28a000 r--p 00023000 103:0c 188751                        /system/lib64/libprotobuf-cpp-lite.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d28a000-7f8d28b000 rw-p 00024000 103:0c 188751                        /system/lib64/libprotobuf-cpp-lite.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d28b000-7f8d295000 r-xp 00000000 103:0c 188658                        /system/lib64/libstagefright_avc_common.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d295000-7f8d2a4000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d2a4000-7f8d2a5000 r--p 00009000 103:0c 188658                        /system/lib64/libstagefright_avc_common.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2a5000-7f8d2a6000 rw-p 0000a000 103:0c 188658                        /system/lib64/libstagefright_avc_common.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2a6000-7f8d2a7000 r-xp 00000000 103:0c 188659                        /system/lib64/libstagefright_enc_common.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2a7000-7f8d2b6000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d2b6000-7f8d2b7000 r--p 00000000 103:0c 188659                        /system/lib64/libstagefright_enc_common.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2b7000-7f8d2b8000 rw-p 00001000 103:0c 188659                        /system/lib64/libstagefright_enc_common.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2b8000-7f8d2bb000 r-xp 00000000 103:0c 188627                        /system/lib64/libpowermanager.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2bb000-7f8d2cb000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d2cb000-7f8d2cc000 r--p 00003000 103:0c 188627                        /system/lib64/libpowermanager.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2cc000-7f8d2cd000 rw-p 00004000 103:0c 188627                        /system/lib64/libpowermanager.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2cd000-7f8d2ea000 r-xp 00000000 103:0c 188705                        /system/lib64/libvorbisidec.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2ea000-7f8d2f9000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d2f9000-7f8d2fa000 r--p 0001c000 103:0c 188705                        /system/lib64/libvorbisidec.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2fa000-7f8d2fb000 rw-p 0001d000 103:0c 188705                        /system/lib64/libvorbisidec.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2fb000-7f8d2fe000 r-xp 00000000 103:0c 188682                        /system/lib64/libstagefright_yuv.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d2fe000-7f8d30e000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d30e000-7f8d30f000 r--p 00003000 103:0c 188682                        /system/lib64/libstagefright_yuv.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d30f000-7f8d310000 rw-p 00004000 103:0c 188682                        /system/lib64/libstagefright_yuv.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d310000-7f8d349000 r-xp 00000000 103:0c 188662                        /system/lib64/libstagefright_omx.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d349000-7f8d358000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d358000-7f8d35d000 r--p 0003e000 103:0c 188662                        /system/lib64/libstagefright_omx.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d35d000-7f8d35e000 rw-p 00043000 103:0c 188662                        /system/lib64/libstagefright_omx.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d35e000-7f8d35f000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d35f000-7f8d3aa000 r-xp 00000000 103:0c 188619                        /system/lib64/libopus.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3aa000-7f8d3ba000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d3ba000-7f8d3bb000 r--p 0004b000 103:0c 188619                        /system/lib64/libopus.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3bb000-7f8d3bc000 rw-p 0004c000 103:0c 188619                        /system/lib64/libopus.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3bc000-7f8d3c3000 r-xp 00000000 103:0c 188748                        /system/lib64/libmediautils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3c3000-7f8d3d2000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d3d2000-7f8d3d4000 r--p 00007000 103:0c 188748                        /system/lib64/libmediautils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3d4000-7f8d3d5000 rw-p 00009000 103:0c 188748                        /system/lib64/libmediautils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3d5000-7f8d3f3000 r-xp 00000000 103:0c 188524                        /system/lib64/libdrmframework.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d3f3000-7f8d403000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d403000-7f8d408000 r--p 00023000 103:0c 188524                        /system/lib64/libdrmframework.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d408000-7f8d409000 rw-p 00028000 103:0c 188524                        /system/lib64/libdrmframework.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d409000-7f8d433000 r-xp 00000000 103:0c 188471                        /system/lib64/libRScpp.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d433000-7f8d442000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d442000-7f8d443000 r--p 00029000 103:0c 188471                        /system/lib64/libRScpp.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d443000-7f8d444000 rw-p 0002a000 103:0c 188471                        /system/lib64/libRScpp.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d444000-7f8d445000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d445000-7f8d49a000 r-xp 00000000 103:0c 188469                        /system/lib64/libRS.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d49a000-7f8d4aa000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d4aa000-7f8d4ad000 r--p 00058000 103:0c 188469                        /system/lib64/libRS.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4ad000-7f8d4ae000 rw-p 0005b000 103:0c 188469                        /system/lib64/libRS.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4ae000-7f8d4af000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 07:44:40.592  6489  6489 W art     : 7f8d4af000-7f8d4b2000 r-xp 00000000 103:0c 188724                        /system/lib64/libspeexresampler.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4b2000-7f8d4c1000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d4c1000-7f8d4c2000 r--p 00002000 103:0c 188724                        /system/lib64/libspeexresampler.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4c2000-7f8d4c3000 rw-p 00003000 103:0c 188724                        /system/lib64/libspeexresampler.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4c3000-7f8d4cf000 r-xp 00000000 103:0c 188610                        /system/lib64/libnbaio.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4cf000-7f8d4df000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d4df000-7f8d4e0000 r--p 0000c000 103:0c 188610                        /system/lib64/libnbaio.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4e0000-7f8d4e1000 rw-p 0000d000 103:0c 188610                        /system/lib64/libnbaio.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4e1000-7f8d4fb000 r-xp 00000000 103:0c 188750                        /system/lib64/libpcre.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d4fb000-7f8d50a000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d50a000-7f8d50b000 r--p 00019000 103:0c 188750                        /system/lib64/libpcre.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d50b000-7f8d50c000 rw-p 0001a000 103:0c 188750                        /system/lib64/libpcre.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d50c000-7f8d50d000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d50d000-7f8d512000 r-xp 00000000 103:0c 188714                        /system/lib64/libwpa_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d512000-7f8d521000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d521000-7f8d522000 r--p 00004000 103:0c 188714                        /system/lib64/libwpa_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d522000-7f8d523000 rw-p 00005000 103:0c 188714                        /system/lib64/libwpa_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d523000-7f8d524000 rw-p 00000000 00:00 0                              [anon:linker_alloc_64]
06-22 07:44:40.592  6489  6489 W art     : 7f8d524000-7f8d532000 r-xp 00000000 103:0c 188566                        /system/lib64/libhostapd_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d532000-7f8d542000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d542000-7f8d543000 r--p 0000e000 103:0c 188566                        /system/lib64/libhostapd_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d543000-7f8d544000 rw-p 0000f000 103:0c 188566                        /system/lib64/libhostapd_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d544000-7f8d614000 r-xp 00000000 103:0c 188454                        /system/lib64/libGLES_trace.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d614000-7f8d623000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d623000-7f8d624000 r--p 000d2000 103:0c 188454                        /system/lib64/libGLES_trace.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d624000-7f8d626000 rw-p 000d3000 103:0c 188454                        /system/lib64/libGLES_trace.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d626000-7f8d68d000 r-xp 00000000 103:0c 188556                        /system/lib64/libft2.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d68d000-7f8d69d000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d69d000-7f8d6a0000 r--p 00069000 103:0c 188556                        /system/lib64/libft2.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6a0000-7f8d6a1000 rw-p 0006c000 103:0c 188556                        /system/lib64/libft2.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6a1000-7f8d6d6000 r-xp 00000000 103:0c 188624                        /system/lib64/libpng.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6d6000-7f8d6e6000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d6e6000-7f8d6e7000 r--p 00035000 103:0c 188624                        /system/lib64/libpng.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6e7000-7f8d6e8000 rw-p 00036000 103:0c 188624                        /system/lib64/libpng.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6e8000-7f8d6e9000 r-xp 00000000 103:0c 188689                        /system/lib64/libsync.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6e9000-7f8d6f8000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d6f8000-7f8d6f9000 r--p 00000000 103:0c 188689                        /system/lib64/libsync.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6f9000-7f8d6fa000 rw-p 00001000 103:0c 188689                        /system/lib64/libsync.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6fa000-7f8d6fb000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d6fb000-7f8d6fe000 r-xp 00000000 103:0c 188684                        /system/lib64/libstdc++.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d6fe000-7f8d70d000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d70d000-7f8d70e000 r--p 00002000 103:0c 188684                        /system/lib64/libstdc++.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d70e000-7f8d70f000 rw-p 00003000 103:0c 188684                        /system/lib64/libstdc++.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d70f000-7f8d72a000 r-xp 00000000 103:0c 188698                        /system/lib64/libunwind.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d72a000-7f8d739000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d739000-7f8d73a000 r--p 0001a000 103:0c 188698                        /system/lib64/libunwind.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d73a000-7f8d73b000 rw-p 0001b000 103:0c 188698                        /system/lib64/libunwind.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d73b000-7f8d7a4000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d7a4000-7f8d7a5000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d7a5000-7f8d7ae000 r-xp 00000000 103:0c 188738                        /system/lib64/libbase.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7ae000-7f8d7bd000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d7bd000-7f8d7be000 r--p 00008000 103:0c 188738                        /system/lib64/libbase.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7be000-7f8d7bf000 rw-p 00009000 103:0c 188738                        /system/lib64/libbase.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7bf000-7f8d7c4000 r-xp 00000000 103:0c 188548           
06-22 07:44:40.592  6489  6489 W art     :              /system/lib64/libeffects.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7c4000-7f8d7d3000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d7d3000-7f8d7d4000 r--p 00004000 103:0c 188548                        /system/lib64/libeffects.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7d4000-7f8d7d5000 rw-p 00005000 103:0c 188548                        /system/lib64/libeffects.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7d5000-7f8d7d6000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8d7d6000-7f8d7d8000 r-xp 00000000 103:0c 188661                        /system/lib64/libstagefright_http_support.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7d8000-7f8d7e7000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d7e7000-7f8d7e8000 r--p 00001000 103:0c 188661                        /system/lib64/libsta
06-22 07:44:40.592  6489  6489 W art     : gefright_http_support.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7e8000-7f8d7e9000 rw-p 00002000 103:0c 188661                        /system/lib64/libstagefright_http_support.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d7e9000-7f8d809000 r-xp 00000000 103:0c 188660                        /system/lib64/libstagefright_foundation.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d809000-7f8d818000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8d818000-7f8d81b000 r--p 00020000 103:0c 188660                        /system/lib64/libstagefright_foundation.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d81b000-7f8d81c000 rw-p 00023000 103:0c 188660                        /system/lib64/libstagefright_foundation.so
06-22 07:44:40.592  6489  6489 W art     : 7f8d81c000-7f8da43000 r-xp 00000000 103:0c 188625                        /system/lib64/libstagefright.so
06-22 07:44:40.592  6489  6489 W art     : 7f8da43000-7f8da53000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8da53000-7f8da6a000 r--p 00227000 103:0c 188625                        /system/lib64/libstagefright.so
06-22 07:44:40.592  6489  6489 W art     : 7f8da6a000-7f8da6b000 rw-p 0023e000 103:0c 188625                        /system/lib64/libstagefright.so
06-22 07:44:40.592  6489  6489 W art     : 7f8da6b000-7f8da6e000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8da6e000-7f8db06000 r-xp 00000000 103:0c 188575                        /system/lib64/libhwui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db06000-7f8db15000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8db15000-7f8db1b000 r--p 0009e000 103:0c 188575                        /system/lib64/libhwui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db1b000-7f8db1c000 rw-p 000a4000 103:0c 188575                        /system/lib64/libhwui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db1c000-7f8db1d000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8db1d000-7f8db1f000 r-xp 00000000 103:0c 188754                        /system/lib64/libradio_metadata.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db1f000-7f8db2e000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8db2e000-7f8db2f000 r--p 00001000 103:0c 188754                        /system/lib64/libradio_metadata.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db2f000-7f8db30000 rw-p 00002000 103:0c 188754                        /system/lib64/libradio_metadata.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db30000-7f8db33000 r-xp 00000000 103:0c 188609                        /system/lib64/libnativebridge.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db33000-7f8db42000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8db42000-7f8db44000 r--p 00002000 103:0c 188609                        /system/lib64/libnativebridge.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db44000-7f8db45000 rw-p 00004000 103:0c 188609                        /system/lib64/libnativebridge.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db45000-7f8db47000 r-xp 00000000 103:0c 188629                        /system/lib64/libprocessgroup.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db47000-7f8db56000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8db56000-7f8db57000 r--p 00001000 103:0c 188629                        /system/lib64/libprocessgroup.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db57000-7f8db58000 rw-p 00002000 103:0c 188629                        /system/lib64/libprocessgroup.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db58000-7f8db6d000 r-xp 00000000 103:0c 188604                        /system/lib64/libminikin.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db6d000-7f8db7d000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8db7d000-7f8db7e000 r--p 00015000 103:0c 188604                        /system/lib64/libminikin.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db7e000-7f8db7f000 rw-p 00016000 103:0c 188604                        /system/lib64/libminikin.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db7f000-7f8db89000 r-xp 00000000 103:0c 188650                        /system/lib64/libsoundtrigger.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db89000-7f8db98000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8db98000-7f8db9c000 r--p 0000d000 103:0c 188650                        /system/lib64/libsoundtrigger.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db9c000-7f8db9d000 rw-p 00011000 103:0c 188650                        /system/lib64/libsoundtrigger.so
06-22 07:44:40.592  6489  6489 W art     : 7f8db9d000-7f8dba7000 r-xp 00000000 103:0c 188753                        /system/lib64/libradio.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dba7000-7f8dbb7000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8dbb7000-7f8dbbb000 r--p 0000e000 103:0c 188753                        /system/lib64/libradio.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbbb000-7f8dbbc000 rw-p 00012000 103:0c 188753                        /system/lib64/libradio.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbbc000-7f8dbbe000 r-xp 00000000 103:0c 188612                        /system/lib64/libnetd_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbbe000-7f8dbcd000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8dbcd000-7f8dbce000 r--p 00001000 103:0c 188612                        /system/lib64/libnetd_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbce000-7f8dbcf000 rw-p 00002000 103:0c 188612                        /system/lib64/libnetd_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbcf000-7f8dbe2000 r-xp 00000000 103:0c 188578                        /system/lib64/libimg_utils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbe2000-7f8dbf1000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8dbf1000-7f8dbf4000 r--p 00013000 103:0c 188578                        /system/lib64/libimg_utils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbf4000-7f8dbf5000 rw-p 00016000 103:0c 188578                        /system/lib64/libimg_utils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8dbf5000-7f8e019000 r-xp 00000000 103:0c 188723                        /system/lib64/libpdfium.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e019000-7f8e028000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e028000-7f8e039000 r--p 00428000 103:0c 188723                        /system/lib64/libpdfium.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e039000-7f8e03e000 rw-p 00439000 103:0c 188723                        /system/lib64/libpdfium.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e03e000-7f8e03f000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e03f000-7f8e04a000 r-xp 00000000 103:0c 188488                        /system/lib64/libaudioutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e04a000-7f8e059000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e059000-7f8e05a000 r--p 0000a000 103:0c 188488                        /system/lib64/libaudioutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e05a000-7f8e05b000 rw-p 0000b000 103:0c 188488                        /system/lib64/libaudioutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e05b000-7f8e05c000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8e05c000-7f8e078000 r-xp 00000000 103:0c 188716                        /system/lib64/libz.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e078000-7f8e087000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e087000-7f8e088000 r--p 0001b000 103:0c 188716                        /system/lib64/libz.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e088000-7f8e089000 rw-p 0001c000 103:0c 188716                        /system/lib64/libz.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e089000-7f8e0f6000 r-xp 00000000 103:0c 188564                        /system/lib64/libharfbuzz_ng.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e0f6000-7f8e105000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e105000-7f8e107000 r--p 0006c000 103:0c 188564                        /system/lib64/libharfbuzz_ng.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e107000-7f8e108000 rw-p 0006e000 103:0c 188564                        /system/lib64/libharfbuzz_ng.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e108000-7f8e10c000 r-xp 00000000 103:0c 188727                        /system/lib64/libusbhost.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e10c000-7f8e11b000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e11b000-7f8e11c000 r--p 00003000 103:0c 188727                        /system/lib64/libusbhost.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e11c000-7f8e11d000 rw-p 00004000 103:0c 188727                        /system/lib64/libusbhost.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e11d000-7f8e11e000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8e11e000-7f8e154000 r-xp 00000000 103:0c 188590                        /system/lib64/libjpeg.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e154000-7f8e164000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e164000-7f8e165000 r--p 00036000 103:0c 188590                        /system/lib64/libjpeg.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e165000-7f8e166000 rw-p 00037000 103:0c 188590                        /system/lib64/libjpeg.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e166000-7f8e235000 r-xp 00000000 103:0c 188551                        /system/lib64/libmedia.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e235000-7f8e244000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e244000-7f8e279000 r--p 000d7000 103:0c 188551                        /system/lib64/libmedia.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e279000-7f8e27a000 rw-p 0010c000 103:0c 188551                        /system/lib64/libmedia.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e27a000-7f8e496000 r-xp 00000000 103:0c 188576                        /system/lib64/libicui18n.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e496000-7f8e4a6000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e4a6000-7f8e4ba000 r--p 00226000 103:0c 188576                        /system/lib64/libicui18n.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e4ba000-7f8e4bb000 rw-p 0023a000 103:0c 188576                        /system/lib64/libicui18n.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e4bb000-7f8e63f000 r-xp 00000000 103:0c 188577                        /system/lib64/libicuuc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e63f000-7f8e64e000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e64e000-7f8e660000 r--p 0018c000 103:0c 188577                        /system/lib64/libicuuc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e660000-7f8e661000 rw-p 0019e000 103:0c 188577                        /system/lib64/libicuuc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e661000-7f8e665000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e665000-7f8e69f000 r-xp 00000000 103:0c 188655                        /system/lib64/libssl.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e69f000-7f8e6af000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e6af000-7f8e6b1000 r--p 0003a000 103:0c 188655                        /system/lib64/libssl.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e6b1000-7f8e6b2000 rw-p 0003c000 103:0c 188655                        /system/lib64/libssl.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e6b2000-7f8e6b3000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8e6b3000-7f8e7b5000 r-xp 00000000 103:0c 188513                        /system/lib64/libcrypto.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e7b5000-7f8e7c4000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e7c4000-7f8e7d8000 r--p 00101000 103:0c 188513                        /system/lib64/libcrypto.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e7d8000-7f8e7d9000 rw-p 00115000 103:0c 188513                        /system/lib64/libcrypto.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e7d9000-7f8e831000 r-xp 00000000 103:0c 188648                        /system/lib64/libsonivox.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e831000-7f8e841000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e841000-7f8e842000 r--p 00058000 103:0c 188648                        /system/lib64/libsonivox.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e842000-7f8e843000 rw-p 00059000 103:0c 188648                        /system/lib64/libsonivox.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e843000-7f8e844000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e844000-7f8e859000 r-xp 00000000 103:0c 188641                        /system/lib64/libselinux.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e859000-7f8e869000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e869000-7f8e86a000 r--p 00015000 103:0c 188641                        /system/lib64/libselinux.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e86a000-7f8e86b000 rw-p 00016000 103:0c 188641                        /system/lib64/libselinux.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e86b000-7f8e86c000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e86c000-7f8e877000 r-xp 00000000 103:0c 188563                        /system/lib64/libhardware_legacy.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e877000-7f8e886000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e886000-7f8e887000 r--p 0000a000 103:0c 188563                        /system/lib64/libhardware_legacy.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e887000-7f8e888000 rw-p 0000b000 103:0c 188563                        /system/lib64/libhardware_legacy.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e888000-7f8e889000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e889000-7f8e88b000 r-xp 00000000 103:0c 188562                        /system/lib64/libhardware.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e88b000-7f8e89a000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e89a000-7f8e89b000 r--p 00001000 103:0c 188562                        /system/lib64/libhardware.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e89b000-7f8e89c000 rw-p 00002000 103:0c 188562                        /system/lib64/libhardware.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e89c000-7f8e89f000 r-xp 00000000 103:0c 188452                        /system/lib64/libETC1.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e89f000-7f8e8af000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e8af000-7f8e8b0000 r--p 00003000 103:0c 188452                        /system/lib64/libETC1.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8b0000-7f8e8b1000 rw-p 00004000 103:0c 188452                        /system/lib64/libETC1.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8b1000-7f8e8c1000 r-xp 00000000 103:0c 188456                        /system/lib64/libGLESv2.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8c1000-7f8e8d0000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e8d0000-7f8e8d1000 r--p 0000f000 103:0c 188456                        /system/lib64/libGLESv2.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8d1000-7f8e8d2000 rw-p 00010000 103:0c 188456                        /system/lib64/libGLESv2.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8d2000-7f8e8db000 r-xp 00000000 103:0c 188455                        /system/lib64/libGLESv1_CM.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8db000-7f8e8ea000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e8ea000-7f8e8eb000 r--p 00008000 103:0c 188455                        /system/lib64/libGLESv1_CM.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8eb000-7f8e8ec000 rw-p 00009000 103:0c 188455                        /system/lib64/libGLESv1_CM.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e8ec000-7f8e8ed000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8e8ed000-7f8e9c0000 r-xp 00000000 103:0c 188451                        /system/lib64/libEGL.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e9c0000-7f8e9cf000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e9cf000-7f8e9d3000 r--p 000db000 103:0c 188451                        /system/lib64/libEGL.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e9d3000-7f8e9df000 rw-p 000df000 103:0c 188451                        /system/lib64/libEGL.so
06-22 07:44:40.592  6489  6489 W art     : 7f8e9df000-7f8e9e5000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8e9e5000-7f8eaa0000 r-xp 00000000 103:0c 188653                        /system/lib64/libsqlite.so
06-22 07:44:40.592  6489  6489 W art     : 7f8eaa0000-7f8eab0000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8eab0000-7f8eab2000 r--p 000be000 103:0c 188653                        /system/lib64/libsqlite.so
06-22 07:44:40.592  6489  6489 W art     : 7f8eab2000-7f8eab4000 rw-p 000c0000 103:0c 188653                        /system/lib64/libsqlite.so
06-22 07:44:40.592  6489  6489 W art     : 7f8eab4000-7f8eab5000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8eab5000-7f8ef57000 r-xp 00000000 103:0c 188645                        /system/lib64/libskia.so
06-22 07:44:40.592  6489  6489 W art     : 7f8ef57000-7f8ef66000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8ef66000-7f8ef97000 r--p 004a2000 103:0c 188645                        /system/lib64/libskia.so
06-22 07:44:40.592  6489  6489 W art     : 7f8ef97000-7f8ef99000 rw-p 004d3000 103:0c 188645                        /system/lib64/libskia.so
06-22 07:44:40.592  6489  6489 W art     : 7f8ef99000-7f8efa2000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8efa2000-7f8efa3000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8efa3000-7f8efab000 r-xp 00000000 103:0c 188505                        /system/lib64/libcamera_metadata.so
06-22 07:44:40.592  6489  6489 W art     : 7f8efab000-7f8efba000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8efba000-7f8efbb000 r--p 00008000 103:0c 188505                        /system/lib64/libcamera_metad
06-22 07:44:40.592  6489  6489 W art     : ata.so
06-22 07:44:40.592  6489  6489 W art     : 7f8efbb000-7f8efbd000 rw-p 00009000 103:0c 188505                        /system/lib64/libcamera_metadata.so
06-22 07:44:40.592  6489  6489 W art     : 7f8efbd000-7f8effd000 r-xp 00000000 103:0c 188504                        /system/lib64/libcamera_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8effd000-7f8f00c000 ---p 00000000 00:0
06-22 07:44:40.592  6489  6489 W art     : 0 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f00c000-7f8f017000 r--p 0004c000 103:0c 188504                        /system/lib64/libcamera_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f017000-7f8f018000 rw-p 00057000 103:0c 188504                        /system/lib64/libcamera_client.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f018000-7f8f074000 r-xp 00000000 103:0c
06-22 07:44:40.592  6489  6489 W art     :  188582                        /system/lib64/libinputflinger.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f074000-7f8f078000 r--p 00060000 103:0c 188582                        /system/lib64/libinputflinger.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f078000-7f8f079000 rw-p 00064000 103:0c 188582                        /system/lib64/libinputflinger.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f079000-7f8f09e000 r-xp 00000000 103:0c 188579                        /system/lib64/libinput.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f09e000-7f8f0ae000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f0ae000-7f8f0b5000 r--p 0002b000 103:0c 188579                        /system/lib64/libinput.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f0b5000-7f8f0b6000 rw-p 00032000 103:0c 188579                        /system/lib64/libinput.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f0b6000-7f8f11f000 r-xp 00000000 103:0c 188561                        /system/lib64/libgui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f11f000-7f8f12e000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f12e000-7f8f144000 r--p 0006a000 103:0c 188561                        /system/lib64/libgui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f144000-7f8f145000 rw-p 00080000 103:0c 188561                        /system/lib64/libgui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f145000-7f8f146000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8f146000-7f8f158000 r-xp 00000000 103:0c 188697                        /system/lib64/libui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f158000-7f8f167000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f167000-7f8f168000 r--p 00011000 103:0c 188697                        /system/lib64/libui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f168000-7f8f169000 rw-p 00012000 103:0c 188697                        /system/lib64/libui.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f169000-7f8f171000 r-xp 00000000 103:0c 188615                        /system/lib64/libnetutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f171000-7f8f180000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f180000-7f8f181000 r--p 00007000 103:0c 188615                        /system/lib64/libnetutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f181000-7f8f182000 rw-p 00008000 103:0c 188615                        /system/lib64/libnetutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f182000-7f8f189000 r-xp 00000000 103:0c 188599                        /system/lib64/libnativehelper.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f189000-7f8f198000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f198000-7f8f199000 r--p 00006000 103:0c 188599                        /system/lib64/libnativehelper.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f199000-7f8f19a000 rw-p 00007000 103:0c 188599                        /system/lib64/libnativehelper.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f19a000-7f8f1bb000 r-xp 00000000 103:0c 188514                        /system/lib64/libexpat.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f1bb000-7f8f1cb000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f1c
06-22 07:44:40.592  6489  6489 W art     : b000-7f8f1cd000 r--p 00021000 103:0c 188514                        /system/lib64/libexpat.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f1cd000-7f8f1ce000 rw-p 00023000 103:0c 188514                        /system/lib64/libexpat.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f1ce000-7f8f20c000 r-xp 00000000 103:0c 188477                        /system/lib64/libandroidfw.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f20c000-7f8f21c000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f21c000-7f8f21e000 r--p 0003f000 103:0c 188477                        /system/lib64/libandroidfw.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f21e000-7f8f21f000 rw-p 00041000 103:0c 188477                        /system/lib64/libandroidfw.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f21f000-7f8f220000 r-xp 00000000 103:0c 188603                        /system/lib64/libmemtrack.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f220000-7f8f230000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f230000-7f8f231000 r--p 00001000 103:0c 188603                        /system/lib64/libmemtrack.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f231000-7f8f232000 rw-p 00002000 103:0c 188603                        /system/lib64/libmemtrack.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f232000-7f8f23d000 r-xp 00000000 103:0c 188490                        /system/lib64/libbacktrace.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f23d000-7f8f24d000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f24d000-7f8f24e000 r--p 0000b000 103:0c 188490                        /system/lib64/libbacktrace.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f24e000-7f8f24f000 rw-p 0000c000 103:0c 188490                        /system/lib64/libbacktrace.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f24f000-7f8f287000 r-xp 00000000 103:0c 188719                        /system/lib64/libm.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f287000-7f8f297000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f297000-7f8f298000 r--p 00038000 103:0c 188719                        /system/lib64/libm.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f298000-7f8f299000 rw-p 00039000 103:0c 188719                        /system/lib64/libm.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f299000-7f8f32f000 r-xp 00000000 103:0c 188494                        /system/lib64/libc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f32f000-7f8f33e000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f33e000-7f8f343000 r--p 00095000 103:0c 188494                        /system/lib64/libc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f343000-7f8f346000 rw-p 0009a000 103:0c 188494                        /system/lib64/libc.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f346000-7f8f354000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f354000-7f8f42b000 r-xp 00000000 103:0c 188496                        /system/lib64/libc++.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f42b000-7f8f43a000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f43a000-7f8f441000 r--p 000df000 103:0c 188496                        /system/lib64/libc++.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f441000-7f8f442000 rw-p 000e6000 103:0c 188496                        /system/lib64/libc++.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f442000-7f8f445000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f445000-7f8f481000 r-xp 00000000 103:0c 188712                        /system/lib64/libwilhelm.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f481000-7f8f491000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f491000-7f8f496000 r--p 00041000 103:0c 188712                        /system/lib64/libwilhelm.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f496000-7f8f497000 rw-p 00046000 103:0c 188712                        /system/lib64/libwilhelm.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f497000-7f8f5fa000 r-xp 00000000 103:0c 188474                        /system/lib64/libandroid_runtime.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f5fa000-7f8f609000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f609000-7f8f614000 r--p 0016f000 103:0c 188474                        /system/lib64/libandroid_runtime.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f614000-7f8f623000 rw-p 0017a000 103:0c 188474                        /system/lib64/libandroid_runtime.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f623000-7f8f625000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f625000-7f8f65d000 r-xp 00000000 103:0c 188493                        /system/lib64/libbinder.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f65d000-7f8f66c000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f66c000-7f8f678000 r--p 00044000 103:0c 188493                        /system/lib64/libbinder.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f678000-7f8f679000 rw-p 00050000 103:0c 188493                        /system/lib64/libbinder.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f679000-7f8f682000 r-xp 00000000 103:0c 188596                        /system/lib64/liblog.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f682000-7f8f691000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f691000-7f8f692000 r--p 00008000 103:0c 188596                        /system/lib64/liblog.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f692000-7f8f693000 rw-p 00009000 103:0c 188596                        /system/lib64/liblog.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f693000-7f8f6bb000 r-xp 00000000 103:0c 188702                        /system/lib64/libutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f6bb000-7f8f6ca000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f6ca000-7f8f6cc000 r--p 00028000 103:0c 188702                        /system/lib64/libutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f6cc000-7f8f6cd000 rw-p 0002a000 103:0c 188702                        /system/lib64/libutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f6cd000-7f8f6e3000 r-xp 00000000 103:0c 188517                        /system/lib64/libcutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f6e3000-7f8f6f3000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f6f3000-7f8f6f4000 r--p 00016000 103:0c 188517                        /system/lib64/libcutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f6f4000-7f8f6f5000 rw-p 00017000 103:0c 188517                        /system/lib64/libcutils.so
06-22 07:44:40.592  6489  6489 W art     : 7f8f6f5000-7f8f6f6000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 07:44:40.592  6489  6489 W art     : 7f8f6f6000-7f8f6f9000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8f6f9000-7f8f6fa000 rw-p 00000000 00:00 0                              [anon:linker_alloc_64]
06-22 07:44:40.592  6489  6489 W art     : 7f8f6fa000-7f8f6fc000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8f6fc000-7f8f6fd000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8f6fd000-7f8f6fe000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 07:44:40.592  6489  6489 W art     : 7f8f6fe000-7f8f71e000 r--s 00000000 00:0c 3769                           /dev/__properties__
06-22 07:44:40.592  6489  6489 W art     : 7f8f71e000-7f8f71f000 r--p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f71f000-7f8f720000 ---p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7f8f720000-7f8f724000 rw-p 00000000 00:00 0                              [anon:thread signal stack]
06-22 07:44:40.592  6489  6489 W art     : 7f8f724000-7f8f726000 r-xp 00000000 00:00 0                              [vdso]
06-22 07:44:40.592  6489  6489 W art     : 7f8f726000-7f8f756000 r-xp 00000000 103:0c 65                            /system/bin/linker64
06-22 07:44:40.592  6489  6489 W art     : 7f8f756000-7f8f757000 r--p 00030000 103:0c 65                            /system/bin/linker64
06-22 07:44:40.592  6489  6489 W art     : 7f8f757000-7f8f759000 rw-p 00031000 103:0c 65                            /system/bin/linker64
06-22 07:44:40.592  6489  6489 W art     : 7f8f759000-7f8f75d000 rw-p 00000000 00:00 0 
06-22 07:44:40.592  6489  6489 W art     : 7ff0f78000-7ff0f99000 rw-p 00000000 00:00 0                              [stack]
06-22 07:44:40.602  6489  6489 I art     : buildType: user, roAaReport: com, roSf: 1
06-22 07:44:40.672  6489  6489 D CustomizationManager: ====startRecUseTime====
06-22 07:44:40.672  6489  6489 D htc.customization.log.level:  is 
06-22 07:44:40.682  6489  6489 W CustomizationLogLevel: Level value is invalid, use default level 2
06-22 07:44:40.742  6489  6489 D CustomizationManager:  Read ACC file spent 0.029 (s)
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__001
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__102
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__032
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__016
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__002
06-22 07:44:40.742  6489  6489 D CIDMapFileReader: Parsing tag item name = HTC__031
06-22 07:44:40.742  6489  6489 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-22 07:44:40.742  6489  6489 I CustomizationCIDLoader: Parsing tag category name = system
06-22 07:44:40.742  6489  6489 I CustomizationCIDLoader: Parsing tag category name = application
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: Parsing tag category name = ACC
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 42507
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 21902
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23420
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 22299
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 24002
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23210
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23205
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23806
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23430
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23408
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27205
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27202:27205
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23203
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23207
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23001
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 26201
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 20201
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 20416
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 26002
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310160
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310200
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310210
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310220
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310230
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310240
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310250
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310260
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310270
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310300
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310310
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310490
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310530
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310580
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310590
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310640
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310660
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 310800
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 22801
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 20810
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 26202
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 20205
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 22210
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 20404
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 26801
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 21401
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 21418
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 23415
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 27201
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 22610
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 21404
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = 22201
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: add string-array item, value = FreeWifi_secure
06-22 07:44:40.752  6489  6489 I CustomizationCIDLoader: Parsing tag category name = Settings
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 234
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 272
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 23594
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 204
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 206
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 270
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 262
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 232
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 228
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20810
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20801
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name, = 20820
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20815
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20823
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20826
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64700
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64710
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 34001
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 22201
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 22210
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 22299
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 22288
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 238
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 240
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 242
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 214
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 268
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 280
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20210
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20209
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20205
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 20201
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 250
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25012
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25007
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25017
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 28301
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 28310
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 28305
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 40102
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 40101
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25020
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25002
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25099
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25001
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25011
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 28310
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25701
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25702
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 40101
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 40102
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 28305
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 28301
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 25039
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 218
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 278
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 297
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 294
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 276
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 257
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 420
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 415
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 416
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 417
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 418
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 419
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 421
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 422
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 424
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 426
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 427
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 432
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 602
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 603
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 604
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 605
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 606
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 612
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 617
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 620
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 621
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 624
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 628
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 630
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 631
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 639
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 640
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 641
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 655
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 659
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 286
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 255
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 425
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 260
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 248
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 226
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 259
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 293
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 220
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 219
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 284
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 230
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 231
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 216
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 246
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 247
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65501
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63102
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61603
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61605
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65201
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65202
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62401
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62402
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63901
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63002
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63089
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62803
06-22 07:44:40.752  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63902
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63903
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63905
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65101
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64601
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64602
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64603
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65001
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65010
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61701
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61710
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64301
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64304
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64901
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64903
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62120
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62130
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62150
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62160
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62901
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62907
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62910
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63510
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63513
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63301
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63401
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 63402
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65310
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64002
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64003
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64004
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64005
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64101
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64110
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64111
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64122
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64501
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64502
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 64804
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62001
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62002
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 62003
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61202
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61203
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61203
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61204
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61205
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61206
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61701
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 61710
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65510
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65502
06-22 07:44:40.762  6489  6489 D MNSMapFileLoader: Parsing tag item name = 65507
06-22 07:44:40.762  6489  6489 E BaseLoader: parseConfig error:java.io.FileNotFoundException: /system/customize/spn_map.xml: open failed: ENOENT (No such file or directory)
06-22 07:44:40.762  6489  6489 E BaseLoader: parseConfig error:java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
06-22 07:44:40.762  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/250.xml
06-22 07:44:40.762  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.762  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.782  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.782  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.782  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/420.xml
06-22 07:44:40.782  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.782  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.792  5259  5717 D osz     : Package com.test.thalitest's hash: c54b0979c92367c90c11058a0bc3a47f427c6241204b15c1acc95cf19a856617
06-22 07:44:40.792  5259  5717 D osq     : Look up (com.test.thalitest:19) returned no result
06-22 07:44:40.792  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.802  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.802  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/65501.xml
06-22 07:44:40.802  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.802  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.812  5259  5717 D osz     : Saved the app info in cache for package:com.test.thalitest.
06-22 07:44:40.812  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.812  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.812  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/240.xml
06-22 07:44:40.812  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.812  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.832  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.832  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.832  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/20810.xml
06-22 07:44:40.832  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.832  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.842  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.842  6489  6501 D CustomizationMNSLoader: Parsing tag category name = CustomAppInstaller
06-22 07:44:40.842  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.842  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/268.xml
06-22 07:44:40.842  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.852  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.852  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.852  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.862  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/238.xml
06-22 07:44:40.862  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.862  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.872  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.872  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.872  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/260.xml
06-22 07:44:40.872  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.872  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.882  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.882  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.882  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/218.xml
06-22 07:44:40.882  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.892  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.892  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.892  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.892  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/206.xml
06-22 07:44:40.902  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.902  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.902  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.902  6489  6501 D CustomizationMNSLoader: Parsing tag category name = CustomAppInstaller
06-22 07:44:40.902  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.902  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/22201.xml
06-22 07:44:40.912  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.912  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.912  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.912  6489  6501 D CustomizationMNSLoader: Parsing tag category name = CustomAppInstaller
06-22 07:44:40.922  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.922  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/231.xml
06-22 07:44:40.922  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.922  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/219.xml
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.932  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.942  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/226.xml
06-22 07:44:40.942  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.942  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.942  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.942  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.952  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/248.xml
06-22 07:44:40.952  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.952  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.952  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.952  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/204.xml
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: Parsing tag category name = CustomAppInstaller
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.962  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/247.xml
06-22 07:44:40.972  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.972  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.972  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.972  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.972  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/234.xml
06-22 07:44:40.972  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.982  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.982  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.982  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.982  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/246.xml
06-22 07:44:40.982  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.982  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:40.992  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:40.992  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:40.992  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/20201.xml
06-22 07:44:40.992  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:40.992  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.002  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.002  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.002  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/262.xml
06-22 07:44:41.002  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.002  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.002  6440  6475 W linker  : /data/app/com.google.android.gms-2/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
06-22 07:44:41.012  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.012  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.012  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/228.xml
06-22 07:44:41.012  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.012  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.022  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.022  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.022  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/20210.xml
06-22 07:44:41.022  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.022  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.032  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.032  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.032  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/242.xml
06-22 07:44:41.032  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.032  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.042  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.042  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.042  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/284.xml
06-22 07:44:41.042  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.042  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.052  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.052  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.052  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/20205.xml
06-22 07:44:41.052  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.052  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.062  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.062  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.062  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/280.xml
06-22 07:44:41.062  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.062  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.072  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.072  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.072  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/220.xml
06-22 07:44:41.072  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.072  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/286.xml
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.082  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.092  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/230.xml
06-22 07:44:41.092  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.092  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.092  6440  6475 W linker  : /data/app/com.google.android.gms-2/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-22 07:44:41.092  6440  6475 W linker  : /data/app/com.google.android.gms-2/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x176
06-22 07:44:41.092  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.092  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.092  6440  6475 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
06-22 07:44:41.102  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/216.xml
06-22 07:44:41.102  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.102  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.102  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.102  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.112  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/22288.xml
06-22 07:44:41.112  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.112  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.112  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.112  6489  6501 D CustomizationMNSLoader: Parsing tag category name = CustomAppInstaller
06-22 07:44:41.112  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.122  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/293.xml
06-22 07:44:41.122  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.122  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.122  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.122  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.122  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/425.xml
06-22 07:44:41.132  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.132  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.132  5259  5717 I Icing   : Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
06-22 07:44:41.142  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.142  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.142  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/255.xml
06-22 07:44:41.142  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.142  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.142  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/214.xml
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: Parsing tag category name = CustomAppInstaller
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.152  6489  6501 D CustomizationMNSLoader: full path : /system/customize/MNS/232.xml
06-22 07:44:41.162  6489  6501 D CustomizationMNSLoader: Parsing tag category name = system
06-22 07:44:41.162  6489  6501 D CustomizationMNSLoader: Parsing tag category name = application
06-22 07:44:41.162  6489  6501 D CustomizationMNSLoader: Parsing tag category name = ulog_policy
06-22 07:44:41.162  6489  6501 D CustomizationMNSLoader: Parsing tag category name = force_change
06-22 07:44:41.192  6440  6475 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:44:41.202  1614  2877 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6489 on display 0
06-22 07:44:41.202  1614  1856 D PMS     : acquireHCC(7a1794c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1614 1000 null
06-22 07:44:41.202  1614  1856 D PMS     : acquireHCC(f7dfd95): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1614 1000 null
06-22 07:44:41.232  5259  5717 I Icing   : Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
06-22 07:44:41.232  1614  2877 V BoostFramework: BoostFramework() : mPerf = com.qualcomm.qti.Performance@312de38
06-22 07:44:41.232  1614  2877 I ActivityManager: Start proc 6507:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-22 07:44:41.232  1614  1843 D StatusBarManagerService: setSystemUiVisibility(0x80008700)
06-22 07:44:41.232  2401  2401 I PhoneStatusBar: setSystemUiVisibility vis=80008700 mask=ffffffff oldVal=80008000 newVal=80008700 diff=700
06-22 07:44:41.232  1614  1843 D StatusBarManagerService: disable:userId=0 what=0x0 which=0x1 pkg=Window{cdce1bd u0 com.htc.launcher/com.htc.launcher.Launcher}
06-22 07:44:41.232  2401  2401 I PhoneStatusBar: updatePolicy(false,false,false,true)
06-22 07:44:41.232  1614  1843 D StatusBarManagerService: hiding MENU key
06-22 07:44:41.232  2401  2401 I PhoneStatusBar: hiding the MENU button
06-22 07:44:41.252  1614  2877 D PMS     : releaseWL(58dc4c6): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
06-22 07:44:41.252  1614  1850 E HtcMirrorLinkAmsListener: onHandleTopAppChanged, process data is invalid
06-22 07:44:41.272  2594  2594 D DotMatrix: [EventService]  onDisplayChanged: 0
06-22 07:44:41.272  1614  1614 D DeviceIdleController: updateDisplayLocked: screenOn=false
06-22 07:44:41.272  2594  2594 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
06-22 07:44:41.282  1614  1850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:786 com.htc.server.HtcMirrorLinkAmsListener.onHandleTopAppChanged:122 com.android.server.am.HtcAmsCallbackManager.handleTopAppChanged:933 com.android.server.am.HtcAmsCallbackManager.handleAmsCallback:358 com.android.server.am.HtcAmsCallbackManager.access$100:27 
06-22 07:44:41.282  1614  2756 D ActivityManager: screenshot for ActivityRecord{2268eaa u0 com.test.thalitest/.MainActivity t34}, bitmap=null, time = 0
06-22 07:44:41.282  1614  1850 D HtcMirrorLinkAmsListener: onHandleTopAppChanged, sendBroadcast : com.test.thalitest
06-22 07:44:41.302  2750  2750 I TrimMemoryManager: [trimMemory] 20
06-22 07:44:41.332  6507  6507 I WebViewFactory: Loading com.google.android.webview version 46.0.2490.76 (code 249007650)
06-22 07:44:41.382  6507  6507 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 9959-9973)
06-22 07:44:41.382  6507  6507 I cr.library_loader: Expected native library version number "46.0.2490.76", actual native library version number "46.0.2490.76"
06-22 07:44:41.392  6507  6507 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c06c3ed}
06-22 07:44:41.392  6507  6507 I cr.library_loader: Expected native library version number "46.0.2490.76", actual native library version number "46.0.2490.76"
06-22 07:44:41.402  6507  6507 I chromium: [INFO:library_loader_hooks.cc(118)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:44:41.412  6507  6507 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
06-22 07:44:41.422  6507  6507 E SysUtils: ApplicationContext is null in ApplicationStatus
06-22 07:44:41.472  6507  6522 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
,06-22 07:44:41.502  6507  6507 I Adreno  : QUALCOMM build                   : 8249e7b, Iacb76f3f7d
06-22 07:44:41.502  6507  6507 I Adreno  : Build Date                       : 03/22/16
06-22 07:44:41.502  6507  6507 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.05
06-22 07:44:41.502  6507  6507 I Adreno  : Local Branch                     : 
06-22 07:44:41.502  6507  6507 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.2.6_RB1.06.00.01.179.016
06-22 07:44:41.502  6507  6507 I Adreno  : Remote Branch                    : NONE
06-22 07:44:41.502  6507  6507 I Adreno  : Reconstruct Branch               : NOTHING
06-22 07:44:41.542  6507  6507 E chromium: [ERROR:browser_gpu_channel_host_factory.cc(258)] Failed to init browser shader disk cache.
06-22 07:44:41.552  1614  1847 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
06-22 07:44:41.552  1614  1847 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5afe213:true
06-22 07:44:41.582  6507  6507 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:44:41.652  6507  6507 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-22 07:44:41.672  6507  6507 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
06-22 07:44:41.732  1614  2805 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
06-22 07:44:41.752  1614  1843 D StatusBarManagerService: setSystemUiVisibility(0x80008600)
06-22 07:44:41.752  2401  2401 I PhoneStatusBar: setSystemUiVisibility vis=80008600 mask=ffffffff oldVal=80008700 newVal=80008600 diff=100
06-22 07:44:41.752  1614  1843 D StatusBarManagerService: disable:userId=0 what=0x0 which=0x1 pkg=Window{ca1cbfe u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 07:44:41.752  2401  2401 I PhoneStatusBar: updatePolicy(false,false,false,true)
06-22 07:44:41.752  1614  1843 D StatusBarManagerService: hiding MENU key
06-22 07:44:41.752  2401  2401 I PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=80008600 newVal=8600 diff=80000000
06-22 07:44:41.752  1614  1843 D StatusBarManagerService: setSystemUiVisibility(0x8600)
06-22 07:44:41.752  2401  2401 I PhoneStatusBar: updatePolicy(false,false,false,true)
06-22 07:44:41.752  1614  1843 D StatusBarManagerService: disable:userId=0 what=0x0 which=0x1 pkg=Window{ca1cbfe u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 07:44:41.752  2401  2401 I PhoneStatusBar: hiding the MENU button
06-22 07:44:41.752  1614  1843 D StatusBarManagerService: hiding MENU key
06-22 07:44:41.772  6507  6507 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@f920ccf, mServedView=org.apache.cordova.engine.SystemWebView{830b65c VFEDH.C.. .F....ID 0,0-720,1134 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@b75dd65
06-22 07:44:41.772  1614  2700 I InputMethodManagerService: Disable input method client, pid=5637
06-22 07:44:41.772  1614  2700 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
06-22 07:44:41.772  1614  2700 D InputMethodManagerService: Switching to client com.test.thalitest(6507), IME=com.htc.sense.ime/.HTCIMEService
06-22 07:44:41.772  2401  2401 I PhoneStatusBar: setImeWindowStatus(false,false)
06-22 07:44:41.912  1614  1848 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +626ms (total +689ms)
06-22 07:44:41.912  1614  2805 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: system_server, category: activity_launch_time
06-22 07:44:42.022  6507  6507 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6507
06-22 07:44:42.182  6507  6507 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-22 07:44:42.262  5866  6493 I HtcModeClient: handler message = 4011
06-22 07:44:42.262  5866  6493 D HtcModeClient: getConnectionCheckCount first 0
06-22 07:44:42.262  5866  6493 D HtcModeClient: getConnectionCheckCount count = 6
06-22 07:44:42.262  5866  6493 E HtcModeClient: Check connection and retry 7 times.
06-22 07:44:42.262  5866  6493 D HtcModeClient: setConnectionCheckCount count = 7
06-22 07:44:42.262  5866  6493 D HtcModeClient: setupRestart delayedTime = 3000
06-22 07:44:42.262  5866  5866 D HtcModeClient: setBtPriority priority = on
06-22 07:44:42.262  5866  5866 D HtcModeClient: unbindBlueToothService
06-22 07:44:42.262  5866  5866 D HtcModeClient: Don't start project servcice
06-22 07:44:42.262  5866  5866 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-22 07:44:42.262  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:44:42.262  5866  5866 D SilentMusic: call stop
06-22 07:44:42.262  5866  5866 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:44:42.262  5866  6494 W CANMesgAgentLocalSocket: read the terminate packet, so break
06-22 07:44:42.272  5866  5866 D HtcModeClient: onDestroy
06-22 07:44:42.302  6507  6554 D jxcore_app_log: JniHelper::setJavaVM(0xab95c5f0), pthread_self() = -561768144
06-22 07:44:42.302  6507  6554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:44:42.302  6507  6554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:44:42.302  6507  6554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:44:42.302  6507  6554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:44:42.302  6507  6554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:44:42.302  6507  6554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf1d692 added. We now have 1 listener(s)
06-22 07:44:42.312  6507  6554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:AB:A4:6A
06-22 07:44:42.312  6507  6554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:AB:A4:6A"
06-22 07:44:42.312  6507  6554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:44:42.312  6507  6554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:AB:A4:6A
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:44:42.312  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:44:42.322  6507  6554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7de1519 added. We now have 1 listener(s)
06-22 07:44:42.322  6507  6554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-22 07:44:42.322  1614  2187 D WifiService: New client listening to asynchronous messages
06-22 07:44:42.322  6507  6554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:42.322  6507  6554 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-22 07:44:42.322  6507  6554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:44:42.322  6507  6554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:44:42.322  6507  6554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:44:42.322  6507  6554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-22 07:44:42.332  6507  6554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:44:42.332  6507  6554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:AB:A4:6A
06-22 07:44:42.332  6507  6554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:42.332  6507  6554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:42.332  6507  6554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:44:42.332  6507  6554 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:44:42.332  6507  6554 I io.jxcore.node.LifeCycleMonitor: start: OK
06-22 07:44:42.352  6507  6507 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-22 07:44:42.452  1614  2692 I ActivityManager: Killing 6192:android.process.media/u0a21 (adj 15): empty #17
06-22 07:44:42.452  1614  2692 D Process : killProcessQuiet, pid=6192
06-22 07:44:42.452  1614  2692 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 07:44:42.612  1614  2877 I ActivityManager: Recipient 6192
,06-22 07:44:42.852  6507  6556 W jxcore-log: Initializing JXcore engine
06-22 07:44:42.852  6507  6556 W jxcore-log: JXcore engine is ready
,06-22 07:44:42.902  6507  6556 W jxcore-log: Starting JXcore engine,
,06-22 07:44:42.992  6507  6556 W jxcore-log: Platform android
06-22 07:44:42.992  6507  6556 W jxcore-log: 
06-22 07:44:42.992  6507  6556 W jxcore-log: Process ARCH arm
06-22 07:44:42.992  6507  6556 W jxcore-log: 
,06-22 07:44:43.162  6507  6556 I jxcore-log: JXcore Cordova bridge is ready!,
06-22 07:44:43.162  6507  6556 I jxcore-log: 
06-22 07:44:43.162  6507  6556 W jxcore-log: JXcore engine is started
,06-22 07:44:43.172  6507  6554 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,06-22 07:44:43.172  1614  2727 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 pid 6507 on display 0
,06-22 07:44:43.182  1614  2727 V BoostFramework: BoostFramework() : mPerf = com.qualcomm.qti.Performance@fdfe5f3,
06-22 07:44:43.182  1614  2727 I ActivityManager: Start proc 6557:com.android.packageinstaller/u0a162 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-22 07:44:43.192  6507  6554 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,06-22 07:44:43.222  1614  1850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:786 com.htc.server.HtcMirrorLinkAmsListener.onHandleTopAppChanged:122 com.android.server.am.HtcAmsCallbackManager.handleTopAppChanged:933 com.android.server.am.HtcAmsCallbackManager.handleAmsCallback:358 com.android.server.am.HtcAmsCallbackManager.access$100:27 ,
,06-22 07:44:43.222  1614  2692 D ActivityManager: screenshot for ActivityRecord{855f32d u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t34}, bitmap=null, time = 0,
06-22 07:44:43.222  1614  1850 D HtcMirrorLinkAmsListener: onHandleTopAppChanged, sendBroadcast : com.android.packageinstaller
,06-22 07:44:43.242  6557  6557 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
,06-22 07:44:43.352  1614  2805 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,06-22 07:44:43.372  1614  1843 D StatusBarManagerService: setSystemUiVisibility(0x8000)
06-22 07:44:43.372  1614  1843 D StatusBarManagerService: disable:userId=0 what=0x0 which=0x1 pkg=Window{fdf5ae5 u0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
06-22 07:44:43.382  2401  2401 I PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-22 07:44:43.382  2401  2401 I PhoneStatusBar: updatePolicy(false,false,false,true)
06-22 07:44:43.382  1614  1843 D StatusBarManagerService: hiding MENU key
06-22 07:44:43.382  2401  2401 I PhoneStatusBar: hiding the MENU button
,06-22 07:44:43.392  6557  6569 I Adreno  : QUALCOMM build                   : 8249e7b, Iacb76f3f7d,
06-22 07:44:43.392  6557  6569 I Adreno  : Build Date                       : 03/22/16
06-22 07:44:43.392  6557  6569 I Adreno  : OpenGL ES Shader Compiler Version: XE031.06.00.05
06-22 07:44:43.392  6557  6569 I Adreno  : Local Branch                     : 
06-22 07:44:43.392  6557  6569 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BR.1.2.6_RB1.06.00.01.179.016
06-22 07:44:43.392  6557  6569 I Adreno  : Remote Branch                    : NONE
06-22 07:44:43.392  6557  6569 I Adreno  : Reconstruct Branch               : NOTHING
,06-22 07:44:43.422  1614  2460 I InputMethodManagerService: Disable input method client, pid=6507
06-22 07:44:43.422  2401  2401 I PhoneStatusBar: setImeWindowStatus(false,false)
06-22 07:44:43.422  1614  2460 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,06-22 07:44:43.422  1614  2460 D InputMethodManagerService: Switching to client com.android.packageinstaller(6557), IME=com.htc.sense.ime/.HTCIMEService
,06-22 07:44:43.582  1614  1848 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +358ms (total +405ms)
,06-22 07:44:43.582  1614  2805 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: system_server, category: activity_launch_time
,06-22 07:44:45.172  1614  1856 D PMS     : releaseHCC(7a1794c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
06-22 07:44:45.172  1614  1856 D PMS     : releaseHCC(f7dfd95): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,06-22 07:44:46.832  1614  2407 D Process : killProcessQuiet, pid=6083,
06-22 07:44:46.832  1614  2407 I ActivityManager: Killing 6083:com.htc.calendar/u0a13 (adj 15): empty #17
06-22 07:44:46.832  1614  2407 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 ,
,06-22 07:44:46.902  1614  2671 I ActivityManager: Recipient 6083,
,06-22 07:44:47.262  1614  2040 D PMS     : acquireWL(210206b): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10177}
06-22 07:44:47.262  1614  2040 D AlarmManager: sending alarm PendingIntent{88097c8: PendingIntentRecord{d84e969 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=103856, Int=0
,06-22 07:44:47.272  5866  5866 D AlarmReceiver: ACTION_RESTART_INTENT,
,06-22 07:44:47.282  1614  1614 D PMS     : releaseWL(210206b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10177}
,06-22 07:44:47.282  5866  5866 D LocalBluetoothProfile: getPriorityOnValue = 100,
06-22 07:44:47.282  5866  5866 D LocalBluetoothProfile: getPriorityOffValue = 0
06-22 07:44:47.282  5866  5866 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-22 07:44:47.282  5866  5866 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,06-22 07:44:47.322  5866  6575 D HtcModeClient: start the htcmodeservice thread
,06-22 07:44:47.322  5866  6575 D HtcModeClient: initCanAgent
,06-22 07:44:47.322  5866  6575 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-22 07:44:47.322  5866  6575 D HtcModeClient: sense info: version = none, id = 2,
06-22 07:44:47.322  5866  6575 D HtcModeClient: display info: width = 720, height = 1184,
06-22 07:44:47.322  5866  6575 D HtcModeClient: display info: mode = 10
,06-22 07:44:47.422  5866  5866 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false,
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = false
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: Force_AWAKE = false
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = true
06-22 07:44:47.422  5866  5866 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-22 07:44:47.432  1614  1627 I art     : Background partial concurrent mark sweep GC freed 45772(4MB) AllocSpace objects, 7(192KB) LOS objects, 33% free, 23MB/35MB, paused 1.386ms total 109.092ms
,06-22 07:44:49.432  5866  6575 I HtcModeClient: handler message = 4011,
06-22 07:44:49.432  5866  6575 D HtcModeClient: getConnectionCheckCount first 0
06-22 07:44:49.432  5866  6575 D HtcModeClient: getConnectionCheckCount count = 7
06-22 07:44:49.432  5866  6575 E HtcModeClient: Check connection and retry 8 times.
,06-22 07:44:49.432  5866  6575 D HtcModeClient: setConnectionCheckCount count = 8
,06-22 07:44:49.442  5866  6575 D HtcModeClient: setupRestart delayedTime = 3000
,06-22 07:44:49.442  5866  5866 D HtcModeClient: setBtPriority priority = on,
06-22 07:44:49.442  5866  5866 D HtcModeClient: unbindBlueToothService
,06-22 07:44:49.442  5866  5866 D HtcModeClient: Don't start project servcice
06-22 07:44:49.442  5866  5866 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,06-22 07:44:49.452  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:44:49.452  5866  5866 D SilentMusic: call stop
06-22 07:44:49.452  5866  5866 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:44:49.452  5866  6576 W CANMesgAgentLocalSocket: read the terminate packet, so break
,06-22 07:44:49.462  5866  5866 D HtcModeClient: onDestroy,
,06-22 07:44:54.452  1614  2040 D PMS     : acquireWL(8171a99): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10177},
06-22 07:44:54.452  1614  2040 D AlarmManager: sending alarm PendingIntent{747215e: PendingIntentRecord{d84e969 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=111033, Int=0
,06-22 07:44:54.452  5866  5866 D AlarmReceiver: ACTION_RESTART_INTENT
,06-22 07:44:54.452  1614  1614 D PMS     : releaseWL(8171a99): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10177},
06-22 07:44:54.462  5866  5866 D LocalBluetoothProfile: getPriorityOnValue = 100
06-22 07:44:54.462  5866  5866 D LocalBluetoothProfile: getPriorityOffValue = 0
06-22 07:44:54.462  5866  5866 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-22 07:44:54.462  5866  5866 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,06-22 07:44:54.502  5866  6578 D HtcModeClient: start the htcmodeservice thread
,06-22 07:44:54.502  5866  6578 D HtcModeClient: initCanAgent
,06-22 07:44:54.502  5866  6578 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-22 07:44:54.502  5866  6578 D HtcModeClient: sense info: version = none, id = 2,
06-22 07:44:54.502  5866  6578 D HtcModeClient: display info: width = 720, height = 1184,
06-22 07:44:54.502  5866  6578 D HtcModeClient: display info: mode = 10
,06-22 07:44:54.602  5866  5866 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false,
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = false
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: Force_AWAKE = false
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = true
06-22 07:44:54.602  5866  5866 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-22 07:44:55.072  1614  2040 D PMS     : acquireWL(c73d6a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10074}
06-22 07:44:55.082  1614  2040 D AlarmManager: sending alarm PendingIntent{f908c0d: PendingIntentRecord{a45c7c2 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574295066, Int=0
06-22 07:44:55.082  1614  1614 D PMS     : releaseWL(c73d6a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10074}
,06-22 07:44:55.082  6216  6258 I Finsky  : [478] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,06-22 07:44:55.302  1614  2727 I ActivityManager: Start proc 6580:android.process.media/u0a21 for content provider com.android.providers.media/.MediaProvider
,06-22 07:44:55.332  6216  6258 I Finsky  : [478] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.,
06-22 07:44:55.332  6216  6216 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,06-22 07:44:55.382  6580  6580 W System  : ClassLoader referenced unknown path: /system/priv-app/MediaProvider/lib/arm64,
,06-22 07:44:55.392  6580  6580 W System  : ClassLoader referenced unknown path: /system/priv-app/DownloadProvider/lib/arm64,
,06-22 07:44:56.612  5866  6578 I HtcModeClient: handler message = 4011
06-22 07:44:56.612  5866  6578 D HtcModeClient: getConnectionCheckCount first 0
06-22 07:44:56.612  5866  6578 D HtcModeClient: getConnectionCheckCount count = 8
06-22 07:44:56.612  5866  6578 E HtcModeClient: Check connection and retry 9 times.
06-22 07:44:56.622  5866  6578 D HtcModeClient: setConnectionCheckCount count = 9
06-22 07:44:56.622  5866  6578 D HtcModeClient: setupRestart delayedTime = 3000
06-22 07:44:56.632  5866  5866 D HtcModeClient: setBtPriority priority = on
06-22 07:44:56.632  5866  5866 D HtcModeClient: unbindBlueToothService
06-22 07:44:56.632  5866  5866 D HtcModeClient: Don't start project servcice
06-22 07:44:56.632  5866  5866 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-22 07:44:56.632  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:44:56.632  5866  5866 D SilentMusic: call stop
06-22 07:44:56.632  5866  5866 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:44:56.642  5866  6579 W CANMesgAgentLocalSocket: read the terminate packet, so break
06-22 07:44:56.652  5866  5866 D HtcModeClient: onDestroy
06-22 07:44:56.652  1614  2735 I ActivityManager: Killing 6286:com.google.android.gms:car/u0a29 (adj 15): empty #17
06-22 07:44:56.652  1614  2735 D Process : killProcessQuiet, pid=6286
06-22 07:44:56.652  1614  2735 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
06-22 07:44:56.712  1614  2877 I ActivityManager: Recipient 6286
,06-22 07:44:59.142   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-22 07:44:59.232  2729  2844 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
06-22 07:44:59.232  2729  2844 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,06-22 07:45:00.592  1614  2671 D PMS     : releaseWL(34dcd3f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.account.be.accountstate.LoginAccountsChangedIntentService 0x1 null,
,06-22 07:45:01.632  1614  2040 D PMS     : acquireWL(169b910): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1614 1000 WorkSource{1000}
06-22 07:45:01.632  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118579, Int=0
06-22 07:45:01.632  1614  2040 D AlarmManager: sending alarm PendingIntent{2c6dc09: PendingIntentRecord{d84e969 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=118219, Int=0
06-22 07:45:01.642  5866  5866 D AlarmReceiver: ACTION_RESTART_INTENT
,06-22 07:45:01.652  5866  5866 D LocalBluetoothProfile: getPriorityOnValue = 100,
06-22 07:45:01.652  5866  5866 D LocalBluetoothProfile: getPriorityOffValue = 0
06-22 07:45:01.652  5866  5866 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,06-22 07:45:01.652  5866  5866 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,06-22 07:45:01.692  5866  6598 D HtcModeClient: start the htcmodeservice thread
,06-22 07:45:01.692  5866  6598 D HtcModeClient: initCanAgent
,06-22 07:45:01.692  5866  6598 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-22 07:45:01.692  5866  6598 D HtcModeClient: sense info: version = none, id = 2
,06-22 07:45:01.702  5866  6598 D HtcModeClient: display info: width = 720, height = 1184,
06-22 07:45:01.702  5866  6598 D HtcModeClient: display info: mode = 10
,06-22 07:45:01.732  1614  1614 D PMS     : releaseWL(169b910): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 07:45:01.792  5866  5866 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: BT_TURNON_BYME = false
,06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = false
,06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: Force_AWAKE = false
06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = true
06-22 07:45:01.792  5866  5866 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-22 07:45:03.802  5866  6598 I HtcModeClient: handler message = 4011
,06-22 07:45:03.802  5866  6598 D HtcModeClient: getConnectionCheckCount first 0
,06-22 07:45:03.802  5866  6598 D HtcModeClient: getConnectionCheckCount count = 9
,06-22 07:45:03.802  5866  6598 E HtcModeClient: Check connection and retry 10 times.
,06-22 07:45:03.812  5866  6598 D HtcModeClient: setConnectionCheckCount count = 10,
06-22 07:45:03.812  5866  6598 D HtcModeClient: setupRestart delayedTime = 3000
,06-22 07:45:03.812  5866  5866 D HtcModeClient: setBtPriority priority = on,
06-22 07:45:03.812  5866  5866 D HtcModeClient: unbindBlueToothService
06-22 07:45:03.812  5866  5866 D HtcModeClient: Don't start project servcice
06-22 07:45:03.812  5866  5866 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-22 07:45:03.812  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:45:03.812  5866  5866 D SilentMusic: call stop
,06-22 07:45:03.812  5866  5866 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:45:03.822  5866  6599 W CANMesgAgentLocalSocket: read the terminate packet, so break
,06-22 07:45:03.832  5866  5866 D HtcModeClient: onDestroy,
,06-22 07:45:04.022  1614  2040 D PMS     : acquireWL(22260e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10029},
06-22 07:45:04.022  1614  2040 D AlarmManager: sending alarm PendingIntent{a0d8627: PendingIntentRecord{fcc30d4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=122616, Int=0
06-22 07:45:04.022  1614  1842 D DeviceIdleController: Adding AppId 10029 to temp whitelist
06-22 07:45:04.022  1614  1842 D DeviceIdleController: Setting wakelock temp whitelist to [10029]
06-22 07:45:04.032  1614  1842 D NetworkManagement: oldRule = 0, newRule=0 for uid=10029
06-22 07:45:04.032  1614  1842 D NetworkManagement: !!!!! Skipping change,
06-22 07:45:04.032  1614  1614 D PMS     : releaseWL(22260e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10029}
,06-22 07:45:08.822  1614  2040 D PMS     : acquireWL(8c9927d): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10177}
06-22 07:45:08.822  1614  2040 D AlarmManager: sending alarm PendingIntent{223a572: PendingIntentRecord{d84e969 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=125406, Int=0
,06-22 07:45:08.822  5866  5866 D AlarmReceiver: ACTION_RESTART_INTENT
,06-22 07:45:08.832  1614  1614 D PMS     : releaseWL(8c9927d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10177},
,06-22 07:45:08.832  5866  5866 D LocalBluetoothProfile: getPriorityOnValue = 100,
06-22 07:45:08.832  5866  5866 D LocalBluetoothProfile: getPriorityOffValue = 0
06-22 07:45:08.832  5866  5866 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,06-22 07:45:08.832  5866  5866 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,06-22 07:45:08.872  5866  6601 D HtcModeClient: start the htcmodeservice thread,
06-22 07:45:08.872  5866  6601 D HtcModeClient: initCanAgent,
06-22 07:45:08.872  5866  6601 I CANMesgAgentLocalSocket: CANAgent Id = 0,
,06-22 07:45:08.882  5866  6601 D HtcModeClient: sense info: version = none, id = 2
,06-22 07:45:08.882  5866  6601 D HtcModeClient: display info: width = 720, height = 1184
,06-22 07:45:08.882  5866  6601 D HtcModeClient: display info: mode = 10
,06-22 07:45:08.972  5866  5866 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = false
,06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: Force_AWAKE = false
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = true
06-22 07:45:08.972  5866  5866 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-22 07:45:09.142   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:45:10.992  5866  6601 I HtcModeClient: handler message = 4011,
06-22 07:45:10.992  5866  6601 D HtcModeClient: getConnectionCheckCount first 0
06-22 07:45:10.992  5866  6601 D HtcModeClient: getConnectionCheckCount count = 10
,06-22 07:45:10.992  5866  6601 E HtcModeClient: Check connection and retry 11 times.
,06-22 07:45:10.992  5866  6601 D HtcModeClient: setConnectionCheckCount count = 11,
06-22 07:45:10.992  5866  6601 D HtcModeClient: setupRestart delayedTime = 3000
,06-22 07:45:10.992  5866  5866 D HtcModeClient: setBtPriority priority = on,
06-22 07:45:10.992  5866  5866 D HtcModeClient: unbindBlueToothService
,06-22 07:45:10.992  5866  5866 D HtcModeClient: Don't start project servcice
,06-22 07:45:11.002  5866  5866 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,06-22 07:45:11.002  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false,
06-22 07:45:11.002  5866  5866 D SilentMusic: call stop
06-22 07:45:11.002  5866  5866 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:45:11.002  5866  6602 W CANMesgAgentLocalSocket: read the terminate packet, so break
,06-22 07:45:11.002  5866  5866 D HtcModeClient: onDestroy,
,06-22 07:45:14.042  1614  1841 D DeviceIdleController: handleMessage(5),
06-22 07:45:14.042  1614  1841 D DeviceIdleController: Removing UID 10029 from temp whitelist
06-22 07:45:14.042  1614  1841 D DeviceIdleController: Setting wakelock temp whitelist to []
,06-22 07:45:14.042  1614  1841 D NetworkManagement: oldRule = 0, newRule=0 for uid=10029
,06-22 07:45:14.042  1614  1841 D NetworkManagement: !!!!! Skipping change
,06-22 07:45:16.002  1614  2040 D PMS     : acquireWL(12fc23b): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10177}
06-22 07:45:16.002  1614  2040 D AlarmManager: sending alarm PendingIntent{325dd58: PendingIntentRecord{d84e969 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=132586, Int=0
,06-22 07:45:16.002  5866  5866 D AlarmReceiver: ACTION_RESTART_INTENT,
,06-22 07:45:16.012  1614  1614 D PMS     : releaseWL(12fc23b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10177},
,06-22 07:45:16.012  5866  5866 D LocalBluetoothProfile: getPriorityOnValue = 100,
06-22 07:45:16.012  5866  5866 D LocalBluetoothProfile: getPriorityOffValue = 0
06-22 07:45:16.012  5866  5866 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-22 07:45:16.012  5866  5866 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,06-22 07:45:16.042  5866  6604 D HtcModeClient: start the htcmodeservice thread,
06-22 07:45:16.042  5866  6604 D HtcModeClient: initCanAgent
,06-22 07:45:16.042  5866  6604 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-22 07:45:16.042  5866  6604 D HtcModeClient: sense info: version = none, id = 2,
,06-22 07:45:16.052  5866  6604 D HtcModeClient: display info: width = 720, height = 1184
06-22 07:45:16.052  5866  6604 D HtcModeClient: display info: mode = 10
,06-22 07:45:16.152  5866  5866 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = false
06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: Force_AWAKE = false
,06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: PHONE_PULGIN = true
06-22 07:45:16.152  5866  5866 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-22 07:45:18.162  5866  6604 I HtcModeClient: handler message = 4011,
06-22 07:45:18.162  5866  6604 D HtcModeClient: getConnectionCheckCount first 0
,06-22 07:45:18.162  5866  6604 D HtcModeClient: getConnectionCheckCount count = 11,
,06-22 07:45:18.162  5866  6604 E HtcModeClient: Check connection and retry 12 times. Time out!
,06-22 07:45:18.162  5866  6604 D HtcModeClient: setConnectionCheckCount count = 0,
06-22 07:45:18.162  5866  6604 D HtcModeClient: cancelRestart
,06-22 07:45:18.172  5866  5866 D HtcModeClient: setBtPriority priority = on,
06-22 07:45:18.172  5866  5866 D HtcModeClient: unbindBlueToothService
06-22 07:45:18.172  5866  5866 D HtcModeClient: Don't start project servcice
06-22 07:45:18.172  5866  5866 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-22 07:45:18.172  5866  5866 D HtcModeClient: connectState: CONNECTION_READY = false
06-22 07:45:18.172  5866  5866 D SilentMusic: call stop
06-22 07:45:18.172  5866  5866 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:45:18.172  5866  6605 W CANMesgAgentLocalSocket: read the terminate packet, so break
,06-22 07:45:18.182  5866  5866 D HtcModeClient: onDestroy
,06-22 07:45:24.142   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 07:45:31.202  1614  2040 I ActivityManager: Start proc 6606:com.htc.mms.backupagent/u0a78 for service com.htc.mms.backupagent/.SMSBackupAgentService,
06-22 07:45:31.202  1614  2040 D PMS     : acquireWL(2f12e9): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10078}
,06-22 07:45:31.202  1614  2040 D AlarmManager: sending alarm PendingIntent{5043b6e: PendingIntentRecord{1fd020f com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1466574299203, Int=60000
,06-22 07:45:31.202  1614  2040 D AlarmManager: sending alarm PendingIntent{35cf4a5: PendingIntentRecord{dbca07a com.google.android.gms startService}}, i=com.google.android.gms.drive.ApiService.RESET_AFTER_BOOT, t=2, cnt=1, w=120000, Int=0
,06-22 07:45:31.202  1614  2040 D AlarmManager: sending alarm PendingIntent{2bd61bc: PendingIntentRecord{1d21545 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=149763, Int=0
06-22 07:45:31.212  1614  2683 D PMS     : acquireWL(a91b02b): PARTIAL_WAKE_LOCK  NetworkTimeUpdateService 0x1 1614 1000 null
06-22 07:45:31.212  1614  2683 D PMS     : releaseWL(a91b02b): PARTIAL_WAKE_LOCK  NetworkTimeUpdateService 0x1 null
,06-22 07:45:31.212  1614  1614 D PMS     : releaseWL(2f12e9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,06-22 07:45:31.262  6606  6606 W System  : ClassLoader referenced unknown path: /system/app/SMSBackup/lib/arm64
,06-22 07:45:31.272  6606  6618 D SMSBackup: SMSBackupAgentService started,
06-22 07:45:31.272  6606  6618 D SMSBackup: Checking restore status
,06-22 07:45:31.292  6606  6618 D SMSBackup: Restore complete,
06-22 07:45:31.292  6606  6618 D SMSBackup: cancelCheckAlarm
,06-22 07:45:31.292  6606  6618 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,06-22 07:45:31.332  1614  3927 D ConnectivityService: listenForNetwork for Listen from uid/pid:10029/5259 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
,06-22 07:45:31.392  5259  6621 W DriveInitializer: Background init thread started
,06-22 07:45:31.402  1614  2700 D Process : killProcessQuiet, pid=6333,
06-22 07:45:31.402  1614  2700 I ActivityManager: Killing 6333:com.htc.bgp/1001 (adj 15): empty #17
06-22 07:45:31.402  1614  2700 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 07:45:31.552  1614  2692 I ActivityManager: Recipient 6333,
,06-22 07:45:31.622  5259  6621 W DriveInitializer: Background init thread ended,
,06-22 07:45:33.912  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1,
06-22 07:45:33.912  1614  2877 D PMS     : acquireWL(1358859): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null
06-22 07:45:33.912  1614  1614 I BatteryLightController: updateBattery(plugged=true plugin=true low=false full=true health=2 status=5 timeout=false usbOverheat=false)
06-22 07:45:33.912  1614  2877 I BatteryService: n_update end
06-22 07:45:33.912  1614  1614 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:45:33.912  1614  2877 D PMS     : releaseWL(1358859): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:45:33.912  1614  1614 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:45:33.912  1614  1852 D HtcPowerSaver: updateBatteryInfo
06-22 07:45:33.912  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,06-22 07:45:33.912  1614  1614 I DeviceIdleController: updateChargingLocked: charging=true
06-22 07:45:33.912  1614  1614 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:45:33.912  1614  1614 W DeviceIdleController: becomeActiveLocked, reason = charging
06-22 07:45:33.912  1614  1614 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:45:33.912  1614  1614 D PMS     : runPSCheck
06-22 07:45:33.912  2594  2594 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,mbIsDeviceSupportDotView:true
06-22 07:45:33.912  1614  1614 D HtcPowerSaver: Checking...
06-22 07:45:33.912  1614  1614 I HtcPowerSaver: >> updateStatus
06-22 07:45:33.912  1614  1614 I HtcPowerSaver: << updateStatus,
06-22 07:45:33.912  2401  2401 D PowerUI : closing low battery warning: level=100
,06-22 07:45:33.922  2401  2401 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
06-22 07:45:33.922  2401  2401 I QuickSettingPowerSaverEX: batteryLevelChanged:true
06-22 07:45:33.922  2401  2401 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
06-22 07:45:33.922  2401  2401 I BatteryController: status:5 health:2 level:100 unsupport:false plugged:true timeout:falsecharging:true,
,06-22 07:45:37.692  3423  4181 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-22 07:45:42.532  1614  1841 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA,
,06-22 07:45:42.542  1614  1841 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,06-22 07:45:44.152   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:45:55.502  5796  5796 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@b98b1e9 for type 1
,06-22 07:45:55.502  5796  5796 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@b98b1e9 for type 0
,06-22 07:45:55.502  1614  1667 D Process : killProcessQuiet, pid=5796
06-22 07:45:55.502  1614  1667 I ActivityManager: Killing 5796:com.htc.music:musicenhancer/u0a1 (adj 15): empty #17
,06-22 07:45:55.502  1614  1667 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 07:45:55.562  1614  2692 I ActivityManager: Recipient 5796
,06-22 07:46:04.282  2729  2729 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,06-22 07:46:06.542  1614  2040 D PMS     : acquireWL(12c5c1e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1614 1000 WorkSource{1000},
06-22 07:46:06.542  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178579, Int=0
,06-22 07:46:06.562  1614  2040 I ActivityManager: Start proc 6628:com.htc.sense.mms/u0a4 for service com.htc.sense.mms/.transaction.TransactionService
06-22 07:46:06.562  1614  2040 D AlarmManager: sending alarm PendingIntent{1288cff: PendingIntentRecord{573eacc com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1466574366559, Int=0,
,06-22 07:46:06.672  6628  6628 D MessageFrequencyProvider: onCreate,
06-22 07:46:06.672  1614  1614 D PMS     : releaseWL(12c5c1e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 07:46:06.682  6628  6628 D Messaging: Is Secure ROM >false,
,06-22 07:46:06.682  6628  6628 D RcsChatUtils: isSup> false
,06-22 07:46:06.682  6628  6628 D j       : createReceiver
06-22 07:46:06.682  6628  6628 D j       : registerReceiver return intent = null
06-22 07:46:06.692  6628  6628 D HtcThemeUtils: context=android.view.ContextThemeWrapper@7f5390f, category=1, byUser=false, userHandle=0
06-22 07:46:06.692  6628  6628 D HtcThemeUtils: [CC][checkIfNeedRecreate] mNeedRecreate=false, mCategoryRes=null, mCategoryTheme=null, sameDefRes=false,
,06-22 07:46:06.702  6628  6628 D HtcThemeUtils: context=android.view.ContextThemeWrapper@7f5390f, target=CCategoryOne.apk
06-22 07:46:06.702  6628  6628 D HtcThemeUtils: optionalPath=/data/user/0/com.htc.home.personalize/files/.htc_theme/
,06-22 07:46:06.702  6628  6628 W asset   : Asset path CCategoryOne.apk is neither a directory nor file (type=1).
06-22 07:46:06.702  6628  6628 D HtcThemeUtils: AssetMaanger addAssetPath CCategoryOne fail!
06-22 07:46:06.702  6628  6628 D HtcThemeUtils: context=android.view.ContextThemeWrapper@7f5390f, optional=/data/user/0/com.htc.home.personalize/files/.htc_theme/CCategoryOne.apk
06-22 07:46:06.702  6628  6628 W asset   : Asset path /data/user/0/com.htc.home.personalize/files/.htc_theme/CCategoryOne.apk is neither a directory nor file (type=0).
06-22 07:46:06.702  6628  6628 D HtcThemeUtils: AssetMaanger addOptionalPath CCategoryOne fail!
,06-22 07:46:06.712  6628  6628 D HtcThemeUtils: context=android.view.ContextThemeWrapper@7f5390f, target=CResources.apk
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: optionalPath=/data/user/0/com.htc.home.personalize/files/.htc_theme/
06-22 07:46:06.712  6628  6628 W asset   : Asset path CResources.apk is neither a directory nor file (type=1).
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: context=android.view.ContextThemeWrapper@7f5390f, optional=/data/user/0/com.htc.home.personalize/files/.htc_theme/CResources.apk
06-22 07:46:06.712  6628  6628 W asset   : Asset path /data/user/0/com.htc.home.personalize/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: AssetMaanger addOptionalPath CResources fail!
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: init done
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: Register com.htc.sense.mms.util.z@54183a5 for type 0,
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: Register com.htc.sense.mms.util.z@54183a5 for type 1
06-22 07:46:06.712  6628  6628 D HtcThemeUtils: Register com.htc.sense.mms.util.z@54183a5 for type 5
06-22 07:46:06.712  6628  6640 D Mms     : MmsApp onCreateBG start
,06-22 07:46:06.722  6628  6628 V TransactionService: 1-Creating TransactionService
,06-22 07:46:06.722  6628  6628 D MmsNetworkManager: bind: false,
06-22 07:46:06.722  6628  6628 D MmsNetworkManager: bindService
06-22 07:46:06.722  6628  6640 D MessageCustFlag: sku_id=99
,06-22 07:46:06.742  6628  6640 D MessageCustFlag: sense_version=7.0
06-22 07:46:06.742  1614  2735 I ActivityManager: Start proc 6644:com.htc.sense.mms:mms/u0a4 for service com.htc.sense.mms/com.htc.messaging.service.MmsService
,06-22 07:46:06.742  6628  6628 D MmsNetworkManager: bind: true,
06-22 07:46:06.742  6628  6628 V TransactionService: onStartCommand: 1
06-22 07:46:06.742  6628  6628 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
06-22 07:46:06.742  6628  6642 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$a }
,06-22 07:46:06.742  6628  6642 V TransactionService: Loading previous transactions.
,06-22 07:46:06.752  6628  6640 D HfmClient: bCheckCarmode = true,
06-22 07:46:06.752  6628  6640 D HfmClient: getIHFMServiceHMSApiLevel: +++
06-22 07:46:06.752  6628  6640 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
06-22 07:46:06.752  6628  6640 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
,06-22 07:46:06.762  6628  6640 D HfmClient: getIHFMServiceHMSApiLevel: Level = 2,
06-22 07:46:06.762  6628  6640 D HfmClient: HfmServiceHMS API Level = 2
06-22 07:46:06.762  6628  6640 D HfmMessageClient: currentProcessName : com.htc.sense.mms
,06-22 07:46:06.772  6628  6640 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@b98b1e9
06-22 07:46:06.772  6628  6640 D Mms     : MmsApp onCreateBG end
,06-22 07:46:06.782  2729  3226 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
,06-22 07:46:06.802  6628  6642 D TransactionService: Force clearing mTransactionList
06-22 07:46:06.802  6628  6642 D MmsNetworkManager: closeAllConnections> service is null
06-22 07:46:06.802  6628  6642 D TransactionService: Force set service start id to 1
,06-22 07:46:06.802  6628  6642 V TransactionService: stopSelfIfIdle
06-22 07:46:06.802  6628  6642 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
06-22 07:46:06.802  6628  6628 V TransactionService: Destroying TransactionService
06-22 07:46:06.802  6628  6628 D MmsNetworkManager: unbind: true
06-22 07:46:06.802  6628  6628 D MmsNetworkManager: unbindService
,06-22 07:46:06.812  6628  6642 V TransactionService: 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$a }
06-22 07:46:06.812  1614  2756 I ActivityManager: Killing 6347:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
06-22 07:46:06.812  6628  6642 V Scheduler: Scheduler safely quits looper.
06-22 07:46:06.812  1614  2756 D Process : killProcessQuiet, pid=6347
06-22 07:46:06.812  1614  2756 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
06-22 07:46:06.812  6644  6644 D Messaging: Is Secure ROM >false
,06-22 07:46:06.812  6644  6644 D RcsChatUtils: isSup> false
,06-22 07:46:06.812  6644  6644 D j       : createReceiver
,06-22 07:46:06.932  1614  1667 I ActivityManager: Recipient 6347
,06-22 07:46:06.932  6644  6644 D j       : registerReceiver return intent = null
,06-22 07:46:06.942  6644  6644 D HtcThemeUtils: context=android.view.ContextThemeWrapper@1f29e17, category=1, byUser=false, userHandle=0
,06-22 07:46:06.952  6644  6644 D HtcThemeUtils: [CC][checkIfNeedRecreate] mNeedRecreate=false, mCategoryRes=null, mCategoryTheme=null, sameDefRes=false,
06-22 07:46:06.952  6644  6644 D HtcThemeUtils: context=android.view.ContextThemeWrapper@1f29e17, target=CCategoryOne.apk
06-22 07:46:06.952  6644  6644 D HtcThemeUtils: optionalPath=/data/user/0/com.htc.home.personalize/files/.htc_theme/
06-22 07:46:06.962  6644  6644 W asset   : Asset path CCategoryOne.apk is neither a directory nor file (type=1).
06-22 07:46:06.962  6644  6644 D HtcThemeUtils: AssetMaanger addAssetPath CCategoryOne fail!
06-22 07:46:06.962  6644  6644 D HtcThemeUtils: context=android.view.ContextThemeWrapper@1f29e17, optional=/data/user/0/com.htc.home.personalize/files/.htc_theme/CCategoryOne.apk
06-22 07:46:06.962  6644  6644 W asset   : Asset path /data/user/0/com.htc.home.personalize/files/.htc_theme/CCategoryOne.apk is neither a directory nor file (type=0).
06-22 07:46:06.962  6644  6644 D HtcThemeUtils: AssetMaanger addOptionalPath CCategoryOne fail!
,06-22 07:46:06.962  6644  6644 D HtcThemeUtils: context=android.view.ContextThemeWrapper@1f29e17, target=CResources.apk
06-22 07:46:06.962  6644  6644 D HtcThemeUtils: optionalPath=/data/user/0/com.htc.home.personalize/files/.htc_theme/
,06-22 07:46:06.962  6644  6644 W asset   : Asset path CResources.apk is neither a directory nor file (type=1).
06-22 07:46:06.962  6644  6644 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
06-22 07:46:06.962  6644  6644 D HtcThemeUtils: context=android.view.ContextThemeWrapper@1f29e17, optional=/data/user/0/com.htc.home.personalize/files/.htc_theme/CResources.apk
06-22 07:46:06.972  6644  6644 W asset   : Asset path /data/user/0/com.htc.home.personalize/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
06-22 07:46:06.972  6644  6644 D HtcThemeUtils: AssetMaanger addOptionalPath CResources fail!
06-22 07:46:06.972  6644  6644 D HtcThemeUtils: init done
06-22 07:46:06.972  6644  6644 D HtcThemeUtils: Register com.htc.sense.mms.util.z@c06c3ed for type 0
,06-22 07:46:06.972  6644  6644 D HtcThemeUtils: Register com.htc.sense.mms.util.z@c06c3ed for type 1
06-22 07:46:06.972  6644  6644 D HtcThemeUtils: Register com.htc.sense.mms.util.z@c06c3ed for type 5
06-22 07:46:06.972  6644  6657 D Mms     : MmsApp onCreateBG start
,06-22 07:46:06.982  6644  6657 D MessageCustFlag: sku_id=99,
,06-22 07:46:06.992  6644  6644 D HtcMmsService: onCreate() executed,
,06-22 07:46:07.002  6644  6644 D HtcMmsService: onDestroy() executed
,06-22 07:46:07.002  1614  2877 D Process : killProcessQuiet, pid=6137,
06-22 07:46:07.002  1614  2877 I ActivityManager: Killing 6137:com.google.android.googlequicksearchbox:search/u0a86 (adj 15): empty #17
06-22 07:46:07.002  1614  2877 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 07:46:07.022  6644  6657 D MessageCustFlag: sense_version=7.0,
,06-22 07:46:07.042  6644  6657 D HfmClient: bCheckCarmode = true,
06-22 07:46:07.042  6644  6657 D HfmClient: getIHFMServiceHMSApiLevel: +++
,06-22 07:46:07.042  6644  6657 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
,06-22 07:46:07.042  6644  6657 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
,06-22 07:46:07.042  6644  6657 D HfmClient: getIHFMServiceHMSApiLevel: Level = 2
,06-22 07:46:07.052  6644  6657 D HfmClient: HfmServiceHMS API Level = 2
,06-22 07:46:07.102  1614  1667 I ActivityManager: Recipient 6137
,06-22 07:46:07.112  6644  6657 D HfmMessageClient: currentProcessName : com.htc.sense.mms:mms
,06-22 07:46:07.122  6644  6657 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@e90fdb1
,06-22 07:46:07.122  6644  6657 D Mms     : MmsApp onCreateBG end,
,06-22 07:46:08.782  6628  6628 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist,
,06-22 07:46:08.782  6628  6628 D ReportIndicatorCache: startAsyncQueryReports --- , first = true
,06-22 07:46:08.792  6628  6641 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
,06-22 07:46:08.792  2729  3211 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
06-22 07:46:08.792  2729  3211 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:08.792  2729  3211 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null
06-22 07:46:08.792  6628  6640 D MmsAsyncWorkHandler: 
06-22 07:46:08.792  6628  6640 D MmsAsyncWorkHandler: HM tk = 20002
,06-22 07:46:08.802  2729  2747 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
06-22 07:46:08.802  6628  6628 D DraftCache: [DraftCache/1] DraftCache.constructor
06-22 07:46:08.812  6628  6628 D DraftCache: [DraftCache/1] refresh
,06-22 07:46:08.812  6628  6628 D MmsConfig: networkCode: 
06-22 07:46:08.812  6628  6628 D da      : createReceiver
,06-22 07:46:08.822  6628  6662 D MmsConfig: Start to get Carrier ID,
06-22 07:46:08.822  2729  3226 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
,06-22 07:46:08.822  6628  6659 D Messaging: mNeedToUpdateDate2 start
,06-22 07:46:08.832  6628  6664 D Messaging: ViewCache CreatePreloadOnlyConversationList
06-22 07:46:08.832  6628  6664 D MessageCustFlag: sense_version=7.0
,06-22 07:46:08.832  2729  2748 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
,06-22 07:46:08.832  2729  2748 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:08.832  2729  2748 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
06-22 07:46:08.832  6628  6662 D MmsConfig: Carrier ID is NULL
,06-22 07:46:08.842  6628  6661 I Messaging: mccmnc> ,
,06-22 07:46:08.842  2729  3226 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
,06-22 07:46:08.852  6628  6664 D Jerry   : start to preload cursor >>>>>>>,
,06-22 07:46:08.852  6628  6665 D da      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
06-22 07:46:08.852  2729  2747 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
06-22 07:46:08.852  2729  2747 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:08.852  2729  2747 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,06-22 07:46:08.862  6628  6665 D da      : /storage/emulated/0 : mounted
,06-22 07:46:08.862  2729  3211 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
06-22 07:46:08.862  2729  3211 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:08.862  2729  3211 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,06-22 07:46:08.862  6628  6665 D da      : HtcStorageHelper.getRemovableStorageDir.Count = 0
06-22 07:46:08.872  2729  3407 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
06-22 07:46:08.872  2729  3407 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:08.872  6628  6660 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,06-22 07:46:08.872  2729  3226 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
06-22 07:46:08.872  2729  3226 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:08.872  2729  3226 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,06-22 07:46:08.882  6628  6659 D Messaging: mNeedToUpdateDate2: false,
,06-22 07:46:08.902  6628  6664 D Messaging: ViewCache CreatePreload
,06-22 07:46:08.902  6628  6664 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,06-22 07:46:08.912  6628  6640 D DraftCache: [DraftCache/139] rebuildCache,
,06-22 07:46:08.922  2729  3407 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
,06-22 07:46:08.922  6628  6664 D Cust_MMSMS: _has_set_default_values_2=true,
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size38
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size32
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size0
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size38
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size44
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size49
06-22 07:46:08.922  6628  6664 D TextSizeManager: [get_list_body_TextSize]__size55
06-22 07:46:08.922  6628  6664 D MsgPreferenceUtils: def_index_b: 0
06-22 07:46:08.922  2729  3407 D Jerry   : URI_DRAFT
,06-22 07:46:08.932  6628  6640 D DraftCache: hasDraft() = false mNeedNotifyChange = true
06-22 07:46:08.932  6628  6640 D DraftCache: [DraftCache/139] rebuildCache time: 1,
,06-22 07:46:08.932  6628  6664 D MsgPreferenceUtils: phone state: true,
06-22 07:46:08.932  6628  6664 D MsgPreferenceUtils: sd state 0: false
06-22 07:46:08.932  6628  6664 D MsgPreferenceUtils: sd state 1: false
06-22 07:46:08.932  6628  6664 D MsgPreferenceUtils: def_index_a: 0
,06-22 07:46:08.962  6628  6683 D RcsWorkingHandler: handler msg:{ when=-1ms what=1 target=com.htc.sense.mms.rcschat.ay$a }
06-22 07:46:08.962  6628  6683 D RcsWorkingHandler: not support Rcs, return
06-22 07:46:08.962  6628  6664 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
,06-22 07:46:08.962  6628  6664 D PersonalizeUtils: isHTCThemeChange_full isChange= false
06-22 07:46:08.962  6628  6664 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
06-22 07:46:08.962  6628  6664 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
06-22 07:46:08.962  6628  6664 D PersonalizeUtils: isHTCThemeChange_CC equal time= null,old=
06-22 07:46:08.962  6628  6664 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,06-22 07:46:09.142  6644  6644 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist,
,06-22 07:46:09.142  6644  6644 D ReportIndicatorCache: startAsyncQueryReports --- , first = true
,06-22 07:46:09.142  6644  6658 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
,06-22 07:46:09.152  6644  6657 D MmsAsyncWorkHandler: ,
06-22 07:46:09.152  6644  6657 D MmsAsyncWorkHandler: HM tk = 20002
06-22 07:46:09.152   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
06-22 07:46:09.152  2729  3211 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
,06-22 07:46:09.152  2729  3211 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:09.152  2729  3211 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null,
06-22 07:46:09.162  2729  2747 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
06-22 07:46:09.162  6644  6644 D DraftCache: [DraftCache/1] DraftCache.constructor
06-22 07:46:09.162  6644  6644 D DraftCache: [DraftCache/1] refresh
,06-22 07:46:09.172  6644  6687 D MmsConfig: Start to get Carrier ID
,06-22 07:46:09.172  6644  6684 D Messaging: mNeedToUpdateDate2 start,
,06-22 07:46:09.172  2729  2748 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66,
,06-22 07:46:09.182  6644  6644 D MmsConfig: networkCode: 
,06-22 07:46:09.182  6644  6644 D da      : createReceiver
,06-22 07:46:09.192  6644  6686 I Messaging: mccmnc> 
,06-22 07:46:09.192  6644  6687 D MmsConfig: Carrier ID is NULL
,06-22 07:46:09.192  2729  3211 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 79
06-22 07:46:09.192  2729  3211 D MmsSmsV2Provider:  slotId = -1,
06-22 07:46:09.192  2729  3211 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
06-22 07:46:09.192  6644  6689 D Messaging: ViewCache CreatePreloadOnlyConversationList
06-22 07:46:09.192  6644  6689 D MessageCustFlag: sense_version=7.0
,06-22 07:46:09.202  2729  2748 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
06-22 07:46:09.202  2729  2748 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:09.202  2729  2748 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,06-22 07:46:09.212  6644  6690 D da      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
,06-22 07:46:09.212  2729  3407 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
,06-22 07:46:09.212  6644  6690 D da      : /storage/emulated/0 : mounted
,06-22 07:46:09.212  6644  6690 D da      : HtcStorageHelper.getRemovableStorageDir.Count = 0
06-22 07:46:09.212  6644  6689 D Jerry   : start to preload cursor >>>>>>>
,06-22 07:46:09.222  2729  2747 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
06-22 07:46:09.222  2729  2747 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:09.222  2729  2747 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,06-22 07:46:09.232  2729  3407 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
06-22 07:46:09.232  2729  3407 D MmsSmsV2Provider:  slotId = -1
06-22 07:46:09.232  2729  3407 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,06-22 07:46:09.232  6644  6685 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true,
06-22 07:46:09.232  6644  6684 D Messaging: mNeedToUpdateDate2: false
06-22 07:46:09.232  2729  2747 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
06-22 07:46:09.232  2729  2747 D MmsSmsV2Provider:  slotId = -1
,06-22 07:46:09.262  6644  6689 D Messaging: ViewCache CreatePreload
,06-22 07:46:09.262  6644  6689 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,06-22 07:46:09.272  6644  6657 D DraftCache: [DraftCache/143] rebuildCache,
,06-22 07:46:09.272  2729  3226 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
,06-22 07:46:09.282  2729  3226 D Jerry   : URI_DRAFT,
,06-22 07:46:09.282  6644  6689 D Cust_MMSMS: _has_set_default_values_2=true,
06-22 07:46:09.282  6644  6657 D DraftCache: hasDraft() = false mNeedNotifyChange = true
06-22 07:46:09.282  6644  6657 D DraftCache: [DraftCache/143] rebuildCache time: 1
,06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size38
06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size32,
06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size0
06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size38
06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size44
,06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size49
06-22 07:46:09.282  6644  6689 D TextSizeManager: [get_list_body_TextSize]__size55
,06-22 07:46:09.282  6644  6689 D MsgPreferenceUtils: def_index_b: 0
,06-22 07:46:09.292  6644  6689 D MsgPreferenceUtils: phone state: true,
06-22 07:46:09.292  6644  6689 D MsgPreferenceUtils: sd state 0: false
06-22 07:46:09.292  6644  6689 D MsgPreferenceUtils: sd state 1: false
06-22 07:46:09.292  6644  6689 D MsgPreferenceUtils: def_index_a: 0
,06-22 07:46:09.322  6644  6689 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=,
06-22 07:46:09.322  6644  6689 D PersonalizeUtils: isHTCThemeChange_full isChange= false
06-22 07:46:09.322  6644  6689 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
06-22 07:46:09.322  6644  6689 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
06-22 07:46:09.322  6644  6689 D PersonalizeUtils: isHTCThemeChange_CC equal time= null,old=
06-22 07:46:09.322  6644  6689 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,06-22 07:46:09.322  6644  6709 D RcsWorkingHandler: handler msg:{ when=-2ms what=1 target=com.htc.sense.mms.rcschat.ay$a }
,06-22 07:46:09.322  6644  6709 D RcsWorkingHandler: not support Rcs, return
,06-22 07:46:32.002  2401  3531 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,06-22 07:46:32.002  2401  3531 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,06-22 07:46:32.002  2665  2665 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@e2714a2
,06-22 07:46:32.002  1614  2407 D Process : killProcessQuiet, pid=6156
06-22 07:46:32.002  1614  2407 I ActivityManager: Killing 6156:com.google.android.partnersetup/u0a32 (adj 15): empty #17
06-22 07:46:32.002  1614  2407 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 07:46:32.062  1614  2727 I ActivityManager: Recipient 6156
,06-22 07:46:34.072  1614  2460 D PMS     : acquireWL(2a56de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null,
06-22 07:46:34.072  1614  2460 I BatteryService: n_update end
06-22 07:46:34.072  1614  2460 D PMS     : releaseWL(2a56de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:46:34.072  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:46:34.072  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:46:34.072  2594  2594 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,mbIsDeviceSupportDotView:true
06-22 07:46:34.072  2401  2401 D PowerUI : closing low battery warning: level=100
,06-22 07:46:34.072  1614  1614 I BatteryLightController: updateBattery(plugged=true plugin=true low=false full=true health=2 status=5 timeout=false usbOverheat=false)
06-22 07:46:34.072  1614  1852 D HtcPowerSaver: updateBatteryInfo
06-22 07:46:34.072  1614  1614 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:46:34.072  1614  1614 I DeviceIdleController: updateChargingLocked: charging=true
06-22 07:46:34.072  1614  1614 D UsbnetService: onReceive BATTERY_CHANGED
,06-22 07:46:34.072  1614  1614 W DeviceIdleController: becomeActiveLocked, reason = charging,
06-22 07:46:34.072  1614  1614 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:46:34.072  1614  1614 D PMS     : runPSCheck
06-22 07:46:34.072  1614  1614 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:46:34.072  1614  1614 D HtcPowerSaver: Checking...
06-22 07:46:34.072  2401  2401 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
06-22 07:46:34.072  1614  1614 I HtcPowerSaver: >> updateStatus
06-22 07:46:34.072  2401  2401 I QuickSettingPowerSaverEX: batteryLevelChanged:true
06-22 07:46:34.082  1614  1614 I HtcPowerSaver: << updateStatus
06-22 07:46:34.072  2401  2401 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
,06-22 07:46:34.082  2401  2401 I BatteryController: status:5 health:2 level:100 unsupport:false plugged:true timeout:falsecharging:true
,06-22 07:46:49.162   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-22 07:46:59.172   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-22 07:47:14.162   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:47:34.182   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-22 07:47:59.172   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:48:33.502  1614  2355 D HtcWLD_v5.3.2:     Turn end: total_sum=30 screen_off_sum=25,
06-22 07:48:33.502  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:48:33.502  1614  2355 D HtcWLD_v5.3.2:     Turn#2
,06-22 07:48:44.172   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-22 07:48:54.182   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-22 07:49:09.192   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:49:13.682  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:49:13.692  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:49:13.692  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:49:13.752  6216  6255 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=com.android.vending
,06-22 07:49:13.752  6216  6255 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
,06-22 07:49:13.752   426  6710 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=/system/bin/netd,
06-22 07:49:13.752   426  6710 D libc    : [NET] android_getaddrinfo_proxy-, fd error: Success(0)
06-22 07:49:13.752   426  6710 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
06-22 07:49:13.762  6216  6255 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-22 07:49:29.192   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:49:54.202   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:49:59.992  1614  2040 D PMS     : acquireWL(964f8d): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{1000},
06-22 07:49:59.992  1614  2040 D AlarmManager: sending alarm PendingIntent{2bd61bc: PendingIntentRecord{1d21545 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=209802, Int=0
06-22 07:49:59.992  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238579, Int=0
06-22 07:49:59.992  1614  2040 D AlarmManager: sending alarm PendingIntent{626a37b: PendingIntentRecord{4b0542 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=418579, Int=0
06-22 07:49:59.992  1614  2040 D AlarmManager: sending alarm PendingIntent{e978953: PendingIntentRecord{b8ef290 com.htc.widget.weatherclock broadcastIntent}}, i=com.htc.widget.weatherclock.action.TRIGGER_WEATHER_DATA, t=1, cnt=1, w=1466574425284, Int=0
06-22 07:49:59.992  1614  2683 D PMS     : acquireWL(5255789): PARTIAL_WAKE_LOCK  NetworkTimeUpdateService 0x1 1614 1000 null
06-22 07:49:59.992  1614  2683 D PMS     : releaseWL(5255789): PARTIAL_WAKE_LOCK  NetworkTimeUpdateService 0x1 null
,06-22 07:50:00.002  1614  2757 D PMS     : acquireWL(e88338e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.012  1614  2692 I ActivityManager: Start proc 6711:com.htc.widget.hmsproc2/u0a45 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver,
,06-22 07:50:00.102  1614  1668 D PMS     : acquireWL(d8767af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.142  6711  6711 W System  : ClassLoader referenced unknown path: /system/priv-app/HtcWeatherClockWidget/lib/arm64
,06-22 07:50:00.152  1614  1614 D PMS     : releaseWL(964f8d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10045}
,06-22 07:50:00.172  1614  2407 D AlarmManager: [AlarmGrouping_3.5] before: 857fa9a 2016-06-22 07:56:29 808404 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=292229 interval=0
06-22 07:50:00.172  1614  2407 D AlarmManager: [AlarmGrouping_3.5] after:  857fa9a 2016-06-22 08:00:00 1018579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=292229 interval=0
06-22 07:50:00.172  1614  2700 D PMS     : releaseWL(e88338e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.202  6711  6725 D WeatherUtility: Weather sync is On,
,06-22 07:50:00.262  6711  6725 W WeatherRequest: request cur loc, but there is no sys cur,
06-22 07:50:00.262  6711  6725 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:50:00.292  2750  2750 I RemoteViews: apply(18,2)/com.htc.widget.weatherclock
,06-22 07:50:00.352  1614  1627 I art     : Background partial concurrent mark sweep GC freed 22192(1628KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 23MB/35MB, paused 1.462ms total 126.021ms,
,06-22 07:50:00.452  1614  2407 D PMS     : acquireWL(e8735fd): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.462  1614  2671 D AlarmManager: [AlarmGrouping_3.5] before: b1634f9 2026-06-20 07:50:00 315360419056 name=com.google.android.gms action=null type=ELAPSED_WAKEUP window=236519999998 interval=0
06-22 07:50:00.462  1614  2671 D AlarmManager: [AlarmGrouping_3.5] after:  b1634f9 2026-06-20 08:00:00 315361018579 name=com.google.android.gms action=null type=ELAPSED_WAKEUP window=236519999998 interval=0
,06-22 07:50:00.482  3423  3423 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b3d99f6b-4797-4858-878b-63b935740c91,
,06-22 07:50:00.492  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:50:00.492  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:50:00.672  1614  2877 D PMS     : acquireWL(85890ee): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.682  3423  3609 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-22 07:50:00.682  1614  2756 D PMS     : releaseWL(85890ee): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.692  3423  3685 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-22 07:50:00.692  5259  6723 D UdcContextInitService: registered all accounts: true,
,06-22 07:50:00.772  3423  3685 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-22 07:50:00.772  3423  3423 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null},
06-22 07:50:00.782  1614  1667 D PMS     : releaseWL(e8735fd): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms},
,06-22 07:50:00.792  1614  2735 D PMS     : releaseWL(d8767af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
06-22 07:50:00.792  1614  2877 D PMS     : acquireWL(dc0cdfa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.802  1614  1667 D AlarmManager: [AlarmGrouping_3.5] before: 3360fab 2016-06-22 07:56:29 808404 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=291759 interval=0
06-22 07:50:00.802  1614  1667 D AlarmManager: [AlarmGrouping_3.5] after:  3360fab 2016-06-22 08:00:00 1018579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=291759 interval=0,
,06-22 07:50:00.802  1614  3927 D PMS     : releaseWL(dc0cdfa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,06-22 07:50:00.802  1614  2460 D PMS     : acquireWL(cf608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.852  1614  3927 D PMS     : acquireWL(aab61a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.882  1614  2460 D AlarmManager: [AlarmGrouping_3.5] before: 6c3fb87 2016-06-22 08:56:53 4432090 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=3009462 interval=0,
06-22 07:50:00.882  1614  2460 D AlarmManager: [AlarmGrouping_3.5] after:  6c3fb87 2016-06-22 09:00:00 4618579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=3009462 interval=0
,06-22 07:50:00.882  1614  2727 D PMS     : releaseWL(cf608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.892  3423  6731 I VacuumService: Vacuum at: now=1466574600905 tag=VacuumService,
,06-22 07:50:00.922  1614  2756 D PMS     : releaseWL(aab61a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,06-22 07:50:00.922  1614  2757 D PMS     : acquireWL(97f6ab4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.932  1614  3927 D AlarmManager: [AlarmGrouping_3.5] before: 8fb76dd 2016-06-22 08:56:53 4432090 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=3009422 interval=0
06-22 07:50:00.932  1614  3927 D AlarmManager: [AlarmGrouping_3.5] after:  8fb76dd 2016-06-22 09:00:00 4618580 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=3009422 interval=0
06-22 07:50:00.932  1614  2460 D PMS     : releaseWL(97f6ab4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:50:00.942  1614  2727 D PMS     : acquireWL(d372252): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms},
,06-22 07:50:00.972  1614  2692 D AlarmManager: [AlarmGrouping_3.5] before: a5ac923 2016-06-22 07:56:29 808404 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=291627 interval=0,
06-22 07:50:00.972  1614  2692 D AlarmManager: [AlarmGrouping_3.5] after:  a5ac923 2016-06-22 08:00:00 1018579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=291627 interval=0
,06-22 07:50:00.982  1614  2671 D PMS     : releaseWL(d372252): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:50:01.302  1614  1667 D Process : killProcessQuiet, pid=6384,
06-22 07:50:01.302  1614  1667 I ActivityManager: Killing 6384:com.htc.sense.socialnetwork.googleplus/u0a25 (adj 15): empty #17
06-22 07:50:01.302  1614  1667 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 07:50:01.422  1614  1668 I ActivityManager: Recipient 6384
,06-22 07:50:44.202   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:50:54.202   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:51:00.832  1614  2877 D PMS     : acquireWL(6027e20): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:51:00.902  3423  3685 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.,
06-22 07:51:00.902  3423  3685 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.,
,06-22 07:51:00.912  3423  3685 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-22 07:51:00.912  3423  3685 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
,06-22 07:51:00.912  3423  3685 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-22 07:51:00.922  3423  3685 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-22 07:51:00.922  1614  2756 D PMS     : releaseWL(6027e20): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:51:09.212   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 07:51:29.212   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-22 07:51:54.222   475   475 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:52:49.322  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:52:59.312  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:53:08.062  1614  2757 D PMS     : acquireWL(e3da3d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null,
06-22 07:53:08.062  1614  2757 I BatteryService: n_update end
06-22 07:53:08.062  1614  2757 D PMS     : releaseWL(e3da3d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:53:14.312  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 07:53:29.142  2729  2844 D ContactMessageStore: MSG_CHECK_DELETION >>
,06-22 07:53:29.142  2729  2844 D ContactMessageStore: mDeleteTask = null, bDeleting = false,
,06-22 07:53:29.152  2729  2844 D AccFlag : sense_version=7.0
,06-22 07:53:29.152  2729  2844 D AccFlag : sense 7.0, sku_id=99
,06-22 07:53:29.152  2729  2844 D ContactMessageStore: MSG_CHECK_DELETION <<
,06-22 07:53:29.152  2729  6740 D ContactMessageStore: start background delete task...
,06-22 07:53:29.152  2729  6740 D ContactMessageStore: size: 0 , 0
,06-22 07:53:29.162  2729  6740 D ContactMessageStore: Background delete complete
,06-22 07:53:32.462  3730  3737 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     Turn end: total_sum=30 screen_off_sum=30,
,06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     screen_off_now=true screen_off_always=true total_sum=60 screen_off_sum=55 threshold=0.8
,06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.google.process.gapps com.google.android.gsf 400 280911
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.google.android.gms.persistent com.google.android.gms 200 303271
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     org.simalliance.openmobileapi.service:remote org.simalliance.openmobileapi.service 200 305331
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.qualcomm.qti.tetherservice com.qualcomm.qti.tetherservice 100 306461
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.quicinc.cne.CNEService com.quicinc.cne.CNEService 100 306511
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.google.android.googlequicksearchbox:interactor com.google.android.googlequicksearchbox 100 306861
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.test.thalitest com.test.thalitest 150 232281
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.google.android.gms com.google.android.gms 400 279121
06-22 07:53:33.662  1614  2355 D HtcWLD_v5.3.2:     com.google.android.apps.plus com.google.android.apps.plus 400 261241
,06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     com.google.android.apps.docs com.google.android.apps.docs 400 235091
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     com.nero.android.htc.sync com.nero.android.htc.sync 300 272691
06-22 07:53:33.672  1614  2355 D HtcPitroadConnector: [HtcWLD] Clear list
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for KnownIssueList case.
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     all normal
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for GPS case.
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     No one requests location, do nothing.
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for wakelock case.
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     There is no wakelock held over 600000 ms
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for crazy CPU usage case.
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     all normal
06-22 07:53:33.672  1614  2355 D HtcPitroadConnector: [HtcWLD] Nothing to send.
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2: << Wake Lock Detector >>,
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:  
06-22 07:53:33.672  1614  2355 D HtcWLD_v5.3.2:     Turn#1
,06-22 07:53:34.322  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-22 07:53:35.182  1614  2671 D PMS     : acquireWL(b01119e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null,
06-22 07:53:35.192  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:53:35.182  1614  2671 I BatteryService: n_update end
06-22 07:53:35.192  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:53:35.192  2594  2594 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,mbIsDeviceSupportDotView:true
06-22 07:53:35.192  1614  2671 D PMS     : releaseWL(b01119e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:53:35.192  1614  1614 I BatteryLightController: updateBattery(plugged=true plugin=true low=false full=true health=2 status=5 timeout=false usbOverheat=false)
06-22 07:53:35.192  1614  1852 D HtcPowerSaver: updateBatteryInfo
06-22 07:53:35.192  1614  1614 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:53:35.192  1614  1614 I DeviceIdleController: updateChargingLocked: charging=true
06-22 07:53:35.192  1614  1614 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:53:35.192  2401  2401 D PowerUI : closing low battery warning: level=100
06-22 07:53:35.192  1614  1614 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:53:35.192  1614  1614 W DeviceIdleController: becomeActiveLocked, reason = charging
,06-22 07:53:35.192  1614  1614 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:53:35.192  1614  1614 D PMS     : runPSCheck
06-22 07:53:35.192  2401  2401 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
06-22 07:53:35.192  1614  1614 D HtcPowerSaver: Checking...
06-22 07:53:35.192  2401  2401 I QuickSettingPowerSaverEX: batteryLevelChanged:true
06-22 07:53:35.192  1614  1614 I HtcPowerSaver: >> updateStatus
06-22 07:53:35.192  2401  2401 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
06-22 07:53:35.192  1614  1614 I HtcPowerSaver: << updateStatus
,06-22 07:53:35.202  2401  2401 I BatteryController: status:5 health:2 level:100 unsupport:false plugged:true timeout:falsecharging:true
,06-22 07:53:59.332  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-22 07:54:08.162  1614  2040 D PMS     : acquireWL(106d47f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1614 1000 WorkSource{1000}
06-22 07:54:08.162  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=478579, Int=0
,06-22 07:54:08.162  6216  6216 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false,
06-22 07:54:08.172  1614  2040 D AlarmManager: sending alarm PendingIntent{1dba495: PendingIntentRecord{adcdda8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574818338, Int=0
06-22 07:54:08.172  1614  2040 D AlarmManager: sending alarm PendingIntent{6e8a9aa: PendingIntentRecord{83e399b com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1466574848168, Int=1800000
06-22 07:54:08.172  1614  2040 D AlarmManager: sending alarm PendingIntent{edf138: PendingIntentRecord{b8ef290 com.htc.widget.weatherclock broadcastIntent}}, i=com.htc.widget.weatherclock.action.TRIGGER_WEATHER_DATA, t=1, cnt=1, w=1466574780283, Int=0
,06-22 07:54:08.182  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:54:08.192  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:54:08.192  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:54:08.202  1614  2727 D PMS     : acquireWL(641af50): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 5259 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:54:08.232  1614  2877 D PMS     : acquireWL(356d15a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 5259 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:54:08.242  1614  2735 D PMS     : releaseWL(641af50): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:54:08.242  6711  6746 D WeatherUtility: Weather sync is On
,06-22 07:54:08.302  1614  1614 D PMS     : releaseWL(106d47f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 07:54:08.322  6216  6244 D libc    : [NET] android_getaddrinfofornetcontext+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024, proc=com.android.vending
06-22 07:54:08.322  6216  6244 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:54:08.322   426  6748 D libc    : [NET] android_getaddrinfofornetcontext+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024, proc=/system/bin/netd
06-22 07:54:08.322   426  6748 D libc    : [NET] android_getaddrinfo_proxy-, fd error: Success(0)
06-22 07:54:08.322   426  6748 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,06-22 07:54:08.322  5259  6747 I EventLogChimeraService: Aggregate from 1466573047963 (log), 1466573047963 (data),
,06-22 07:54:08.322  6216  6244 D libc    : [NET] android_getaddrinfo_proxy-, NODATA,
06-22 07:54:08.332  6711  6746 W WeatherRequest: request cur loc, but there is no sys cur
06-22 07:54:08.332  6711  6746 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:54:08.332  6216  6216 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,06-22 07:54:08.342  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:54:08.362  2750  2750 I RemoteViews: apply(18,3)/com.htc.widget.weatherclock,
,06-22 07:54:08.372  6216  6216 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-22 07:54:08.382  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:54:08.442  6216  6216 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,06-22 07:54:08.512  1614  2700 D AlarmManager: [AlarmGrouping_3.5] before: 9f6a944 2016-06-22 08:24:08 1466576648481 name=com.google.android.gms action=null type=RTC_WAKEUP window=1350000 interval=1800000,
06-22 07:54:08.512  1614  2700 D AlarmManager: [AlarmGrouping_3.5] after:  9f6a944 2016-06-22 08:30:00 1466577000000 name=com.google.android.gms action=null type=RTC_WAKEUP window=1350000 interval=1800000
06-22 07:54:08.512  1614  2757 D PMS     : releaseWL(356d15a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:54:08.522  5259  6749 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.,
,06-22 07:54:08.532  5259  6749 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-22 07:54:08.812  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:54:08.852  6216  6216 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-22 07:54:08.852  6216  6216 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,06-22 07:54:08.872  6216  6216 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,06-22 07:54:08.882  1614  2756 D PMS     : acquireWL(d3441e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 07:54:08.882  6216  6216 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 31 minutes (failures=2),
06-22 07:54:08.882  1614  2040 D PMS     : acquireWL(77204ba): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10074}
06-22 07:54:08.882  1614  2040 D AlarmManager: sending alarm PendingIntent{ad8df6b: PendingIntentRecord{a2beac8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1466574848871, Int=0
,06-22 07:54:08.902  3423  3628 D DeviceConnectionService: client connected with version: 8486000,
,06-22 07:54:08.902  1614  2700 D PMS     : acquireWL(3f1c89d): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 6216 10074 null,
06-22 07:54:08.902  1614  1614 D PMS     : releaseWL(77204ba): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10074}
,06-22 07:54:08.912  6216  6751 I Finsky  : [490] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-22 07:54:08.912  6216  6255 I PlayCommon: [475] com.google.android.play.a.w.a(27551): Starting to flush logs
,06-22 07:54:08.942  1614  2735 D AlarmManager: [AlarmGrouping_3.5] before: 20fd0e3 2016-06-22 07:56:29 808404 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=105651 interval=0
,06-22 07:54:08.942  1614  2735 D AlarmManager: [AlarmGrouping_3.5] after:  20fd0e3 2016-06-22 08:00:00 1018579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=105651 interval=0
06-22 07:54:08.942  1614  2407 D PMS     : releaseWL(d3441e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:54:08.952  3423  3423 D WearableService: callingUid 10029, callindPid: 3423,
,06-22 07:54:08.962  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:54:08.962  6216  6216 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
06-22 07:54:08.962  6216  6216 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
,06-22 07:54:08.982  6216  6255 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=com.android.vending
,06-22 07:54:08.982  6216  6255 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:54:08.982   426  6752 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=/system/bin/netd
06-22 07:54:08.982   426  6752 D libc    : [NET] android_getaddrinfo_proxy-, fd error: Success(0)
06-22 07:54:08.982   426  6752 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
06-22 07:54:08.982  6216  6255 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-22 07:54:08.992  6216  6255 I PlayCommon: [475] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
,06-22 07:54:08.992  1614  2692 D PMS     : releaseWL(3f1c89d): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,06-22 07:54:13.792  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:54:13.822  6216  6255 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=com.android.vending,
06-22 07:54:13.832  6216  6255 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:54:13.832   426  6753 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=/system/bin/netd
06-22 07:54:13.832   426  6753 D libc    : [NET] android_getaddrinfo_proxy-, fd error: Success(0)
06-22 07:54:13.832   426  6753 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,06-22 07:54:13.832  6216  6255 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-22 07:54:23.452  6216  6258 I Finsky  : [478] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
06-22 07:54:23.452  1614  2040 D PMS     : acquireWL(fd89ad1): PARTIAL_WAKE_LOCK  *alarm* 0x1 1614 1000 WorkSource{10074}
,06-22 07:54:23.462  1614  2040 D AlarmManager: sending alarm PendingIntent{d0bc936: PendingIntentRecord{a45c7c2 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574863458, Int=0
06-22 07:54:23.462  1614  1614 D PMS     : releaseWL(fd89ad1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10074}
,06-22 07:54:23.762  6216  6258 I Finsky  : [478] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.,
06-22 07:54:23.762  6216  6216 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,06-22 07:54:34.332  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:54:35.352  1614  1668 D PMS     : acquireWL(b175037): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null,
06-22 07:54:35.352  1614  1668 I BatteryService: n_update end
06-22 07:54:35.352  1614  1668 D PMS     : releaseWL(b175037): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:54:35.352  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:54:35.352  2401  2401 D PowerUI : closing low battery warning: level=100
06-22 07:54:35.352  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,06-22 07:54:35.352  1614  1852 D HtcPowerSaver: updateBatteryInfo,
06-22 07:54:35.352  2594  2594 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,mbIsDeviceSupportDotView:true
06-22 07:54:35.352  1614  1614 I DeviceIdleController: updateChargingLocked: charging=true
06-22 07:54:35.352  1614  1614 I BatteryLightController: updateBattery(plugged=true plugin=true low=false full=true health=2 status=5 timeout=false usbOverheat=false)
06-22 07:54:35.352  1614  1614 W DeviceIdleController: becomeActiveLocked, reason = charging
06-22 07:54:35.352  1614  1614 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:54:35.352  1614  1614 D PMS     : runPSCheck
06-22 07:54:35.352  1614  1614 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:54:35.352  1614  1614 D HtcPowerSaver: Checking...
06-22 07:54:35.352  1614  1614 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:54:35.352  1614  1614 I HtcPowerSaver: >> updateStatus
06-22 07:54:35.352  1614  1614 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:54:35.362  1614  1614 I HtcPowerSaver: << updateStatus
06-22 07:54:35.362  2401  2401 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
06-22 07:54:35.362  2401  2401 I QuickSettingPowerSaverEX: batteryLevelChanged:true
06-22 07:54:35.362  2401  2401 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
06-22 07:54:35.362  2401  2401 I BatteryController: status:5 health:2 level:100 unsupport:false plugged:true timeout:falsecharging:true
,06-22 07:54:44.332  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-22 07:54:59.342  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:55:19.352  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:55:44.352  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:56:24.352  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:56:29.812  1614  2040 D PMS     : acquireWL(4e819a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1614 1000 WorkSource{1000},
06-22 07:56:29.812  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=718579, Int=0
06-22 07:56:29.812  1614  2040 D AlarmManager: sending alarm PendingIntent{20fd0e3: PendingIntentRecord{4b0542 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=1018579, Int=0
,06-22 07:56:29.832  1614  2460 D PMS     : acquireWL(77b130d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms},
,06-22 07:56:29.902  1614  2735 D AlarmManager: [AlarmGrouping_3.5] before: 84342c2 2016-06-22 08:00:53 1072083 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=197695 interval=0,
06-22 07:56:29.902  1614  2735 D AlarmManager: [AlarmGrouping_3.5] after:  84342c2 2016-06-22 08:10:00 1618579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=197695 interval=0
06-22 07:56:29.902  1614  3927 D PMS     : releaseWL(77b130d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 07:56:29.922  1614  1614 D PMS     : releaseWL(4e819a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 07:56:32.142  1614  1668 D PMS     : acquireWL(706b8d3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null,
06-22 07:56:32.142  1614  1668 I BatteryService: n_update end
06-22 07:56:32.152  1614  1668 D PMS     : releaseWL(706b8d3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:56:32.152  1614  1614 I BatteryLightController: updateBattery(plugged=true plugin=true low=false full=true health=2 status=5 timeout=false usbOverheat=false)
06-22 07:56:32.152  1614  1614 I DeviceIdleController: updateChargingLocked: charging=true
06-22 07:56:32.152  1614  1614 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:56:32.152  1614  1614 W DeviceIdleController: becomeActiveLocked, reason = charging
06-22 07:56:32.152  1614  1614 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:56:32.152  1614  1852 D HtcPowerSaver: updateBatteryInfo
06-22 07:56:32.152  1614  1614 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:56:32.152  1614  1614 D PMS     : runPSCheck
06-22 07:56:32.152  1614  1614 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:56:32.152  1614  1614 D HtcPowerSaver: Checking...
06-22 07:56:32.152  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:56:32.152  1614  1614 I HtcPowerSaver: >> updateStatus
06-22 07:56:32.152  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:56:32.152  2594  2594 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,mbIsDeviceSupportDotView:true
06-22 07:56:32.152  1614  1614 I HtcPowerSaver: << updateStatus
,06-22 07:56:32.162  2401  2401 D PowerUI : closing low battery warning: level=100
06-22 07:56:32.162  2401  2401 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
06-22 07:56:32.162  2401  2401 I QuickSettingPowerSaverEX: batteryLevelChanged:true
06-22 07:56:32.162  2401  2401 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
06-22 07:56:32.162  2401  2401 I BatteryController: status:5 health:2 level:100 unsupport:false plugged:true timeout:falsecharging:true
,06-22 07:56:34.362  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-22 07:56:49.362  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:57:09.362  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:57:32.312  1614  2735 D PMS     : acquireWL(5f2c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null
06-22 07:57:32.312  1614  2735 I BatteryService: n_update end
06-22 07:57:32.312  1614  2735 D PMS     : releaseWL(5f2c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:57:32.312  1614  1852 D HtcPowerSaver: updateBatteryInfo
06-22 07:57:32.312  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:57:32.312  2401  2401 D PowerUI : closing low battery warning: level=100
06-22 07:57:32.312  2594  2594 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
06-22 07:57:32.312  1614  1614 I DeviceIdleController: updateChargingLocked: charging=true
06-22 07:57:32.312  2594  2594 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,mbIsDeviceSupportDotView:true
06-22 07:57:32.312  1614  1614 W DeviceIdleController: becomeActiveLocked, reason = charging
06-22 07:57:32.312  1614  1614 I BatteryLightController: updateBattery(plugged=true plugin=true low=false full=true health=2 status=5 timeout=false usbOverheat=false)
06-22 07:57:32.312  1614  1614 D PMS     : runPSCheck
06-22 07:57:32.312  1614  1614 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:57:32.312  1614  1614 D HtcPowerSaver: Checking...
06-22 07:57:32.312  1614  1614 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:57:32.312  1614  1614 I HtcPowerSaver: >> updateStatus
06-22 07:57:32.312  1614  1614 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:57:32.322  1614  1614 I HtcPowerSaver: << updateStatus
06-22 07:57:32.312  1614  1614 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:57:32.322  2401  2401 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
06-22 07:57:32.322  2401  2401 I QuickSettingPowerSaverEX: batteryLevelChanged:true
06-22 07:57:32.322  2401  2401 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
06-22 07:57:32.322  2401  2401 I BatteryController: status:5 health:2 level:100 unsupport:false plugged:true timeout:falsecharging:true
,06-22 07:57:34.372  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-22 07:58:19.372  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:58:29.382  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:58:33.862  1614  2355 D HtcWLD_v5.3.2:     Turn end: total_sum=30 screen_off_sum=30,
06-22 07:58:33.862  1614  2355 D HtcWLD_v5.3.2:  ,
06-22 07:58:33.862  1614  2355 D HtcWLD_v5.3.2:     Turn#2,
,06-22 07:58:44.392  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:59:04.392  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-22 07:59:13.952  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:59:13.962  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:59:13.962  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,06-22 07:59:14.022  6216  6255 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=com.android.vending,
06-22 07:59:14.022  6216  6255 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:59:14.022   426  6755 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=/system/bin/netd
,06-22 07:59:14.022   426  6755 D libc    : [NET] android_getaddrinfo_proxy-, fd error: Success(0)
06-22 07:59:14.022   426  6755 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
06-22 07:59:14.022  6216  6255 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-22 07:59:29.402  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 08:00:19.392  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 08:00:29.412  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 08:00:44.412  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 08:00:53.492  1614  2040 D PMS     : acquireWL(ea6b527): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1614 1000 WorkSource{1000},
06-22 08:00:53.492  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=838579, Int=0,
06-22 08:00:53.492  1614  2040 D AlarmManager: sending alarm PendingIntent{84342c2: PendingIntentRecord{4b0542 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=1618579, Int=0
06-22 08:00:53.492  1614  2040 D AlarmManager: sending alarm PendingIntent{b5733d4: PendingIntentRecord{b8ef290 com.htc.widget.weatherclock broadcastIntent}}, i=com.htc.widget.weatherclock.action.TRIGGER_WEATHER_DATA, t=1, cnt=1, w=1466575028345, Int=0
,06-22 08:00:53.492  1614  2040 D AlarmManager: sending alarm PendingIntent{fe3d97d: PendingIntentRecord{1621a34 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1466575144498, Int=0
06-22 08:00:53.502  1614  2460 D PMS     : acquireWL(3f5e072): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 08:00:53.562  1614  2727 I ActivityManager: Start proc 6757:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
,06-22 08:00:53.582  6711  6762 D WeatherUtility: Weather sync is On,
,06-22 08:00:53.582  1614  2671 D AlarmManager: [AlarmGrouping_3.5] before: 8ddb940 2016-06-22 08:01:23 1102098 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=22444 interval=0
,06-22 08:00:53.582  1614  2671 D AlarmManager: [AlarmGrouping_3.5] after:  8ddb940 2016-06-22 08:10:00 1618579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=22444 interval=0
,06-22 08:00:53.592  1614  1667 D PMS     : releaseWL(3f5e072): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 08:00:53.632  6711  6762 W WeatherRequest: request cur loc, but there is no sys cur,
06-22 08:00:53.632  6711  6762 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 08:00:53.652  6757  6757 W System  : ClassLoader referenced unknown path: /system/priv-app/HtcPowerManager/lib/arm64,
,06-22 08:00:53.662  2750  2750 I RemoteViews: apply(18,2)/com.htc.widget.weatherclock,
,06-22 08:00:53.672  6757  6757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1229 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:21 android.app.ActivityThread.handleReceiver:2835 ,
06-22 08:00:53.672  1614  1614 D PMS     : releaseWL(ea6b527): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 08:00:53.672  6757  6770 D PowerUtils: getUserIdOfProcess, curUserId = 0,
06-22 08:00:53.672  6757  6770 D PowerUtils: isRunningUnderOwner, isOwner = true
,06-22 08:00:53.682  6757  6770 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
,06-22 08:00:53.692  6757  6770 D PowerUsageService: repeat time = 1466576153701,
,06-22 08:00:53.692  1614  2735 E WifiStateMachine: syncGetLinkLayerStats return null, due to not ready,
06-22 08:00:53.692  1614  2735 E KernelWakelockReader: neither /proc/wakelocks nor /d/wakeup_sources exists
06-22 08:00:53.692  1614  2735 W BatSI   : Couldn't get kernel wake lock stats
,06-22 08:00:53.772  5259  6771 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.,
,06-22 08:00:53.782  1614  2756 E WifiStateMachine: syncGetLinkLayerStats return null, due to not ready
,06-22 08:00:53.792  1614  2756 E KernelWakelockReader: neither /proc/wakelocks nor /d/wakeup_sources exists,
06-22 08:00:53.792  1614  2756 W BatSI   : Couldn't get kernel wake lock stats
,06-22 08:00:53.862  5259  6772 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.,
,06-22 08:00:53.862  6757  6770 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8,
,06-22 08:00:53.882  6757  6770 D PowerUtils: getUserIdOfProcess, curUserId = 0
,06-22 08:00:53.892  6757  6770 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,06-22 08:00:53.892  6757  6770 D HtcWrapCustomizationManager: [ACC][RR] Method:getCustomizationReader
,06-22 08:00:53.892  6757  6770 D HtcWrapCustomizationManager: [ACC][RR] Method:getCustomizationReader
,06-22 08:00:54.682  1614  1668 D Process : killProcessQuiet, pid=6397,
06-22 08:00:54.682  1614  1668 I ActivityManager: Killing 6397:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
06-22 08:00:54.682  1614  1668 D Process : com.android.server.am.ProcessRecord.kill:582 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20324 com.android.server.am.ActivityManagerService.updateOomAdjLocked:20161 
,06-22 08:00:54.772  1614  2735 I ActivityManager: Recipient 6397,
,06-22 08:01:04.412  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 08:01:23.512  1614  2040 D PMS     : acquireWL(c881a96): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1614 1000 WorkSource{1000}
06-22 08:01:23.512  1614  2040 D AlarmManager: sending alarm PendingIntent{fed5c74: PendingIntentRecord{ff3e59d android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1078579, Int=0
,06-22 08:01:23.512  1614  2040 D AlarmManager: sending alarm PendingIntent{8ddb940: PendingIntentRecord{4b0542 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=1618579, Int=0
,06-22 08:01:23.512  1614  1668 D PMS     : acquireWL(4113617): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3423 10029 WorkSource{10029 com.google.android.gms}
,06-22 08:01:23.602  1614  1667 D AlarmManager: [AlarmGrouping_3.5] before: 6993a04 2016-06-22 08:44:02 3661234 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=1919282 interval=0,
06-22 08:01:23.602  1614  1667 D AlarmManager: [AlarmGrouping_3.5] after:  6993a04 2016-06-22 08:50:00 4018579 name=com.google.android.gms action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE type=ELAPSED_WAKEUP window=1919282 interval=0,
06-22 08:01:23.602  1614  1668 D PMS     : releaseWL(4113617): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,06-22 08:01:23.612  1614  1614 D PMS     : releaseWL(c881a96): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 08:01:29.412  6736  6736 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-22 08:02:24.472  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-22 08:02:34.482  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-22 08:02:49.482  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 08:03:08.062  1614  2692 D PMS     : acquireWL(2031bed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1614 1000 null,
06-22 08:03:08.062  1614  2692 I BatteryService: n_update end
06-22 08:03:08.062  1614  2692 D PMS     : releaseWL(2031bed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 08:03:09.492  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 08:03:23.622  1614  1841 I UsageStatsService: User[0] Flushing usage stats to disk,
,06-22 08:03:32.472  3730  3737 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     Turn end: total_sum=30 screen_off_sum=30,
,06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     screen_off_now=true screen_off_always=true total_sum=60 screen_off_sum=60 threshold=0.8
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.test.thalitest com.test.thalitest 150 832652,
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.google.process.gapps com.google.android.gsf 400 881282
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.google.android.gms.persistent com.google.android.gms 200 903642
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.google.android.gms com.google.android.gms 400 879492
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.google.android.apps.plus com.google.android.apps.plus 400 861612
,06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.google.android.apps.docs com.google.android.apps.docs 400 835462
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.nero.android.htc.sync com.nero.android.htc.sync 300 873062
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     org.simalliance.openmobileapi.service:remote org.simalliance.openmobileapi.service 200 905702
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.qualcomm.qti.tetherservice com.qualcomm.qti.tetherservice 100 906832
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.quicinc.cne.CNEService com.quicinc.cne.CNEService 100 906882
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     com.google.android.googlequicksearchbox:interactor com.google.android.googlequicksearchbox 100 907232
06-22 08:03:34.072  1614  2355 D HtcPitroadConnector: [HtcWLD] Clear list
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:  
06-22 08:03:34.072  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for KnownIssueList case.
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     all normal
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:  
,06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for GPS case.
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     No one requests location, do nothing.
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:  
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for wakelock case.
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     There is no wakelock held over 600000 ms
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:  
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     # Check abnormal process for crazy CPU usage case.
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     all normal
06-22 08:03:34.082  1614  2355 D HtcPitroadConnector: [HtcWLD] Nothing to send.
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:  
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2: << Wake Lock Detector >>
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:  
06-22 08:03:34.082  1614  2355 D HtcWLD_v5.3.2:     Turn#1
,06-22 08:03:34.492  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-22 08:04:09.502  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 08:04:14.142  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 08:04:14.142  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 08:04:14.142  3423  3423 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 08:04:14.182  6216  6255 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=com.android.vending
,06-22 08:04:14.182  6216  6255 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 08:04:14.182   426  6779 D libc    : [NET] android_getaddrinfofornetcontext+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024, proc=/system/bin/netd
06-22 08:04:14.182   426  6779 D libc    : [NET] android_getaddrinfo_proxy-, fd error: Success(0)
06-22 08:04:14.182   426  6779 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,06-22 08:04:14.182  6216  6255 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-22 08:04:19.502  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 08:04:34.512  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 08:04:54.522  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-22 08:05:19.522  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-22 08:05:59.522  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-22 08:06:09.522  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 08:06:24.532  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 08:06:44.542  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 08:07:09.552  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-22 08:07:54.552  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 08:08:04.552  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-22 08:08:19.562  6775  6775 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,TIME-OUT KILL (timeout was 1400000ms),06-22 08:08:34.272  1614  2355 D HtcWLD_v5.3.2:     Turn end: total_sum=30 screen_off_sum=30
06-22 08:08:34.272  1614  2355 D HtcWLD_v5.3.2:  
06-22 08:08:34.272  1614  2355 D HtcWLD_v5.3.2:     Turn#2
06-22 08:08:37.922  6781  6781 E cutils-trace: Error opening trace file: No such file or directory (2)
06-22 08:08:37.932  6781  6781 W art     : 6f10f000-6ff31000 rw-p 00000000 103:0d 589826                            /data/dalvik-cache/arm64/system@framework@boot.art
06-22 08:08:37.932  6781  6781 W art     : 5583229000-558322e000 r-xp 00000000 103:0c 26                            /system/bin/app_process64
06-22 08:08:37.932  6781  6781 W art     : 558323d000-558323e000 r--p 00004000 103:0c 26                            /system/bin/app_process64
06-22 08:08:37.932  6781  6781 W art     : 558323e000-558323f000 rw-p 00005000 103:0c 26                            /system/bin/app_process64
06-22 08:08:37.932  6781  6781 W art     : 559ed56000-559ed92000 rw-p 00000000 00:00 0                              [heap]
06-22 08:08:37.932  6781  6781 W art     : 7f9cda9000-7f9f03f000 r--p 00000000 103:0c 8544                          /system/framework/arm64/boot.oat
06-22 08:08:37.932  6781  6781 W art     : 7f9f03f000-7fa1526000 r-xp 02296000 103:0c 8544                          /system/framework/arm64/boot.oat
06-22 08:08:37.932  6781  6781 W art     : 7fa1526000-7fa1527000 rw-p 0477d000 103:0c 8544                          /system/framework/arm64/boot.oat
06-22 08:08:37.932  6781  6781 W art     : 7fa1527000-7fa1551000 r--p 00e22000 103:0d 589826                        /data/dalvik-cache/arm64/system@framework@boot.art
06-22 08:08:37.932  6781  6781 W art     : 7fa1551000-7fa1552000 r-xp 00000000 103:0c 188644                        /system/lib64/libsigchain.so
06-22 08:08:37.932  6781  6781 W art     : 7fa1552000-7fa1561000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa1561000-7fa1562000 r--p 00000000 103:0c 188644                        /system/lib64/libsigchain.so
06-22 08:08:37.932  6781  6781 W art     : 7fa1562000-7fa1563000 rw-p 00001000 103:0c 188644                        /system/lib64/libsigchain.so
06-22 08:08:37.932  6781  6781 W art     : 7fa1563000-7fa1b52000 r-xp 00000000 103:0c 188480                        /system/lib64/libart.so
06-22 08:08:37.932  6781  6781 W art     : 7fa1b52000-7fa1b61000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa1b61000-7fa1b74000 r--p 005f8000 103:0c 188480                        /system/lib64/libart.so
06-22 08:08:37.932  6781  6781 W art     : 7fa1b74000-7fa1b76000 rw-p 0060b000 103:0c 188480                        /system/lib64/libart.so
06-22 08:08:37.932  6781  6781 W art     : 7fa1b76000-7fa1b79000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa1b7d000-7fa1b82000 r--p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa1b82000-7fa1ba2000 r--s 00000000 00:0c 3769                           /dev/__properties__
06-22 08:08:37.932  6781  6781 W art     : 7fa1ba2000-7fa1ba3000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 08:08:37.932  6781  6781 W art     : 7fa1ba3000-7fa1ba4000 r--p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa1ba4000-7fa1ba5000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 08:08:37.932  6781  6781 W art     : 7fa1ba5000-7fa2abc000 r-xp 00000000 103:0c 188457                        /system/lib64/libLLVM.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2abc000-7fa2acc000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2acc000-7fa2b67000 r--p 00f24000 103:0c 188457                        /system/lib64/libLLVM.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2b67000-7fa2b6b000 rw-p 00fbf000 103:0c 188457                        /system/lib64/libLLVM.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2b6b000-7fa2b79000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2b79000-7fa2bc4000 r-xp 00000000 103:0c 188473                        /system/lib64/libbcinfo.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2bc4000-7fa2bd4000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2bd4000-7fa2bd5000 r--p 0004b000 103:0c 188473                        /system/lib64/libbcinfo.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2bd5000-7fa2bd6000 rw-p 0004c000 103:0c 188473                        /system/lib64/libbcinfo.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2bd6000-7fa2c37000 r-xp 00000000 103:0c 188500       
06-22 08:08:37.932  6781  6781 W art     :                  /system/lib64/libbcc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c37000-7fa2c47000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2c47000-7fa2c49000 r--p 00062000 103:0c 188500                        /system/lib64/libbcc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c49000-7fa2c4a000 rw-p 00064000 103:0c 188500                        /system/lib64/libbcc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c4a000-7fa2c4b000 r--p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2c4b000-7fa2c4c000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa2c4c000-7fa2c58000 r-xp 00000000 103:0c 188511                        /system/lib64/libcommon_time_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c58000-7fa2c67000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2c67000-7fa2c6b000 r--p 0000f000 103:0c 188511                        /system/lib64/libcommon_time_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c6b000-7fa2c6c000 rw-p 00013000 103:0c 188511                        /system/lib64/libcommon_time_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c6c000-7fa2c8f000 r-xp 00000000 103:0c 188751                        /system/lib64/libprotobuf-cpp-lite.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2c8f000-7fa2c9f000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2c9f000-7fa2ca0000 r--p 00023000 103:0c 188751                        /system/lib64/libprotobuf-cpp-lite.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ca0000-7fa2ca1000 rw-p 00024000 103:0c 188751                        /system/lib64/libprotobuf-cpp-lite.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ca1000-7fa2cab000 r-xp 00000000 103:0c 188658                        /system/lib64/libstagefright_avc_common.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2cab000-7fa2cba000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2cba000-7fa2cbb000 r--p 00009000 103:0c 188658                        /system/lib64/libstagefright_avc_common.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2cbb000-7fa2cbc000 rw-p 0000a000 103:0c 188658                        /system/lib64/libstagefright_avc_common.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2cbc000-7fa2cbd000 r-xp 00000000 103:0c 188659                        /system/lib64/libstagefright_enc_common.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2cbd000-7fa2ccc000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2ccc000-7fa2ccd000 r--p 00000000 103:0c 188659                        /system/lib64/libstagefright_enc_common.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ccd000-7fa2cce000 rw-p 00001000 103:0c 188659                        /system/lib64/libstagefright_enc_common.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2cce000-7fa2cd1000 r-xp 00000000 103:0c 188627                        /system/lib64/libpowermanager.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2cd1000-7fa2ce1000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2ce1000-7fa2ce2000 r--p 00003000 103:0c 188627                        /system/lib64/libpowermanager.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ce2000-7fa2ce3000 rw-p 00004000 103:0c 188627                        /system/lib64/libpowermanager.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ce3000-7fa2d00000 r-xp 00000000 103:0c 188705                        /system/lib64/libvorbisidec.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d00000-7fa2d0f000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2d0f000-7fa2d10000 r--p 0001c000 103:0c 188705                        /system/lib64/libvorbisidec.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d10000-7fa2d11000 rw-p 0001d000 103:0c 188705                        /system/lib64/libvorbisidec.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d11000-7fa2d14000 r-xp 00000000 103:0c 188682                        /system/lib64/libstagefright_yuv.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d14000-7fa2d24000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2d24000-7fa2d25000 r--p 00003000 103:0c 188682                        /system/lib64/libstagefright_yuv.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d25000-7fa2d26000 rw-p 00004000 103:0c 188682                        /system/lib64/libstagefright_yuv.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d26000-7fa2d5f000 r-xp 00000000 103:0c 188662                        /system/lib64/libstagefright_omx.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d5f000-7fa2d6e000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2d6e000-7fa2d73000 r--p 0003e000 103:0c 188662                        /system/lib64/libstagefright_omx.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d73000-7fa2d74000 rw-p 00043000 103:0c 188662                        /system/lib64/libstagefright_omx.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2d74000-7fa2d75000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa2d75000-7fa2dc0000 r-xp 00000000 103:0c 188619                        /system/lib64/libopus.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2dc0000-7fa2dd0000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2dd0000-7fa2dd1000 r--p 0004b000 103:0c 188619                        /system/lib64/libopus.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2dd1000-7fa2dd2000 rw-p 0004c000 103:0c 188619                        /system/lib64/libopus.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2dd2000-7fa2dd9000 r-xp 00000000 103:0c 188748                        /system/lib64/libmediautils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2dd9000-7fa2de8000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2de8000-7fa2dea000 r--p 00007000 103:0c 188748                        /system/lib64/libmediautils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2dea000-7fa2deb000 rw-p 00009000 103:0c 188748                        /system/lib64/libmediautils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2deb000-7fa2e09000 r-xp 00000000 103:0c 188524                        /system/lib64/libdrmframework.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2e09000-7fa2e19000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2e19000-7fa2e1e000 r--p 00023000 103:0c 188524                        /system/lib64/libdrmframework.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2e1e000-7fa2e1f000 rw-p 00028000 103:0c 188524                        /system/lib64/libdrmframework.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2e1f000-7fa2e49000 r-xp 00000000 103:0c 188471                        /system/lib64/libRScpp.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2e49000-7fa2e58000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2e58000-7fa2e59000 r--p 00029000 103:0c 188471                        /system/lib64/libRScpp.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2e59000-7fa2e5a000 rw-p 0002a000 103:0c 188471                        /system/lib64/libRScpp.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2e5a000-7fa2e5b000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa2e5b000-7fa2eb0000 r-xp 00000000 103:0c 188469                        /system/lib64/libRS.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2eb0000-7fa2ec0000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2ec0000-7fa2ec3000 r--p 00058000 103:0c 188469                        /system/lib64/libRS.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ec3000-7fa2ec4000 rw-p 0005b000 103:0c 188469                        /system/lib64/libRS.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ec4000-7fa2ec5000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 08:08:37.932  6781  6781 W art     : 7fa2ec5000-7fa2ec8000 r-xp 00000000 103:0c 188724                        /system/lib64/libspeexresampler.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ec8000-7fa2ed7000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2ed7000-7fa2ed8000 r--p 00002000 103:0c 188724                        /system/lib64/libspeexresampler.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ed8000-7fa2ed9000 rw-p 00003000 103:0c 188724                        /system/lib64/libspeexresampler.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ed9000-7fa2ee5000 r-xp 00000000 103:0c 188610                        /system/lib64/libnbaio.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ee5000-7fa2ef5000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2ef5000-7fa2ef6000 r--p 0000c000 103:0c 188610                        /system/lib64/libnbaio.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ef6000-7fa2ef7000 rw-p 0000d000 103:0c 188610                        /system/lib64/libnbaio.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2ef7000-7fa2f11000 r-xp 00000000 103:0c 188750                        /system/lib64/libpcre.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f11000-7fa2f20000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2f20000-7fa2f21000 r--p 00019000 103:0c 188750                        /system/lib64/libpcre.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f21000-7fa2f22000 rw-p 0001a000 103:0c 188750                        /system/lib64/libpcre.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f22000-7fa2f23000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa2f23000-7fa2f28000 r-xp 00000000 103:0c 188714                        /system/lib64/libwpa_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f28000-7fa2f37000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2f37000-7fa2f38000 r--p 00004000 103:0c 188714                        /system/lib64/libwpa_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f38000-7fa2f39000 rw-p 00005000 103:0c 188714                        /system/lib64/libwpa_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f39000-7fa2f3a000 rw-p 00000000 00:00 0                              [anon:linker_alloc_64]
06-22 08:08:37.932  6781  6781 W art     : 7fa2f3a000-7fa2f48000 r-xp 00000000 103:0c 188566                        /system/lib64/libhostapd_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f48000-7fa2f58000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa2f58000-7fa2f59000 r--p 0000e000 103:0c 188566                        /system/lib64/libhostapd_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f59000-7fa2f5a000 rw-p 0000f000 103:0c 188566                        /system/lib64/libhostapd_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa2f5a000-7fa302a000 r-xp 00000000 103:0c 188454                        /system/lib64/libGLES_trace.so
06-22 08:08:37.932  6781  6781 W art     : 7fa302a000-7fa3039000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3039000-7fa303a000 r--p 000d2000 103:0c 188454                        /system/lib64/libGLES_trace.so
06-22 08:08:37.932  6781  6781 W art     : 7fa303a000-7fa303c000 rw-p 000d3000 103:0c 188454                        /system/lib64/libGLES_trace.so
06-22 08:08:37.932  6781  6781 W art     : 7fa303c000-7fa30a3000 r-xp 00000000 103:0c 188556                        /system/lib64/libft2.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30a3000-7fa30b3000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa30b3000-7fa30b6000 r--p 00069000 103:0c 188556                        /system/lib64/libft2.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30b6000-7fa30b7000 rw-p 0006c000 103:0c 188556                        /system/lib64/libft2.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30b7000-7fa30ec000 r-xp 00000000 103:0c 188624                        /system/lib64/libpng.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30ec000-7fa30fc000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa30fc000-7fa30fd000 r--p 00035000 103:0c 188624                        /system/lib64/libpng.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30fd000-7fa30fe000 rw-p 00036000 103:0c 188624                        /system/lib64/libpng.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30fe000-7fa30ff000 r-xp 00000000 103:0c 188689                        /system/lib64/libsync.so
06-22 08:08:37.932  6781  6781 W art     : 7fa30ff000-7fa310e000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa310e000-7fa310f000 r--p 00000000 103:0c 188689                        /system/lib64/libsync.so
06-22 08:08:37.932  6781  6781 W art     : 7fa310f000-7fa3110000 rw-p 00001000 103:0c 188689                        /system/lib64/libsync.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3110000-7fa3111000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa3111000-7fa3114000 r-xp 00000000 103:0c 188684                        /system/lib64/libstdc++.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3114000-7fa3123000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3123000-7fa3124000 r--p 00002000 103:0c 188684                        /system/lib64/libstdc++.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3124000-7fa3125000 rw-p 00003000 103:0c 188684                        /system/lib64/libstdc++.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3125000-7fa3140000 r-xp 00000000 103:0c 188698                        /system/lib64/libunwind.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3140000-7fa314f000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa314f000-7fa3150000 r--p 0001a000 103:0c 188698                        /system/lib64/libunwind.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3150000-7fa3151000 rw-p 0001b000 103:0c 188698                        /system/lib64/libunwind.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3151000-7fa31ba000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa31ba000-7fa31bb000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa31bb000-7fa31c4000 r-xp 00000000 103:0c 188738                        /system/lib64/libbase.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31c4000-7fa31d3000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa31d3000-7fa31d4000 r--p 00008000 103:0c 188738                        /system/lib64/libbase.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31d4000-7fa31d5000 rw-p 00009000 103:0c 188738                        /system/lib64/libbase.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31d5000-7fa31da000 r-xp 00000000 103:0c 188548           
06-22 08:08:37.932  6781  6781 W art     :              /system/lib64/libeffects.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31da000-7fa31e9000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa31e9000-7fa31ea000 r--p 00004000 103:0c 188548                        /system/lib64/libeffects.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31ea000-7fa31eb000 rw-p 00005000 103:0c 188548                        /system/lib64/libeffects.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31eb000-7fa31ec000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa31ec000-7fa31ee000 r-xp 00000000 103:0c 188661                        /system/lib64/libstagefright_http_support.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31ee000-7fa31fd000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa31fd000-7fa31fe000 r--p 00001000 103:0c 188661                        /system/lib64/libsta
06-22 08:08:37.932  6781  6781 W art     : gefright_http_support.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31fe000-7fa31ff000 rw-p 00002000 103:0c 188661                        /system/lib64/libstagefright_http_support.so
06-22 08:08:37.932  6781  6781 W art     : 7fa31ff000-7fa321f000 r-xp 00000000 103:0c 188660                        /system/lib64/libstagefright_foundation.so
06-22 08:08:37.932  6781  6781 W art     : 7fa321f000-7fa322e000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa322e000-7fa3231000 r--p 00020000 103:0c 188660                        /system/lib64/libstagefright_foundation.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3231000-7fa3232000 rw-p 00023000 103:0c 188660                        /system/lib64/libstagefright_foundation.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3232000-7fa3459000 r-xp 00000000 103:0c 188625                        /system/lib64/libstagefright.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3459000-7fa3469000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3469000-7fa3480000 r--p 00227000 103:0c 188625                        /system/lib64/libstagefright.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3480000-7fa3481000 rw-p 0023e000 103:0c 188625                        /system/lib64/libstagefright.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3481000-7fa3484000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3484000-7fa351c000 r-xp 00000000 103:0c 188575                        /system/lib64/libhwui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa351c000-7fa352b000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa352b000-7fa3531000 r--p 0009e000 103:0c 188575                        /system/lib64/libhwui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3531000-7fa3532000 rw-p 000a4000 103:0c 188575                        /system/lib64/libhwui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3532000-7fa3533000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa3533000-7fa3535000 r-xp 00000000 103:0c 188754                        /system/lib64/libradio_metadata.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3535000-7fa3544000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3544000-7fa3545000 r--p 00001000 103:0c 188754                        /system/lib64/libradio_metadata.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3545000-7fa3546000 rw-p 00002000 103:0c 188754                        /system/lib64/libradio_metadata.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3546000-7fa3549000 r-xp 00000000 103:0c 188609                        /system/lib64/libnativebridge.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3549000-7fa3558000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3558000-7fa355a000 r--p 00002000 103:0c 188609                        /system/lib64/libnativebridge.so
06-22 08:08:37.932  6781  6781 W art     : 7fa355a000-7fa355b000 rw-p 00004000 103:0c 188609                        /system/lib64/libnativebridge.so
06-22 08:08:37.932  6781  6781 W art     : 7fa355b000-7fa355d000 r-xp 00000000 103:0c 188629                        /system/lib64/libprocessgroup.so
06-22 08:08:37.932  6781  6781 W art     : 7fa355d000-7fa356c000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa356c000-7fa356d000 r--p 00001000 103:0c 188629                        /system/lib64/libprocessgroup.so
06-22 08:08:37.932  6781  6781 W art     : 7fa356d000-7fa356e000 rw-p 00002000 103:0c 188629                        /system/lib64/libprocessgroup.so
06-22 08:08:37.932  6781  6781 W art     : 7fa356e000-7fa3583000 r-xp 00000000 103:0c 188604                        /system/lib64/libminikin.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3583000-7fa3593000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3593000-7fa3594000 r--p 00015000 103:0c 188604                        /system/lib64/libminikin.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3594000-7fa3595000 rw-p 00016000 103:0c 188604                        /system/lib64/libminikin.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3595000-7fa359f000 r-xp 00000000 103:0c 188650                        /system/lib64/libsoundtrigger.so
06-22 08:08:37.932  6781  6781 W art     : 7fa359f000-7fa35ae000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa35ae000-7fa35b2000 r--p 0000d000 103:0c 188650                        /system/lib64/libsoundtrigger.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35b2000-7fa35b3000 rw-p 00011000 103:0c 188650                        /system/lib64/libsoundtrigger.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35b3000-7fa35bd000 r-xp 00000000 103:0c 188753                        /system/lib64/libradio.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35bd000-7fa35cd000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa35cd000-7fa35d1000 r--p 0000e000 103:0c 188753                        /system/lib64/libradio.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35d1000-7fa35d2000 rw-p 00012000 103:0c 188753                        /system/lib64/libradio.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35d2000-7fa35d4000 r-xp 00000000 103:0c 188612                        /system/lib64/libnetd_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35d4000-7fa35e3000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa35e3000-7fa35e4000 r--p 00001000 103:0c 188612                        /system/lib64/libnetd_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35e4000-7fa35e5000 rw-p 00002000 103:0c 188612                        /system/lib64/libnetd_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35e5000-7fa35f8000 r-xp 00000000 103:0c 188578                        /system/lib64/libimg_utils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa35f8000-7fa3607000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3607000-7fa360a000 r--p 00013000 103:0c 188578                        /system/lib64/libimg_utils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa360a000-7fa360b000 rw-p 00016000 103:0c 188578                        /system/lib64/libimg_utils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa360b000-7fa3a2f000 r-xp 00000000 103:0c 188723                        /system/lib64/libpdfium.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a2f000-7fa3a3e000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3a3e000-7fa3a4f000 r--p 00428000 103:0c 188723                        /system/lib64/libpdfium.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a4f000-7fa3a54000 rw-p 00439000 103:0c 188723                        /system/lib64/libpdfium.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a54000-7fa3a55000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3a55000-7fa3a60000 r-xp 00000000 103:0c 188488                        /system/lib64/libaudioutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a60000-7fa3a6f000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3a6f000-7fa3a70000 r--p 0000a000 103:0c 188488                        /system/lib64/libaudioutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a70000-7fa3a71000 rw-p 0000b000 103:0c 188488                        /system/lib64/libaudioutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a71000-7fa3a72000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa3a72000-7fa3a8e000 r-xp 00000000 103:0c 188716                        /system/lib64/libz.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a8e000-7fa3a9d000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3a9d000-7fa3a9e000 r--p 0001b000 103:0c 188716                        /system/lib64/libz.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a9e000-7fa3a9f000 rw-p 0001c000 103:0c 188716                        /system/lib64/libz.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3a9f000-7fa3b0c000 r-xp 00000000 103:0c 188564                        /system/lib64/libharfbuzz_ng.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b0c000-7fa3b1b000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3b1b000-7fa3b1d000 r--p 0006c000 103:0c 188564                        /system/lib64/libharfbuzz_ng.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b1d000-7fa3b1e000 rw-p 0006e000 103:0c 188564                        /system/lib64/libharfbuzz_ng.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b1e000-7fa3b22000 r-xp 00000000 103:0c 188727                        /system/lib64/libusbhost.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b22000-7fa3b31000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3b31000-7fa3b32000 r--p 00003000 103:0c 188727                        /system/lib64/libusbhost.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b32000-7fa3b33000 rw-p 00004000 103:0c 188727                        /system/lib64/libusbhost.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b33000-7fa3b34000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa3b34000-7fa3b6a000 r-xp 00000000 103:0c 188590                        /system/lib64/libjpeg.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b6a000-7fa3b7a000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3b7a000-7fa3b7b000 r--p 00036000 103:0c 188590                        /system/lib64/libjpeg.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b7b000-7fa3b7c000 rw-p 00037000 103:0c 188590                        /system/lib64/libjpeg.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3b7c000-7fa3c4b000 r-xp 00000000 103:0c 188551                        /system/lib64/libmedia.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3c4b000-7fa3c5a000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3c5a000-7fa3c8f000 r--p 000d7000 103:0c 188551                        /system/lib64/libmedia.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3c8f000-7fa3c90000 rw-p 0010c000 103:0c 188551                        /system/lib64/libmedia.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3c90000-7fa3eac000 r-xp 00000000 103:0c 188576                        /system/lib64/libicui18n.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3eac000-7fa3ebc000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa3ebc000-7fa3ed0000 r--p 00226000 103:0c 188576                        /system/lib64/libicui18n.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3ed0000-7fa3ed1000 rw-p 0023a000 103:0c 188576                        /system/lib64/libicui18n.so
06-22 08:08:37.932  6781  6781 W art     : 7fa3ed1000-7fa4055000 r-xp 00000000 103:0c 188577                        /system/lib64/libicuuc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4055000-7fa4064000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4064000-7fa4076000 r--p 0018c000 103:0c 188577                        /system/lib64/libicuuc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4076000-7fa4077000 rw-p 0019e000 103:0c 188577                        /system/lib64/libicuuc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4077000-7fa407b000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa407b000-7fa40b5000 r-xp 00000000 103:0c 188655                        /system/lib64/libssl.so
06-22 08:08:37.932  6781  6781 W art     : 7fa40b5000-7fa40c5000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa40c5000-7fa40c7000 r--p 0003a000 103:0c 188655                        /system/lib64/libssl.so
06-22 08:08:37.932  6781  6781 W art     : 7fa40c7000-7fa40c8000 rw-p 0003c000 103:0c 188655                        /system/lib64/libssl.so
06-22 08:08:37.932  6781  6781 W art     : 7fa40c8000-7fa40c9000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa40c9000-7fa41cb000 r-xp 00000000 103:0c 188513                        /system/lib64/libcrypto.so
06-22 08:08:37.932  6781  6781 W art     : 7fa41cb000-7fa41da000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa41da000-7fa41ee000 r--p 00101000 103:0c 188513                        /system/lib64/libcrypto.so
06-22 08:08:37.932  6781  6781 W art     : 7fa41ee000-7fa41ef000 rw-p 00115000 103:0c 188513                        /system/lib64/libcrypto.so
06-22 08:08:37.932  6781  6781 W art     : 7fa41ef000-7fa4247000 r-xp 00000000 103:0c 188648                        /system/lib64/libsonivox.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4247000-7fa4257000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4257000-7fa4258000 r--p 00058000 103:0c 188648                        /system/lib64/libsonivox.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4258000-7fa4259000 rw-p 00059000 103:0c 188648                        /system/lib64/libsonivox.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4259000-7fa425a000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa425a000-7fa426f000 r-xp 00000000 103:0c 188641                        /system/lib64/libselinux.so
06-22 08:08:37.932  6781  6781 W art     : 7fa426f000-7fa427f000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa427f000-7fa4280000 r--p 00015000 103:0c 188641                        /system/lib64/libselinux.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4280000-7fa4281000 rw-p 00016000 103:0c 188641                        /system/lib64/libselinux.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4281000-7fa4282000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4282000-7fa428d000 r-xp 00000000 103:0c 188563                        /system/lib64/libhardware_legacy.so
06-22 08:08:37.932  6781  6781 W art     : 7fa428d000-7fa429c000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa429c000-7fa429d000 r--p 0000a000 103:0c 188563                        /system/lib64/libhardware_legacy.so
06-22 08:08:37.932  6781  6781 W art     : 7fa429d000-7fa429e000 rw-p 0000b000 103:0c 188563                        /system/lib64/libhardware_legacy.so
06-22 08:08:37.932  6781  6781 W art     : 7fa429e000-7fa429f000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa429f000-7fa42a1000 r-xp 00000000 103:0c 188562                        /system/lib64/libhardware.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42a1000-7fa42b0000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa42b0000-7fa42b1000 r--p 00001000 103:0c 188562                        /system/lib64/libhardware.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42b1000-7fa42b2000 rw-p 00002000 103:0c 188562                        /system/lib64/libhardware.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42b2000-7fa42b5000 r-xp 00000000 103:0c 188452                        /system/lib64/libETC1.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42b5000-7fa42c5000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa42c5000-7fa42c6000 r--p 00003000 103:0c 188452                        /system/lib64/libETC1.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42c6000-7fa42c7000 rw-p 00004000 103:0c 188452                        /system/lib64/libETC1.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42c7000-7fa42d7000 r-xp 00000000 103:0c 188456                        /system/lib64/libGLESv2.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42d7000-7fa42e6000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa42e6000-7fa42e7000 r--p 0000f000 103:0c 188456                        /system/lib64/libGLESv2.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42e7000-7fa42e8000 rw-p 00010000 103:0c 188456                        /system/lib64/libGLESv2.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42e8000-7fa42f1000 r-xp 00000000 103:0c 188455                        /system/lib64/libGLESv1_CM.so
06-22 08:08:37.932  6781  6781 W art     : 7fa42f1000-7fa4300000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4300000-7fa4301000 r--p 00008000 103:0c 188455                        /system/lib64/libGLESv1_CM.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4301000-7fa4302000 rw-p 00009000 103:0c 188455                        /system/lib64/libGLESv1_CM.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4302000-7fa4303000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa4303000-7fa43d6000 r-xp 00000000 103:0c 188451                        /system/lib64/libEGL.so
06-22 08:08:37.932  6781  6781 W art     : 7fa43d6000-7fa43e5000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa43e5000-7fa43e9000 r--p 000db000 103:0c 188451                        /system/lib64/libEGL.so
06-22 08:08:37.932  6781  6781 W art     : 7fa43e9000-7fa43f5000 rw-p 000df000 103:0c 188451                        /system/lib64/libEGL.so
06-22 08:08:37.932  6781  6781 W art     : 7fa43f5000-7fa43fb000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa43fb000-7fa44b6000 r-xp 00000000 103:0c 188653                        /system/lib64/libsqlite.so
06-22 08:08:37.932  6781  6781 W art     : 7fa44b6000-7fa44c6000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa44c6000-7fa44c8000 r--p 000be000 103:0c 188653                        /system/lib64/libsqlite.so
06-22 08:08:37.932  6781  6781 W art     : 7fa44c8000-7fa44ca000 rw-p 000c0000 103:0c 188653                        /system/lib64/libsqlite.so
06-22 08:08:37.932  6781  6781 W art     : 7fa44ca000-7fa44cb000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa44cb000-7fa496d000 r-xp 00000000 103:0c 188645                        /system/lib64/libskia.so
06-22 08:08:37.932  6781  6781 W art     : 7fa496d000-7fa497c000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa497c000-7fa49ad000 r--p 004a2000 103:0c 188645                        /system/lib64/libskia.so
06-22 08:08:37.932  6781  6781 W art     : 7fa49ad000-7fa49af000 rw-p 004d3000 103:0c 188645                        /system/lib64/libskia.so
06-22 08:08:37.932  6781  6781 W art     : 7fa49af000-7fa49b8000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa49b8000-7fa49b9000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa49b9000-7fa49c1000 r-xp 00000000 103:0c 188505                        /system/lib64/libcamera_metadata.so
06-22 08:08:37.932  6781  6781 W art     : 7fa49c1000-7fa49d0000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa49d0000-7fa49d1000 r--p 00008000 103:0c 188505                        /system/lib64/libcamera_metad
06-22 08:08:37.932  6781  6781 W art     : ata.so
06-22 08:08:37.932  6781  6781 W art     : 7fa49d1000-7fa49d3000 rw-p 00009000 103:0c 188505                        /system/lib64/libcamera_metadata.so
06-22 08:08:37.932  6781  6781 W art     : 7fa49d3000-7fa4a13000 r-xp 00000000 103:0c 188504                        /system/lib64/libcamera_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4a13000-7fa4a22000 ---p 00000000 00:0
06-22 08:08:37.932  6781  6781 W art     : 0 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4a22000-7fa4a2d000 r--p 0004c000 103:0c 188504                        /system/lib64/libcamera_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4a2d000-7fa4a2e000 rw-p 00057000 103:0c 188504                        /system/lib64/libcamera_client.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4a2e000-7fa4a8a000 r-xp 00000000 103:0c
06-22 08:08:37.932  6781  6781 W art     :  188582                        /system/lib64/libinputflinger.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4a8a000-7fa4a8e000 r--p 00060000 103:0c 188582                        /system/lib64/libinputflinger.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4a8e000-7fa4a8f000 rw-p 00064000 103:0c 188582                        /system/lib64/libinputflinger.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4a8f000-7fa4ab4000 r-xp 00000000 103:0c 188579                        /system/lib64/libinput.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4ab4000-7fa4ac4000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4ac4000-7fa4acb000 r--p 0002b000 103:0c 188579                        /system/lib64/libinput.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4acb000-7fa4acc000 rw-p 00032000 103:0c 188579                        /system/lib64/libinput.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4acc000-7fa4b35000 r-xp 00000000 103:0c 188561                        /system/lib64/libgui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b35000-7fa4b44000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4b44000-7fa4b5a000 r--p 0006a000 103:0c 188561                        /system/lib64/libgui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b5a000-7fa4b5b000 rw-p 00080000 103:0c 188561                        /system/lib64/libgui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b5b000-7fa4b5c000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa4b5c000-7fa4b6e000 r-xp 00000000 103:0c 188697                        /system/lib64/libui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b6e000-7fa4b7d000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4b7d000-7fa4b7e000 r--p 00011000 103:0c 188697                        /system/lib64/libui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b7e000-7fa4b7f000 rw-p 00012000 103:0c 188697                        /system/lib64/libui.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b7f000-7fa4b87000 r-xp 00000000 103:0c 188615                        /system/lib64/libnetutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b87000-7fa4b96000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4b96000-7fa4b97000 r--p 00007000 103:0c 188615                        /system/lib64/libnetutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b97000-7fa4b98000 rw-p 00008000 103:0c 188615                        /system/lib64/libnetutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b98000-7fa4b9f000 r-xp 00000000 103:0c 188599                        /system/lib64/libnativehelper.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4b9f000-7fa4bae000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4bae000-7fa4baf000 r--p 00006000 103:0c 188599                        /system/lib64/libnativehelper.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4baf000-7fa4bb0000 rw-p 00007000 103:0c 188599                        /system/lib64/libnativehelper.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4bb0000-7fa4bd1000 r-xp 00000000 103:0c 188514                        /system/lib64/libexpat.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4bd1000-7fa4be1000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4be
06-22 08:08:37.932  6781  6781 W art     : 1000-7fa4be3000 r--p 00021000 103:0c 188514                        /system/lib64/libexpat.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4be3000-7fa4be4000 rw-p 00023000 103:0c 188514                        /system/lib64/libexpat.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4be4000-7fa4c22000 r-xp 00000000 103:0c 188477                        /system/lib64/libandroidfw.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c22000-7fa4c32000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4c32000-7fa4c34000 r--p 0003f000 103:0c 188477                        /system/lib64/libandroidfw.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c34000-7fa4c35000 rw-p 00041000 103:0c 188477                        /system/lib64/libandroidfw.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c35000-7fa4c36000 r-xp 00000000 103:0c 188603                        /system/lib64/libmemtrack.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c36000-7fa4c46000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4c46000-7fa4c47000 r--p 00001000 103:0c 188603                        /system/lib64/libmemtrack.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c47000-7fa4c48000 rw-p 00002000 103:0c 188603                        /system/lib64/libmemtrack.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c48000-7fa4c53000 r-xp 00000000 103:0c 188490                        /system/lib64/libbacktrace.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c53000-7fa4c63000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4c63000-7fa4c64000 r--p 0000b000 103:0c 188490                        /system/lib64/libbacktrace.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c64000-7fa4c65000 rw-p 0000c000 103:0c 188490                        /system/lib64/libbacktrace.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c65000-7fa4c9d000 r-xp 00000000 103:0c 188719                        /system/lib64/libm.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4c9d000-7fa4cad000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4cad000-7fa4cae000 r--p 00038000 103:0c 188719                        /system/lib64/libm.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4cae000-7fa4caf000 rw-p 00039000 103:0c 188719                        /system/lib64/libm.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4caf000-7fa4d45000 r-xp 00000000 103:0c 188494                        /system/lib64/libc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4d45000-7fa4d54000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4d54000-7fa4d59000 r--p 00095000 103:0c 188494                        /system/lib64/libc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4d59000-7fa4d5c000 rw-p 0009a000 103:0c 188494                        /system/lib64/libc.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4d5c000-7fa4d6a000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4d6a000-7fa4e41000 r-xp 00000000 103:0c 188496                        /system/lib64/libc++.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4e41000-7fa4e50000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4e50000-7fa4e57000 r--p 000df000 103:0c 188496                        /system/lib64/libc++.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4e57000-7fa4e58000 rw-p 000e6000 103:0c 188496                        /system/lib64/libc++.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4e58000-7fa4e5b000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4e5b000-7fa4e97000 r-xp 00000000 103:0c 188712                        /system/lib64/libwilhelm.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4e97000-7fa4ea7000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa4ea7000-7fa4eac000 r--p 00041000 103:0c 188712                        /system/lib64/libwilhelm.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4eac000-7fa4ead000 rw-p 00046000 103:0c 188712                        /system/lib64/libwilhelm.so
06-22 08:08:37.932  6781  6781 W art     : 7fa4ead000-7fa5010000 r-xp 00000000 103:0c 188474                        /system/lib64/libandroid_runtime.so
06-22 08:08:37.932  6781  6781 W art     : 7fa5010000-7fa501f000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa501f000-7fa502a000 r--p 0016f000 103:0c 188474                        /system/lib64/libandroid_runtime.so
06-22 08:08:37.932  6781  6781 W art     : 7fa502a000-7fa5039000 rw-p 0017a000 103:0c 188474                        /system/lib64/libandroid_runtime.so
06-22 08:08:37.932  6781  6781 W art     : 7fa5039000-7fa503b000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa503b000-7fa5073000 r-xp 00000000 103:0c 188493                        /system/lib64/libbinder.so
06-22 08:08:37.932  6781  6781 W art     : 7fa5073000-7fa5082000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa5082000-7fa508e000 r--p 00044000 103:0c 188493                        /system/lib64/libbinder.so
06-22 08:08:37.932  6781  6781 W art     : 7fa508e000-7fa508f000 rw-p 00050000 103:0c 188493                        /system/lib64/libbinder.so
06-22 08:08:37.932  6781  6781 W art     : 7fa508f000-7fa5098000 r-xp 00000000 103:0c 188596                        /system/lib64/liblog.so
06-22 08:08:37.932  6781  6781 W art     : 7fa5098000-7fa50a7000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa50a7000-7fa50a8000 r--p 00008000 103:0c 188596                        /system/lib64/liblog.so
06-22 08:08:37.932  6781  6781 W art     : 7fa50a8000-7fa50a9000 rw-p 00009000 103:0c 188596                        /system/lib64/liblog.so
06-22 08:08:37.932  6781  6781 W art     : 7fa50a9000-7fa50d1000 r-xp 00000000 103:0c 188702                        /system/lib64/libutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa50d1000-7fa50e0000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa50e0000-7fa50e2000 r--p 00028000 103:0c 188702                        /system/lib64/libutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa50e2000-7fa50e3000 rw-p 0002a000 103:0c 188702                        /system/lib64/libutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa50e3000-7fa50f9000 r-xp 00000000 103:0c 188517                        /system/lib64/libcutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa50f9000-7fa5109000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa5109000-7fa510a000 r--p 00016000 103:0c 188517                        /system/lib64/libcutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa510a000-7fa510b000 rw-p 00017000 103:0c 188517                        /system/lib64/libcutils.so
06-22 08:08:37.932  6781  6781 W art     : 7fa510b000-7fa510c000 rw-p 00000000 00:00 0                              [anon:linker_alloc_vector]
06-22 08:08:37.932  6781  6781 W art     : 7fa510c000-7fa510f000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa510f000-7fa5110000 rw-p 00000000 00:00 0                              [anon:linker_alloc_64]
06-22 08:08:37.932  6781  6781 W art     : 7fa5110000-7fa5112000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa5112000-7fa5113000 rw-p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa5113000-7fa5114000 r--p 00000000 00:00 0                              [anon:linker_alloc]
06-22 08:08:37.932  6781  6781 W art     : 7fa5114000-7fa5134000 r--s 00000000 00:0c 3769                           /dev/__properties__
06-22 08:08:37.932  6781  6781 W art     : 7fa5134000-7fa5135000 r--p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa5135000-7fa5136000 ---p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fa5136000-7fa513a000 rw-p 00000000 00:00 0                              [anon:thread signal stack]
06-22 08:08:37.932  6781  6781 W art     : 7fa513a000-7fa513c000 r-xp 00000000 00:00 0                              [vdso]
06-22 08:08:37.932  6781  6781 W art     : 7fa513c000-7fa516c000 r-xp 00000000 103:0c 65                            /system/bin/linker64
06-22 08:08:37.932  6781  6781 W art     : 7fa516c000-7fa516d000 r--p 00030000 103:0c 65                            /system/bin/linker64
06-22 08:08:37.932  6781  6781 W art     : 7fa516d000-7fa516f000 rw-p 00031000 103:0c 65                            /system/bin/linker64
06-22 08:08:37.932  6781  6781 W art     : 7fa516f000-7fa5173000 rw-p 00000000 00:00 0 
06-22 08:08:37.932  6781  6781 W art     : 7fd91e1000-7fd9202000 rw-p 00000000 00:00 0                              [stack]
06-22 08:08:37.942  6781  6781 I art     : buildType: user, roAaReport: com, roSf: 1
06-22 08:08:38.012  6781  6781 D CustomizationManager: ====startRecUseTime====
06-22 08:08:38.012  6781  6781 D htc.customization.log.level:  is 
06-22 08:08:38.012  6781  6781 W CustomizationLogLevel: Level value is invalid, use default level 2
06-22 08:08:38.082  6781  6781 D CustomizationManager:  Read ACC file spent 0.030 (s)
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__001
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__102
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__032
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__016
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__002
06-22 08:08:38.082  6781  6781 D CIDMapFileReader: Parsing tag item name = HTC__031
06-22 08:08:38.082  6781  6781 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-22 08:08:38.082  6781  6781 I CustomizationCIDLoader: Parsing tag category name = system
06-22 08:08:38.082  6781  6781 I CustomizationCIDLoader: Parsing tag category name = application
06-22 08:08:38.082  6781  6781 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-22 08:08:38.082  6781  6781 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-22 08:08:38.082  6781  6781 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: Parsing tag category name = ACC
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 42507
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 21902
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23420
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 22299
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 24002
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23210
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23205
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23806
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23430
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23408
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27205
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27202:27205
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23203
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23207
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23001
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 26201
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 20201
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 20416
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 26002
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310160
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310200
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310210
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310220
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310230
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310240
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310250
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310260
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310270
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310300
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310310
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310490
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310530
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310580
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310590
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310640
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310660
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 310800
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 22801
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 20810
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 26202
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 20205
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 22210
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 20404
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 26801
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 21401
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 21418
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 23415
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 27201
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 22610
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 21404
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = 22201
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: add string-array item, value = FreeWifi_secure
06-22 08:08:38.092  6781  6781 I CustomizationCIDLoader: Parsing tag category name = Settings
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 234
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 272
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 23594
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 204
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 206
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 270
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 262
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 232
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 228
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20810
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20801
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20820
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20815
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20823
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20826
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64700
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64710
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 34001
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 22201
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 22210
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 22299
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 22288
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 238
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 240
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 242
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 214
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 268
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 280
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20210
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20209
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20205
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 20201
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 250
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25012
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25007
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25017
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 28301
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 28310
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 28305
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 40102
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 40101
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25020
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25002
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25099
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25001
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25011
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 28310
06-22 08:08:38.092  6781  6781 D MNSMa,pFileLoader: Parsing tag item name = 25701
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25702
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 40101
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 40102
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 28305
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 28301
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 25039
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 218
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 278
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 297
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 294
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 276
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 257
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 420
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 415
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 416
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 417
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 418
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 419
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 421
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 422
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 424
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 426
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 427
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 432
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 602
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 603
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 604
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 605
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 606
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 612
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 617
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 620
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 621
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 624
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 628
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 630
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 631
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 639
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 640
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 641
06-22 08:08:38.092  6781  6781 D MNSMapFileLoader: Parsing tag item name = 655
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 659
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 286
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 255
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 425
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 260
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 248
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 226
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 259
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 293
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 220
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 219
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 284
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 230
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 231
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 216
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 246
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 247
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65501
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63102
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61603
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61605
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65201
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65202
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62401
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62402
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63901
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63002
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63089
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62803
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63902
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63903
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63905
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65101
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64601
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64602
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64603
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65001
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65010
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61701
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61710
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64301
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64304
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64901
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64903
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62120
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62130
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62150
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62160
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62901
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62907
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62910
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63510
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63513
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63301
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63401
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 63402
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65310
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64002
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64003
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64004
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64005
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64101
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64110
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64111
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64122
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64501
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64502
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 64804
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62001
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62002
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 62003
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61202
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61203
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61203
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61204
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61205
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61206
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61701
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 61710
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65510
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65502
06-22 08:08:38.102  6781  6781 D MNSMapFileLoader: Parsing tag item name = 65507
06-22 08:08:38.102  6781  6781 E BaseLoader: parseConfig error:java.io.FileNotFoundException: /system/customize/spn_map.xml: open failed: ENOENT (No such file or directory)
06-22 08:08:38.102  6781  6781 E BaseLoader: parseConfig error:java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
06-22 08:08:38.112  6781  6788 D CustomizationMNSLoader: full path : /system/customize/MNS/250.xml
06-22 08:08:38.112  6781  6788 D CustomizationMNSLoader: Parsing tag category name = system
06-22 08:08:38.112  6781  6788 D CustomizationMNSLoader: Parsing tag category name = application

```
