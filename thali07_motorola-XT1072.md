#### Test 757892686fd65a6_thali07_motorola-XT1072 Logs


```
--------- beginning of system
07-01 08:58:01.353  1756  2363 V AlarmManager: sending alarm {dc914ba type 0 *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
--------- beginning of main
07-01 08:58:01.365  5318  5318 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
07-01 08:58:01.375  1756  2731 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
07-01 08:58:01.379  5318  5318 I Finsky  : [1] com.google.android.finsky.utils.bh.run(2302): Package state data is missing for com.test.thalitest
07-01 08:58:01.382  3224  5592 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-01 08:58:01.386  3224  5591 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
07-01 08:58:01.389  3224  5592 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-01 08:58:01.399  3224  3224 D AsyncTaskServiceImpl: Submit a task: nwp
07-01 08:58:01.405  3224  5592 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-01 08:58:01.430  3224  3323 D nwp     : Processing package: com.test.thalitest
07-01 08:58:01.446  1756  1767 I ActivityManager: Killing 5475:com.google.android.partnersetup/u0a19 (adj 13): empty #7
07-01 08:58:01.457  3224  3323 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
07-01 08:58:01.457  3224  3323 D nwp     : Found info for package com.test.thalitest in db.
07-01 08:58:01.559  1756  1756 V AlarmManager: done {dc914ba, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [207ms]
07-01 08:58:01.565  1756  2450 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
07-01 08:58:01.568  5318  5603 I Finsky  : [371] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-01 08:58:01.569  5318  5381 I PlayCommon: [359] com.google.android.play.a.w.a(27551): Starting to flush logs
07-01 08:58:01.606  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 08:58:01.644  5318  5381 I PlayCommon: [359] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
,07-01 08:58:02.622  3224  3323 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
07-01 08:58:02.645  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4244263, SEQNUM=4523, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=338294, POWER_SUPPLY_CHARGE_COUNTER=55, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
07-01 08:58:02.649  1756  2363 V AlarmManager: sending alarm {200b9ba type 2 *walarm*:com.google.android.intent.action.GCM_RECONNECT}
07-01 08:58:02.672  1756  1756 V AlarmManager: done {200b9ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [22ms]
07-01 08:58:02.742  3224  3323 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
07-01 08:58:02.882  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4236055, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=397423, POWER_SUPPLY_CHARGE_COUNTER=47, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
07-01 08:58:03.232  5615  5615 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-01 08:58:03.239  5615  5615 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:03.247  5615  5615 W art     : 6f0da000-6faf4000 rw-p 00000000 103:0a 749835    /data/dalvik-cache/arm/system@framework@boot.art
07-01 08:58:03.247  5615  5615 W art     : b10d4000-b30b2000 r--p 00000000 103:08 426       /system/framework/arm/boot.oat
07-01 08:58:03.247  5615  5615 W art     : b30b2000-b48c5000 r-xp 01fde000 103:08 426       /system/framework/arm/boot.oat
07-01 08:58:03.247  5615  5615 W art     : b48c5000-b48c6000 rw-p 037f1000 103:08 426       /system/framework/arm/boot.oat
07-01 08:58:03.247  5615  5615 W art     : b48c7000-b48e5000 r--p 00a1a000 103:0a 749835    /data/dalvik-cache/arm/system@framework@boot.art
07-01 08:58:03.247  5615  5615 W art     : b48e5000-b48e8000 r-xp 00000000 103:08 1071      /system/lib/libsigchain.so
07-01 08:58:03.247  5615  5615 W art     : b48e8000-b48e9000 r--p 00002000 103:08 1071      /system/lib/libsigchain.so
07-01 08:58:03.247  5615  5615 W art     : b48e9000-b48ea000 rw-p 00003000 103:08 1071      /system/lib/libsigchain.so
07-01 08:58:03.247  5615  5615 W art     : b48ea000-b4d37000 r-xp 00000000 103:08 538       /system/lib/libart.so
07-01 08:58:03.247  5615  5615 W art     : b4d37000-b4d38000 ---p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b4d38000-b4d42000 r--p 0044d000 103:08 538       /system/lib/libart.so
07-01 08:58:03.247  5615  5615 W art     : b4d42000-b4d43000 rw-p 00457000 103:08 538       /system/lib/libart.so
07-01 08:58:03.247  5615  5615 W art     : b4d43000-b4d45000 rw-p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b4d46000-b4d48000 r--p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b4d48000-b4d68000 r--s 00000000 00:0b 7171       /dev/__properties__
07-01 08:58:03.247  5615  5615 W art     : b4d68000-b577a000 r-xp 00000000 103:08 501       /system/lib/libLLVM.so
07-01 08:58:03.247  5615  5615 W art     : b577a000-b57c3000 r--p 00a11000 103:08 501       /system/lib/libLLVM.so
07-01 08:58:03.247  5615  5615 W art     : b57c3000-b57c4000 rw-p 00a5a000 103:08 501       /system/lib/libLLVM.so
07-01 08:58:03.247  5615  5615 W art     : b57c4000-b57cc000 rw-p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b57cd000-b5802000 r-xp 00000000 103:08 567       /system/lib/libbcinfo.so
07-01 08:58:03.247  5615  5615 W art     : b5802000-b5803000 ---p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b5803000-b5804000 r--p 00035000 103:08 567       /system/lib/libbcinfo.so
07-01 08:58:03.247  5615  5615 W art     : b5804000-b5805000 rw-p 00036000 103:08 567       /system/lib/libbcinfo.so
07-01 08:58:03.247  5615  5615 W art     : b5805000-b585d000 r-xp 00000000 103:08 566       /system/lib/libbcc.so
07-01 08:58:03.247  5615  5615 W art     : b585d000-b585e000 ---p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b585e000-b585f000 r--p 00058000 103:08 566       /system/lib/libbcc.so
07-01 08:58:03.247  5615  5615 W art     : b585f000-b5860000 rw-p 00059000 103:08 566       /system/lib/libbcc.so
07-01 08:58:03.247  5615  5615 W art     : b5861000-b586b000 r-xp 00000000 103:08 598       /system/lib/libcommon_ti
07-01 08:58:03.247  5615  5615 W art     : me_client.so
07-01 08:58:03.247  5615  5615 W art     : b586b000-b586e000 r--p 00009000 103:08 598       /system/lib/libcommon_time_client.so
07-01 08:58:03.247  5615  5615 W art     : b586e000-b586f000 rw-p 0000c000 103:08 598       /system/lib/libcommon_time_client.so
07-01 08:58:03.247  5615  5615 W art     : b5870000-b5887000 r-xp 00000000 103:08 1760      /system/lib/libprotobuf-cpp-lite.so
07-01 08:58:03.247  5615  5615 W art     : b5887000-b5888000 ---p 00000000 00:00 0 
07-01 08:58:03.247  5615  5615 W art     : b5888000-b5889000 r--p 00017000 103:08 1760      /system/lib/libprotobuf-cpp-lite.so
07-01 08:58:03.248  5615  5615 W art     : b5889000-b588a000 rw-p 00018000 103:08 1760      /system/lib/libprotobuf-cpp-lite.so
07-01 08:58:03.248  5615  5615 W art     : b588a000-b588b000 r--p 00000000 00:00 0 
07-01 08:58:03.248  5615  5615 W art     : b588
07-01 08:58:03.248  5615  5615 W art     : b000-b5892000 r-xp 00000000 103:08 1103      /system/lib/libstagefright_avc_common.so
07-01 08:58:03.248  5615  5615 W art     : b5892000-b5893000 r--p 00006000 103:08 1103      /system/lib/libstagefright_avc_common.so
07-01 08:58:03.248  5615  5615 W art     : b5893000-b5894000 rw-p 00007000 103:08 1103      /system/lib/libstagefright_avc_common.so
07-01 08:58:03.248  5615  5615 W art     : b5895000-b5898000 r-xp 00000000 103:08 1104      /system/lib/libstagefright_enc_common.so
07-01 08:58:03.248  5615  5615 W art     : b5898000-b5899000 r--p 00002000 103:08 1104      /system/lib/libstagefright_enc_common.so
07-01 08:58:03.248  5615  5615 W art     : b5899000-b589a000 rw-p 00003000 103:08 1104      /system/lib/libstagefright_enc_common.so
07-01 08:58:03.248  5615  5615 W art     : b589b000-b589f000 r-xp 00000000 103:08 900       /system/lib/libpowermanager.so
07-01 08:58:03.248  5615  5615 W art     : b589f000-b58a0000 ---p 00000000 00:00 0 
07-01 08:58:03.248  5615  5615 W art     : b58a0000-b58a1000 r--p 00004000 103:08 900       /system/lib/libpowermanager.so
07-01 08:58:03.248  5615  5615 W art     : b58a1000-b58a2000 rw-p 00005000 103:08 900       /system/lib/libpowermanager.so
07-01 08:58:03.248  5615  5615 W art     : b58a3000-b58c0000 r-xp 00000000 103:08 1147      /system/lib/libvorbisidec.so
07-01 08:58:03.248  5615  5615 W art     : b58c0000-b58c1000 r--p 0001c000 103:08 1147      /system/lib/libvorbisidec.so
07-01 08:58:03.248  5615  5615 W art     : b58c1000-b58c2000 rw-p 0001d000 103:08 1147      /system/lib/libvorbisidec.so
07-01 08:58:03.248  5615  5615 W art     : b58c3000-b58c8000 r-xp 00000000 103:08 1127      /system/lib/libstagefright_yuv.so
07-01 08:58:03.248  5615  5615 W art     : b58c8000-b58c9000 r--p 00004000 103:08 1127      /system/lib/libstagefright_yuv.so
07-01 08:58:03.248  5615  5615 W art     : b58c9000-b58ca000 rw-p 00005000 103:08 1127      /system/lib/libstagefright_yuv.so
07-01 08:58:03.248  5615  5615 W art     : b58cb000-b58f8000 r-xp 00000000 103:08 1108      /system/lib/libstagefright_omx.so
07-01 08:58:03.248  5615  5615 W art     : b58f8000-b58fb000 r--p 0002c000 103:08 1108      /system/lib/libstagefright_omx.so
07-01 08:58:03.248  5615  5615 W art     : b58fb000-b58fc000 rw-p 0002f000 103:08 1108      /system/lib/libstagefright_omx.so
07-01 08:58:03.248  5615  5615 W art     : b58fd000-b5938000 r-xp 00000000 103:08 877       /system/lib/libopus.so
07-01 08:58:03.248  5615  5615 W art     : b5938000-b5939000 r--p 0003a000 103:08 877       /system/lib/libopus.so
07-01 08:58:03.248  5615  5615 W art     : b5939000-b593a000 rw-p 0003b000 103:08 877       /system/lib/libopus.so
07-01 08:58:03.248  5615  5615 W art     : b593b000-b5940000 r-xp 00000000 103:08 1757      /system/lib/libmediautils.so
07-01 08:58:03.248  5615  5615 W art     : b5940000-b5941000 r--p 00004000 103:08 1757      /system/lib/libmediautils.so
07-01 08:58:03.248  5615  5615 W art     : b5941000-b5942000 rw-p 00005000 103:08 1757      /system/lib/libmediautils.so
07-01 08:58:03.248  5615  5615 W art     : b5943000-b5958000 r-xp 00000000 103:08 612       /system/lib/libdrmframework.so
07-01 08:58:03.248  5615  5615 W art     : b5958000-b5959000 ---p 00000000 00:00 0 
07-01 08:58:03.248  5615  5615 W art     : b5959000-b595c000 r--p 00015000 103:08 612       /system/lib/libdrmframework.so
07-01 08:58:03.248  5615  5615 W art     : b595c000-b595d000 rw-p 00018000 103:08 612       /system/lib/libdrmframework.so
07-01 08:58:03.248  5615  5615 W art     : b595d000-b597c000 r-xp 00000000 103:08 528       /system/lib/libRScpp.so
07-01 08:58:03.248  5615  5615 W art     : b597c000-b597d000 r--p 0001e000 103:08 528       /system/lib/libRScpp.so
07-01 08:58:03.249  5615  5615 W art     : b597d000-b597e000 rw-p 0001f000 103:08 528       /system/lib/libRScpp.so
07-01 08:58:03.249  5615  5615 W art     : b597e000-b59bc000 r-xp 00000000 103:08 515       /system/lib/libRS.so
07-01 08:58:03.249  5615  5615 W art     : b59bc000-b59bd000 ---p 00000000 00:00 0 
07-01 08:58:03.249  5615  5615 W art     : b59bd000-b59bf000 r--p 0003e000 103:08 515       /system/lib/libRS.so
07-01 08:58:03.249  5615  5615 W art     : b59bf000-b59c0000 rw-p 00040000 103:08 515       /system/lib/libRS.so
07-01 08:58:03.249  5615  5615 W art     : b59c0000-b59c7000 r-xp 00000000 103:08 1097      /system/lib/libspeexresampler.so
07-01 08:58:03.249  5615  5615 W art     : b59c7000-b59c8000 r--p 00006000 103:08 1097      /system/lib/libspeexresampler.so
07-01 08:58:03.249  5615  5615 W art     : b59c8000-b59c9000 rw-p 00007000 103:08 1097      /system/lib/libspeexresampler.so
07-01 08:58:03.249  5615  5615 W art     : b59c9000-b59d2000 r-xp 00000000 103:08 822       /system/lib/libnbaio.so
07-01 08:58:03.249  5615  5615 W art     : b59d2000-b59d3000 r--p 00008000 103:08 822       /system/lib/libnbaio.so
07-01 08:58:03.249  5615  5615 W art     : b59d3000-b59d4000 rw-p 00009000 103:08 822       /system/lib/libnbaio.so
07-01 08:58:03.249  5615  5615 W art     : b59d4000-b59e6000 r-xp 00000000 103:08 1759      /system/lib/libpcre.so
07-01 08:58:03.249  5615  5615 W art     : b59e6000-b59e7000 r--p 00011000 103:08 1759      /system/lib/libpcre.so
07-01 08:58:03.249  5615  5615 W art     : b59e7000-b59e8000 rw-p 00012000 103:08 1759      /system/lib/libpcre.so
07-01 08:58:03.249  5615  5615 W art     : b59e9000-b59ee000 r-xp 00000000 103:08 1154      /system/lib/libwpa_client.so
07-01 08:58:03.249  5615  5615 W art     : b59ee000-b59ef000 r--p 00004000 103:08 1154      /system/lib/libwpa_client.so
07-01 08:58:03.249  5615  5615 W art     : b59ef000-b59f0000 rw-p 00005000 103:08 1154      /system/lib/libwpa_client.so
07-01 08:58:03.249  5615  5615 W art     : b59f1000-b5a5e000 r-xp 00000000 103:08 498       /system/lib/libGLES_trace.so
07-01 08:58:03.249  5615  5615 W art     : b5a5e000-b5a5f000 ---p 00000000 00:00 0 
07-01 08:58:03.249  5615  5615 W art     : b5a5f000-b5a61000 r--p 0006d000 103:08 498       /system/lib/libGLES_trace.so
07-01 08:58:03.249  5615  5615 W art     : b5a61000-b5a62000 rw-p 0006f000 103:08 498       /system/lib/libGLES_trace.so
07-01 08:58:03.249  5615  5615 W art     : b5a62000-b5a63000 r--p 00000000 00:00 0 
07-01 08:58:03.249  5615  5615 W art     : b5a63000-b5ac4000 r-xp 00000000 103:08 693       /system/lib/libft2.so
07-01 08:58:03.249  5615  5615 W art     : b5ac4000-b5ac6000 r--p 00060000 103:08 693       /system/lib/libft2.so
07-01 08:58:03.249  5615  5615 W art     : b5ac6000-b5ac7000 rw-p 00062000 103:08 693       /system/lib/libft2.so
07-01 08:58:03.249  5615  5615 W art     : b5ac8000-b5aef000 r-xp 00000000 103:08 889       /system/lib/libpng.so
07-01 08:58:03.249  5615  5615 W art     : b5aef000-b5af0000 ---p 00000000 00:00 0 
07-01 08:58:03.249  5615  5615 W art     : b5af0000-b5af1000 r--p 00027000 103:08 889       /system/lib/libpng.so
07-01 08:58:03.249  5615  5615 W art     : b5af1000-b5af2000 rw-p 00028000 103:08 889       /system/lib/libpng.so
07-01 08:58:03.249  5615  5615 W art     : b5af3000-b5af6000 r-xp 00000000 103:08 1134      /system/lib/libsync.so
07-01 08:58:03.249  5615  5615 W art     : b5af6000-b5af7000 r--p 00002000 103:08 1134      /system/lib/libsync.so
07-01 08:58:03.249  5615  5615 W art     : b5af7000-b5af8000 rw-p 00003000 103:08 1134      /system/lib/libsync.so
07-01 08:58:03.249  5615  5615 W art     : b5af8000-b5afd000 r-xp 00000000 103:08 1129      /system/lib/libstdc++.so
07-01 08:58:03.249  5615  5615 W art     : b5afd000-b5afe000 r--p 00004000 103:08 1129      /system/lib/libstdc++.so
07-01 08:58:03.249  5615  5615 W art     : b5afe000-b5aff000 rw-p 00005000 103:08 1129      /system/lib/libstdc++.so
07-01 08:58:03.249  5615  5615 W art     : b5aff000-b5b0f000 r-xp 00000000 103:08 1142      /system/lib/libunwind.so
07-01 08:58:03.250  5615  5615 W art     : b5b0f000-b5b10000 r--p 0000f000 103:08 1142      /system/lib/libunwind.so
07-01 08:58:03.250  5615  5615 W art     : b5b10000-b5b11000 rw-p 00010000 103:08 1142      /system/lib/libunwind.so
07-01 08:58:03.250  5615  5615 W art     : b5b11000-b5b57000 rw-p 00000000 00:00 0 
07-01 08:58:03.250  5615  5615 W art     : b5b57000-b5b60000 r-xp 00000000 103:08 1747      /system/lib/libbase.so
07-01 08:58:03.250  5615  5615 W art     : b5b60000-b5b61000 r--p 00008000 103:08 1747      /system/lib/libbase.so
07-01 08:58:03.250  5615  5615 W art     : b5b61000-b5b62000 rw-p 00009000 103:08 1747      /system/lib/libbase.so
07-01 08:58:03.250  5615  5615 W art     : b5b62000-b5b67000 r-xp 00000000 103:08 664       /system/lib/libeffects.so
07-01 08:58:03.250  5615  5615 W art     : b5b67000-b5b68000 r--p 00004000 103:08 664       /system/lib/libeffects.so
07-01 08:58:03.250  5615  5615 W art     : b5b68000-b5b69000 rw-p 00005000 103:08 664       /system/lib/libeffects.so
07-01 08:58:03.250  5615  5615 W art     : b5b69000-b5b6c000 r-xp 00000000 103:08 1106      /system/lib/libstagefright_http_support.so
07-01 08:58:03.250  5615  5615 W art     : b5b6c000-b5b6d000 ---p 00000000 00:00 0 
07-01 08:58:03.250  5615  5615 W art     : b5b6d000-b5b6e000 r--p 00003000 103:08 1106      /system/lib/libstagefright_http_support.so
07-01 08:58:03.250  5615  5615 W art     : b5b6e000-b5b6f000 rw-p 00004000 103:08 1106      /system/lib/libstagefright_http_support.so
07-01 08:58:03.250  5615  5615 W art     : b5b70000-b5b88000 r-xp 00000000 103:08 1105      /system/lib/libstagefright_foundation.so
07-01 08:58:03.250  5615  5615 W art     : b5b88000-b5b89000 ---p 00000000 00:00 0 
07-01 08:58:03.250  5615  5615 W art     : b5b89000-b5b8a000 r--p 00018000 103:08 1105      /system/lib/libstagefright_foundation.so
07-01 08:58:03.250  5615  5615 W art     : b5b8a000-b5b8b000 rw-p 00019000 103:08 1105      /system/lib/libstagefright_foundation.so
07-01 08:58:03.250  5615  5615 W art     : b5b8c000-b5ce7000 r-xp 00000000 103:08 1101      /system/lib/libstagefright.so
07-01 08:58:03.250  5615  5615 W art     : b5ce7000-b5ce8000 ---p 00000000 00:00 0 
07-01 08:58:03.250  5615  5615 W art     : b5ce8000-b5cf4000 r--p 0015b000 103:08 1101      /system/lib/libstagefright.so
07-01 08:58:03.250  5615  5615 W art     : b5cf4000-b5cf5000 rw-p 00167000 103:08 1101      /system/lib/libstagefright.so
07-01 08:58:03.250  5615  5615 W art     : b5cf6000-b5d61000 r-xp 00000000 103:08 701       /system/lib/libhwui.so
07-01 08:58:03.250  5615  5615 W art     : b5d61000-b5d62000 ---p 00000000 00:00 0 
07-01 08:58:03.250  5615  5615 W art     : b5d62000-b5d65000 r--p 0006b000 103:08 701       /system/lib/libhwui.so
07-01 08:58:03.250  5615  5615 W art     : b5d65000-b5d66000 rw-p 0006e000 103:08 701       /system/lib/libhwui.so
07-01 08:58:03.250  5615  5615 W art     : b5d67000-b5d6a000 r-xp 00000000 103:08 1763      /system/lib/libradio_metadata.so
07-01 08:58:03.250  5615  5615 W art     : b5d6a000-b5d6b000 r--p 00002000 103:08 1763      /system/lib/libradio_metadata.so
07-01 08:58:03.250  5615  5615 W art     : b5d6b000-b5d6c000 rw-p 00003000 103:08 1763      /system/lib/libradio_metadata.so
07-01 08:58:03.250  5615  5615 W art     : b5d6d000-b5d71000 r-xp 00000000 103:08 812       /system/lib/libnativebridge.so
07-01 08:58:03.250  5615  5615 W art     : b5d71000-b5d72000 r--p 00003000 103:08 812       /system/lib/libnativebridge.so
07-01 08:58:03.250  5615  5615 W art     : b5d72000-b5d73000 rw-p 00004000 103:08 812       /system/lib/libnativebridge.so
07-01 08:58:03.250  5615  5615 W art     : b5d74000-b5d78000 r-xp 00000000 103:08 922       /system/lib/libprocessgroup.so
07-01 08:58:03.250  5615  5615 W art     : b5d78000-b5d79000 r--p 00003000 103:08 922       /system/lib/libprocessgroup.so
07-01 08:58:03.250  5615  5615 W art     : b5d79000-b5d7a000 rw-p 00004000 103:08 922       /system/lib/libprocessgroup.so
07-01 08:58:03.251  5615  5615 W art     : b5d7a000-b5d7b000 rw-p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b5d7b000-b5d8a000 r-xp 00000000 103:08 792       /system/lib/libminikin.so
07-01 08:58:03.251  5615  5615 W art     : b5d8a000-b5d8b000 r--p 0000e000 103:08 792       /system/lib/libminikin.so
07-01 08:58:03.251  5615  5615 W art     : b5d8b000-b5d8c000 rw-p 0000f000 103:08 792       /system/lib/libminikin.so
07-01 08:58:03.251  5615  5615 W art     : b5d8c000-b5d96000 r-xp 00000000 103:08 1094      /system/lib/libsoundtrigger.so
07-01 08:58:03.251  5615  5615 W art     : b5d96000-b5d99000 r--p 00009000 103:08 1094      /system/lib/libsoundtrigger.so
07-01 08:58:03.251  5615  5615 W art     : b5d99000-b5d9a000 rw-p 0000c000 103:08 1094      /system/lib/libsoundtrigger.so
07-01 08:58:03.251  5615  5615 W art     : b5d9a000-b5d9b000 r--p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b5d9b000-b5da5000 r-xp 00000000 103:08 1761      /system/lib/libradio.so
07-01 08:58:03.251  5615  5615 W art     : b5da5000-b5da8000 r--p 00009000 103:08 1761      /system/lib/libradio.so
07-01 08:58:03.251  5615  5615 W art     : b5da8000-b5da9000 rw-p 0000c000 103:08 1761      /system/lib/libradio.so
07-01 08:58:03.251  5615  5615 W art     : b5da9000-b5dad000 r-xp 00000000 103:08 824       /system/lib/libnetd_client.so
07-01 08:58:03.251  5615  5615 W art     : b5dad000-b5dae000 r--p 00003000 103:08 824       /system/lib/libnetd_client.so
07-01 08:58:03.251  5615  5615 W art     : b5dae000-b5daf000 rw-p 00004000 103:08 824       /system/lib/libnetd_client.so
07-01 08:58:03.251  5615  5615 W art     : b5daf000-b5db0000 rw-p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b5db0000-b5dbd000 r-xp 00000000 103:08 706       /system/lib/libimg_utils.so
07-01 08:58:03.251  5615  5615 W art     : b5dbd000-b5dbf000 r--p 0000c000 103:08 706       /system/lib/libimg_utils.so
07-01 08:58:03.251  5615  5615 W art     : b5dbf000-b5dc0000 rw-p 0000e000 103:08 706       /system/lib/libimg_utils.so
07-01 08:58:03.251  5615  5615 W art     : b5dc0000-b61d2000 r-xp 00000000 103:08 880       /system/lib/libpdfium.so
07-01 08:58:03.251  5615  5615 W art     : b61d2000-b61d3000 ---p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b61d3000-b61dc000 r--p 00412000 103:08 880       /system/lib/libpdfium.so
07-01 08:58:03.251  5615  5615 W art     : b61dc000-b61e0000 rw-p 0041b000 103:08 880       /system/lib/libpdfium.so
07-01 08:58:03.251  5615  5615 W art     : b61e0000-b61e1000 rw-p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b61e1000-b61e8000 r-xp 00000000 103:08 559       /system/lib/libaudioutils.so
07-01 08:58:03.251  5615  5615 W art     : b61e8000-b61e9000 r--p 00006000 103:08 559       /system/lib/libaudioutils.so
07-01 08:58:03.251  5615  5615 W art     : b61e9000-b61ea000 rw-p 00007000 103:08 559       /system/lib/libaudioutils.so
07-01 08:58:03.251  5615  5615 W art     : b61ea000-b61eb000 r--p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b61eb000-b6206000 r-xp 00000000 103:08 1156      /system/lib/libz.so
07-01 08:58:03.251  5615  5615 W art     : b6206000-b6207000 r--p 0001a000 103:08 1156      /system/lib/libz.so
07-01 08:58:03.251  5615  5615 W art     : b6207000-b6208000 rw-p 0001b000 103:08 1156      /system/lib/libz.so
07-01 08:58:03.251  5615  5615 W art     : b6208000-b6209000 r--p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b6209000-b6255000 r-xp 00000000 103:08 700       /system/lib/libharfbuzz_ng.so
07-01 08:58:03.251  5615  5615 W art     : b6255000-b6256000 r--p 0004b000 103:08 700       /system/lib/libharfbuzz_ng.so
07-01 08:58:03.251  5615  5615 W art     : b6256000-b6257000 rw-p 0004c000 103:08 700       /system/lib/libharfbuzz_ng.so
07-01 08:58:03.251  5615  5615 W art     : b6257000-b6258000 r--p 00000000 00:00 0 
07-01 08:58:03.251  5615  5615 W art     : b6258000-b625c000 r-xp 00000000 103:08 1143      /system/lib/libusbhost.so
07-01 08:58:03.252  5615  5615 W art     : b625c000-b625d000 ---p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b625d000-b625e000 r--p 00004000 103:08 1143      /system/lib/libusbhost.so
07-01 08:58:03.252  5615  5615 W art     : b625e000-b625f000 rw-p 00005000 103:08 1143      /system/lib/libusbhost.so
07-01 08:58:03.252  5615  5615 W art     : b625f000-b6297000 r-xp 00000000 103:08 734       /system/lib/libjpeg.so
07-01 08:58:03.252  5615  5615 W art     : b6297000-b6298000 r--p 00037000 103:08 734       /system/lib/libjpeg.so
07-01 08:58:03.252  5615  5615 W art     : b6298000-b6299000 rw-p 00038000 103:08 734       /system/lib/libjpeg.so
07-01 08:58:03.252  5615  5615 W art     : b6299000-b629a000 r--p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b629a000-b632a000 r-xp 00000000 103:08 769       /system/lib/libmedia.so
07-01 08:58:03.252  5615  5615 W art     : b632a000-b632b000 ---p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b632b000-b6347000 r--p 00090000 103:08 769       /system/lib/libmedia.so
07-01 08:58:03.252  5615  5615 W art     : b6347000-b6348000 rw-p 000ac000 103:08 769       /system/lib/libmedia.so
07-01 08:58:03.252  5615  5615 W art     : b6348000-b64bb000 r-xp 00000000 103:08 702       /system/lib/libicui18n.so
07-01 08:58:03.252  5615  5615 W art     : b64bb000-b64c6000 r--p 00172000 103:08 702       /system/lib/libicui18n.so
07-01 08:58:03.252  5615  5615 W art     : b64c6000-b64c7000 rw-p 0017d000 103:08 702       /system/lib/libicui18n.so
07-01 08:58:03.252  5615  5615 W art     : b64c7000-b65de000 r-xp 00000000 103:08 704       /system/lib/libicuuc.so
07-01 08:58:03.252  5615  5615 W art     : b65de000-b65e9000 r--p 00116000 103:08 704       /system/lib/libicuuc.so
07-01 08:58:03.252  5615  5615 W art     : b65e9000-b65ea000 rw-p 00121000 103:08 704       /system/lib/libicuuc.so
07-01 08:58:03.252  5615  5615 W art     : b65ea000-b65ee000 rw-p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b65ee000-b6611000 r-xp 00000000 103:08 1100      /system/lib/libssl.so
07-01 08:58:03.252  5615  5615 W art     : b6611000-b6613000 r--p 00022000 103:08 1100      /system/lib/libssl.so
07-01 08:58:03.252  5615  5615 W art     : b6613000-b6614000 rw-p 00024000 103:08 1100      /system/lib/libssl.so
07-01 08:58:03.252  5615  5615 W art     : b6614000-b66a4000 r-xp 00000000 103:08 603       /system/lib/libcrypto.so
07-01 08:58:03.252  5615  5615 W art     : b66a4000-b66a5000 ---p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b66a5000-b66b0000 r--p 00090000 103:08 603       /system/lib/libcrypto.so
07-01 08:58:03.252  5615  5615 W art     : b66b0000-b66b1000 rw-p 0009b000 103:08 603       /system/lib/libcrypto.so
07-01 08:58:03.252  5615  5615 W art     : b66b1000-b6704000 r-xp 00000000 103:08 1092      /system/lib/libsonivox.so
07-01 08:58:03.252  5615  5615 W art     : b6704000-b6705000 r--p 00052000 103:08 1092      /system/lib/libsonivox.so
07-01 08:58:03.252  5615  5615 W art     : b6705000-b6706000 rw-p 00053000 103:08 1092      /system/lib/libsonivox.so
07-01 08:58:03.252  5615  5615 W art     : b6706000-b670b000 rw-p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b670b000-b671a000 r-xp 00000000 103:08 1067      /system/lib/libselinux.so
07-01 08:58:03.252  5615  5615 W art     : b671a000-b671b000 r--p 0000e000 103:08 1067      /system/lib/libselinux.so
07-01 08:58:03.252  5615  5615 W art     : b671b000-b671c000 rw-p 0000f000 103:08 1067      /system/lib/libselinux.so
07-01 08:58:03.252  5615  5615 W art     : b671c000-b6723000 r-xp 00000000 103:08 699       /system/lib/libhardware_legacy.so
07-01 08:58:03.252  5615  5615 W art     : b6723000-b6724000 ---p 00000000 00:00 0 
07-01 08:58:03.252  5615  5615 W art     : b6724000-b6725000 r--p 00007000 103:08 699       /system/lib/libhardware_legacy.so
07-01 08:58:03.252  5615  5615 W art     : b6725000-b6726000 rw-p 00008000 103:08 699       /system/lib/libhardware_legacy.so
07-01 08:58:03.252  5615  5615 W art     : b6726000-b6727000 rw-p 00000000 00:00 0 
07-01 08:58:03.253  5615  5615 W art     : b6727000-b672a000 r-xp 00000000 103:08 698       /system/lib/libhardware.so
07-01 08:58:03.253  5615  5615 W art     : b672a000-b672b000 r--p 00002000 103:08 698       /system/lib/libhardware.so
07-01 08:58:03.253  5615  5615 W art     : b672b000-b672c000 rw-p 00003000 103:08 698       /system/lib/libhardware.so
07-01 08:58:03.253  5615  5615 W art     : b672c000-b6730000 r-xp 00000000 103:08 496       /system/lib/libETC1.so
07-01 08:58:03.253  5615  5615 W art     : b6730000-b6731000 r--p 00003000 103:08 496       /system/lib/libETC1.so
07-01 08:58:03.253  5615  5615 W art     : b6731000-b6732000 rw-p 00004000 103:08 496       /system/lib/libETC1.so
07-01 08:58:03.253  5615  5615 W art     : b6732000-b673f000 r-xp 00000000 103:08 500       /system/lib/libGLESv2.so
07-01 08:58:03.253  5615  5615 W art     : b673f000-b6740000 r--p 0000c000 103:08 500       /system/lib/libGLESv2.so
07-01 08:58:03.253  5615  5615 W art     : b6740000-b6741000 rw-p 0000d000 103:08 500       /system/lib/libGLESv2.so
07-01 08:58:03.253  5615  5615 W art     : b6741000-b6749000 r-xp 00000000 103:08 499       /system/lib/libGLESv1_CM.so
07-01 08:58:03.253  5615  5615 W art     : b6749000-b674a000 r--p 00007000 103:08 499       /system/lib/libGLESv1_CM.so
07-01 08:58:03.253  5615  5615 W art     : b674a000-b674b000 rw-p 00008000 103:08 499       /system/lib/libGLESv1_CM.so
07-01 08:58:03.253  5615  5615 W art     : b674b000-b67a7000 r-xp 00000000 103:08 495       /system/lib/libEGL.so
07-01 08:58:03.253  5615  5615 W art     : b67a7000-b67a8000 ---p 00000000 00:00 0 
07-01 08:58:03.253  5615  5615 W art     : b67a8000-b67aa000 r--p 0005c000 103:08 495       /system/lib/libEGL.so
07-01 08:58:03.253  5615  5615 W art     : b67aa000-b67b3000 rw-p 0005e000 103:08 495       /system/lib/libEGL.so
07-01 08:58:03.253  5615  5615 W art     : b67b3000-b67b6000 rw-p 00000000 00:00 0 
07-01 08:58:03.253  5615  5615 W art     : b67b6000-b6884000 r-xp 00000000 103:08 1098      /system/lib/libsqlite.so
07-01 08:58:03.253  5615  5615 W art     : b6884000-b6886000 r--p 000cd000 103:08 1098      /system/lib/libsqlite.so
07-01 08:58:03.253  5615  5615 W art     : b6886000-b6887000 rw-p 000cf000 103:08 1098      /system/lib/libsqlite.so
07-01 08:58:03.253  5615  5615 W art     : b6887000-b6ae0000 r-xp 00000000 103:08 1073      /system/lib/libskia.so
07-01 08:58:03.253  5615  5615 W art     : b6ae0000-b6afa000 r--p 00258000 103:
07-01 08:58:03.253  5615  5615 W art     : 08 1073      /system/lib/libskia.so
07-01 08:58:03.253  5615  5615 W art     : b6afa000-b6afc000 rw-p 00272000 103:08 1073      /system/lib/libskia.so
07-01 08:58:03.253  5615  5615 W art     : b6afc000-b6b01000 rw-p 00000000 00:00 0 
07-01 08:58:03.253  5615  5615 W art     : b6b01000-b6b09000 r-xp 00000000 103:08 577       /system/lib/libcamera_metadata.so
07-01 08:58:03.253  5615  5615 W art     : b6b09000-b6b0a000 r--p 00007000 103:08 577       /system/lib
07-01 08:58:03.253  5615  5615 W art     : /libcamera_metadata.so
07-01 08:58:03.253  5615  5615 W art     : b6b0a000-b6b0b000 rw-p 00008000 103:08 577       /system/lib/libcamera_metadata.so
07-01 08:58:03.253  5615  5615 W art     : b6b0b000-b6b2f000 r-xp 00000000 103:08 576       /system/lib/libcamera_client.so
07-01 08:58:03.253  5615  5615 W art     : b6b2f000-b6b30000 ---p 00000000 00:00 0 
07-01 08:58:03.253  5615  5615 W art     : b6b30000-b6b37000 r--p 00024000 103:08 576       /s
07-01 08:58:03.253  5615  5615 W art     : ystem/lib/libcamera_client.so
07-01 08:58:03.253  5615  5615 W art     : b6b37000-b6b38000 rw-p 0002b000 103:08 576       /system/lib/libcamera_client.so
07-01 08:58:03.253  5615  5615 W art     : b6b38000-b6b73000 r-xp 00000000 103:08 708       /system/lib/libinputflinger.so
07-01 08:58:03.253  5615  5615 W art     : b6b73000-b6b74000 ---p 00000000 00:00 0 
07-01 08:58:03.253  5615  5615 W art     : b6b74000-b6b77000 r--p 0003b000 103:08 708       /syst
07-01 08:58:03.254  5615  5615 W art     : em/lib/libinputflinger.so
07-01 08:58:03.254  5615  5615 W art     : b6b77000-b6b78000 rw-p 0003e000 103:08 708       /system/lib/libinputflinger.so
07-01 08:58:03.254  5615  5615 W art     : b6b78000-b6b91000 r-xp 00000000 103:08 707       /system/lib/libinput.so
07-01 08:58:03.254  5615  5615 W art     : b6b91000-b6b92000 ---p 00000000 00:00 0 
07-01 08:58:03.254  5615  5615 W art     : b6b92000-b6b96000 r--p 00019000 103:08 707       /system/lib/l
07-01 08:58:03.254  5615  5615 W art     : ibinput.so
07-01 08:58:03.254  5615  5615 W art     : b6b96000-b6b97000 rw-p 0001d000 103:08 707       /system/lib/libinput.so
07-01 08:58:03.254  5615  5615 W art     : b6b97000-b6be2000 r-xp 00000000 103:08 697       /system/lib/libgui.so
07-01 08:58:03.254  5615  5615 W art     : b6be2000-b6be3000 ---p 00000000 00:00 0 
07-01 08:58:03.254  5615  5615 W art     : b6be3000-b6bef000 r--p 0004b000 103:08 697       /system/lib/libgui.so
07-01 08:58:03.254  5615  5615 W art     : b6bef000-b6bf0000 rw-p 00057000 103:08 697       /system/lib/libgui.so
07-01 08:58:03.254  5615  5615 W art     : b6bf0000-b6bfd000 r-xp 00000000 103:08 1141      /system/lib/libui.so
07-01 08:58:03.254  5615  5615 W art     : b6bfd000-b6bfe000 ---p 00000000 00:00 0 
07-01 08:58:03.254  5615  5615 W art     : b6bfe000-b6bff000 r--p 0000d000 103:08 1141      /system/lib/libui.so
07-01 08:58:03.254  5615  5615 W art     : b6bff000-b6c00000 rw-p 0000e000 103:08 1141      /system/lib/libui.so
07-01 08:58:03.254  5615  5615 W art     : b6c00000-b6c07000 r-xp 00000000 103:08 860       /system/lib/libnetutils.so
07-01 08:58:03.254  5615  5615 W art     : b6c07000-b6c08000 r--p 00006000 103:08 860       /system/lib/libnetutils.so
07-01 08:58:03.254  5615  5615 W art     : b6c08000-b6c09000 rw-p 00007000 103:08 860       /system/lib/libnetutils.so
07-01 08:58:03.254  5615  5615 W art     : b6c09000-b6c10000 r-xp 00000000 103:08 813       /system/lib/libnativehelper.so
07-01 08:58:03.254  5615  5615 W art     : b6c10000-b6c11000 r--p 00006000 103:08 813       /system/lib/libnativehelper.so
07-01 08:58:03.254  5615  5615 W art     : b6c11000-b6c12000 rw-p 00007000 103:08 813       /system/lib/libnativehelper.so
07-01 08:58:03.254  5615  5615 W art     : b6c12000-b6c26000 r-xp 00000000 103:08 666       /system/lib/libexpat.so
07-01 08:58:03.254  5615  5615 W art     : b6c26000-b6c28000 r--p 00013000 103:08 666       /system/lib/libexpat.so
07-01 08:58:03.254  5615  5615 W art     : b6c28000-b6c29000 rw-p 00015000 103:08 666       /system/lib/libexpat.so
07-01 08:58:03.254  5615  5615 W art     : b6c29000-b6c50000 r-xp 00000000 103:08 535       /system/lib/libandroidfw.so
07-01 08:58:03.254  5615  5615 W art     : b6c50000-b6c51000 ---p 00000000 00:00 0 
07-01 08:58:03.254  5615  5615 W art     : b6c51000-b6c52000 r--p 00027000 103:08 535       /system/lib/libandroidfw.so
07-01 08:58:03.254  5615  5615 W art     : b6c52000-b6c53000 rw-p 00028000 103:08 535       /system/lib/libandroidfw.so
07-01 08:58:03.254  5615  5615 W art     : b6c53000-b6c56000 r-xp 00000000 103:08 791       /system/lib/libmemtrack.so
07-01 08:58:03.254  5615  5615 W art     : b6c56000-b6c57000 r--p 00002000 103:08 791       /system/lib/libmemtrack.so
07-01 08:58:03.254  5615  5615 W art     : b6c57000-b6c58000 rw-p 00003000 103:08 791       /system/lib/libmemtrack.so
07-01 08:58:03.254  5615  5615 W art     : b6c58000-b6c61000 r-xp 00000000 103:08 565       /system/lib/libbacktrace.so
07-01 08:58:03.254  5615  5615 W art     : b6c61000-b6c62000 r--p 00008000 103:08 565       /system/lib/libbacktrace.so
07-01 08:58:03.254  5615  5615 W art     : b6c62000-b6c63000 rw-p 00009000 103:08 565       /system/lib/libbacktrace.so
07-01 08:58:03.254  5615  5615 W art     : b6c63000-b6c83000 r-xp 00000000 103:08 763       /system/lib/libm.so
07-01 08:58:03.254  5615  5615 W art     : b6c83000-b6c84000 r--p 0001f000 103:08 763       /system/lib/libm.so
07-01 08:58:03.255  5615  5615 W art     : b6c84000-b6c85000 rw-p 00020000 103:08 763       /system/lib/libm.so
07-01 08:58:03.255  5615  5615 W art     : b6c85000-b6ce2000 r-xp 00000000 103:08 573       /system/lib/libc.so
07-01 08:58:03.255  5615  5615 W art     : b6ce2000-b6ce5000 r--p 0005c000 103:08 573       /system/lib/libc.so
07-01 08:58:03.255  5615  5615 W art     : b6ce5000-b6ce8000 rw-p 0005f000 103:08 573       /system/lib/libc.so
07-01 08:58:03.255  5615  5615 W art     : b6ce8000-b6cf1000 rw-p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6cf1000-b6d79000 r-xp 00000000 103:08 572       /system/lib/libc++.so
07-01 08:58:03.255  5615  5615 W art     : b6d79000-b6d7a000 ---p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6d7a000-b6d7e000 r--p 00088000 103:08 572       /system/lib/libc++.so
07-01 08:58:03.255  5615  5615 W art     : b6d7e000-b6d7f000 rw-p 0008c000 103:08 572       /system/lib/libc++.so
07-01 08:58:03.255  5615  5615 W art     : b6d7f000-b6d80000 rw-p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6d80000-b6da8000 r-xp 00000000 103:08 1153      /system/lib/libwilhelm.so
07-01 08:58:03.255  5615  5615 W art     : b6da8000-b6da9000 ---p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6da9000-b6dac000 r--p 00028000 103:08 1153      /system/lib/libwilhelm.so
07-01 08:58:03.255  5615  5615 W art     : b6dac000-b6dad000 rw-p 0002b000 103:08 1153      /system/lib/libwilhelm.so
07-01 08:58:03.255  5615  5615 W art     : b6dad000-b6e7b000 r-xp 00000000 103:08 533       /system/lib/libandroid_runtime.so
07-01 08:58:03.255  5615  5615 W art     : b6e7b000-b6e82000 r--p 000cd000 103:08 533       /system/lib/libandroid_runtime.so
07-01 08:58:03.255  5615  5615 W art     : b6e82000-b6e8a000 rw-p 000d4000 103:08 533       /system/lib/libandroid_runtime.so
07-01 08:58:03.255  5615  5615 W art     : b6e8a000-b6e8c000 rw-p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6e8c000-b6e8d000 r--p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6e8d000-b6e90000 r--p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6e90000-b6eb5000 r-xp 00000000 103:08 568       /system/lib/libbinder.so
07-01 08:58:03.255  5615  5615 W art     : b6eb5000-b6eb6000 ---p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6eb6000-b6ebd000 r--p 00025000 103:08 568       /system/li
07-01 08:58:03.255  5615  5615 W art     : b/libbinder.so
07-01 08:58:03.255  5615  5615 W art     : b6ebd000-b6ebe000 rw-p 0002c000 103:08 568       /system/lib/libbinder.so
07-01 08:58:03.255  5615  5615 W art     : b6ebe000-b6ec6000 r-xp 00000000 103:08 756       /system/lib/liblog.so
07-01 08:58:03.255  5615  5615 W art     : b6ec6000-b6ec7000 r--p 00007000 103:08 756       /system/lib/liblog.so
07-01 08:58:03.255  5615  5615 W art     : b6ec7000-b6ec8000 rw-p 00008000 103:08 7
07-01 08:58:03.255  5615  5615 W art     : 56       /system/lib/liblog.so
07-01 08:58:03.255  5615  5615 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6ec9000-b6ee1000 r-xp 00000000 103:08 1144      /system/lib/libutils.so
07-01 08:58:03.255  5615  5615 W art     : b6ee1000-b6ee2000 ---p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6ee2000-b6ee3000 r--p 00018000 103:08 1144      /system/lib/libutils.so
07-01 08:58:03.255  5615  5615 W art     : b6ee3000-b6ee4000 rw-p 00019000 103:08 1144      /system/lib/libutils.so
07-01 08:58:03.255  5615  5615 W art     : b6ee4000-b6ef3000 r-xp 00000000 103:08 604       /system/lib/libcutils.so
07-01 08:58:03.255  5615  5615 W art     : b6ef3000-b6ef4000 r--p 0000e000 103:08 604       /system/lib/libcutils.so
07-01 08:58:03.255  5615  5615 W art     : b6ef4000-b6ef5000 rw-p 0000f000 103:08 604       /system/lib/libcutils.so
07-01 08:58:03.255  5615  5615 W art     : b6ef5000-b6ef6000 rw-p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6ef6000-b6ef8000 r--p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6ef8000-b6efb000 rw-p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6efb000-b6efc000 r--p 00000000 00:00 0 
07-01 08:58:03.255  5615  5615 W art     : b6efc000-b6f1c000 r--s 00000000 00:0b 7171       /dev/__properties__
07-01 08:58:03.256  5615  5615 W art     : b6f1c000-b6f1d000 r--p 00000000 00:00 0 
07-01 08:58:03.256  5615  5615 W art     : b6f1d000-b6f1e000 ---p 00000000 00:00 0 
07-01 08:58:03.256  5615  5615 W art     : b6f1e000-b6f20000 rw-p 00000000 00:00 0 
07-01 08:58:03.256  5615  5615 W art     : b6f20000-b6f21000 r-xp 00000000 00:00 0          [sigpage]
07-01 08:58:03.256  5615  5615 W art     : b6f21000-b6f3e000 r-xp 00000000 103:08 167       /system/bin/linker
07-01 08:58:03.256  5615  5615 W art     : b6f3e000-b6f3f000 r--p 0001c000 103:08 167       /system/bin/linker
07-01 08:58:03.256  5615  5615 W art     : b6f3f000-b6f41000 rw-p 0001d000 103:08 167       /system/bin/linker
07-01 08:58:03.256  5615  5615 W art     : b6f41000-b6f43000 rw-p 00000000 00:00 0 
07-01 08:58:03.256  5615  5615 W art     : b6f43000-b6f48000 r-xp 00000000 103:08 90        /system/bin/app_process32
07-01 08:58:03.256  5615  5615 W art     : b6f48000-b6f49000 r--p 00004000 103:08 90        /system/bin/app_process32
07-01 08:58:03.256  5615  5615 W art     : b6f49000-b6f4a000 rw-p 00000000 00:00 0 
07-01 08:58:03.256  5615  5615 W art     : b7289000-b72bb000 rw-p 00000000 00:00 0          [heap]
07-01 08:58:03.256  5615  5615 W art     : be2bd000-beabc000 rw-p 00000000 00:00 0          [stack]
07-01 08:58:03.256  5615  5615 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-01 08:58:03.300  5615  5615 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-01 08:58:03.335  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4266868, SEQNUM=4529, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=164952, POWER_SUPPLY_CHARGE_COUNTER=148, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
07-01 08:58:03.370  5615  5615 I Radio-JNI: register_android_hardware_Radio DONE
07-01 08:58:03.418  5615  5615 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 08:58:03.427  1756  2986 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 08:58:03.461  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4262180, SEQNUM=4531, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=200328, POWER_SUPPLY_CHARGE_COUNTER=92, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
07-01 08:58:03.478  5615  5615 D AndroidRuntime: Shutting down VM
07-01 08:58:03.512  3041  3053 W SearchService: Abort, client detached.
07-01 08:58:03.523  3041  3213 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d2aee35
07-01 08:58:03.523  3041  3220 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-01 08:58:03.529  3041  3041 I HotwordDetector: Closing mic
07-01 08:58:03.540  1756  2986 I ActivityManager: Start proc 5638:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
07-01 08:58:03.570  3041  3041 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-01 08:58:03.587   374  3222 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-01 08:58:03.587   374  3222 D audio_hw_primary: disable_snd_device: snd_device(70: voice-rec-mic)
07-01 08:58:03.601  3041  3219 I MicroRecognitionRnrImpl: Detection finished
07-01 08:58:03.607  2953  3136 E Surface : getSlotFromBufferLocked: unknown buffer: 0xb9cc7b70
07-01 08:58:03.615  3041  3215 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-01 08:58:03.668  5638  5638 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,07-01 08:58:03.777  5638  5638 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-01 08:58:03.852  5638  5638 I cr.library_loader: Time to load native libraries: 22 ms (timestamps 2114-2136)
,07-01 08:58:03.852  5638  5638 I cr.library_loader: Expected native library version number "", actual native library version number ""
,07-01 08:58:03.893  5638  5638 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4b15921}
07-01 08:58:03.893  5638  5638 I cr.library_loader: Expected native library version number "", actual native library version number ""
,07-01 08:58:03.904  5638  5638 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 08:58:03.926  5638  5638 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,07-01 08:58:03.935   352   352 I SFPerfTracer:      triggers: (rate: 6:316) (compose: 0:2) (post: 0:1) (render: 0:2) (17:501 frames) (18:649)
,07-01 08:58:03.936   352   352 D SFPerfTracer:        layers: (5:10) (FocusedStackFrame (0xb7accda8): 1:4)* (StatusBar (0xb7b3fd08): 0:175) (NavigationBar (0xb7b433a0): 0:18) (com.android.systemui.ImageWallpaper (0xb7af55c0): 0:8) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7af6888): 0:67) (DimLayer (0xb7b0fc50): 1:1)* (Starting com.test.thalitest (0xb7b2d700): 18:20) 
,07-01 08:58:03.948  5638  5638 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 08:58:04.031  5638  5657 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
,07-01 08:58:04.044  5638  5638 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/09/15, 6cbbf7d, I3193f6e94a
,07-01 08:58:04.050   352  1041 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (22:593 vsyncs) (24:987)
,07-01 08:58:04.179  1756  1852 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@daf297d:true
,07-01 08:58:04.210  5638  5638 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-01 08:58:04.294  5421  5421 D CAR.SERVICE: onUnbind
,07-01 08:58:04.295  5421  5421 D CAR.SERVICE: CSB onClientsDisconnected
,07-01 08:58:04.295  5421  5421 D CAR.SERVICE: tearDown
07-01 08:58:04.295  5421  5421 D CAR.SERVICE: tearDownCarState
07-01 08:58:04.295  5421  5421 D CAR.SERVICE: Skip, car not connected.
07-01 08:58:04.295  5421  5421 D CAR.SERVICE: tearDownClientState
07-01 08:58:04.296  5421  5421 D CAR.SERVICE: requestStop
07-01 08:58:04.297  5421  5421 D CAR.SERVICE: onDestroy
07-01 08:58:04.298  5421  5421 D CAR.SERVICE: tearDown
07-01 08:58:04.298  5421  5421 D CAR.SERVICE: tearDownCarState
07-01 08:58:04.298  5421  5421 D CAR.SERVICE: Skip, car not connected.
,07-01 08:58:04.298  5421  5421 D CAR.SERVICE: tearDownClientState
07-01 08:58:04.298  5421  5421 D CAR.SERVICE: requestStop
,07-01 08:58:04.314  5421  5421 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@81d4ce9 that was originally bound here
07-01 08:58:04.314  5421  5421 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@81d4ce9 that was originally bound here
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at irv.a(:com.google.android.gms:120)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at irv.a(:com.google.android.gms:137)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at com.google.android.gms.car.CarCallService.h(:com.google.android.gms:76)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at com.google.android.gms.car.CarCallService.<init>(:com.google.android.gms:64)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at fgl.i(:com.google.android.gms:551)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:163)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:160)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2922)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.ActivityThread.-wrap2(ActivityThread.java)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5443)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:728)
07-01 08:58:04.314  5421  5421 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:618)
07-01 08:58:04.315  1756  2450 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@eac2a96
,07-01 08:58:04.339  5638  5638 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 08:58:04.357  5638  5638 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-01 08:58:04.384   349   349 E SELinux : avc:  denied  { find } for service=batteryproperties scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:healthd_service:s0 tclass=service_manager
,07-01 08:58:04.405  5638  5679 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:58:04.457  5638  5666 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,07-01 08:58:04.488  5638  5679 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:04.574  1756  1853 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1053
,07-01 08:58:04.574  1756  1853 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s53ms
,07-01 08:58:04.581  2882  2882 I Keyboard.Facilitator: onFinishInput()
,07-01 08:58:04.608  1756  1765 I art     : Background partial concurrent mark sweep GC freed 32764(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/26MB, paused 2.172ms total 134.871ms
,07-01 08:58:04.695  1756  3000 I ActivityManager: Killing 5493:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,07-01 08:58:04.716  5638  5638 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5638
,07-01 08:58:05.239  5638  5638 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 08:58:05.329  5638  5690 E linker  : readlink('/proc/self/fd/96') failed: Permission denied [fd=96]
,07-01 08:58:05.329  5638  5690 E linker  : warning: unable to get realpath for the library "/data/app/com.test.thalitest-1/lib/arm/libjxcore.so". Will use given name.
,07-01 08:58:05.401  5638  5690 D jxcore_app_log: JniHelper::setJavaVM(0xb8c2cb70), pthread_self() = -1615009488
,07-01 08:58:05.406  5638  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:05.406  5638  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:05.406  5638  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:05.406  5638  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:05.406  5638  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 08:58:05.406  5638  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7224db added. We now have 1 listener(s)
,07-01 08:58:05.413  5638  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:00:00:10:DD:3C
,07-01 08:58:05.415  5638  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:00:00:10:DD:3C"
,07-01 08:58:05.416  5638  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 08:58:05.416  5638  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:00:00:10:DD:3C
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:05.420  5638  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb80ab6 added. We now have 1 listener(s)
,07-01 08:58:05.420  5638  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:58:05.423  1756  2378 D WifiService: New client listening to asynchronous messages
07-01 08:58:05.423  5638  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-01 08:58:05.424  5638  5690 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-01 08:58:05.431  5638  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-01 08:58:05.431  5638  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:05.431  5638  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 08:58:05.431  5638  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:58:05.434  5638  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 08:58:05.434  5638  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:00:00:10:DD:3C
,07-01 08:58:05.436  5638  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 08:58:05.436  5638  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 08:58:05.436  5638  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:05.436  5638  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 08:58:05.437  5638  5690 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 08:58:05.479  5638  5638 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:06.493  5638  5709 W jxcore-log: Initializing JXcore engine
,07-01 08:58:06.493  5638  5709 W jxcore-log: JXcore engine is ready
,07-01 08:58:06.563  5709  5709 W Thread-398: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10011 path="socket:[9816]" dev="sockfs" ino=9816 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-01 08:58:06.563  5709  5709 W Thread-398: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10011 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 08:58:06.563  5709  5709 W Thread-398: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10011 path="socket:[24798]" dev="sockfs" ino=24798 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-01 08:58:06.595  5638  5709 W jxcore-log: Starting JXcore engine
,07-01 08:58:06.733  5638  5709 W jxcore-log: Platform android
07-01 08:58:06.733  5638  5709 W jxcore-log: 
07-01 08:58:06.733  5638  5709 W jxcore-log: Process ARCH arm
07-01 08:58:06.733  5638  5709 W jxcore-log: 
,07-01 08:58:07.005  5638  5709 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:07.005  5638  5709 I jxcore-log: 
,07-01 08:58:07.006  5638  5709 W jxcore-log: JXcore engine is started
,07-01 08:58:07.014  5638  5690 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 08:58:07.020  1756  2450 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10011 on display 0
,07-01 08:58:07.026  5638  5638 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-01 08:58:07.027  5638  5638 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-01 08:58:07.032  5638  5690 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,07-01 08:58:07.044  1756  1766 I ActivityManager: Start proc 5710:com.android.packageinstaller/u0a84 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,07-01 08:58:07.142  5710  5710 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,07-01 08:58:07.329  5710  5722 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:58:07.371  5710  5722 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/09/15, 6cbbf7d, I3193f6e94a
,07-01 08:58:07.372  5710  5722 E linker  : readlink('/proc/self/fd/26') failed: Permission denied [fd=26]
07-01 08:58:07.372  5710  5722 E linker  : warning: unable to get realpath for the library "/vendor/lib/egl/eglsubAndroid.so". Will use given name.
07-01 08:58:07.374  5710  5722 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:07.395  2882  2882 I Keyboard.Facilitator: onFinishInput()
,07-01 08:58:07.464  1756  1853 I LaunchCheckinHandler: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity,cp,ca,431
,07-01 08:58:07.464  1756  1853 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +431ms
,07-01 08:58:07.639  5638  5638 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78cb118 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1fe9438, 16908290=android.view.AbsSavedState$1@1fe9438}, android:focusedViewId=100}]}]
,07-01 08:58:07.639  5638  5638 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-01 08:58:07.733  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=328, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4253332, SEQNUM=4540, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=279267, POWER_SUPPLY_CHARGE_COUNTER=29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:07.950   385   573 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,07-01 08:58:07.959   385   572 I ThermalEngine: Sensor:batt_therm:34800 mC
,07-01 08:58:07.969  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=328, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4257407, SEQNUM=4541, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=231257, POWER_SUPPLY_CHARGE_COUNTER=48, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:08.402  3773  3906 I MMApiBackOffService: MMAPIWebServiceRequest backOff fired!
,07-01 08:58:08.406  3773  3906 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:08.419  1756  2951 I ActivityManager: Killing 5563:android.process.media/u0a13 (adj 15): empty #7
,07-01 08:58:08.459  3773  3898 I MMApiWebService: inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 08:58:08.461  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:08.462  3773  3898 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,07-01 08:58:08.464  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:08.466  3773  3898 I MMApiWebService: request will be re-tried again later: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 08:58:08.467  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:08.509  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=328, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4254143, SEQNUM=4545, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=274314, POWER_SUPPLY_CHARGE_COUNTER=82, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:09.175  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4256182, SEQNUM=4550, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=222868, POWER_SUPPLY_CHARGE_COUNTER=28, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:09.352  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4283778, SEQNUM=4552, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=12027, POWER_SUPPLY_CHARGE_COUNTER=33, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:09.500  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=327, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4281431, SEQNUM=4553, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=23044, POWER_SUPPLY_CHARGE_COUNTER=54, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:10.341  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=326, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4258508, SEQNUM=4559, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=23044, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:10.387   369   369 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8cd5f20
,07-01 08:58:10.387   369   369 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,07-01 08:58:10.387   369   369 I rmt_storage: wakelock acquired: 1, error no: 42
,07-01 08:58:10.388   369  1196 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1227507408)
,07-01 08:58:10.508   369  1196 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,07-01 08:58:10.508   369  1196 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
07-01 08:58:10.509   369  1196 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1227507408) wakelock released: 1, error no: 22
07-01 08:58:10.509   369  1196 I rmt_storage: 
,07-01 08:58:10.512   369   369 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8cd5f20
,07-01 08:58:10.516  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=326, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4250867, SEQNUM=4560, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=250562, POWER_SUPPLY_CHARGE_COUNTER=9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:11.285  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=326, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4258183, SEQNUM=4564, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=250562, POWER_SUPPLY_CHARGE_COUNTER=56, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:11.908  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=326, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259646, SEQNUM=4566, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=224586, POWER_SUPPLY_CHARGE_COUNTER=21, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:12.115  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=325, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4284882, SEQNUM=4570, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=224586, POWER_SUPPLY_CHARGE_COUNTER=35, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:12.304  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=325, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4245552, SEQNUM=4571, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=224586, POWER_SUPPLY_CHARGE_COUNTER=47, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:13.337   352   352 I SFPerfTracer:      triggers: (rate: 6:318) (compose: 0:2) (post: 0:1) (render: 0:2) (0:557 frames) (1:749)
,07-01 08:58:13.337   352   352 D SFPerfTracer:        layers: (5:12) (FocusedStackFrame (0xb7accda8): 0:9)* (StatusBar (0xb7b3fd08): 1:203) (NavigationBar (0xb7b433a0): 0:18) (com.android.systemui.ImageWallpaper (0xb7af55c0): 0:9)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7af6888): 0:67)- (DimLayer (0xb7afc3b0): 0:10) (DimLayer (0xb7b0fc50): 0:2)* (Starting com.test.thalitest (0xb7b2d700): 0:38)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7b51920): 0:41) (com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity (0xb7af6888): 0:16) 
,07-01 08:58:13.360  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4256088, SEQNUM=4574, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=243385, POWER_SUPPLY_CHARGE_COUNTER=113, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:13.597  1756  2363 V AlarmManager: sending alarm {534abf6 type 3 *alarm*:send_events}
,07-01 08:58:13.607  1756  1756 V AlarmManager: done {534abf6, *alarm*:send_events} [10ms]
,07-01 08:58:13.815  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4237042, SEQNUM=4577, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=214175, POWER_SUPPLY_CHARGE_COUNTER=29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:14.097  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259603, SEQNUM=4581, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=214175, POWER_SUPPLY_CHARGE_COUNTER=29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:14.276  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4272546, SEQNUM=4582, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=214175, POWER_SUPPLY_CHARGE_COUNTER=64, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:14.900   352  1041 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:644 vsyncs) (1:1088)
,07-01 08:58:14.931  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=323, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4257535, SEQNUM=4585, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=236715, POWER_SUPPLY_CHARGE_COUNTER=45, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:15.281  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=322, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259868, SEQNUM=4587, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=236715, POWER_SUPPLY_CHARGE_COUNTER=62, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:15.842  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=322, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4244370, SEQNUM=4591, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=375792, POWER_SUPPLY_CHARGE_COUNTER=83, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:16.351  1756  2363 V AlarmManager: sending alarm {34ac093 type 0 *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,07-01 08:58:16.359  1756  2463 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:58:16.363  1756  1756 V AlarmManager: done {34ac093, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,07-01 08:58:16.364  1756  2450 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:58:16.366  5318  5387 I Finsky  : [362] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-01 08:58:16.368  1756  2979 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:58:16.523  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=322, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4261054, SEQNUM=4598, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=291396, POWER_SUPPLY_CHARGE_COUNTER=42, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:16.542  5318  5387 I Finsky  : [362] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-01 08:58:16.549  5318  5318 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-01 08:58:16.697  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=322, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4255803, SEQNUM=4601, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=320101, POWER_SUPPLY_CHARGE_COUNTER=62, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:17.557  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=321, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259556, SEQNUM=4607, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=220745, POWER_SUPPLY_CHARGE_COUNTER=108, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:17.956   385   573 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,07-01 08:58:17.964   385   572 I ThermalEngine: Sensor:batt_therm:34100 mC
,07-01 08:58:18.325  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=320, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4261886, SEQNUM=4612, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=206393, POWER_SUPPLY_CHARGE_COUNTER=30, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:18.539  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=320, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259245, SEQNUM=4613, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=261073, POWER_SUPPLY_CHARGE_COUNTER=45, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:19.623  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=320, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4258342, SEQNUM=4616, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=248338, POWER_SUPPLY_CHARGE_COUNTER=108, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:20.302  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=319, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4257450, SEQNUM=4619, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=241061, POWER_SUPPLY_CHARGE_COUNTER=30, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:20.529  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=319, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4256866, SEQNUM=4622, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=215186, POWER_SUPPLY_CHARGE_COUNTER=42, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:20.700  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=319, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259211, SEQNUM=4623, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=210739, POWER_SUPPLY_CHARGE_COUNTER=55, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:21.605  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=318, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4258021, SEQNUM=4626, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=239444, POWER_SUPPLY_CHARGE_COUNTER=107, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:22.256  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4255671, SEQNUM=4629, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=243385, POWER_SUPPLY_CHARGE_COUNTER=18, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:22.474  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4240993, SEQNUM=4632, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=235603, POWER_SUPPLY_CHARGE_COUNTER=38, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:22.691  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4258008, SEQNUM=4633, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=220139, POWER_SUPPLY_CHARGE_COUNTER=51, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:23.453  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4287369, SEQNUM=4636, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=174, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:24.098  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=316, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4257416, SEQNUM=4638, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=241668, POWER_SUPPLY_CHARGE_COUNTER=23, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:24.362  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=316, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4262969, SEQNUM=4640, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=213063, POWER_SUPPLY_CHARGE_COUNTER=37, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:24.578  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=316, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4285309, SEQNUM=4643, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=14250, POWER_SUPPLY_CHARGE_COUNTER=74, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:25.237  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4257100, SEQNUM=4645, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=254908, POWER_SUPPLY_CHARGE_COUNTER=37, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:25.559  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259164, SEQNUM=4648, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=221756, POWER_SUPPLY_CHARGE_COUNTER=36, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:25.950  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4258862, SEQNUM=4650, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=243385, POWER_SUPPLY_CHARGE_COUNTER=57, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:26.463  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259433, SEQNUM=4652, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=236715, POWER_SUPPLY_CHARGE_COUNTER=19, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:26.742  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4260321, SEQNUM=4656, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=206898, POWER_SUPPLY_CHARGE_COUNTER=35, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:26.943  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=314, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4260606, SEQNUM=4657, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=245003, POWER_SUPPLY_CHARGE_COUNTER=50, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:27.914  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=314, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4259710, SEQNUM=4660, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=240556, POWER_SUPPLY_CHARGE_COUNTER=107, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:27.965   385   573 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,07-01 08:58:27.980   385   572 I ThermalEngine: Sensor:batt_therm:33400 mC
,07-01 08:58:28.637  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=313, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4257663, SEQNUM=4664, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=270372, POWER_SUPPLY_CHARGE_COUNTER=29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:28.787  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=313, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4275579, SEQNUM=4665, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=12532, POWER_SUPPLY_CHARGE_COUNTER=46, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:31.554  1756  2363 V AlarmManager: sending alarm {86380c9 type 2 *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,07-01 08:58:31.562  1756  1756 V AlarmManager: done {86380c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,07-01 08:58:33.922  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=310, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4260555, SEQNUM=4670, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=211244, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:34.095  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=310, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4262304, SEQNUM=4671, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=208515, POWER_SUPPLY_CHARGE_COUNTER=14, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:34.523  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=310, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4292845, SEQNUM=4673, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-24539, POWER_SUPPLY_CHARGE_COUNTER=68, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:34.696  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=310, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4291092, SEQNUM=4675, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16927, POWER_SUPPLY_CHARGE_COUNTER=33, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:37.969   385   573 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,07-01 08:58:37.985   385   572 I ThermalEngine: Sensor:batt_therm:32900 mC
,07-01 08:58:38.466  3773  4397 I MMApiBackOffService: MMAPIWebServiceRequest backOff fired!
,07-01 08:58:38.468  3773  4397 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:38.482  3773  4394 I MMApiWebService: inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 08:58:38.485  3773  4394 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:38.486  3773  4394 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,07-01 08:58:38.487  3773  4394 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:38.488  3773  4394 I MMApiWebService: request will be re-tried again later: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 08:58:38.490  3773  4394 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:58:47.974   385   573 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,07-01 08:58:47.989   385   572 I ThermalEngine: Sensor:batt_therm:32500 mC
,07-01 08:58:53.219  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4267188, SEQNUM=4677, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3734, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:53.395  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4271005, SEQNUM=4678, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3734, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:53.444  1756  2363 V AlarmManager: sending alarm {200b9ba type 2 *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,07-01 08:58:53.449  1756  1756 V AlarmManager: done {200b9ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4ms]
,07-01 08:58:54.032  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4295097, SEQNUM=4683, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=56736, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:54.130  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4294810, SEQNUM=4684, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=56736, POWER_SUPPLY_CHARGE_COUNTER=4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:58:57.978   385   573 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,07-01 08:58:57.994   385   572 I ThermalEngine: Sensor:batt_therm:32200 mC
,07-01 08:58:59.999  1756  2363 V AlarmManager: sending alarm {99c8998 type 3 *alarm*:android.intent.action.TIME_TICK}
,07-01 08:59:00.052  1756  1756 V AlarmManager: done {99c8998, *alarm*:android.intent.action.TIME_TICK} [53ms]
,07-01 08:59:07.396  2882  3011 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 08:59:07.396  2882  3011 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 08:59:07.983   385   573 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,07-01 08:59:07.999   385   572 I ThermalEngine: Sensor:batt_therm:32000 mC
,07-01 08:59:12.077  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=300, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4271838, SEQNUM=4690, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=177477, POWER_SUPPLY_CHARGE_COUNTER=17, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:12.260  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=300, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=N/A, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4276828, SEQNUM=4691, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=177477, POWER_SUPPLY_CHARGE_COUNTER=26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:12.553   352   352 I SFPerfTracer:      triggers: (rate: 6:321) (compose: 0:2) (post: 0:1) (render: 0:2) (0:559 frames) (1:849)
,07-01 08:59:12.553   352   352 D SFPerfTracer:        layers: (5:10) (FocusedStackFrame (0xb7accda8): 0:9)* (StatusBar (0xb7b3fd08): 1:303) (NavigationBar (0xb7b433a0): 0:18) (com.android.systemui.ImageWallpaper (0xb7af55c0): 0:9)* (DimLayer (0xb7afc3b0): 0:10) (DimLayer (0xb7b0fc50): 0:2)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7b51920): 0:41) (com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity (0xb7af6888): 0:16) 
,07-01 08:59:12.578  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=299, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4305606, SEQNUM=4693, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=177477, POWER_SUPPLY_CHARGE_COUNTER=75, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:12.684  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=299, POWER_SUPPLY_STATUS=Charging, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4298270, SEQNUM=4694, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=177477, POWER_SUPPLY_CHARGE_COUNTER=44, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=1, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:14.429  1756  1856 I PowerManagerService: Nap time (uid 1000)...
,07-01 08:59:14.431  1756  1856 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-01 08:59:14.440  2882  2882 I Keyboard.Facilitator: onFinishInput()
,07-01 08:59:14.441  2421  2454 D KeyguardViewMediator: onStartedGoingToSleep(3)
,07-01 08:59:14.474  1756  1856 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/09/15, 6cbbf7d, I3193f6e94a
,07-01 08:59:14.492   352  2972 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (170 us)
,07-01 08:59:14.734   352  1041 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (6:650 vsyncs) (8:1193)
,07-01 08:59:15.020  5638  5638 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-01 08:59:15.020  5638  5638 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-01 08:59:15.025  1756  1856 D         : activate, handle: 1598182242, enabled: 0, index 2
07-01 08:59:15.025  1756  1856 D         : BstSensorExt: id=1598182242, en=0
07-01 08:59:15.025  1756  1856 D         : enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 209
,07-01 08:59:15.029  1756  1856 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-01 08:59:15.029  1756  1856 D         : activate, handle: 2, enabled: 0, index 5
,07-01 08:59:15.031  1756  1853 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-01 08:59:15.036   352   352 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb7a13df8
07-01 08:59:15.037   352   352 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-01 08:59:15.353   352   352 I qdhwcomposer: enable_dcabc: Done setting OFF mode
,07-01 08:59:15.354   352   352 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
07-01 08:59:15.354   352   352 I SFPerfTracer:       trigger: frame rate (-35.325%)	(38.805 fps)	(25.770 ms) 	(3 drops)	(13 frames)
07-01 08:59:15.354   352   352 I SFPerfTracer:      triggers: (rate: 7:324) (compose: 0:2) (post: 0:1) (render: 0:2) (13:572 frames) (14:868)
07-01 08:59:15.355   352   352 D SFPerfTracer:        layers: (6:11) (FocusedStackFrame (0xb7accda8): 0:9)* (StatusBar (0xb7b3fd08): 0:306) (NavigationBar (0xb7b433a0): 0:18) (com.android.systemui.ImageWallpaper (0xb7af55c0): 0:9)* (DimLayer (0xb7afc3b0): 0:10) (DimLayer (0xb7b0fc50): 0:2)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7b51920): 0:41) (com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity (0xb7af6888): 0:16) (ColorFade (0xb7b2d700): 14:16) 
,07-01 08:59:15.355  1756  2397 D SurfaceControl: Excessive delay in setPowerMode(): 324ms
,07-01 08:59:15.358   352  1031 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-01 08:59:15.361  1756  1856 I PowerManagerService: Sleeping (uid 1000)...
07-01 08:59:15.364  1756  1756 V MotorolaSettingsProvider: getSecureSetting(privacy_aov_bypass_keyguard_google_now_kill_switch, 0)
,07-01 08:59:15.365  1756  1756 V MotorolaSettingsProvider: getSecureSetting(privacy_aov_bypass_keyguard_google_now_user_setting, 0)
,07-01 08:59:15.399   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-01 08:59:15.402   374   374 D audio_hw_fm: audio_extn_fm_set_parameters: Inside
,07-01 08:59:15.402   374   374 V audio_hw_fm: audio_extn_fm_set_parameters: enter
07-01 08:59:15.402   374   374 V audio_hw_fm: audio_extn_fm_set_parameters: exit
,07-01 08:59:15.403   374   374 E bt_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,07-01 08:59:15.431  1756  2374 E WifiStateMachine:  Fail to set up pno, want false now false
,07-01 08:59:15.431  1756  2374 D WifiStateMachine: backgroundScan enabled=false
07-01 08:59:15.432  1756  2374 D WifiStateMachine: handleScreenStateChanged Exit: true
07-01 08:59:15.435  1756  2374 D WifiStateMachine: setSuspendOptimizations: 4 false
07-01 08:59:15.435  1756  2374 D WifiStateMachine: mSuspendOptNeedsDisabled 4
,07-01 08:59:15.479  1756  1756 I qdlights: RGB: NOTI, color=0xff200000, flash=1, onMs/offMs=500/2000
,07-01 08:59:15.479  1756  1756 I qdlights: RGB: selected NOTI, color=0x00200000, onMs/offMs=500/2000
07-01 08:59:15.480  1756  1756 D         : activate, handle: 1598182229, enabled: 0, index 0
07-01 08:59:15.480  1756  1756 E         : <BST> disable accel, orig state: 1
07-01 08:59:15.480  1756  1756 I         : <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
07-01 08:59:15.481   374  1941 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-01 08:59:15.481   374  1941 D audio_hw_fm: audio_extn_fm_set_parameters: Inside
07-01 08:59:15.481   374  1941 V audio_hw_fm: audio_extn_fm_set_parameters: enter
07-01 08:59:15.481   374  1941 V audio_hw_fm: audio_extn_fm_set_parameters: exit
07-01 08:59:15.481   374  1941 E bt_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 08:59:15.482  1756  2374 E WifiStateMachine:  Fail to set up pno, want false now false
07-01 08:59:15.482  1756  2374 D WifiStateMachine: backgroundScan enabled=false
07-01 08:59:15.482  1756  2374 D WifiStateMachine: handleScreenStateChanged Exit: false
,07-01 08:59:15.493  1756  2374 D WifiStateMachine: setSuspendOptimizations: 4 true
,07-01 08:59:15.493  1756  2374 D WifiStateMachine: mSuspendOptNeedsDisabled 0
,07-01 08:59:16.064  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=299, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309709, SEQNUM=4700, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-70012, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:16.199  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=299, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4308835, SEQNUM=4701, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-70012, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:17.988   385   573 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,07-01 08:59:18.003   385   572 I ThermalEngine: Sensor:batt_therm:31900 mC
,07-01 08:59:19.455  1756  2363 V AlarmManager: sending alarm {3a58001 type 2 *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,07-01 08:59:19.458  2421  2421 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
07-01 08:59:19.460  1756  1756 V AlarmManager: done {3a58001, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,07-01 08:59:20.642  1756  2363 V AlarmManager: sending alarm {c3dfea6 type 2 *walarm*:com.google.android.gms.drive.ApiService.RESET_AFTER_BOOT}
,07-01 08:59:20.651  1756  2363 V AlarmManager: sending alarm {86380c9 type 2 *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,07-01 08:59:20.668  1756  2363 V AlarmManager: sending alarm {63e0db3 type 3 *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,07-01 08:59:20.669  1756  1756 V AlarmManager: done {c3dfea6, *walarm*:com.google.android.gms.drive.ApiService.RESET_AFTER_BOOT} [27ms]
,07-01 08:59:20.670  1756  1756 V AlarmManager: done {86380c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [27ms]
,07-01 08:59:20.670  1756  1756 V AlarmManager: done {63e0db3, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [28ms]
,07-01 08:59:20.821  1756  2463 D ConnectivityService: listenForNetwork for Listen from uid/pid:10016/3224 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 08:59:20.877  3224  5854 W DriveInitializer: Background init thread started
,07-01 08:59:20.898  1756  3000 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:59:20.944  3224  5854 W DriveInitializer: Background init thread ended
,07-01 08:59:23.955  3773  4803 E global frequency: no tags to log
,07-01 08:59:23.957  3773  4803 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,07-01 08:59:23.981  2946  4073 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-01 08:59:24.064  3773  4803 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,07-01 08:59:24.068  1756  2450 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:59:24.068  3773  4803 E CCE     : Motorola Account not available!
07-01 08:59:24.069  3773  4803 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:24.074  3773  4803 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,07-01 08:59:24.077  3773  4803 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,07-01 08:59:24.078  3773  4803 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
07-01 08:59:24.078  3773  4803 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,07-01 08:59:24.079  3773  4803 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,07-01 08:59:24.082  3773  4803 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,07-01 08:59:24.262  3773  4803 I global frequency: BcsDSCheckin.events found events 753
,07-01 08:59:24.263  3773  4803 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,07-01 08:59:24.276  3773  4803 I global frequency: The whitelist not avialabale, the defualt one applied: SYSTEM_BOOT,system_app_anr,system_app_crash,data_app_anr,SYSTEM_TOMBSTONE,data_app_crash,MODEM_SILENT_PANIC,KERNEL_PANIC,SYSTEM_RESTART,SYSTEM_PANIC,MODEM_CRITICAL_PANIC,system_server_watchdog,system_server_crash,gpu_ft_report,system_server_anr,bug2go_attach_start,graphics_hang_postmortem,bug2go_attach_complete,SUBSYS_SILENT_PANIC
,07-01 08:59:24.277  3773  4803 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,07-01 08:59:24.278  3773  4803 I global frequency: The whitelist of dropbox: SYSTEM_BOOT,system_app_anr,system_app_crash,data_app_anr,SYSTEM_TOMBSTONE,data_app_crash,MODEM_SILENT_PANIC,KERNEL_PANIC,SYSTEM_RESTART,SYSTEM_PANIC,MODEM_CRITICAL_PANIC,system_server_watchdog,system_server_crash,gpu_ft_report,system_server_anr,bug2go_attach_start,graphics_hang_postmortem,bug2go_attach_complete,SUBSYS_SILENT_PANIC
,07-01 08:59:24.279  3773  4803 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,07-01 08:59:24.314  3773  4803 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,07-01 08:59:24.405  3773  5869 I MMApiWebService: inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,07-01 08:59:24.406  3773  5869 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:24.409  3773  5869 I CCE     : AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,07-01 08:59:24.410  3773  5869 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:24.416  3773  5869 I CCE.ErrorTranslator: unknown error code mapping for: 0
,07-01 08:59:24.416  3773  5869 I global frequency: BcsCore.status() called with error code=ERROR_FAIL
,07-01 08:59:24.418  3773  5869 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,07-01 08:59:27.992   385   573 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,07-01 08:59:28.008   385   572 I ThermalEngine: Sensor:batt_therm:31700 mC
,07-01 08:59:36.979  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310225, SEQNUM=4709, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-57391, POWER_SUPPLY_CHARGE_COUNTER=-355, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 08:59:37.997   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 08:59:38.012   385   572 I ThermalEngine: Sensor:batt_therm:31500 mC
,07-01 08:59:38.489  3773  3906 I MMApiBackOffService: MMAPIWebServiceRequest backOff fired!
,07-01 08:59:38.491  3773  3906 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:38.507  3773  3898 I MMApiWebService: inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 08:59:38.510  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:38.512  3773  3898 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,07-01 08:59:38.514  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:38.516  3773  3898 I MMApiWebService: request will be re-tried again later: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 08:59:38.517  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 08:59:45.517  1756  2363 V AlarmManager: sending alarm {5b0b22c type 2 *walarm*:com.google.android.intent.action.SEND_IDLE}
,07-01 08:59:45.521  1756  1756 V AlarmManager: done {5b0b22c, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,07-01 08:59:48.002   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 08:59:48.017   385   572 I ThermalEngine: Sensor:batt_therm:31300 mC
,07-01 08:59:50.664  1756  2363 V AlarmManager: sending alarm {86380c9 type 2 *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,07-01 08:59:50.673  1756  1756 V AlarmManager: done {86380c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,07-01 08:59:50.839  1756  1767 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:59:51.184  1756  2731 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:59:51.234  3263  3263 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=2b22c205-9f4f-49b7-a3c2-c1283d89fe76
,07-01 08:59:51.249  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 08:59:51.250  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 08:59:51.388  1756  1765 I art     : Background partial concurrent mark sweep GC freed 47812(4MB) AllocSpace objects, 14(588KB) LOS objects, 33% free, 17MB/26MB, paused 2.024ms total 106.169ms
,07-01 08:59:51.415  3263  3305 W GCoreFlp: No location to return for getLastLocation()
,07-01 08:59:51.431  1756  2731 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:59:51.461  3263  3318 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 08:59:51.463  3224  5873 D UdcContextInitService: registered all accounts: true
,07-01 08:59:51.471  3263  3320 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-01 08:59:51.534  3263  3320 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-01 08:59:51.608  3263  3320 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-01 08:59:51.609  1756  2731 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 08:59:53.627  3263  3320 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-01 08:59:53.628  3263  3320 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-01 08:59:58.006   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 08:59:58.022   385   572 I ThermalEngine: Sensor:batt_therm:31200 mC
,07-01 08:59:59.235  3263  3722 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:00:08.011   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 09:00:08.026   385   572 I ThermalEngine: Sensor:batt_therm:31100 mC
,07-01 09:00:14.440  2882  3011 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 09:00:14.440  2882  3011 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 09:00:18.016   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 09:00:18.031   385   572 I ThermalEngine: Sensor:batt_therm:31000 mC
,07-01 09:00:28.020   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 09:00:28.035   385   572 I ThermalEngine: Sensor:batt_therm:30900 mC
,07-01 09:00:34.975  1756  2363 V AlarmManager: sending alarm {99c8998 type 3 *alarm*:android.intent.action.TIME_TICK}
,07-01 09:00:34.978  1756  2363 V AlarmManager: sending alarm {63e0db3 type 3 *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,07-01 09:00:34.978  1756  2363 V AlarmManager: sending alarm {200b9ba type 2 *walarm*:com.google.android.intent.action.GCM_RECONNECT}
07-01 09:00:34.991  1756  1756 V AlarmManager: done {63e0db3, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [16ms]
07-01 09:00:34.991  1756  1756 V AlarmManager: done {200b9ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [16ms]
,07-01 09:00:35.054  1756  1756 V AlarmManager: done {99c8998, *alarm*:android.intent.action.TIME_TICK} [79ms]
,07-01 09:00:38.025   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 09:00:38.040   385   572 I ThermalEngine: Sensor:batt_therm:30800 mC
,07-01 09:00:48.030   385   573 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,07-01 09:00:48.045   385   572 I ThermalEngine: Sensor:batt_therm:30700 mC
,07-01 09:00:57.935  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309523, SEQNUM=4715, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-40865, POWER_SUPPLY_CHARGE_COUNTER=-1398, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 09:00:58.042   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:00:58.062   385   572 I ThermalEngine: Sensor:batt_therm:30600 mC
,07-01 09:01:08.047   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:01:08.067   385   572 I ThermalEngine: Sensor:batt_therm:30600 mC
,07-01 09:01:18.051   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:01:18.071   385   572 I ThermalEngine: Sensor:batt_therm:30600 mC
,07-01 09:01:28.056   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:01:28.076   385   572 I ThermalEngine: Sensor:batt_therm:30500 mC
,07-01 09:01:38.060   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:01:38.080   385   572 I ThermalEngine: Sensor:batt_therm:30400 mC
,07-01 09:01:48.065   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:01:48.085   385   572 I ThermalEngine: Sensor:batt_therm:30300 mC
,07-01 09:01:58.070   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:01:58.090   385   572 I ThermalEngine: Sensor:batt_therm:30300 mC
,07-01 09:02:08.074   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:02:08.094   385   572 I ThermalEngine: Sensor:batt_therm:30300 mC
,07-01 09:02:18.079   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:02:18.099   385   572 I ThermalEngine: Sensor:batt_therm:30300 mC
,07-01 09:02:28.084   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:02:28.103   385   572 I ThermalEngine: Sensor:batt_therm:30300 mC
,07-01 09:02:38.088   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:02:38.108   385   572 I ThermalEngine: Sensor:batt_therm:30200 mC
,07-01 09:02:48.093   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:02:48.113   385   572 I ThermalEngine: Sensor:batt_therm:30200 mC
,07-01 09:02:57.800  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:57.811  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:57.812  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:58.097   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:02:58.118   385   572 I ThermalEngine: Sensor:batt_therm:30100 mC
,07-01 09:03:08.102   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:03:08.123   385   572 I ThermalEngine: Sensor:batt_therm:30100 mC
,07-01 09:03:18.107   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:03:18.127   385   572 I ThermalEngine: Sensor:batt_therm:30100 mC
,07-01 09:03:28.111   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:03:28.132   385   572 I ThermalEngine: Sensor:batt_therm:30000 mC
,07-01 09:03:38.116   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:03:38.137   385   572 I ThermalEngine: Sensor:batt_therm:30000 mC
,07-01 09:03:48.120   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:03:48.141   385   572 I ThermalEngine: Sensor:batt_therm:30000 mC
,07-01 09:03:58.046  1756  2363 V AlarmManager: sending alarm {99c8998 type 3 *alarm*:android.intent.action.TIME_TICK}
,07-01 09:03:58.048  1756  2363 V AlarmManager: sending alarm {200b9ba type 2 *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,07-01 09:03:58.055  1756  1756 V AlarmManager: done {200b9ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8ms]
,07-01 09:03:58.120  1756  1756 V AlarmManager: done {99c8998, *alarm*:android.intent.action.TIME_TICK} [74ms]
,07-01 09:03:58.125   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:03:58.146   385   572 I ThermalEngine: Sensor:batt_therm:30000 mC
,07-01 09:04:08.130   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:04:08.151   385   572 I ThermalEngine: Sensor:batt_therm:30000 mC
,07-01 09:04:18.134   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:04:18.155   385   572 I ThermalEngine: Sensor:batt_therm:30000 mC
,07-01 09:04:28.139   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:04:28.160   385   572 I ThermalEngine: Sensor:batt_therm:29900 mC
,07-01 09:04:38.143   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:04:38.164   385   572 I ThermalEngine: Sensor:batt_therm:29900 mC
,07-01 09:04:38.516  3773  4397 I MMApiBackOffService: MMAPIWebServiceRequest backOff fired!
,07-01 09:04:38.519  3773  4397 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:04:38.536  3773  4394 I MMApiWebService: inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 09:04:38.538  3773  4394 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:04:38.539  3773  4394 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,07-01 09:04:38.540  3773  4394 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:04:38.541  3773  4394 I MMApiWebService: request will be re-tried again later: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 09:04:38.543  3773  4394 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:04:48.148   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:04:48.169   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:04:57.925  3263  3722 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:04:58.153   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:04:58.174   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:04:58.896  1756  2357 D BatteryService: uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49f3800/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309398, SEQNUM=4719, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12520, POWER_SUPPLY_CHARGE_COUNTER=-2997, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,07-01 09:05:08.157   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:05:08.178   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:05:18.162   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:05:18.183   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:05:28.166   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:05:28.187   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:05:38.171   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:05:38.192   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:05:48.176   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:05:48.197   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:05:58.180   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:05:58.201   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:06:08.185   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:06:08.206   385   572 I ThermalEngine: Sensor:batt_therm:29800 mC
,07-01 09:06:18.189   385   573 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,07-01 09:06:18.210   385   572 I ThermalEngine: Sensor:batt_therm:29700 mC
,07-01 09:06:28.194   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:06:28.215   385   572 I ThermalEngine: Sensor:batt_therm:29700 mC
,07-01 09:06:38.199   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:06:38.219   385   572 I ThermalEngine: Sensor:batt_therm:29700 mC
,07-01 09:06:48.204   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:06:48.224   385   572 I ThermalEngine: Sensor:batt_therm:29700 mC
,07-01 09:06:58.208   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:06:58.229   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:07:08.213   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:07:08.233   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:07:18.218   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:07:18.238   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:07:28.222   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:07:28.242   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:07:38.227   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:07:38.247   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:07:48.231   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:07:48.252   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:07:57.992  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:58.001  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:58.002  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:58.236   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:07:58.256   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:08:08.241   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:08:08.261   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:08:18.245   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:08:18.265   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:08:28.250   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:08:28.270   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:08:38.255   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:08:38.275   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:08:45.644  1756  2363 V AlarmManager: sending alarm {99c8998 type 3 *alarm*:android.intent.action.TIME_TICK}
,07-01 09:08:45.647  1756  2363 V AlarmManager: sending alarm {ffa6aec type 0 *walarm*:com.google.android.gms/.checkin.EventLogServiceReceiver}
,07-01 09:08:45.650  1756  2363 V AlarmManager: sending alarm {2f20704 type 0 *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene$DailyHygieneService}
07-01 09:08:45.658  1756  1756 V AlarmManager: done {2f20704, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene$DailyHygieneService} [14ms]
07-01 09:08:45.660  5318  5318 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,07-01 09:08:45.695  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:45.704  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:45.704  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:45.751  1756  1756 V AlarmManager: done {99c8998, *alarm*:android.intent.action.TIME_TICK} [106ms]
,07-01 09:08:45.783  1756  1756 V AlarmManager: done {ffa6aec, *walarm*:com.google.android.gms/.checkin.EventLogServiceReceiver} [139ms]
,07-01 09:08:45.793  5318  5318 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:08:45.802  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:45.822  3224  5923 I EventLogChimeraService: Aggregate from 1467355000788 (log), 1467355000788 (data)
,07-01 09:08:45.825  5318  5318 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:08:45.826  1756  3000 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
07-01 09:08:45.827  1756  2986 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:08:45.835  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:45.867  5318  5318 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:08:45.870  1756  2986 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:08:45.952  3224  5932 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-01 09:08:45.968  3224  5932 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-01 09:08:46.026  1756  2450 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:08:46.034  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:46.076  5318  5318 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:08:46.080  5318  5318 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,07-01 09:08:46.086  1756  1767 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:08:46.090  5318  5318 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,07-01 09:08:46.098  5318  5318 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 32 minutes (failures=2)
,07-01 09:08:46.107  1756  1766 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:08:46.111  1756  2363 V AlarmManager: sending alarm {aa77c49 type 0 *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,07-01 09:08:46.120  3263  3274 D DeviceConnectionService: client connected with version: 8486000
,07-01 09:08:46.122  1756  1756 V AlarmManager: done {aa77c49, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [12ms]
,07-01 09:08:46.126  1756  1766 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:08:46.143  5318  5933 I Finsky  : [373] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-01 09:08:46.145  5318  5381 I PlayCommon: [359] com.google.android.play.a.w.a(27551): Starting to flush logs
,07-01 09:08:46.156  3263  3263 D WearableService: callingUid 10016, callindPid: 3263
,07-01 09:08:46.164  5318  5318 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-01 09:08:46.165  5318  5318 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
,07-01 09:08:46.170  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:08:46.206  5318  5381 I PlayCommon: [359] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
,07-01 09:08:48.259   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:08:48.279   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:08:58.264   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:08:58.284   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:09:00.867  1756  2363 V AlarmManager: sending alarm {99c8998 type 3 *alarm*:android.intent.action.TIME_TICK}
,07-01 09:09:00.869  1756  2363 V AlarmManager: sending alarm {31ac867 type 0 *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
07-01 09:09:00.875  1756  4583 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
07-01 09:09:00.880  1756  1756 V AlarmManager: done {31ac867, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [13ms]
07-01 09:09:00.888  1756  3000 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
07-01 09:09:00.888  5318  5387 I Finsky  : [362] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-01 09:09:00.890  1756  1767 I AccountManagerService: getTypesVisibleToCaller: isPermitted? true
,07-01 09:09:00.947  1756  1756 V AlarmManager: done {99c8998, *alarm*:android.intent.action.TIME_TICK} [80ms]
,07-01 09:09:01.051  5318  5387 I Finsky  : [362] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-01 09:09:01.052  5318  5318 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-01 09:09:08.268   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:09:08.289   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:09:18.273   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:09:18.293   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:09:28.278   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:09:28.298   385   572 I ThermalEngine: Sensor:batt_therm:29600 mC
,07-01 09:09:38.282   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:09:38.302   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:09:48.287   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:09:48.307   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:09:58.291   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:09:58.311   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:10:08.296   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:10:08.316   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:10:18.301   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:10:18.321   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:10:28.305   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:10:28.325   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:10:38.310   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:10:38.330   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:10:44.149  1756  2363 V AlarmManager: sending alarm {99c8998 type 3 *alarm*:android.intent.action.TIME_TICK}
,07-01 09:10:44.151  1756  2363 V AlarmManager: sending alarm {200b9ba type 2 *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,07-01 09:10:44.158  1756  1756 V AlarmManager: done {200b9ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9ms]
,07-01 09:10:44.224  1756  1756 V AlarmManager: done {99c8998, *alarm*:android.intent.action.TIME_TICK} [75ms]
,07-01 09:10:48.314   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:10:48.334   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:10:58.319   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:10:58.339   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:11:08.324   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:11:08.344   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:11:18.328   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:11:18.348   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:11:28.333   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:11:28.353   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:11:38.338   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:11:38.357   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:11:48.342   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:11:48.362   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:11:58.347   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:11:58.367   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:12:08.351   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:12:08.371   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:12:18.356   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:12:18.376   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:12:28.361   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:12:28.380   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:12:38.365   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:12:38.385   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:12:48.370   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:12:48.390   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:12:58.081  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:58.091  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:58.092  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:58.374   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:12:58.394   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:13:08.379   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:13:08.399   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:13:18.384   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:13:18.403   385   572 I ThermalEngine: Sensor:batt_therm:29500 mC
,07-01 09:13:28.388   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:13:28.408   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:13:38.393   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:13:38.413   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:13:48.397   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:13:48.417   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:13:58.402   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:13:58.422   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:14:08.407   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:14:08.426   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:14:18.411   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:14:18.431   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:14:28.416   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:14:28.436   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:14:38.421   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:14:38.440   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:14:38.542  3773  3906 I MMApiBackOffService: MMAPIWebServiceRequest backOff fired!
,07-01 09:14:38.544  3773  3906 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:14:38.560  3773  3898 I MMApiWebService: inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 09:14:38.563  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:14:38.565  3773  3898 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,07-01 09:14:38.567  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:14:38.568  3773  3898 I MMApiWebService: request will be re-tried again later: com.motorola.ccc.notification.GetNotificationsWS.Request
,07-01 09:14:38.571  3773  3898 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,07-01 09:14:48.425   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:14:48.445   385   572 I ThermalEngine: Sensor:batt_therm:29400 mC
,07-01 09:14:58.430   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:14:58.449   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:15:08.435   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:15:08.454   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:15:18.439   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:15:18.459   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:15:28.444   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:15:28.463   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:15:38.448   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:15:38.468   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:15:48.453   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:15:48.472   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:15:58.458   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:15:58.477   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:16:08.462   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:16:08.482   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:16:18.467   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:16:18.486   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:16:28.471   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:16:28.491   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:16:38.476   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:16:38.495   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:16:48.481   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:16:48.500   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:16:53.953  1756  1847 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 09:16:58.485   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:16:58.505   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:17:08.490   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:17:08.509   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:17:18.495   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:17:18.514   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:17:28.499   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:17:28.518   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:17:38.504   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:17:38.523   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:17:48.509   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:17:48.528   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:17:58.197  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:58.205  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 09:17:58.206  3263  3263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:58.513   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:17:58.532   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:18:08.518   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:18:08.537   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:18:18.522   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:18:18.541   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:18:28.527   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:18:28.546   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:18:38.532   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:18:38.551   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:18:48.536   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:18:48.555   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:18:58.541   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:18:58.560   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:19:08.546   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:19:08.564   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:19:18.550   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:19:18.569   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:19:28.555   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:19:28.574   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:19:38.559   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:19:38.578   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:19:48.564   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:19:48.583   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:19:58.569   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:19:58.587   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:20:08.573   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:20:08.592   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:20:18.578   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:20:18.597   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:20:28.582   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:20:28.601   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:20:38.587   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:20:38.606   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:20:48.592   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:20:48.611   385   572 I ThermalEngine: Sensor:batt_therm:29200 mC
,07-01 09:20:58.596   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:20:58.615   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:21:08.601   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:21:08.620   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:21:18.606   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:21:18.624   385   572 I ThermalEngine: Sensor:batt_therm:29300 mC
,07-01 09:21:28.610   385   573 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,07-01 09:21:28.629   385   572 I ThermalEngine: Sensor:batt_therm:29200 mC
,TIME-OUT KILL (timeout was 1400000ms)
```
