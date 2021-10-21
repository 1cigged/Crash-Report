# Crash-Report
RAGE Plugin Hook v1.87.1293.16189 PUBLIC

Game: Grand Theft Auto V
Game build: 2372
Branch: Steam

Plugins loaded at the time of the crash:

No plugin was ticking at the time of this crash.
Base address: 00007ff7bcfc0000
Exception address: 00007ff7bd117d43
Exception offset: 00157d43
Exception code: 0xc0000005 (EXCEPTION_ACCESS_VIOLATION)

Stack trace (unmanaged):
	0x00007ffff7edc347 - UnhandledExceptionFilter - in Unknown:0 (C:\Windows\System32\KERNELBASE.dll)
	0x00007ffffa3151b0 - memset - in Unknown:0 (C:\Windows\SYSTEM32\ntdll.dll)
	0x00007ffffa2fc766 - _C_specific_handler - in Unknown:0 (C:\Windows\SYSTEM32\ntdll.dll)
	0x00007ffffa3120cf - _chkstk - in Unknown:0 (C:\Windows\SYSTEM32\ntdll.dll)
	0x00007ffffa2c1454 - RtlRaiseException - in Unknown:0 (C:\Windows\SYSTEM32\ntdll.dll)
	0x00007ffffa310bfe - KiUserExceptionDispatcher - in Unknown:0 (C:\Windows\SYSTEM32\ntdll.dll)
	0x00007ff7bd117d43 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd158b85 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be5b2799 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be5afcfe - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be5af3a4 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8b85f8 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8c1ce4 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8ca5cb - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8ca69f - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8ca82e - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8cae1a - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8ca632 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8caeaa - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8e000e - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8c97d1 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8bd9b1 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8d859c - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bd8d865b - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be596556 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bcfd4ae7 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bcfd7389 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bcfd6e4a - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bcfe620c - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bcfdf86b - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be59b098 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7bcfc14a8 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be28b2c3 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ff7be78c570 - KiUserExceptionDispatcher - in Unknown:0 (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	0x00007ffff99f7034 - BaseThreadInitThunk - in Unknown:0 (C:\Windows\System32\KERNEL32.DLL)
	0x00007ffffa2c2651 - RtlUserThreadStart - in Unknown:0 (C:\Windows\SYSTEM32\ntdll.dll)

Stack trace (managed):
	  Hook:OnGameCrashManaged(_EXCEPTION_POINTERS* exceptionInfo, Void** stackFrames, Int32 framesCaptured, SByte* exceptionName, Plugin plugin, String pluginStackTrace)
	  Hook:OnGameCrashManaged(_EXCEPTION_POINTERS* exceptionInfo, Void** stackFrames, Int32 framesCaptured, SByte* exceptionName)


General purpose registers:
	RAX: 0xfffffffd98105dfd
	RCX: 0x0000000000000000
	RDX: 0xffffffffffffff58
	RBX: 0x000000001ad5d6d0
	RSP: 0x000000ed8e2fefc0
	RBP: 0x000000ed8e2ff130
	RSI: 0x00007ff7bef62440
	RDI: 0x0000000000000000
	R8: 0x000000ed8e2ff038
	R9: 0x000000001ad5d6d0
	R10: 0x00007ff7bef62478
	R11: 0x000000ed8e2ff048
	R12: 0x00007ff7bef62440
	R13: 0x0000000000000000
	R14: 0x000000ed8e2ff038
	R15: 0x000000ed8e2ff048
	RIP: 0x00007ff7bd117d43

Segment registers:
	CS: 0x0033
	DS: 0x002b
	ES: 0x002b
	FS: 0x0053
	GS: 0x002b
	SS: 0x002b
	Flags: 0x00010246

Debug registers:
	Dr0: 0x0000000000000000
	Dr1: 0x0000000000000000
	Dr2: 0x0000000000000000
	Dr3: 0x0000000000000000
	Dr6: 0x0000000000000000
	Dr7: 0x0000000000000000

Floating point state:
	Xmm0: Low: 0x000000000000002e, High: 0x000000000000002e
	Xmm1: Low: 0xe64455701704b278, High: 0xe64455701704b278
	Xmm2: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm3: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm4: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm5: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm6: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm7: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm8: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm9: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm10: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm11: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm12: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm13: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm14: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm15: Low: 0x0000000000000000, High: 0x0000000000000000

Threads:
	Id: 6268 (0x187c) (CURRENT); state: Running
	Id: 10936 (0x2ab8)state: Wait (Reason: EventPairLow)
	Id: 19516 (0x4c3c)state: Wait (Reason: UserRequest)
	Id: 42972 (0xa7dc)state: Wait (Reason: ExecutionDelay)
	Id: 21496 (0x53f8)state: Wait (Reason: UserRequest)
	Id: 26008 (0x6598)state: Wait (Reason: ExecutionDelay)
	Id: 9440 (0x24e0)state: Wait (Reason: UserRequest)
	Id: 40116 (0x9cb4)state: Wait (Reason: UserRequest)
	Id: 29008 (0x7150)state: Wait (Reason: UserRequest)
	Id: 27108 (0x69e4)state: Wait (Reason: UserRequest)
	Id: 20632 (0x5098)state: Wait (Reason: UserRequest)
	Id: 27088 (0x69d0)state: Wait (Reason: UserRequest)
	Id: 23980 (0x5dac)state: Wait (Reason: UserRequest)
	Id: 19700 (0x4cf4)state: Wait (Reason: UserRequest)
	Id: 19764 (0x4d34)state: Wait (Reason: UserRequest)
	Id: 48832 (0xbec0)state: Wait (Reason: UserRequest)
	Id: 47668 (0xba34)state: Wait (Reason: UserRequest)
	Id: 42456 (0xa5d8)state: Wait (Reason: EventPairLow)
	Id: 38944 (0x9820)state: Wait (Reason: EventPairLow)
	Id: 30740 (0x7814)state: Wait (Reason: EventPairLow)
	Id: 9980 (0x26fc)state: Wait (Reason: UserRequest)
	Id: 33820 (0x841c)state: Wait (Reason: UserRequest)
	Id: 15968 (0x3e60)state: Wait (Reason: UserRequest)
	Id: 12208 (0x2fb0)state: Wait (Reason: UserRequest)
	Id: 37172 (0x9134)state: Running
	Id: 24772 (0x60c4)state: Wait (Reason: UserRequest)
	Id: 31364 (0x7a84)state: Wait (Reason: UserRequest)
	Id: 2772 (0x0ad4)state: Wait (Reason: UserRequest)
	Id: 20852 (0x5174)state: Wait (Reason: UserRequest)
	Id: 6388 (0x18f4)state: Wait (Reason: UserRequest)
	Id: 18872 (0x49b8)state: Wait (Reason: UserRequest)
	Id: 42056 (0xa448)state: Wait (Reason: UserRequest)
	Id: 42576 (0xa650)state: Wait (Reason: UserRequest)
	Id: 27460 (0x6b44)state: Wait (Reason: UserRequest)
	Id: 34068 (0x8514)state: Wait (Reason: UserRequest)
	Id: 5192 (0x1448)state: Wait (Reason: UserRequest)
	Id: 18040 (0x4678)state: Wait (Reason: UserRequest)
	Id: 15372 (0x3c0c)state: Wait (Reason: UserRequest)
	Id: 2724 (0x0aa4)state: Wait (Reason: UserRequest)
	Id: 14364 (0x381c)state: Wait (Reason: UserRequest)
	Id: 8500 (0x2134)state: Wait (Reason: UserRequest)
	Id: 48420 (0xbd24)state: Wait (Reason: UserRequest)
	Id: 10312 (0x2848)state: Wait (Reason: UserRequest)
	Id: 13948 (0x367c)state: Wait (Reason: UserRequest)
	Id: 488 (0x01e8)state: Wait (Reason: UserRequest)
	Id: 15612 (0x3cfc)state: Wait (Reason: UserRequest)
	Id: 18832 (0x4990)state: Wait (Reason: UserRequest)
	Id: 17176 (0x4318)state: Wait (Reason: UserRequest)
	Id: 47932 (0xbb3c)state: Wait (Reason: UserRequest)
	Id: 16112 (0x3ef0)state: Wait (Reason: UserRequest)
	Id: 43468 (0xa9cc)state: Wait (Reason: UserRequest)
	Id: 46812 (0xb6dc)state: Wait (Reason: UserRequest)
	Id: 22764 (0x58ec)state: Wait (Reason: UserRequest)
	Id: 20868 (0x5184)state: Wait (Reason: UserRequest)
	Id: 31464 (0x7ae8)state: Wait (Reason: UserRequest)
	Id: 48004 (0xbb84)state: Wait (Reason: UserRequest)
	Id: 32012 (0x7d0c)state: Wait (Reason: UserRequest)
	Id: 28248 (0x6e58)state: Wait (Reason: UserRequest)
	Id: 25240 (0x6298)state: Wait (Reason: UserRequest)
	Id: 23412 (0x5b74)state: Wait (Reason: UserRequest)
	Id: 17048 (0x4298)state: Wait (Reason: UserRequest)
	Id: 45868 (0xb32c)state: Wait (Reason: UserRequest)
	Id: 24512 (0x5fc0)state: Wait (Reason: UserRequest)
	Id: 47788 (0xbaac)state: Wait (Reason: UserRequest)
	Id: 7428 (0x1d04)state: Wait (Reason: UserRequest)
	Id: 19120 (0x4ab0)state: Wait (Reason: UserRequest)
	Id: 48272 (0xbc90)state: Wait (Reason: UserRequest)
	Id: 12636 (0x315c)state: Wait (Reason: UserRequest)
	Id: 14532 (0x38c4)state: Wait (Reason: UserRequest)
	Id: 11316 (0x2c34)state: Wait (Reason: ExecutionDelay)
	Id: 28432 (0x6f10)state: Wait (Reason: UserRequest)
	Id: 38340 (0x95c4)state: Wait (Reason: UserRequest)
	Id: 27356 (0x6adc)state: Wait (Reason: UserRequest)
	Id: 28892 (0x70dc)state: Wait (Reason: UserRequest)
	Id: 7056 (0x1b90)state: Wait (Reason: UserRequest)
	Id: 30924 (0x78cc)state: Wait (Reason: UserRequest)
	Id: 25584 (0x63f0)state: Wait (Reason: UserRequest)
	Id: 29760 (0x7440)state: Wait (Reason: UserRequest)
	Id: 43888 (0xab70)state: Wait (Reason: UserRequest)
	Id: 38140 (0x94fc)state: Wait (Reason: UserRequest)
	Id: 4804 (0x12c4)state: Wait (Reason: UserRequest)
	Id: 23300 (0x5b04)state: Wait (Reason: UserRequest)
	Id: 10792 (0x2a28)state: Wait (Reason: UserRequest)
	Id: 9456 (0x24f0)state: Wait (Reason: UserRequest)
	Id: 18480 (0x4830)state: Wait (Reason: ExecutionDelay)
	Id: 18600 (0x48a8)state: Wait (Reason: UserRequest)
	Id: 13452 (0x348c)state: Wait (Reason: UserRequest)
	Id: 31208 (0x79e8)state: Wait (Reason: UserRequest)
	Id: 33684 (0x8394)state: Wait (Reason: UserRequest)
	Id: 21444 (0x53c4)state: Wait (Reason: UserRequest)
	Id: 21240 (0x52f8)state: Wait (Reason: EventPairLow)
	Id: 7632 (0x1dd0)state: Wait (Reason: UserRequest)
	Id: 19908 (0x4dc4)state: Wait (Reason: EventPairLow)
	Id: 21664 (0x54a0)state: Wait (Reason: EventPairLow)
	Id: 34320 (0x8610)state: Wait (Reason: UserRequest)
	Id: 1608 (0x0648)state: Wait (Reason: UserRequest)
	Id: 43432 (0xa9a8)state: Wait (Reason: UserRequest)
	Id: 35396 (0x8a44)state: Wait (Reason: UserRequest)
	Id: 12136 (0x2f68)state: Wait (Reason: UserRequest)
	Id: 46788 (0xb6c4)state: Wait (Reason: UserRequest)
	Id: 23624 (0x5c48)state: Wait (Reason: UserRequest)
	Id: 19984 (0x4e10)state: Wait (Reason: UserRequest)
	Id: 4252 (0x109c)state: Wait (Reason: UserRequest)
	Id: 35364 (0x8a24)state: Wait (Reason: UserRequest)
	Id: 36296 (0x8dc8)state: Wait (Reason: UserRequest)
	Id: 34928 (0x8870)state: Wait (Reason: EventPairLow)
	Id: 33144 (0x8178)state: Wait (Reason: ExecutionDelay)
	Id: 31964 (0x7cdc)state: Wait (Reason: UserRequest)
	Id: 14624 (0x3920)state: Wait (Reason: UserRequest)
	Id: 12084 (0x2f34)state: Wait (Reason: ExecutionDelay)
	Id: 48076 (0xbbcc)state: Wait (Reason: UserRequest)
	Id: 1432 (0x0598)state: Wait (Reason: UserRequest)
	Id: 42668 (0xa6ac)state: Wait (Reason: UserRequest)
	Id: 46424 (0xb558)state: Wait (Reason: UserRequest)
	Id: 7084 (0x1bac)state: Wait (Reason: ExecutionDelay)
	Id: 49080 (0xbfb8)state: Wait (Reason: UserRequest)
	Id: 33104 (0x8150)state: Wait (Reason: UserRequest)
	Id: 8836 (0x2284)state: Wait (Reason: UserRequest)
	Id: 41200 (0xa0f0)state: Wait (Reason: UserRequest)
	Id: 36104 (0x8d08)state: Wait (Reason: UserRequest)
	Id: 42788 (0xa724)state: Wait (Reason: UserRequest)
	Id: 46328 (0xb4f8)state: Wait (Reason: UserRequest)
	Id: 21728 (0x54e0)state: Wait (Reason: UserRequest)
	Id: 38020 (0x9484)state: Wait (Reason: EventPairLow)
	Id: 11952 (0x2eb0)state: Wait (Reason: EventPairLow)
	Id: 35476 (0x8a94)state: Wait (Reason: UserRequest)
	Id: 19124 (0x4ab4)state: Wait (Reason: UserRequest)
	Id: 44036 (0xac04)state: Wait (Reason: UserRequest)
	Id: 20472 (0x4ff8)state: Wait (Reason: UserRequest)
	Id: 33384 (0x8268)state: Wait (Reason: UserRequest)
	Id: 21408 (0x53a0)state: Wait (Reason: UserRequest)
	Id: 26972 (0x695c)state: Wait (Reason: UserRequest)
	Id: 41868 (0xa38c)state: Wait (Reason: UserRequest)
	Id: 11996 (0x2edc)state: Wait (Reason: UserRequest)
	Id: 41944 (0xa3d8)state: Wait (Reason: ExecutionDelay)
	Id: 45952 (0xb380)state: Wait (Reason: UserRequest)
	Id: 6832 (0x1ab0)state: Wait (Reason: UserRequest)
	Id: 9264 (0x2430)state: Wait (Reason: UserRequest)
	Id: 42656 (0xa6a0)state: Wait (Reason: UserRequest)
	Id: 23936 (0x5d80)state: Wait (Reason: UserRequest)
	Id: 34736 (0x87b0)state: Wait (Reason: UserRequest)
	Id: 11772 (0x2dfc)state: Wait (Reason: UserRequest)
	Id: 18648 (0x48d8)state: Wait (Reason: UserRequest)
	Id: 37448 (0x9248)state: Wait (Reason: UserRequest)
	Id: 6580 (0x19b4)state: Wait (Reason: UserRequest)
	Id: 23916 (0x5d6c)state: Wait (Reason: UserRequest)
	Id: 32896 (0x8080)state: Wait (Reason: UserRequest)
	Id: 25524 (0x63b4)state: Wait (Reason: UserRequest)
	Id: 21696 (0x54c0)state: Wait (Reason: UserRequest)
	Id: 42584 (0xa658)state: Wait (Reason: UserRequest)
	Id: 32644 (0x7f84)state: Wait (Reason: UserRequest)
	Id: 27236 (0x6a64)state: Wait (Reason: UserRequest)
	Id: 7440 (0x1d10)state: Wait (Reason: UserRequest)
	Id: 24368 (0x5f30)state: Wait (Reason: UserRequest)
	Id: 19952 (0x4df0)state: Wait (Reason: UserRequest)
	Id: 46256 (0xb4b0)state: Wait (Reason: UserRequest)
	Id: 29868 (0x74ac)state: Wait (Reason: UserRequest)
	Id: 10780 (0x2a1c)state: Wait (Reason: UserRequest)
	Id: 42124 (0xa48c)state: Wait (Reason: UserRequest)
	Id: 45480 (0xb1a8)state: Wait (Reason: UserRequest)
	Id: 14012 (0x36bc)state: Wait (Reason: UserRequest)
	Id: 40420 (0x9de4)state: Wait (Reason: EventPairLow)
	Id: 43292 (0xa91c)state: Wait (Reason: UserRequest)
	Id: 36540 (0x8ebc)state: Wait (Reason: UserRequest)
	Id: 42864 (0xa770)state: Wait (Reason: UserRequest)
	Id: 5764 (0x1684)state: Wait (Reason: UserRequest)
	Id: 6268 (0x187c) (CURRENT)
		Start address: 0x0000000000000000
		State: Running
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:05 PM
		Total processor time: 00:00:19.7968750
		User processor time: 00:00:19.7968750

	Id: 10936 (0x2ab8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 11
		Priority level: Normal
		Start time: 10/21/2021 3:29:05 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19516 (0x4c3c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:06 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42972 (0xa7dc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 21496 (0x53f8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:01.4843750
		User processor time: 00:00:01.4843750

	Id: 26008 (0x6598)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 9440 (0x24e0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 40116 (0x9cb4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 29008 (0x7150)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 27108 (0x69e4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 20632 (0x5098)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 27088 (0x69d0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 23980 (0x5dac)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19700 (0x4cf4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19764 (0x4d34)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 48832 (0xbec0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:09 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 47668 (0xba34)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42456 (0xa5d8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 10
		Priority level: Normal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 38944 (0x9820)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 30740 (0x7814)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 11
		Priority level: Normal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 9980 (0x26fc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 33820 (0x841c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00.2031250
		User processor time: 00:00:00.2031250

	Id: 15968 (0x3e60)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00.1562500
		User processor time: 00:00:00.1562500

	Id: 12208 (0x2fb0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:01.1093750
		User processor time: 00:00:01.1093750

	Id: 37172 (0x9134)
		Start address: 0x0000000000000000
		State: Running
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:06.9062500
		User processor time: 00:00:06.9062500

	Id: 24772 (0x60c4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 31364 (0x7a84)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 2772 (0x0ad4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 20852 (0x5174)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 6388 (0x18f4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 18872 (0x49b8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42056 (0xa448)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:02.3750000
		User processor time: 00:00:02.3750000

	Id: 42576 (0xa650)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 13
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00.0312500
		User processor time: 00:00:00.0312500

	Id: 27460 (0x6b44)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 34068 (0x8514)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 5192 (0x1448)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 18040 (0x4678)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15372 (0x3c0c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 2724 (0x0aa4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14364 (0x381c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 13
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 8500 (0x2134)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 13
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 48420 (0xbd24)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 10312 (0x2848)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13948 (0x367c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 488 (0x01e8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15612 (0x3cfc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 18832 (0x4990)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:10 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 17176 (0x4318)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:11 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 47932 (0xbb3c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:11 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 16112 (0x3ef0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 43468 (0xa9cc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 46812 (0xb6dc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 22764 (0x58ec)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 14
		Priority level: Highest
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 20868 (0x5184)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0312500
		User processor time: 00:00:00.0312500

	Id: 31464 (0x7ae8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 48004 (0xbb84)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 32012 (0x7d0c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0937500
		User processor time: 00:00:00.0937500

	Id: 28248 (0x6e58)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0781250
		User processor time: 00:00:00.0781250

	Id: 25240 (0x6298)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 23412 (0x5b74)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.1406250
		User processor time: 00:00:00.1406250

	Id: 17048 (0x4298)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.1250000
		User processor time: 00:00:00.1250000

	Id: 45868 (0xb32c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 24512 (0x5fc0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 47788 (0xbaac)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 7428 (0x1d04)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19120 (0x4ab0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 48272 (0xbc90)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12636 (0x315c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00.3281250
		User processor time: 00:00:00.3281250

	Id: 14532 (0x38c4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 11316 (0x2c34)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 28432 (0x6f10)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 14
		Priority level: Highest
		Start time: 10/21/2021 3:29:12 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 38340 (0x95c4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 27356 (0x6adc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 28892 (0x70dc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 7056 (0x1b90)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 30924 (0x78cc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 25584 (0x63f0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 29760 (0x7440)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 43888 (0xab70)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 38140 (0x94fc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 4804 (0x12c4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 23300 (0x5b04)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 10792 (0x2a28)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 22
		Priority level: 14
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 9456 (0x24f0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 18480 (0x4830)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:03.6718750
		User processor time: 00:00:03.6718750

	Id: 18600 (0x48a8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13452 (0x348c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00.0625000
		User processor time: 00:00:00.0625000

	Id: 31208 (0x79e8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 33684 (0x8394)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 21444 (0x53c4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 21240 (0x52f8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 7632 (0x1dd0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:13 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 19908 (0x4dc4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:15 PM
		Total processor time: 00:00:00.2968750
		User processor time: 00:00:00.2968750

	Id: 21664 (0x54a0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:15 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 34320 (0x8610)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 1608 (0x0648)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 43432 (0xa9a8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 35396 (0x8a44)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12136 (0x2f68)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 46788 (0xb6c4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 23624 (0x5c48)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19984 (0x4e10)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 4252 (0x109c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 35364 (0x8a24)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 36296 (0x8dc8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 34928 (0x8870)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 33144 (0x8178)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 31964 (0x7cdc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14624 (0x3920)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12084 (0x2f34)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 7
		Priority level: BelowNormal
		Start time: 10/21/2021 3:29:16 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 48076 (0xbbcc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00.2031250
		User processor time: 00:00:00.2031250

	Id: 1432 (0x0598)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00.2031250
		User processor time: 00:00:00.2031250

	Id: 42668 (0xa6ac)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00.0937500
		User processor time: 00:00:00.0937500

	Id: 46424 (0xb558)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00.2031250
		User processor time: 00:00:00.2031250

	Id: 7084 (0x1bac)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 49080 (0xbfb8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 33104 (0x8150)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 8836 (0x2284)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 41200 (0xa0f0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 36104 (0x8d08)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42788 (0xa724)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 22
		Priority level: 14
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00.0937500
		User processor time: 00:00:00.0937500

	Id: 46328 (0xb4f8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 21728 (0x54e0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 38020 (0x9484)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 11
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 11952 (0x2eb0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 10/21/2021 3:29:17 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 35476 (0x8a94)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19124 (0x4ab4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 44036 (0xac04)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 20472 (0x4ff8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 33384 (0x8268)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 21408 (0x53a0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 26972 (0x695c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 41868 (0xa38c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 11996 (0x2edc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00.0625000
		User processor time: 00:00:00.0625000

	Id: 41944 (0xa3d8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: ExecutionDelay)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 45952 (0xb380)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 6832 (0x1ab0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 9264 (0x2430)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42656 (0xa6a0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 23936 (0x5d80)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 34736 (0x87b0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 11772 (0x2dfc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 18648 (0x48d8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 37448 (0x9248)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 6580 (0x19b4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 23916 (0x5d6c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 32896 (0x8080)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 25524 (0x63b4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 21696 (0x54c0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42584 (0xa658)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 10/21/2021 3:29:18 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 32644 (0x7f84)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 27236 (0x6a64)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 7440 (0x1d10)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 24368 (0x5f30)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 19952 (0x4df0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 46256 (0xb4b0)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 29868 (0x74ac)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 10780 (0x2a1c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 42124 (0xa48c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 45480 (0xb1a8)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14012 (0x36bc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:19 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 40420 (0x9de4)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: EventPairLow)
		Priority: 13
		Priority level: AboveNormal
		Start time: 10/21/2021 3:29:21 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 43292 (0xa91c)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:25 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 36540 (0x8ebc)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:59 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 42864 (0xa770)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 10/21/2021 3:29:59 PM
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 5764 (0x1684)
		Start address: 0x00007ffffa2c2630
		State: Wait (Reason: UserRequest)
		Priority: 13
		Priority level: Normal
		Start time: 10/21/2021 3:30:08 PM
		Total processor time: 00:00:00.0312500
		User processor time: 00:00:00.0312500

Modules:
	Name: GTA5.exe; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe (Grand Theft Auto V v1.0.2372.2, by Rockstar Games)
	Name: ntdll.dll; path: C:\Windows\SYSTEM32\ntdll.dll (Microsoft® Windows® Operating System v10.0.19041.1023, by Microsoft Corporation)
	Name: KERNEL32.DLL; path: C:\Windows\System32\KERNEL32.DLL (Microsoft® Windows® Operating System v10.0.19041.1151, by Microsoft Corporation)
	Name: KERNELBASE.dll; path: C:\Windows\System32\KERNELBASE.dll (Microsoft® Windows® Operating System v10.0.19041.1151, by Microsoft Corporation)
	Name: USER32.dll; path: C:\Windows\System32\USER32.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: win32u.dll; path: C:\Windows\System32\win32u.dll (Microsoft® Windows® Operating System v10.0.19041.1288, by Microsoft Corporation)
	Name: GDI32.dll; path: C:\Windows\System32\GDI32.dll (Microsoft® Windows® Operating System v10.0.19041.1202, by Microsoft Corporation)
	Name: gdi32full.dll; path: C:\Windows\System32\gdi32full.dll (Microsoft® Windows® Operating System v10.0.19041.1110, by Microsoft Corporation)
	Name: msvcp_win.dll; path: C:\Windows\System32\msvcp_win.dll (Microsoft® Windows® Operating System v10.0.19041.789, by Microsoft Corporation)
	Name: ucrtbase.dll; path: C:\Windows\System32\ucrtbase.dll (Microsoft® Windows® Operating System v10.0.19041.789, by Microsoft Corporation)
	Name: WS2_32.dll; path: C:\Windows\System32\WS2_32.dll (Microsoft® Windows® Operating System v10.0.19041.1081, by Microsoft Corporation)
	Name: RPCRT4.dll; path: C:\Windows\System32\RPCRT4.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: GFSDK_ShadowLib.win64.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_ShadowLib.win64.dll ( v, by )
	Name: PSAPI.DLL; path: C:\Windows\System32\PSAPI.DLL (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: steam_api64.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\steam_api64.dll (Steam Client API v01.00.00.01, by Valve Corporation)
	Name: CRYPT32.dll; path: C:\Windows\System32\CRYPT32.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: VERSION.dll; path: C:\Windows\SYSTEM32\VERSION.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: ADVAPI32.dll; path: C:\Windows\System32\ADVAPI32.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: msvcrt.dll; path: C:\Windows\System32\msvcrt.dll (Microsoft® Windows® Operating System v7.0.19041.546, by Microsoft Corporation)
	Name: WINTRUST.dll; path: C:\Windows\System32\WINTRUST.dll (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: DSOUND.dll; path: C:\Windows\SYSTEM32\DSOUND.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: IMM32.dll; path: C:\Windows\System32\IMM32.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: sechost.dll; path: C:\Windows\System32\sechost.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: combase.dll; path: C:\Windows\System32\combase.dll (Microsoft® Windows® Operating System v10.0.19041.1202, by Microsoft Corporation)
	Name: bink2w64.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\bink2w64.dll (Bink and Smacker v1.994a, by RAD Game Tools, Inc.)
	Name: SHELL32.dll; path: C:\Windows\System32\SHELL32.dll (Microsoft® Windows® Operating System v10.0.19041.964, by Microsoft Corporation)
	Name: bcrypt.dll; path: C:\Windows\System32\bcrypt.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: ole32.dll; path: C:\Windows\System32\ole32.dll (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: WINMM.dll; path: C:\Windows\SYSTEM32\WINMM.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: SHLWAPI.dll; path: C:\Windows\System32\SHLWAPI.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: MFPlat.DLL; path: C:\Windows\SYSTEM32\MFPlat.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: OLEAUT32.dll; path: C:\Windows\System32\OLEAUT32.dll (Microsoft® Windows® Operating System v10.0.19041.985, by Microsoft Corporation)
	Name: MF.dll; path: C:\Windows\SYSTEM32\MF.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: msdmo.dll; path: C:\Windows\SYSTEM32\msdmo.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: cfgmgr32.dll; path: C:\Windows\System32\cfgmgr32.dll (Microsoft® Windows® Operating System v10.0.19041.1151, by Microsoft Corporation)
	Name: MFReadWrite.dll; path: C:\Windows\SYSTEM32\MFReadWrite.dll (Microsoft® Windows® Operating System v10.0.19041.746, by Microsoft Corporation)
	Name: PROPSYS.dll; path: C:\Windows\SYSTEM32\PROPSYS.dll (Windows® Search v7.0.19041.1, by Microsoft Corporation)
	Name: shcore.dll; path: C:\Windows\System32\shcore.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: d3dx9_43.dll; path: C:\Windows\SYSTEM32\d3dx9_43.dll (Microsoft® DirectX for Windows® v9.29.952.3111, by Microsoft Corporation)
	Name: WTSAPI32.dll; path: C:\Windows\SYSTEM32\WTSAPI32.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: GFSDK_TXAA_AlphaResolve.win64.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_TXAA_AlphaResolve.win64.dll ( v, by )
	Name: d3d9.dll; path: C:\Windows\SYSTEM32\d3d9.dll (Microsoft® Windows® Operating System v10.0.19041.928, by Microsoft Corporation)
	Name: powrprof.dll; path: C:\Windows\SYSTEM32\powrprof.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: D3DCOMPILER_43.dll; path: C:\Windows\SYSTEM32\D3DCOMPILER_43.dll (Microsoft® DirectX for Windows® v9.29.952.3111, by Microsoft Corporation)
	Name: DINPUT8.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\DINPUT8.dll (GTA V Asi loader v1.0.0.1, by Alexander Blade)
	Name: XINPUT1_3.dll; path: C:\Windows\SYSTEM32\XINPUT1_3.dll (Microsoft® DirectX for Windows® v9.18.944.0000, by Microsoft Corporation)
	Name: SETUPAPI.dll; path: C:\Windows\System32\SETUPAPI.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: winmmbase.dll; path: C:\Windows\SYSTEM32\winmmbase.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: IPHLPAPI.DLL; path: C:\Windows\SYSTEM32\IPHLPAPI.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: kernel.appcore.dll; path: C:\Windows\SYSTEM32\kernel.appcore.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: OPENGL32.dll; path: C:\Windows\SYSTEM32\OPENGL32.dll (Microsoft® Windows® Operating System v10.0.19041.1081, by Microsoft Corporation)
	Name: windows.storage.dll; path: C:\Windows\SYSTEM32\windows.storage.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: dwmapi.dll; path: C:\Windows\SYSTEM32\dwmapi.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: Wldp.dll; path: C:\Windows\SYSTEM32\Wldp.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: GLU32.dll; path: C:\Windows\SYSTEM32\GLU32.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: MFCORE.DLL; path: C:\Windows\SYSTEM32\MFCORE.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: ksuser.dll; path: C:\Windows\SYSTEM32\ksuser.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: CRYPTBASE.DLL; path: C:\Windows\SYSTEM32\CRYPTBASE.DLL (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: UMPDC.dll; path: C:\Windows\SYSTEM32\UMPDC.dll ( v, by )
	Name: bcryptPrimitives.dll; path: C:\Windows\System32\bcryptPrimitives.dll (Microsoft® Windows® Operating System v10.0.19041.1202, by Microsoft Corporation)
	Name: RTWorkQ.DLL; path: C:\Windows\SYSTEM32\RTWorkQ.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: MSASN1.dll; path: C:\Windows\SYSTEM32\MSASN1.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: dinput8.dll; path: C:\Windows\system32\dinput8.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: gameoverlayrenderer64.dll; path: D:\Program Files (x86)\gameoverlayrenderer64.dll (Steam Game Overlay Renderer v01.00.00.01, by Valve Corporation)
	Name: inputhost.dll; path: C:\Windows\SYSTEM32\inputhost.dll (Microsoft® Windows® Operating System v10.0.19041.906, by Microsoft Corporation)
	Name: wintypes.dll; path: C:\Windows\SYSTEM32\wintypes.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: CoreMessaging.dll; path: C:\Windows\SYSTEM32\CoreMessaging.dll (Microsoft® Windows® Operating System v10.0.19041.746, by Microsoft Corporation)
	Name: CoreUIComponents.dll; path: C:\Windows\SYSTEM32\CoreUIComponents.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: ntmarta.dll; path: C:\Windows\SYSTEM32\ntmarta.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: Menyoo.asi; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Menyoo.asi ( v, by )
	Name: ScriptHookV.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookV.dll (ScriptHookV v1.0.2372.0, by Alexander Blade)
	Name: d3dx11_43.dll; path: C:\Windows\SYSTEM32\d3dx11_43.dll (Microsoft® DirectX for Windows® v9.29.952.3111, by Microsoft Corporation)
	Name: NativeTrainer.asi; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\NativeTrainer.asi ( v, by )
	Name: openCameraV.asi; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\openCameraV.asi (openCamera for GTAV v1.0.0.1, by OpenIV Dev. Team)
	Name: OpenIV.asi; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\OpenIV.asi (OpenIV v2.0.0.0, by OpenIV Team)
	Name: ScriptHookVDotNet.asi; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet.asi ( v, by )
	Name: mscoree.dll; path: C:\Windows\SYSTEM32\mscoree.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: VCRUNTIME140.dll; path: C:\Windows\SYSTEM32\VCRUNTIME140.dll (Microsoft® Visual Studio® v14.29.30133.0, by Microsoft Corporation)
	Name: mscoreei.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll (Microsoft® .NET Framework v4.8.4180.0, by Microsoft Corporation)
	Name: dxcore.dll; path: C:\Windows\SYSTEM32\dxcore.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: cryptnet.dll; path: C:\Windows\SYSTEM32\cryptnet.dll (Microsoft® Windows® Operating System v10.0.19041.906, by Microsoft Corporation)
	Name: drvstore.dll; path: C:\Windows\SYSTEM32\drvstore.dll (Microsoft® Windows® Operating System v10.0.19041.1081, by Microsoft Corporation)
	Name: devobj.dll; path: C:\Windows\SYSTEM32\devobj.dll (Microsoft® Windows® Operating System v10.0.19041.1151, by Microsoft Corporation)
	Name: imagehlp.dll; path: C:\Windows\System32\imagehlp.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: CRYPTSP.dll; path: C:\Windows\SYSTEM32\CRYPTSP.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: rsaenh.dll; path: C:\Windows\system32\rsaenh.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: nvspcap64.dll; path: C:\Windows\system32\nvspcap64.dll (NVIDIA GeForce Experience v3.23.0.74, by NVIDIA Corporation)
	Name: profapi.dll; path: C:\Windows\SYSTEM32\profapi.dll (Microsoft® Windows® Operating System v10.0.19041.844, by Microsoft Corporation)
	Name: clbcatq.dll; path: C:\Windows\System32\clbcatq.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: amsi.dll; path: C:\Windows\SYSTEM32\amsi.dll (Microsoft® Windows® Operating System v10.0.19041.746, by Microsoft Corporation)
	Name: USERENV.dll; path: C:\Windows\SYSTEM32\USERENV.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: MpOav.dll; path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2104.10-0\MpOav.dll (Microsoft® Windows® Operating System v4.18.2104.10, by Microsoft Corporation)
	Name: gpapi.dll; path: C:\Windows\SYSTEM32\gpapi.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: WINNSI.DLL; path: C:\Windows\SYSTEM32\WINNSI.DLL (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: NSI.dll; path: C:\Windows\System32\NSI.dll (Microsoft® Windows® Operating System v10.0.19041.610, by Microsoft Corporation)
	Name: steamclient64.dll; path: D:\Program Files (x86)\steamclient64.dll (Steam v03.00.00.01, by Valve Corporation)
	Name: tier0_s64.dll; path: D:\Program Files (x86)\tier0_s64.dll ( tier0_s Dynamic Link Library v01.00.00.01, by Valve Corporation)
	Name: Secur32.dll; path: C:\Windows\SYSTEM32\Secur32.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: vstdlib_s64.dll; path: D:\Program Files (x86)\vstdlib_s64.dll (Steam v03.00.00.01, by Valve Corporation)
	Name: MSWSOCK.dll; path: C:\Windows\SYSTEM32\MSWSOCK.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: SSPICLI.DLL; path: C:\Windows\SYSTEM32\SSPICLI.DLL (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: D3D11.DLL; path: C:\Windows\SYSTEM32\D3D11.DLL (Microsoft® Windows® Operating System v10.0.19041.1202, by Microsoft Corporation)
	Name: dxgi.dll; path: C:\Windows\SYSTEM32\dxgi.dll (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: nvapi64.dll; path: C:\Windows\system32\nvapi64.dll (NVIDIA Windows drivers v30.0.14.7168, by NVIDIA Corporation)
	Name: D3D10_1.DLL; path: C:\Windows\SYSTEM32\D3D10_1.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: d3d10_1core.dll; path: C:\Windows\SYSTEM32\d3d10_1core.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: uxtheme.dll; path: C:\Windows\system32\uxtheme.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: MSCTF.dll; path: C:\Windows\System32\MSCTF.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: textinputframework.dll; path: C:\Windows\SYSTEM32\textinputframework.dll (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: WINSTA.dll; path: C:\Windows\SYSTEM32\WINSTA.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: nvldumdx.dll; path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\nvldumdx.dll (NVIDIA driver loader v30.0.14.7168, by NVIDIA Corporation)
	Name: nvwgf2umx.dll; path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\nvwgf2umx.dll (NVIDIA D3D10 drivers v30.0.14.7168, by NVIDIA Corporation)
	Name: NvCamera64.dll; path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\NvCamera\NvCamera64.dll (NVIDIA Camera v7.1, by NVIDIA Corporation)
	Name: HID.DLL; path: C:\Windows\SYSTEM32\HID.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: XINPUT9_1_0.dll; path: C:\Windows\SYSTEM32\XINPUT9_1_0.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: WindowsCodecs.dll; path: C:\Windows\SYSTEM32\WindowsCodecs.dll (Microsoft® Windows® Operating System v10.0.19041.1151, by Microsoft Corporation)
	Name: d3dcompiler_47_64.dll; path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\NvCamera\d3dcompiler_47_64.dll (Microsoft® Windows® Operating System v6.3.9600.16384, by Microsoft Corporation)
	Name: socialclubhelper.dll; path: C:\Users\Ethan\AppData\Local\Temp\nxwdybhp5d05tpbc\socialclubhelper.dll (RAGE Plugin Hook v1.87.1293.16190, by MulleDK19 / LMS)
	Name: FW1FontWrapper.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\FW1FontWrapper.dll ( v, by )
	Name: dbghelp.dll; path: C:\Windows\SYSTEM32\dbghelp.dll (Microsoft® Windows® Operating System v10.0.19041.867, by Microsoft Corporation)
	Name: MSVCP140.dll; path: C:\Windows\SYSTEM32\MSVCP140.dll (Microsoft® Visual Studio® v14.29.30133.0, by Microsoft Corporation)
	Name: VCRUNTIME140_1.dll; path: C:\Windows\SYSTEM32\VCRUNTIME140_1.dll (Microsoft® Visual Studio® v14.29.30133.0, by Microsoft Corporation)
	Name: dbgcore.DLL; path: C:\Windows\SYSTEM32\dbgcore.DLL (Microsoft® Windows® Operating System v10.0.19041.789, by Microsoft Corporation)
	Name: clr.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll (Microsoft® .NET Framework v4.8.4420.0, by Microsoft Corporation)
	Name: ucrtbase_clr0400.dll; path: C:\Windows\SYSTEM32\ucrtbase_clr0400.dll (Microsoft® Visual Studio® 2017 v14.10.25028.0, by Microsoft Corporation)
	Name: VCRUNTIME140_CLR0400.dll; path: C:\Windows\SYSTEM32\VCRUNTIME140_CLR0400.dll (Microsoft® Visual Studio® 2017 v14.10.25028.0, by Microsoft Corporation)
	Name: mscorlib.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\mscorlib\26a845b249aefca961715129e3e55539\mscorlib.ni.dll (Microsoft® .NET Framework v4.8.4420.0, by Microsoft Corporation)
	Name: clrjit.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clrjit.dll (Microsoft® .NET Framework v4.8.4420.0, by Microsoft Corporation)
	Name: diasymreader.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\diasymreader.dll (Microsoft® .NET Framework v14.8.4084.0, by Microsoft Corporation)
	Name: System.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System\43b97e99fab55055761ec7618b2bf77b\System.ni.dll (Microsoft® .NET Framework v4.8.4360.0, by Microsoft Corporation)
	Name: System.Drawing.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Drawing\98b511e858932d0d2ded15adaa4551a5\System.Drawing.ni.dll (Microsoft® .NET Framework v4.8.4390.0, by Microsoft Corporation)
	Name: OneCoreCommonProxyStub.dll; path: C:\Windows\System32\OneCoreCommonProxyStub.dll (Microsoft® Windows® Operating System v10.0.19041.1081, by Microsoft Corporation)
	Name: System.Windows.Forms.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Windows.Forms\cd71d9086a8f3a18a5620122be995963\System.Windows.Forms.ni.dll (Microsoft® .NET Framework v4.8.4400.0, by Microsoft Corporation)
	Name: OneCoreUAPCommonProxyStub.dll; path: C:\Windows\System32\OneCoreUAPCommonProxyStub.dll (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: dcomp.dll; path: C:\Windows\SYSTEM32\dcomp.dll (Microsoft® Windows® Operating System v10.0.19041.1266, by Microsoft Corporation)
	Name: MMDevApi.dll; path: C:\Windows\System32\MMDevApi.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: XAudio2_7.dll; path: C:\Windows\system32\XAudio2_7.dll (Microsoft® DirectX for Windows® v9.29.1962.0, by Microsoft Corporation)
	Name: AUDIOSES.DLL; path: C:\Windows\SYSTEM32\AUDIOSES.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: resourcepolicyclient.dll; path: C:\Windows\SYSTEM32\resourcepolicyclient.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: System.Core.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Core\73d4c7241519af17f6f645768e72fed4\System.Core.ni.dll (Microsoft® .NET Framework v4.8.4390.0, by Microsoft Corporation)
	Name: System.Xml.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Xml\f11e12906b10e17aa60f233acfd67d67\System.Xml.ni.dll (Microsoft® .NET Framework v4.8.4084.0, by Microsoft Corporation)
	Name: Windows.UI.dll; path: C:\Windows\System32\Windows.UI.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: WindowManagementAPI.dll; path: C:\Windows\System32\WindowManagementAPI.dll ( v, by )
	Name: twinapi.appcore.dll; path: C:\Windows\System32\twinapi.appcore.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: avrt.dll; path: C:\Windows\SYSTEM32\avrt.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: System.Configuration.ni.dll; path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Configuration\5b72adac32c4073289e2cf56ad7790d5\System.Configuration.ni.dll (Microsoft® .NET Framework v4.8.4190.0, by Microsoft Corporation)
	Name: comctl32.dll; path: C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_60b5254171f9507e\comctl32.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: gdiplus.dll; path: C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.1288_none_91a663c8cc864906\gdiplus.dll (Microsoft® Windows® Operating System v10.0.19041.1288, by Microsoft Corporation)
	Name: DWrite.dll; path: C:\Windows\SYSTEM32\DWrite.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: TextShaping.dll; path: C:\Windows\SYSTEM32\TextShaping.dll ( v, by )
	Name: MessageBus.dll; path: C:\Program Files\NVIDIA Corporation\NvContainer\MessageBus.dll ( v, by )
	Name: dhcpcsvc.DLL; path: C:\Windows\SYSTEM32\dhcpcsvc.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: SlimDX.dll; path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\SlimDX.dll ( v, by )
	Name: MSVCR100.dll; path: C:\Windows\SYSTEM32\MSVCR100.dll (Microsoft® Visual Studio® 2010 v10.00.40219.325, by Microsoft Corporation)
	Name: MSVCP100.dll; path: C:\Windows\SYSTEM32\MSVCP100.dll (Microsoft® Visual Studio® 2010 v10.00.40219.325, by Microsoft Corporation)
	Name: DiscordHook64.dll; path: C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\modules\discord_hook-1\discord_hook\2b6f62ed4f4\DiscordHook64.dll ( v, by )
	Name: D3DCompiler_47.dll; path: C:\Windows\SYSTEM32\D3DCompiler_47.dll (Microsoft® Windows® Operating System v10.0.19041.868, by Microsoft Corporation)
	Name: napinsp.dll; path: C:\Windows\system32\napinsp.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: pnrpnsp.dll; path: C:\Windows\system32\pnrpnsp.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: wshbth.dll; path: C:\Windows\system32\wshbth.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: NLAapi.dll; path: C:\Windows\system32\NLAapi.dll (Microsoft® Windows® Operating System v10.0.19041.1151, by Microsoft Corporation)
	Name: DNSAPI.dll; path: C:\Windows\SYSTEM32\DNSAPI.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: winrnr.dll; path: C:\Windows\System32\winrnr.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: mdnsNSP.dll; path: C:\Program Files\Bonjour\mdnsNSP.dll (Bonjour v3,1,0,1, by Apple Inc.)
	Name: fwpuclnt.dll; path: C:\Windows\System32\fwpuclnt.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: rasadhlp.dll; path: C:\Windows\System32\rasadhlp.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: DPAPI.dll; path: C:\Windows\SYSTEM32\DPAPI.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: socialclub.dll; path: C:\Program Files\Rockstar Games\Social Club\socialclub.dll (Social Club v2.0.9.3, by Take-Two Interactive Software, Inc.)
	Name: WININET.dll; path: C:\Windows\SYSTEM32\WININET.dll (Internet Explorer v11.00.19041.1, by Microsoft Corporation)
	Name: FirewallAPI.dll; path: C:\Windows\System32\FirewallAPI.dll (Microsoft® Windows® Operating System v10.0.19041.1023, by Microsoft Corporation)
	Name: fwbase.dll; path: C:\Windows\System32\fwbase.dll (Microsoft® Windows® Operating System v10.0.19041.1288, by Microsoft Corporation)
	Name: FWPolicyIOMgr.dll; path: C:\Windows\System32\FWPolicyIOMgr.dll (Microsoft® Windows® Operating System v10.0.19041.1288, by Microsoft Corporation)
	Name: wdmaud.drv; path: C:\Windows\SYSTEM32\wdmaud.drv (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: msacm32.drv; path: C:\Windows\SYSTEM32\msacm32.drv (Microsoft® Windows® Operating System v10.0.19041.488, by Microsoft Corporation)
	Name: MSACM32.dll; path: C:\Windows\SYSTEM32\MSACM32.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: midimap.dll; path: C:\Windows\SYSTEM32\midimap.dll (Microsoft® Windows® Operating System v10.0.19041.488, by Microsoft Corporation)
	Name: iertutil.dll; path: C:\Windows\SYSTEM32\iertutil.dll (Internet Explorer v11.00.19041.1, by Microsoft Corporation)
	Name: ondemandconnroutehelper.dll; path: C:\Windows\SYSTEM32\ondemandconnroutehelper.dll (Microsoft® Windows® Operating System v10.0.19041.546, by Microsoft Corporation)
	Name: winhttp.dll; path: C:\Windows\SYSTEM32\winhttp.dll (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: dhcpcsvc6.DLL; path: C:\Windows\SYSTEM32\dhcpcsvc6.DLL (Microsoft® Windows® Operating System v10.0.19041.1, by Microsoft Corporation)
	Name: GTA5.exe
		Base address: 0x00007ff7bcfc0000
		Memory size: 0x048bec00
		Entry point address: 0x00007ff7be78c5d8
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe
		Product name: Grand Theft Auto V
		Product version: 1.0.2372.2
		Company: Rockstar Games

	Name: ntdll.dll
		Base address: 0x00007ffffa270000
		Memory size: 0x001f5000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\SYSTEM32\ntdll.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1023
		Company: Microsoft Corporation

	Name: KERNEL32.DLL
		Base address: 0x00007ffff99e0000
		Memory size: 0x000be000
		Entry point address: 0x00007ffff99f70d0
		File path: C:\Windows\System32\KERNEL32.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1151
		Company: Microsoft Corporation

	Name: KERNELBASE.dll
		Base address: 0x00007ffff7dd0000
		Memory size: 0x002c9000
		Entry point address: 0x00007ffff7de0710
		File path: C:\Windows\System32\KERNELBASE.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1151
		Company: Microsoft Corporation

	Name: USER32.dll
		Base address: 0x00007ffff9c00000
		Memory size: 0x001a1000
		Entry point address: 0x00007ffff9c182d0
		File path: C:\Windows\System32\USER32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: win32u.dll
		Base address: 0x00007ffff80a0000
		Memory size: 0x00022000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\System32\win32u.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1288
		Company: Microsoft Corporation

	Name: GDI32.dll
		Base address: 0x00007ffff9bd0000
		Memory size: 0x0002b000
		Entry point address: 0x00007ffff9bd48d0
		File path: C:\Windows\System32\GDI32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1202
		Company: Microsoft Corporation

	Name: gdi32full.dll
		Base address: 0x00007ffff7b70000
		Memory size: 0x0010b000
		Entry point address: 0x00007ffff7b9fea0
		File path: C:\Windows\System32\gdi32full.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1110
		Company: Microsoft Corporation

	Name: msvcp_win.dll
		Base address: 0x00007ffff7990000
		Memory size: 0x0009d000
		Entry point address: 0x00007ffff79a5390
		File path: C:\Windows\System32\msvcp_win.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.789
		Company: Microsoft Corporation

	Name: ucrtbase.dll
		Base address: 0x00007ffff7c80000
		Memory size: 0x00100000
		Entry point address: 0x00007ffff7c96110
		File path: C:\Windows\System32\ucrtbase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.789
		Company: Microsoft Corporation

	Name: WS2_32.dll
		Base address: 0x00007ffff9db0000
		Memory size: 0x0006b000
		Entry point address: 0x00007ffff9dc4300
		File path: C:\Windows\System32\WS2_32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1081
		Company: Microsoft Corporation

	Name: RPCRT4.dll
		Base address: 0x00007ffff82c0000
		Memory size: 0x0012a000
		Entry point address: 0x00007ffff831edb0
		File path: C:\Windows\System32\RPCRT4.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: GFSDK_ShadowLib.win64.dll
		Base address: 0x00007fffa5b60000
		Memory size: 0x003cc000
		Entry point address: 0x00007fffa5b6cf10
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_ShadowLib.win64.dll
		Product name: 
		Product version: 
		Company: 

	Name: PSAPI.DLL
		Base address: 0x00007ffff99d0000
		Memory size: 0x00008000
		Entry point address: 0x00007ffff99d1110
		File path: C:\Windows\System32\PSAPI.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: steam_api64.dll
		Base address: 0x0000000067400000
		Memory size: 0x0003f000
		Entry point address: 0x000000006740ac48
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\steam_api64.dll
		Product name: Steam Client API
		Product version: 01.00.00.01
		Company: Valve Corporation

	Name: CRYPT32.dll
		Base address: 0x00007ffff80d0000
		Memory size: 0x00156000
		Entry point address: 0x00007ffff811f2d0
		File path: C:\Windows\System32\CRYPT32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: VERSION.dll
		Base address: 0x00007ffff1910000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffff1911390
		File path: C:\Windows\SYSTEM32\VERSION.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: ADVAPI32.dll
		Base address: 0x00007ffff83f0000
		Memory size: 0x000ac000
		Entry point address: 0x00007ffff8405620
		File path: C:\Windows\System32\ADVAPI32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: msvcrt.dll
		Base address: 0x00007ffff9490000
		Memory size: 0x0009e000
		Entry point address: 0x00007ffff9497850
		File path: C:\Windows\System32\msvcrt.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 7.0.19041.546
		Company: Microsoft Corporation

	Name: WINTRUST.dll
		Base address: 0x00007ffff8260000
		Memory size: 0x00060000
		Entry point address: 0x00007ffff8271100
		File path: C:\Windows\System32\WINTRUST.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: DSOUND.dll
		Base address: 0x00007fffbf2f0000
		Memory size: 0x0009c000
		Entry point address: 0x00007fffbf2ff9b0
		File path: C:\Windows\SYSTEM32\DSOUND.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: IMM32.dll
		Base address: 0x00007ffff9360000
		Memory size: 0x00030000
		Entry point address: 0x00007ffff93614d0
		File path: C:\Windows\System32\IMM32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: sechost.dll
		Base address: 0x00007ffff9390000
		Memory size: 0x0009b000
		Entry point address: 0x00007ffff93acd40
		File path: C:\Windows\System32\sechost.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: combase.dll
		Base address: 0x00007ffff9e20000
		Memory size: 0x00355000
		Entry point address: 0x00007ffff9f12b90
		File path: C:\Windows\System32\combase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1202
		Company: Microsoft Corporation

	Name: bink2w64.dll
		Base address: 0x00007fffd1f60000
		Memory size: 0x0008d000
		Entry point address: 0x00007fffd1f63a78
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\bink2w64.dll
		Product name: Bink and Smacker
		Product version: 1.994a
		Company: RAD Game Tools, Inc.

	Name: SHELL32.dll
		Base address: 0x00007ffff8670000
		Memory size: 0x0073f000
		Entry point address: 0x00007ffff8781630
		File path: C:\Windows\System32\SHELL32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.964
		Company: Microsoft Corporation

	Name: bcrypt.dll
		Base address: 0x00007ffff8230000
		Memory size: 0x00027000
		Entry point address: 0x00007ffff8238690
		File path: C:\Windows\System32\bcrypt.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: ole32.dll
		Base address: 0x00007ffff8db0000
		Memory size: 0x0012a000
		Entry point address: 0x00007ffff8dd6360
		File path: C:\Windows\System32\ole32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: WINMM.dll
		Base address: 0x00007fffed800000
		Memory size: 0x00027000
		Entry point address: 0x00007fffed804220
		File path: C:\Windows\SYSTEM32\WINMM.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: SHLWAPI.dll
		Base address: 0x00007ffff9b70000
		Memory size: 0x00055000
		Entry point address: 0x00007ffff9b7a7a0
		File path: C:\Windows\System32\SHLWAPI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: MFPlat.DLL
		Base address: 0x00007fffcc120000
		Memory size: 0x001bc000
		Entry point address: 0x00007fffcc154960
		File path: C:\Windows\SYSTEM32\MFPlat.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: OLEAUT32.dll
		Base address: 0x00007ffff9aa0000
		Memory size: 0x000cd000
		Entry point address: 0x00007ffff9abde00
		File path: C:\Windows\System32\OLEAUT32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.985
		Company: Microsoft Corporation

	Name: MF.dll
		Base address: 0x00007fffc4dc0000
		Memory size: 0x00084000
		Entry point address: 0x00007fffc4dcaf80
		File path: C:\Windows\SYSTEM32\MF.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: msdmo.dll
		Base address: 0x00007fffefa20000
		Memory size: 0x0000b000
		Entry point address: 0x00007fffefa21570
		File path: C:\Windows\SYSTEM32\msdmo.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: cfgmgr32.dll
		Base address: 0x00007ffff7d80000
		Memory size: 0x0004e000
		Entry point address: 0x00007ffff7d93280
		File path: C:\Windows\System32\cfgmgr32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1151
		Company: Microsoft Corporation

	Name: MFReadWrite.dll
		Base address: 0x00007fffbe5b0000
		Memory size: 0x0010a000
		Entry point address: 0x00007fffbe5d6d70
		File path: C:\Windows\SYSTEM32\MFReadWrite.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.746
		Company: Microsoft Corporation

	Name: PROPSYS.dll
		Base address: 0x00007ffff3570000
		Memory size: 0x000f6000
		Entry point address: 0x00007ffff35b2b30
		File path: C:\Windows\SYSTEM32\PROPSYS.dll
		Product name: Windows® Search
		Product version: 7.0.19041.1
		Company: Microsoft Corporation

	Name: shcore.dll
		Base address: 0x00007ffffa180000
		Memory size: 0x000ad000
		Entry point address: 0x00007ffffa1bb840
		File path: C:\Windows\System32\shcore.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: d3dx9_43.dll
		Base address: 0x00007fffa5800000
		Memory size: 0x00263000
		Entry point address: 0x00007fffa5a15d1c
		File path: C:\Windows\SYSTEM32\d3dx9_43.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.952.3111
		Company: Microsoft Corporation

	Name: WTSAPI32.dll
		Base address: 0x00007ffff31f0000
		Memory size: 0x00014000
		Entry point address: 0x00007ffff31f28c0
		File path: C:\Windows\SYSTEM32\WTSAPI32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: GFSDK_TXAA_AlphaResolve.win64.dll
		Base address: 0x00007ffff51c0000
		Memory size: 0x0001c000
		Entry point address: 0x00007ffff51c493c
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_TXAA_AlphaResolve.win64.dll
		Product name: 
		Product version: 
		Company: 

	Name: d3d9.dll
		Base address: 0x00007fffec2a0000
		Memory size: 0x001ce000
		Entry point address: 0x00007fffec2e2800
		File path: C:\Windows\SYSTEM32\d3d9.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.928
		Company: Microsoft Corporation

	Name: powrprof.dll
		Base address: 0x00007ffff7800000
		Memory size: 0x0004b000
		Entry point address: 0x00007ffff7803480
		File path: C:\Windows\SYSTEM32\powrprof.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: D3DCOMPILER_43.dll
		Base address: 0x00007fffa5380000
		Memory size: 0x0026f000
		Entry point address: 0x00007fffa55bbe5c
		File path: C:\Windows\SYSTEM32\D3DCOMPILER_43.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.952.3111
		Company: Microsoft Corporation

	Name: DINPUT8.dll
		Base address: 0x00007fffedff0000
		Memory size: 0x00025000
		Entry point address: 0x00007fffedff3804
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\DINPUT8.dll
		Product name: GTA V Asi loader
		Product version: 1.0.0.1
		Company: Alexander Blade

	Name: XINPUT1_3.dll
		Base address: 0x0000000000400000
		Memory size: 0x0001e000
		Entry point address: 0x00000000004098e0
		File path: C:\Windows\SYSTEM32\XINPUT1_3.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.18.944.0000
		Company: Microsoft Corporation

	Name: SETUPAPI.dll
		Base address: 0x00007ffff8ee0000
		Memory size: 0x00472000
		Entry point address: 0x00007ffff8f04130
		File path: C:\Windows\System32\SETUPAPI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: winmmbase.dll
		Base address: 0x00007fffe23b0000
		Memory size: 0x00026000
		Entry point address: 0x00007fffe23c6bc0
		File path: C:\Windows\SYSTEM32\winmmbase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: IPHLPAPI.DLL
		Base address: 0x00007ffff6d60000
		Memory size: 0x0003b000
		Entry point address: 0x00007ffff6d6a620
		File path: C:\Windows\SYSTEM32\IPHLPAPI.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: kernel.appcore.dll
		Base address: 0x00007ffff58b0000
		Memory size: 0x00012000
		Entry point address: 0x00007ffff58b3f10
		File path: C:\Windows\SYSTEM32\kernel.appcore.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: OPENGL32.dll
		Base address: 0x00007fffa60b0000
		Memory size: 0x00125000
		Entry point address: 0x00007fffa618dc60
		File path: C:\Windows\SYSTEM32\OPENGL32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1081
		Company: Microsoft Corporation

	Name: windows.storage.dll
		Base address: 0x00007ffff5ab0000
		Memory size: 0x00790000
		Entry point address: 0x00007ffff5c68900
		File path: C:\Windows\SYSTEM32\windows.storage.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: dwmapi.dll
		Base address: 0x00007ffff55c0000
		Memory size: 0x0002f000
		Entry point address: 0x00007ffff55c4d40
		File path: C:\Windows\SYSTEM32\dwmapi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: Wldp.dll
		Base address: 0x00007ffff7310000
		Memory size: 0x0002c000
		Entry point address: 0x00007ffff7312db0
		File path: C:\Windows\SYSTEM32\Wldp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: GLU32.dll
		Base address: 0x00007fffd95d0000
		Memory size: 0x0002c000
		Entry point address: 0x00007fffd95edd30
		File path: C:\Windows\SYSTEM32\GLU32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: MFCORE.DLL
		Base address: 0x00007fffa8c00000
		Memory size: 0x00491000
		Entry point address: 0x00007fffa8c7b580
		File path: C:\Windows\SYSTEM32\MFCORE.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: ksuser.dll
		Base address: 0x00007fffed5d0000
		Memory size: 0x00009000
		Entry point address: 0x00007fffed5d1d50
		File path: C:\Windows\SYSTEM32\ksuser.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: CRYPTBASE.DLL
		Base address: 0x00007ffff7260000
		Memory size: 0x0000c000
		Entry point address: 0x00007ffff7262200
		File path: C:\Windows\SYSTEM32\CRYPTBASE.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: UMPDC.dll
		Base address: 0x00007ffff77e0000
		Memory size: 0x00012000
		Entry point address: 0x00007ffff77e3e30
		File path: C:\Windows\SYSTEM32\UMPDC.dll
		Product name: 
		Product version: 
		Company: 

	Name: bcryptPrimitives.dll
		Base address: 0x00007ffff7ae0000
		Memory size: 0x00083000
		Entry point address: 0x00007ffff7b18cc0
		File path: C:\Windows\System32\bcryptPrimitives.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1202
		Company: Microsoft Corporation

	Name: RTWorkQ.DLL
		Base address: 0x00007fffd3320000
		Memory size: 0x00030000
		Entry point address: 0x00007fffd332be20
		File path: C:\Windows\SYSTEM32\RTWorkQ.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: MSASN1.dll
		Base address: 0x00007ffff74a0000
		Memory size: 0x00012000
		Entry point address: 0x00007ffff74a55f0
		File path: C:\Windows\SYSTEM32\MSASN1.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: dinput8.dll
		Base address: 0x00007fffd6500000
		Memory size: 0x00045000
		Entry point address: 0x00007fffd6506b80
		File path: C:\Windows\system32\dinput8.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: gameoverlayrenderer64.dll
		Base address: 0x00007fffa9670000
		Memory size: 0x001db000
		Entry point address: 0x00007fffa972e074
		File path: D:\Program Files (x86)\gameoverlayrenderer64.dll
		Product name: Steam Game Overlay Renderer
		Product version: 01.00.00.01
		Company: Valve Corporation

	Name: inputhost.dll
		Base address: 0x00007fffdcaf0000
		Memory size: 0x00152000
		Entry point address: 0x00007fffdcb08970
		File path: C:\Windows\SYSTEM32\inputhost.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.906
		Company: Microsoft Corporation

	Name: wintypes.dll
		Base address: 0x00007ffff4a10000
		Memory size: 0x00154000
		Entry point address: 0x00007ffff4a3ad30
		File path: C:\Windows\SYSTEM32\wintypes.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: CoreMessaging.dll
		Base address: 0x00007ffff4ed0000
		Memory size: 0x000f2000
		Entry point address: 0x00007ffff4f27480
		File path: C:\Windows\SYSTEM32\CoreMessaging.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.746
		Company: Microsoft Corporation

	Name: CoreUIComponents.dll
		Base address: 0x00007ffff4b70000
		Memory size: 0x0035e000
		Entry point address: 0x00007ffff4bf2fe0
		File path: C:\Windows\SYSTEM32\CoreUIComponents.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: ntmarta.dll
		Base address: 0x00007ffff6740000
		Memory size: 0x00033000
		Entry point address: 0x00007ffff6746930
		File path: C:\Windows\SYSTEM32\ntmarta.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: Menyoo.asi
		Base address: 0x00007fffa39a0000
		Memory size: 0x00317000
		Entry point address: 0x00007fffa3bc4198
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Menyoo.asi
		Product name: 
		Product version: 
		Company: 

	Name: ScriptHookV.dll
		Base address: 0x00007fffa5680000
		Memory size: 0x0017c000
		Entry point address: 0x00007fffa5690b08
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookV.dll
		Product name: ScriptHookV
		Product version: 1.0.2372.0
		Company: Alexander Blade

	Name: d3dx11_43.dll
		Base address: 0x00007fffd4a30000
		Memory size: 0x00046000
		Entry point address: 0x00007fffd4a67a2c
		File path: C:\Windows\SYSTEM32\d3dx11_43.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.952.3111
		Company: Microsoft Corporation

	Name: NativeTrainer.asi
		Base address: 0x00007fffd6370000
		Memory size: 0x0003c000
		Entry point address: 0x00007fffd637c42c
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\NativeTrainer.asi
		Product name: 
		Product version: 
		Company: 

	Name: openCameraV.asi
		Base address: 0x00007fffd2080000
		Memory size: 0x00024000
		Entry point address: 0x00007fffd2082994
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\openCameraV.asi
		Product name: openCamera for GTAV
		Product version: 1.0.0.1
		Company: OpenIV Dev. Team

	Name: OpenIV.asi
		Base address: 0x00007fffcdfe0000
		Memory size: 0x00027000
		Entry point address: 0x00007fffcdfe2cdc
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\OpenIV.asi
		Product name: OpenIV
		Product version: 2.0.0.0
		Company: OpenIV Team

	Name: ScriptHookVDotNet.asi
		Base address: 0x00007fffc5520000
		Memory size: 0x00027000
		Entry point address: 0x00007fffc552ba86
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet.asi
		Product name: 
		Product version: 
		Company: 

	Name: mscoree.dll
		Base address: 0x00007fffe94f0000
		Memory size: 0x00065000
		Entry point address: 0x00007fffe951bd50
		File path: C:\Windows\SYSTEM32\mscoree.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: VCRUNTIME140.dll
		Base address: 0x00007fffe1440000
		Memory size: 0x0001b000
		Entry point address: 0x00007fffe144fb70
		File path: C:\Windows\SYSTEM32\VCRUNTIME140.dll
		Product name: Microsoft® Visual Studio®
		Product version: 14.29.30133.0
		Company: Microsoft Corporation

	Name: mscoreei.dll
		Base address: 0x00007fffe93f0000
		Memory size: 0x000aa000
		Entry point address: 0x00007fffe93f1010
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4180.0
		Company: Microsoft Corporation

	Name: dxcore.dll
		Base address: 0x00007fffee5a0000
		Memory size: 0x0003b000
		Entry point address: 0x00007fffee5c1b40
		File path: C:\Windows\SYSTEM32\dxcore.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: cryptnet.dll
		Base address: 0x00007ffff0f50000
		Memory size: 0x00031000
		Entry point address: 0x00007ffff0f5e9a0
		File path: C:\Windows\SYSTEM32\cryptnet.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.906
		Company: Microsoft Corporation

	Name: drvstore.dll
		Base address: 0x00007fffee5e0000
		Memory size: 0x0014a000
		Entry point address: 0x00007fffee5ebbc0
		File path: C:\Windows\SYSTEM32\drvstore.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1081
		Company: Microsoft Corporation

	Name: devobj.dll
		Base address: 0x00007ffff7660000
		Memory size: 0x00034000
		Entry point address: 0x00007ffff7668230
		File path: C:\Windows\SYSTEM32\devobj.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1151
		Company: Microsoft Corporation

	Name: imagehlp.dll
		Base address: 0x00007ffff9870000
		Memory size: 0x0001d000
		Entry point address: 0x00007ffff98723b0
		File path: C:\Windows\System32\imagehlp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: CRYPTSP.dll
		Base address: 0x00007ffff7270000
		Memory size: 0x00018000
		Entry point address: 0x00007ffff7274aa0
		File path: C:\Windows\SYSTEM32\CRYPTSP.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: rsaenh.dll
		Base address: 0x00007ffff69f0000
		Memory size: 0x00034000
		Entry point address: 0x00007ffff69f8680
		File path: C:\Windows\system32\rsaenh.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: nvspcap64.dll
		Base address: 0x00007fffc3f60000
		Memory size: 0x002c3000
		Entry point address: 0x00007fffc3f6b3ca
		File path: C:\Windows\system32\nvspcap64.dll
		Product name: NVIDIA GeForce Experience
		Product version: 3.23.0.74
		Company: NVIDIA Corporation

	Name: profapi.dll
		Base address: 0x00007ffff78d0000
		Memory size: 0x0001f000
		Entry point address: 0x00007ffff78d8d30
		File path: C:\Windows\SYSTEM32\profapi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.844
		Company: Microsoft Corporation

	Name: clbcatq.dll
		Base address: 0x00007ffff85c0000
		Memory size: 0x000a9000
		Entry point address: 0x00007ffff85dd990
		File path: C:\Windows\System32\clbcatq.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: amsi.dll
		Base address: 0x00007ffff19a0000
		Memory size: 0x00019000
		Entry point address: 0x00007ffff19a9940
		File path: C:\Windows\SYSTEM32\amsi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.746
		Company: Microsoft Corporation

	Name: USERENV.dll
		Base address: 0x00007ffff7850000
		Memory size: 0x0002e000
		Entry point address: 0x00007ffff7854f10
		File path: C:\Windows\SYSTEM32\USERENV.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: MpOav.dll
		Base address: 0x00007ffff1920000
		Memory size: 0x00079000
		Entry point address: 0x00007ffff1940820
		File path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2104.10-0\MpOav.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 4.18.2104.10
		Company: Microsoft Corporation

	Name: gpapi.dll
		Base address: 0x00007ffff6250000
		Memory size: 0x00023000
		Entry point address: 0x00007ffff6253730
		File path: C:\Windows\SYSTEM32\gpapi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: WINNSI.DLL
		Base address: 0x00007ffff2e60000
		Memory size: 0x0000b000
		Entry point address: 0x00007ffff2e61f70
		File path: C:\Windows\SYSTEM32\WINNSI.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: NSI.dll
		Base address: 0x00007ffff9530000
		Memory size: 0x00008000
		Entry point address: 0x00007ffff95322f0
		File path: C:\Windows\System32\NSI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.610
		Company: Microsoft Corporation

	Name: steamclient64.dll
		Base address: 0x00007fff97800000
		Memory size: 0x014b5000
		Entry point address: 0x00007fff98451c0c
		File path: D:\Program Files (x86)\steamclient64.dll
		Product name: Steam
		Product version: 03.00.00.01
		Company: Valve Corporation

	Name: tier0_s64.dll
		Base address: 0x00007fffa7650000
		Memory size: 0x00175000
		Entry point address: 0x00007fffa7670590
		File path: D:\Program Files (x86)\tier0_s64.dll
		Product name:  tier0_s Dynamic Link Library
		Product version: 01.00.00.01
		Company: Valve Corporation

	Name: Secur32.dll
		Base address: 0x00007fffd9700000
		Memory size: 0x0000c000
		Entry point address: 0x00007fffd9702560
		File path: C:\Windows\SYSTEM32\Secur32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: vstdlib_s64.dll
		Base address: 0x00007fffee090000
		Memory size: 0x00081000
		Entry point address: 0x00007fffee0b8f40
		File path: D:\Program Files (x86)\vstdlib_s64.dll
		Product name: Steam
		Product version: 03.00.00.01
		Company: Valve Corporation

	Name: MSWSOCK.dll
		Base address: 0x00007ffff7070000
		Memory size: 0x0006a000
		Entry point address: 0x00007ffff7081200
		File path: C:\Windows\SYSTEM32\MSWSOCK.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: SSPICLI.DLL
		Base address: 0x00007ffff7880000
		Memory size: 0x00031000
		Entry point address: 0x00007ffff788e390
		File path: C:\Windows\SYSTEM32\SSPICLI.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: D3D11.DLL
		Base address: 0x00007ffff3c70000
		Memory size: 0x00264000
		Entry point address: 0x00007ffff3cebd80
		File path: C:\Windows\SYSTEM32\D3D11.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1202
		Company: Microsoft Corporation

	Name: dxgi.dll
		Base address: 0x00007ffff6280000
		Memory size: 0x000f4000
		Entry point address: 0x00007ffff62a55f0
		File path: C:\Windows\SYSTEM32\dxgi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: nvapi64.dll
		Base address: 0x00007fffd9760000
		Memory size: 0x00719000
		Entry point address: 0x00007fffd9b8635c
		File path: C:\Windows\system32\nvapi64.dll
		Product name: NVIDIA Windows drivers
		Product version: 30.0.14.7168
		Company: NVIDIA Corporation

	Name: D3D10_1.DLL
		Base address: 0x00007fffc5430000
		Memory size: 0x00031000
		Entry point address: 0x00007fffc544fdc0
		File path: C:\Windows\SYSTEM32\D3D10_1.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: d3d10_1core.dll
		Base address: 0x00007ffff31d0000
		Memory size: 0x0000d000
		Entry point address: 0x00007ffff31d17b0
		File path: C:\Windows\SYSTEM32\d3d10_1core.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: uxtheme.dll
		Base address: 0x00007ffff53b0000
		Memory size: 0x0009e000
		Entry point address: 0x00007ffff53d8c00
		File path: C:\Windows\system32\uxtheme.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: MSCTF.dll
		Base address: 0x00007ffff84a0000
		Memory size: 0x00115000
		Entry point address: 0x00007ffff84e1520
		File path: C:\Windows\System32\MSCTF.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: textinputframework.dll
		Base address: 0x00007fffeadf0000
		Memory size: 0x000f9000
		Entry point address: 0x00007fffeae2e070
		File path: C:\Windows\SYSTEM32\textinputframework.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: WINSTA.dll
		Base address: 0x00007ffff76d0000
		Memory size: 0x0005a000
		Entry point address: 0x00007ffff76db770
		File path: C:\Windows\SYSTEM32\WINSTA.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: nvldumdx.dll
		Base address: 0x00007fffee120000
		Memory size: 0x00106000
		Entry point address: 0x00007fffee1213a0
		File path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\nvldumdx.dll
		Product name: NVIDIA driver loader
		Product version: 30.0.14.7168
		Company: NVIDIA Corporation

	Name: nvwgf2umx.dll
		Base address: 0x00007fff8fc60000
		Memory size: 0x04a05000
		Entry point address: 0x00007fff8fca8060
		File path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\nvwgf2umx.dll
		Product name: NVIDIA D3D10 drivers
		Product version: 30.0.14.7168
		Company: NVIDIA Corporation

	Name: NvCamera64.dll
		Base address: 0x00007fff9deb0000
		Memory size: 0x00876000
		Entry point address: 0x00007fff9e181a30
		File path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\NvCamera\NvCamera64.dll
		Product name: NVIDIA Camera
		Product version: 7.1
		Company: NVIDIA Corporation

	Name: HID.DLL
		Base address: 0x00007ffff6240000
		Memory size: 0x0000d000
		Entry point address: 0x00007ffff62426a0
		File path: C:\Windows\SYSTEM32\HID.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: XINPUT9_1_0.dll
		Base address: 0x00007ffff51f0000
		Memory size: 0x00007000
		Entry point address: 0x00007ffff51f1550
		File path: C:\Windows\SYSTEM32\XINPUT9_1_0.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: WindowsCodecs.dll
		Base address: 0x00007ffff0f90000
		Memory size: 0x001b4000
		Entry point address: 0x00007ffff1006a60
		File path: C:\Windows\SYSTEM32\WindowsCodecs.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1151
		Company: Microsoft Corporation

	Name: d3dcompiler_47_64.dll
		Base address: 0x00007fff9a360000
		Memory size: 0x00404000
		Entry point address: 0x00007fff9a6ef360
		File path: C:\Windows\System32\DriverStore\FileRepository\nvgbdi.inf_amd64_d22bd77736afdffe\NvCamera\d3dcompiler_47_64.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 6.3.9600.16384
		Company: Microsoft Corporation

	Name: socialclubhelper.dll
		Base address: 0x0000000c00000000
		Memory size: 0x00f1f000
		Entry point address: 0x0000000c00f1a000
		File path: C:\Users\Ethan\AppData\Local\Temp\nxwdybhp5d05tpbc\socialclubhelper.dll
		Product name: RAGE Plugin Hook
		Product version: 1.87.1293.16190
		Company: MulleDK19 / LMS

	Name: FW1FontWrapper.dll
		Base address: 0x00007fffc2b80000
		Memory size: 0x0002a000
		Entry point address: 0x00007fffc2b8e94c
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\FW1FontWrapper.dll
		Product name: 
		Product version: 
		Company: 

	Name: dbghelp.dll
		Base address: 0x00007fffef830000
		Memory size: 0x001e4000
		Entry point address: 0x00007fffef84b1a0
		File path: C:\Windows\SYSTEM32\dbghelp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.867
		Company: Microsoft Corporation

	Name: MSVCP140.dll
		Base address: 0x00007fffde090000
		Memory size: 0x0008d000
		Entry point address: 0x00007fffde0e2990
		File path: C:\Windows\SYSTEM32\MSVCP140.dll
		Product name: Microsoft® Visual Studio®
		Product version: 14.29.30133.0
		Company: Microsoft Corporation

	Name: VCRUNTIME140_1.dll
		Base address: 0x00007fffdef00000
		Memory size: 0x0000c000
		Entry point address: 0x00007fffdef04160
		File path: C:\Windows\SYSTEM32\VCRUNTIME140_1.dll
		Product name: Microsoft® Visual Studio®
		Product version: 14.29.30133.0
		Company: Microsoft Corporation

	Name: dbgcore.DLL
		Base address: 0x00007fffef510000
		Memory size: 0x0002c000
		Entry point address: 0x00007fffef52b730
		File path: C:\Windows\SYSTEM32\dbgcore.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.789
		Company: Microsoft Corporation

	Name: clr.dll
		Base address: 0x00007fffe2870000
		Memory size: 0x00ac1000
		Entry point address: 0x00007fffe2875dc0
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4420.0
		Company: Microsoft Corporation

	Name: ucrtbase_clr0400.dll
		Base address: 0x00007fffe8c90000
		Memory size: 0x000bd000
		Entry point address: 0x00007fffe8d17db0
		File path: C:\Windows\SYSTEM32\ucrtbase_clr0400.dll
		Product name: Microsoft® Visual Studio® 2017
		Product version: 14.10.25028.0
		Company: Microsoft Corporation

	Name: VCRUNTIME140_CLR0400.dll
		Base address: 0x00007fffe8d80000
		Memory size: 0x00016000
		Entry point address: 0x00007fffe8d8c000
		File path: C:\Windows\SYSTEM32\VCRUNTIME140_CLR0400.dll
		Product name: Microsoft® Visual Studio® 2017
		Product version: 14.10.25028.0
		Company: Microsoft Corporation

	Name: mscorlib.ni.dll
		Base address: 0x00007fffce670000
		Memory size: 0x01600000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\mscorlib\26a845b249aefca961715129e3e55539\mscorlib.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4420.0
		Company: Microsoft Corporation

	Name: clrjit.dll
		Base address: 0x00007fffe12f0000
		Memory size: 0x0014f000
		Entry point address: 0x00007fffe12f1090
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clrjit.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4420.0
		Company: Microsoft Corporation

	Name: diasymreader.dll
		Base address: 0x00007fffd40a0000
		Memory size: 0x0016a000
		Entry point address: 0x00007fffd40c8fc0
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\diasymreader.dll
		Product name: Microsoft® .NET Framework
		Product version: 14.8.4084.0
		Company: Microsoft Corporation

	Name: System.ni.dll
		Base address: 0x00007fffcd310000
		Memory size: 0x00c71000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System\43b97e99fab55055761ec7618b2bf77b\System.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4360.0
		Company: Microsoft Corporation

	Name: System.Drawing.ni.dll
		Base address: 0x00007fffcd110000
		Memory size: 0x001f5000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Drawing\98b511e858932d0d2ded15adaa4551a5\System.Drawing.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4390.0
		Company: Microsoft Corporation

	Name: OneCoreCommonProxyStub.dll
		Base address: 0x00007fffedf40000
		Memory size: 0x0007d000
		Entry point address: 0x00007fffedf43b00
		File path: C:\Windows\System32\OneCoreCommonProxyStub.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1081
		Company: Microsoft Corporation

	Name: System.Windows.Forms.ni.dll
		Base address: 0x00007fffc1130000
		Memory size: 0x010ac000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Windows.Forms\cd71d9086a8f3a18a5620122be995963\System.Windows.Forms.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4400.0
		Company: Microsoft Corporation

	Name: OneCoreUAPCommonProxyStub.dll
		Base address: 0x00007fffefc70000
		Memory size: 0x00798000
		Entry point address: 0x00007fffefc86100
		File path: C:\Windows\System32\OneCoreUAPCommonProxyStub.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: dcomp.dll
		Base address: 0x00007ffff44a0000
		Memory size: 0x001e5000
		Entry point address: 0x00007ffff44fe3f0
		File path: C:\Windows\SYSTEM32\dcomp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1266
		Company: Microsoft Corporation

	Name: MMDevApi.dll
		Base address: 0x00007fffef480000
		Memory size: 0x00085000
		Entry point address: 0x00007fffef4a0c40
		File path: C:\Windows\System32\MMDevApi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: XAudio2_7.dll
		Base address: 0x00007fffb81b0000
		Memory size: 0x0008b000
		Entry point address: 0x00007fffb8220650
		File path: C:\Windows\system32\XAudio2_7.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.1962.0
		Company: Microsoft Corporation

	Name: AUDIOSES.DLL
		Base address: 0x00007fffdf350000
		Memory size: 0x00181000
		Entry point address: 0x00007fffdf377ab0
		File path: C:\Windows\SYSTEM32\AUDIOSES.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: resourcepolicyclient.dll
		Base address: 0x00007ffff54c0000
		Memory size: 0x00014000
		Entry point address: 0x00007ffff54c4280
		File path: C:\Windows\SYSTEM32\resourcepolicyclient.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: System.Core.ni.dll
		Base address: 0x00007fffcb5d0000
		Memory size: 0x00a75000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Core\73d4c7241519af17f6f645768e72fed4\System.Core.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4390.0
		Company: Microsoft Corporation

	Name: System.Xml.ni.dll
		Base address: 0x00007fffca000000
		Memory size: 0x008ab000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Xml\f11e12906b10e17aa60f233acfd67d67\System.Xml.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4084.0
		Company: Microsoft Corporation

	Name: Windows.UI.dll
		Base address: 0x00007fffe9e10000
		Memory size: 0x00141000
		Entry point address: 0x00007fffe9e3cf90
		File path: C:\Windows\System32\Windows.UI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: WindowManagementAPI.dll
		Base address: 0x00007ffff1380000
		Memory size: 0x000a1000
		Entry point address: 0x00007ffff1391d70
		File path: C:\Windows\System32\WindowManagementAPI.dll
		Product name: 
		Product version: 
		Company: 

	Name: twinapi.appcore.dll
		Base address: 0x00007ffff1150000
		Memory size: 0x00201000
		Entry point address: 0x00007ffff11bc800
		File path: C:\Windows\System32\twinapi.appcore.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: avrt.dll
		Base address: 0x00007ffff1900000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffff1901010
		File path: C:\Windows\SYSTEM32\avrt.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: System.Configuration.ni.dll
		Base address: 0x00007fffd3120000
		Memory size: 0x00133000
		Entry point address: 0x0000000000000000
		File path: C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Configuration\5b72adac32c4073289e2cf56ad7790d5\System.Configuration.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.8.4190.0
		Company: Microsoft Corporation

	Name: comctl32.dll
		Base address: 0x00007fffe8760000
		Memory size: 0x0029a000
		Entry point address: 0x00007fffe87f9e80
		File path: C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_60b5254171f9507e\comctl32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: gdiplus.dll
		Base address: 0x00007fffe2540000
		Memory size: 0x001a9000
		Entry point address: 0x00007fffe25985d0
		File path: C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.1288_none_91a663c8cc864906\gdiplus.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1288
		Company: Microsoft Corporation

	Name: DWrite.dll
		Base address: 0x00007fffd2720000
		Memory size: 0x00283000
		Entry point address: 0x00007fffd27b8910
		File path: C:\Windows\SYSTEM32\DWrite.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: TextShaping.dll
		Base address: 0x00007fffea600000
		Memory size: 0x000ac000
		Entry point address: 0x00007fffea64a760
		File path: C:\Windows\SYSTEM32\TextShaping.dll
		Product name: 
		Product version: 
		Company: 

	Name: MessageBus.dll
		Base address: 0x00007fffde3b0000
		Memory size: 0x00737000
		Entry point address: 0x00007fffde75b890
		File path: C:\Program Files\NVIDIA Corporation\NvContainer\MessageBus.dll
		Product name: 
		Product version: 
		Company: 

	Name: dhcpcsvc.DLL
		Base address: 0x00007ffff2cd0000
		Memory size: 0x0001d000
		Entry point address: 0x00007ffff2cd29b0
		File path: C:\Windows\SYSTEM32\dhcpcsvc.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: SlimDX.dll
		Base address: 0x0000000180000000
		Memory size: 0x00392000
		Entry point address: 0x00000001801358b4
		File path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\SlimDX.dll
		Product name: 
		Product version: 
		Company: 

	Name: MSVCR100.dll
		Base address: 0x0000000067320000
		Memory size: 0x000d2000
		Entry point address: 0x00000000673414e4
		File path: C:\Windows\SYSTEM32\MSVCR100.dll
		Product name: Microsoft® Visual Studio® 2010
		Product version: 10.00.40219.325
		Company: Microsoft Corporation

	Name: MSVCP100.dll
		Base address: 0x0000000067280000
		Memory size: 0x00098000
		Entry point address: 0x00000000672c71d0
		File path: C:\Windows\SYSTEM32\MSVCP100.dll
		Product name: Microsoft® Visual Studio® 2010
		Product version: 10.00.40219.325
		Company: Microsoft Corporation

	Name: DiscordHook64.dll
		Base address: 0x00007fffa6800000
		Memory size: 0x001d9000
		Entry point address: 0x00007fffa68f8d18
		File path: C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\modules\discord_hook-1\discord_hook\2b6f62ed4f4\DiscordHook64.dll
		Product name: 
		Product version: 
		Company: 

	Name: D3DCompiler_47.dll
		Base address: 0x00007ffff3810000
		Memory size: 0x0045d000
		Entry point address: 0x00007ffff3a7e100
		File path: C:\Windows\SYSTEM32\D3DCompiler_47.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.868
		Company: Microsoft Corporation

	Name: napinsp.dll
		Base address: 0x00007fffd9f90000
		Memory size: 0x00017000
		Entry point address: 0x00007fffd9f91b10
		File path: C:\Windows\system32\napinsp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: pnrpnsp.dll
		Base address: 0x00007fffd9ec0000
		Memory size: 0x0001b000
		Entry point address: 0x00007fffd9ec23d0
		File path: C:\Windows\system32\pnrpnsp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: wshbth.dll
		Base address: 0x00007fffd9ea0000
		Memory size: 0x00015000
		Entry point address: 0x00007fffd9ea8de0
		File path: C:\Windows\system32\wshbth.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: NLAapi.dll
		Base address: 0x00007ffff2ee0000
		Memory size: 0x0001d000
		Entry point address: 0x00007ffff2ee6d40
		File path: C:\Windows\system32\NLAapi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1151
		Company: Microsoft Corporation

	Name: DNSAPI.dll
		Base address: 0x00007ffff6da0000
		Memory size: 0x000cc000
		Entry point address: 0x00007ffff6dcd440
		File path: C:\Windows\SYSTEM32\DNSAPI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: winrnr.dll
		Base address: 0x00007fffd9e80000
		Memory size: 0x00012000
		Entry point address: 0x00007fffd9e81550
		File path: C:\Windows\System32\winrnr.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: mdnsNSP.dll
		Base address: 0x00000000688d0000
		Memory size: 0x00026000
		Entry point address: 0x00000000688d5844
		File path: C:\Program Files\Bonjour\mdnsNSP.dll
		Product name: Bonjour
		Product version: 3,1,0,1
		Company: Apple Inc.

	Name: fwpuclnt.dll
		Base address: 0x00007ffff0ed0000
		Memory size: 0x0007f000
		Entry point address: 0x00007ffff0ed5910
		File path: C:\Windows\System32\fwpuclnt.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: rasadhlp.dll
		Base address: 0x00007ffff2600000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffff26014a0
		File path: C:\Windows\System32\rasadhlp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: DPAPI.dll
		Base address: 0x00007ffff76c0000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffff76c1850
		File path: C:\Windows\SYSTEM32\DPAPI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: socialclub.dll
		Base address: 0x00007fffa4790000
		Memory size: 0x009f1000
		Entry point address: 0x00007fffa4a756c8
		File path: C:\Program Files\Rockstar Games\Social Club\socialclub.dll
		Product name: Social Club
		Product version: 2.0.9.3
		Company: Take-Two Interactive Software, Inc.

	Name: WININET.dll
		Base address: 0x00007fffe0e20000
		Memory size: 0x004d0000
		Entry point address: 0x00007fffe0efa390
		File path: C:\Windows\SYSTEM32\WININET.dll
		Product name: Internet Explorer
		Product version: 11.00.19041.1
		Company: Microsoft Corporation

	Name: FirewallAPI.dll
		Base address: 0x00007ffff65e0000
		Memory size: 0x0009f000
		Entry point address: 0x00007ffff65ea420
		File path: C:\Windows\System32\FirewallAPI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1023
		Company: Microsoft Corporation

	Name: fwbase.dll
		Base address: 0x00007ffff65b0000
		Memory size: 0x0002f000
		Entry point address: 0x00007ffff65b72e0
		File path: C:\Windows\System32\fwbase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1288
		Company: Microsoft Corporation

	Name: FWPolicyIOMgr.dll
		Base address: 0x00007fffe9ac0000
		Memory size: 0x00041000
		Entry point address: 0x00007fffe9acb610
		File path: C:\Windows\System32\FWPolicyIOMgr.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1288
		Company: Microsoft Corporation

	Name: wdmaud.drv
		Base address: 0x00007fffb4a40000
		Memory size: 0x00046000
		Entry point address: 0x00007fffb4a476a0
		File path: C:\Windows\SYSTEM32\wdmaud.drv
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: msacm32.drv
		Base address: 0x00007fffedd70000
		Memory size: 0x0000d000
		Entry point address: 0x00007fffedd74910
		File path: C:\Windows\SYSTEM32\msacm32.drv
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.488
		Company: Microsoft Corporation

	Name: MSACM32.dll
		Base address: 0x00007fffd4530000
		Memory size: 0x0001e000
		Entry point address: 0x00007fffd45336a0
		File path: C:\Windows\SYSTEM32\MSACM32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: midimap.dll
		Base address: 0x00007fffedd60000
		Memory size: 0x0000b000
		Entry point address: 0x00007fffedd617c0
		File path: C:\Windows\SYSTEM32\midimap.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.488
		Company: Microsoft Corporation

	Name: iertutil.dll
		Base address: 0x00007fffecfd0000
		Memory size: 0x002b0000
		Entry point address: 0x00007fffed0071b0
		File path: C:\Windows\SYSTEM32\iertutil.dll
		Product name: Internet Explorer
		Product version: 11.00.19041.1
		Company: Microsoft Corporation

	Name: ondemandconnroutehelper.dll
		Base address: 0x00007fffd4d10000
		Memory size: 0x00017000
		Entry point address: 0x00007fffd4d12210
		File path: C:\Windows\SYSTEM32\ondemandconnroutehelper.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.546
		Company: Microsoft Corporation

	Name: winhttp.dll
		Base address: 0x00007ffff27a0000
		Memory size: 0x00108000
		Entry point address: 0x00007ffff27ed250
		File path: C:\Windows\SYSTEM32\winhttp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

	Name: dhcpcsvc6.DLL
		Base address: 0x00007ffff2cf0000
		Memory size: 0x00017000
		Entry point address: 0x00007ffff2cf24b0
		File path: C:\Windows\SYSTEM32\dhcpcsvc6.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.19041.1
		Company: Microsoft Corporation

Environment:
	TickCount: 253713578
	ExitCode: 0
	CommandLine: "D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe" -ignoreDifferentVideoCard -skipPatcherCheck @commandline.txt -useSteam -steamAppId=271590 -scCommerceProvider=4
	CurrentDirectory: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V
	SystemDirectory: C:\Windows\system32
	MachineName: DESKTOP-59G6GFO
	ProcessorCount: 12
	SystemPageSize: 4096
	Version: 4.0.30319.42000
	WorkingSet: 1713360896
	OSVersion: Microsoft Windows NT 6.2.9200.0
	Is64BitProcess: True
	Is64BitOperatingSystem: True
	HasShutdownStarted: False
	UserName: Ethan
	UserInteractive: True
	UserDomainName: DESKTOP-59G6GFO
	CurrentManagedThreadId: 5

Process list:
	Opera GX crash-reporter 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\80.0.4170.48\opera_crashreporter.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\system32\sihost.exe)
	  by  (C:\Program Files\Oculus\Support\oculus-runtime\OVRServer_x64.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Qt5 5.15.2.0 by The Qt Company Ltd. (C:\Program Files\Electronic Arts\EA Desktop\EA Desktop\QtWebEngineProcess.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\svchost.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\System32\svchost.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\system32\ApplicationFrameHost.exe)
	Microsoft® Windows® Operating System 2001.22012.0.3920 by Microsoft Corporation (C:\Windows\SystemApps\MicrosoftWindows.Client.CBS_cw5n1h2txyewy\InputApp\TextInputHost.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Social Club UI 2.0.9.3 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\SocialClubHelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\svchost.exe)
	Dual Monitor Tools 2.7.0.0 by GNE (C:\Program Files (x86)\Dual Monitor Tools\DMT.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\conhost.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	  by  (C:\Program Files\NVIDIA Corporation\NvContainer\nvcontainer.exe)
	Razer Central 7.3.32.179 by Razer Inc. (C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Central.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\svchost.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	EA 12, 0, 147, 5024 by Electronic Arts (C:\Program Files\Electronic Arts\EA Desktop\EA Desktop\EAConnect_microsoft.exe)
	  by  (C:\Program Files\WindowsApps\Microsoft.GamingApp_2110.1001.3.0_x64__8wekyb3d8bbwe\XboxAppServices.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Qt5 5.15.2.0 by The Qt Company Ltd. (C:\Program Files\Electronic Arts\EA Desktop\EA Desktop\QtWebEngineProcess.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Razer Synapse 3 3.1.627.5 by Razer Inc. (D:\Synapse3\WPFUI\Framework\Razer Synapse 3 Host\Razer Synapse 3.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Social Club UI 2.0.9.3 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\SocialClubHelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.1202 by Microsoft Corporation (C:\Windows\system32\SettingSyncHost.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\conhost.exe)
	Spotify 1.1.70.610 by Spotify Ltd (C:\Users\Ethan\AppData\Roaming\Spotify\Spotify.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Spotify 1.1.70.610 by Spotify Ltd (C:\Users\Ethan\AppData\Roaming\Spotify\Spotify.exe)
	CefSharp 67.0.0.0 by The CefSharp Authors (C:\Program Files (x86)\Razer\Razer Services\Razer Central\CefSharp.BrowserSubprocess.exe)
	CefSharp 67.0.0.0 by The CefSharp Authors (C:\Program Files (x86)\Razer\Razer Services\Razer Central\CefSharp.BrowserSubprocess.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Social Club UI 2.0.9.3 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\SocialClubHelper.exe)
	Spotify 1.1.70.610 by Spotify Ltd (C:\Users\Ethan\AppData\Roaming\Spotify\Spotify.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Spotify 1.1.70.610 by Spotify Ltd (C:\Users\Ethan\AppData\Roaming\Spotify\Spotify.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Microsoft® Windows® Operating System 10.0.19041.1266 by Microsoft Corporation (C:\Windows\SystemApps\Microsoft.Windows.Search_cw5n1h2txyewy\SearchApp.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Microsoft® Windows® Operating System 10.0.19041.546 by Microsoft Corporation (C:\Windows\system32\DllHost.exe)
	  by  (C:\Windows\SystemApps\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy\StartMenuExperienceHost.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Rockstar Games Launcher Redirector 1.0.0.37 by Rockstar Games (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\PlayGTAV.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\System32\smartscreen.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\oobe\UserOOBEBroker.exe)
	Steam 01.00.00.02 by Valve Corporation (D:\Program Files (x86)\steam.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Microsoft® Windows® Operating System 10.0.19041.1151 by Microsoft Corporation (C:\Windows\SystemApps\ShellExperienceHost_cw5n1h2txyewy\ShellExperienceHost.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Xbox Game Bar 5.721.09022.0 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.XboxGamingOverlay_5.721.9022.0_x64__8wekyb3d8bbwe\GameBar.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Node.js 11.13.0 by Node.js (C:\Program Files (x86)\NVIDIA Corporation\NvNode\NVIDIA Web Helper.exe)
	Xbox Game Bar 5.721.09022.0 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.XboxGamingOverlay_5.721.9022.0_x64__8wekyb3d8bbwe\GameBarFTServer.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Razer Synapse Service Process 1.0.0.0 by  (D:\Synapse3\Service\..\UserProcess\Razer Synapse Service Process.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Rockstar Games Launcher 1.0.49.529 by Rockstar Games (D:\Program Files\Rockstar Games\Launcher\Launcher.exe)
	Steam 03.00.00.01 by Valve Corporation (D:\Program Files (x86)\GameOverlayUI.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\conhost.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\svchost.exe)
	NVIDIA Share rel_03_23/6986037 by NVIDIA Corporation (C:\Program Files\NVIDIA Corporation\NVIDIA GeForce Experience\NVIDIA Share.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Microsoft® Windows® Operating System 10.0.19041.1 by Microsoft Corporation (C:\Windows\system32\taskhostw.exe)
	Vanguard Tray 1.9.0.19 by Riot Games, Inc. (C:\Program Files\Riot Vanguard\vgtray.exe)
	Microsoft® Windows® Operating System 10.0.19041.1202 by Microsoft Corporation (C:\Windows\System32\GameBarPresenceWriter.exe)
	Microsoft® Windows® Operating System 10.0.19041.1266 by Microsoft Corporation (C:\Windows\SystemApps\Microsoft.Windows.Search_cw5n1h2txyewy\SearchApp.exe)
	Microsoft® Windows® Operating System 10.0.19041.746 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (D:\Program Files (x86)\bin\cef\cef.win7x64\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.19041.1023 by Microsoft Corporation (C:\Windows\Explorer.EXE)
	Realtek HD Audio Universal Service 1.0.191.1 by Realtek Semiconductor (C:\Windows\System32\RtkAudUService64.exe)
	Blitz 1.15.64.1318 by Blitz, Inc. (C:\Users\Ethan\AppData\Local\Programs\Blitz\Blitz.exe)
	Microsoft Your Phone 1.21084.79.0 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.YourPhone_1.21084.79.0_x64__8wekyb3d8bbwe\YourPhone.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Discord 1.0.9003 by Discord Inc. (C:\Users\Ethan\AppData\Local\Discord\app-1.0.9003\Discord.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	  by  (C:\Program Files\NVIDIA Corporation\NvContainer\nvcontainer.exe)
	Opera GX Internet Browser 80.0.4170.48 by Opera Software (C:\Users\Ethan\AppData\Local\Programs\Opera GX\opera.exe)
	Spotify 1.1.70.610 by Spotify Ltd (C:\Users\Ethan\AppData\Roaming\Spotify\Spotify.exe)
	NVIDIA Share rel_03_23/6986037 by NVIDIA Corporation (C:\Program Files\NVIDIA Corporation\NVIDIA GeForce Experience\NVIDIA Share.exe)
	NVIDIA Share rel_03_23/6986037 by NVIDIA Corporation (C:\Program Files\NVIDIA Corporation\NVIDIA GeForce Experience\NVIDIA Share.exe)
	Spotify 1.1.70.610 by Spotify Ltd (C:\Users\Ethan\AppData\Roaming\Spotify\Spotify.exe)
	Grand Theft Auto V 1.0.2372.2 by Rockstar Games (D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe)
	Social Club UI 2.0.9.3 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\SocialClubHelper.exe)

File list: 
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Albo1125.Common.dll *8bff6ea79f6ce8a855387409b610cef5
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\asiloader.log *5403659a4777d8a2244447090caefc42
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\bink2w64.dll *3722f03c488093cb2631b5412d4f12d9
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\commandline.txt *6b7db9c79d91171a5dee13a08da8cc1c
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\common.rpf *bbe724acef5f9fcfd85a38c4e35e2f00
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\CrashReport_Ethan_637704101583876641.rcr *fcb588c9efa6b0b9b0efca1d17e3e476
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\cursor_32_2.png *be981c7e1461188450c1bc0352aee019
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\d3dcompiler_46.dll *7ea872c2f9803cfb4223098b85e70cc0
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\d3dcsx_46.dll *8355e491fa90ca00045be22bb556b213
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\DdsConvert.dll *65e684e0fd64493392436cb92617ceb0
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\DefaultSkin.png *a7562ebd9a7c54a6575808da4680caf3
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\dinput8.dll *c9b973183908a6631b31ca29f863b4d1
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\discord-rpc.dll *5882c37b79bae47a0d090006564edb22
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\DiscordRpcNet.dll *65c8b3ac6205985288c4ee507481cddc
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\EasyHook.dll *163e0d2a3cccaa53f16bf5d41721730e
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\EasyHook64.dll *2d7a7ddd6f7ebf32543d851d9a55f60b
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\EasyLoad64.dll *0ee88c5ca0bcfdf02290f4b87f8b9a7e
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\FW1FontWrapper.dll *daa32fd4ee493fc1fdf0b66991868ef4
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_ShadowLib.win64.dll *f2c348c5aaff0c420f4dce3abc1bbad6
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_TXAA.win64.dll *167385d13443035ff68643b2c0c59a4d
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GFSDK_TXAA_AlphaResolve.win64.dll *ea04393624856f44854cace25b50ce3c
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTA5.exe *0dcd16adcdfdf8928e075e4fc8e4bcaf
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTAVLanguageSelect.exe *f9df4ec0adeefd4dd503a3780b2aea11
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\GTAVLauncher.exe *f9df4ec0adeefd4dd503a3780b2aea11
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Gwen.dll *367a1b17121dfc7c2347984380939bc2
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Gwen.UnitTest.dll *90b34cfce1f4caba67f42f4d8f135189
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\installscript.vdf *593566c3ade863a12cf9ad2696e3e8cf
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Koma.Extensions.dll *e516fdaaa7cbc173ffb16122c408b4a7
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\LMS.Common.dll *61dfccfc5509df7e88bc4ab7eab982e1
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\LMS.PortableExecutable.dll *6a52fa924073b0f913855f070dc553a7
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Menyoo.asi *6ebec8fa4be000452cd5b84d3212a00b
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\menyooLog.txt *f5feaf928dac1cd8c3d28c5e2d962f39
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Microsoft.Expression.Drawing.dll *5bd39a82aacf1aa423e6eeeeda696eea
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Microsoft.VisualStudio.QualityTools.UnitTestFramework.dll *660103c9ffbd699916d054beeb186bb6
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Mono.Cecil.dll *6d6292bc8e698e53e69556add6f62442
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Mono.Cecil.Mdb.dll *3c6cff9ef0ba7748d6c61dfacb6890a7
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Mono.Cecil.Pdb.dll *c7a0b5173df5bea531a20fbace30fc89
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\Mono.Cecil.Rocks.dll *7c9a0c59ce05aba61485eb46883ba933
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\NativeTrainer.asi *e107b94ae23ec9a56bfa1faaf7118e85
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\openCameraV.asi *33864c75d1b85563da56aff0ea794267
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\openCameraV.log *c33e527eabf2eea82afc4101ec04b685
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\OpenIV.asi *ef3de847eac7ba336e2d83ba96a8d61d
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\OpenIV.log *933f448c5c402cc74ac76227e774ab3c
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ParksTools.dll *80cb769e7dc95390a02f2b2d36ce7732
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ParksTools.pdb *29cd37ec1e88f9f146faff37f7b4bd91
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\PlayGTAV.exe *f9df4ec0adeefd4dd503a3780b2aea11
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\RAGENativeUI.dll *fad7befc2f049a916a987dbcb7fa030a
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\RAGEPluginHook.exe *5c13f292d6d98a333301a80672b0ab07
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\RagePluginHook.ini *eec93a3d4330a79493b28ae555adc3da
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\RagePluginHook.log *2e40eef8aca25dba5ad84826bc05413c
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\RPH_Readme.txt *7b081efb3e794533b99a7c15807ed09a
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookV.dll *660503fdce1d76a887a2e021783215d3
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookV.log *56a4281d7cf4ebf0a7dff3856a3b5fbe
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet.asi *aef8535d2cf477d55f9c43e104efc933
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet.ini *452aa296f999dc789be6e935ff190fb7
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet2.dll *19e9f88c4d18a5364e68f3b6c6559880
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet2.xml *f904cf545397ead90373f4be9f1e7b43
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet3.dll *046fc495df78281f981b108178899472
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\ScriptHookVDotNet3.xml *1be10803891fc59ab68979927144559e
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\SlimDX.dll *5c243b42d2b0103bbe603cf586ea8467
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\startup.rphs *fc0873885922b9b3b1223b85aa0f7407
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\steam_api64.dll *cac66a8487a2ef6d3b1b8a66c20d1c12
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\System.ValueTuple.dll *4be8f58e6a00f0130f051f444987d217
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64a.rpf *edfbe6855ec32a21a698abc27a899341
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64b.rpf *70af24cd4fe2c8ee58edb902f018a558
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64c.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64d.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64e.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64f.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64g.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64h.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64i.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64j.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64k.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64l.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64m.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64n.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64o.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64p.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64q.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64r.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64s.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64t.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64u.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64v.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\x64w.rpf *Unknown
	D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\XInput1_4.dll *d2ef25dff3e2ad78f89a527101767707

Latest log:
10/21/2021 3:29:13 PM.123] Started new log on 10/21/2021 3:29:13 PM.123
[10/21/2021 3:29:13 PM.125] ====================================================================================================
[10/21/2021 3:29:13 PM.118] Log path: D:\Program Files (x86)\steamapps\common\Grand Theft Auto V\RagePluginHook.log
[10/21/2021 3:29:13 PM.125] Log verbosity: Trivial
[10/21/2021 3:29:13 PM.126] Initializing input system
[10/21/2021 3:29:13 PM.128] Initializing game console
[10/21/2021 3:29:13 PM.134] Console key has been set to F4 (key code: 115)
[10/21/2021 3:29:13 PM.194] Initializing console variable "ConsoleScrollAmount".
[10/21/2021 3:29:13 PM.194] Type: System.Int32, Reading section: "Miscellaneous", key: ConsoleScrollAmount
[10/21/2021 3:29:13 PM.196] Read value: <null>
[10/21/2021 3:29:13 PM.196] Initializing console variable "ConsoleKey".
[10/21/2021 3:29:13 PM.196] Type: System.Windows.Forms.Keys, Reading section: "Miscellaneous", key: ConsoleKey
[10/21/2021 3:29:13 PM.197] Read value: <null>
[10/21/2021 3:29:13 PM.197] Initializing console variable "PluginTimeoutThreshold".
[10/21/2021 3:29:13 PM.197] Type: System.Int32, Reading section: "Miscellaneous", key: PluginTimeoutThreshold
[10/21/2021 3:29:13 PM.200] Read value: 60000
[10/21/2021 3:29:13 PM.200] Setting value of console variable "PluginTimeoutThreshold" to stored value.
[10/21/2021 3:29:13 PM.200] Initializing console variable "AlwaysShowConsoleOutput".
[10/21/2021 3:29:13 PM.200] Type: System.Boolean, Reading section: "Miscellaneous", key: AlwaysShowConsoleOutput
[10/21/2021 3:29:13 PM.200] Read value: <null>
[10/21/2021 3:29:13 PM.200] Initializing console variable "ShowConsoleCommandInfoOnPluginLoad".
[10/21/2021 3:29:13 PM.200] Type: System.Boolean, Reading section: "Miscellaneous", key: ShowConsoleCommandInfoOnPluginLoad
[10/21/2021 3:29:13 PM.201] Read value: <null>
[10/21/2021 3:29:13 PM.201] Initializing console variable "ShowOnScreenWarnings".
[10/21/2021 3:29:13 PM.201] Type: System.Boolean, Reading section: "Miscellaneous", key: ShowOnScreenWarnings
[10/21/2021 3:29:13 PM.201] Read value: <null>
[10/21/2021 3:29:13 PM.201] Console initialized
[10/21/2021 3:29:13 PM.201] Initializing forms manager
[10/21/2021 3:29:13 PM.202] Cleaning temp folder
[10/21/2021 3:29:13 PM.203] Version: RAGE Plugin Hook v1.87.1293.16190 for Grand Theft Auto V
[10/21/2021 3:29:13 PM.209] ================ RAGE Plugin Hook ================
[10/21/2021 3:29:13 PM.212] Command line option "ignoreDifferentVideoCard" is specified twice. Please remove one.
[10/21/2021 3:29:13 PM.216] Detected Windows 10 Home Single Language (64-bit) (10.0.19042.0)!
[10/21/2021 3:29:13 PM.216] Checking game support
[10/21/2021 3:29:13 PM.358] Product name: Grand Theft Auto V
[10/21/2021 3:29:13 PM.358] Product version: 1.0.2372.2
[10/21/2021 3:29:13 PM.358] Is steam version: True
[10/21/2021 3:29:13 PM.359] Initializing DirectX
[10/21/2021 3:29:13 PM.361] Initializing Direct3D
[10/21/2021 3:29:13 PM.361] Getting game swap chain
[10/21/2021 3:29:13 PM.390] Swap Chain created: 0x7FF7BFB55810
[10/21/2021 3:29:13 PM.390] Swap Chain VTable: 0x207F3E56A90
[10/21/2021 3:29:13 PM.390] 0x748948000FE285E9;0x8D48564157552024;0x170EC814890246C
[10/21/2021 3:29:13 PM.390] D3D11Present: 0x7FFFF6282A40
[10/21/2021 3:29:13 PM.390] D3D11ResizeBuffers: 0x7FFFF62A1390
[10/21/2021 3:29:13 PM.390] D3D11ResizeTarget: 0x7FFFF62EC440
[10/21/2021 3:29:13 PM.390] D3D11SetFullscreenState: 0x7FFFF62A3150
[10/21/2021 3:29:13 PM.390] Direct3D initialized
[10/21/2021 3:29:13 PM.390] Initialized DirectX
[10/21/2021 3:29:13 PM.391] Direct3D watcher thread spawned
[10/21/2021 3:29:13 PM.398] Getting device
[10/21/2021 3:29:13 PM.399] Retrieved device
[10/21/2021 3:29:13 PM.399] Creating wrapper
[10/21/2021 3:29:13 PM.473] Wrapper created
[10/21/2021 3:29:13 PM.479] Effect created
[10/21/2021 3:29:13 PM.479] Creating buffer
[10/21/2021 3:29:13 PM.479] Created buffer
[10/21/2021 3:29:13 PM.479] Creating blend state
[10/21/2021 3:29:13 PM.479] Created blend state
[10/21/2021 3:29:13 PM.479] Done with creation
[10/21/2021 3:29:13 PM.542] Initializing texture system.
[10/21/2021 3:29:13 PM.542] Initializing texture system; phase 1
[10/21/2021 3:29:13 PM.542] Initializing texture system; phase 2
[10/21/2021 3:29:13 PM.549] Initializing texture system; phase 3
[10/21/2021 3:29:13 PM.550] Initializing texture system; phase 4
[10/21/2021 3:29:13 PM.561] Initializing texture system; phase 5
[10/21/2021 3:29:13 PM.562] Initializing texture system; phase 6
[10/21/2021 3:29:13 PM.564] Initializing texture system; phase 7
[10/21/2021 3:29:13 PM.566] Initializing texture system; phase 8
[10/21/2021 3:29:13 PM.567] Initializing texture system; phase 9
[10/21/2021 3:29:13 PM.568] Initializing texture system; phase 10
[10/21/2021 3:29:13 PM.572] Initializing texture system; phase 11
[10/21/2021 3:29:13 PM.572] Initializing texture system; phase 12
[10/21/2021 3:29:13 PM.574] Initializing texture system; phase 13
[10/21/2021 3:29:13 PM.574] Initializing texture system; phase 14
[10/21/2021 3:29:18 PM.391] Direct3D watcher thread ended
[10/21/2021 3:29:44 PM.309] LoadingScreenMsg: Initializing game support
[10/21/2021 3:29:44 PM.560] Initializing game support
[10/21/2021 3:29:50 PM.079] LoadingScreenMsg: Velocity limit removed
[10/21/2021 3:29:50 PM.388] Compatibility level: 0
[10/21/2021 3:29:50 PM.389] Supported version detected
[10/21/2021 3:29:50 PM.389] ==================================================
[10/21/2021 3:29:50 PM.389] LoadingScreenMsg: Patching code
[10/21/2021 3:29:50 PM.640] LoadingScreenMsg: Waiting for game initialization
[10/21/2021 3:29:50 PM.891] Waiting for game initialization
[10/21/2021 3:29:50 PM.992] LoadingScreenMsg: Initializing core
[10/21/2021 3:29:51 PM.242] Initializing hook
[10/21/2021 3:29:56 PM.265] LoadingScreenMsg: Completing interoperability
[10/21/2021 3:29:56 PM.516] Completing interoperability
[10/21/2021 3:29:56 PM.516] Initialization code 1.
[10/21/2021 3:29:56 PM.516] Initialization code 2.
[10/21/2021 3:29:56 PM.516] Initialization code 3.
[10/21/2021 3:29:56 PM.523] 1 Address: 0x00007FF7BD9F6BA8
[10/21/2021 3:29:56 PM.523] Calling func 1
[10/21/2021 3:29:56 PM.538] 2 Address: 0x00007FF7BE598E2A
[10/21/2021 3:29:56 PM.538] 3 Address: 0x00007FF7BCFC5CA6
[10/21/2021 3:29:56 PM.564] Address: 0x00007FF7BE598DD4
[10/21/2021 3:29:56 PM.564] Unknown var: 0x00007FF7BF5E5090
[10/21/2021 3:29:56 PM.564] Initialization code 4.
[10/21/2021 3:29:56 PM.564] Initialization code 5.
[10/21/2021 3:29:56 PM.564] Completing interoperability, phase 1
[10/21/2021 3:29:56 PM.565] Completing interoperability, phase 2
[10/21/2021 3:29:56 PM.565] Completing interoperability, phase 3
[10/21/2021 3:29:56 PM.565] Completing interoperability, phase 4
[10/21/2021 3:29:56 PM.565] Completing interoperability, phase 5
[10/21/2021 3:29:56 PM.565] Completing interoperability, phase 6
[10/21/2021 3:29:56 PM.565] Completing interoperability, phase 7
[10/21/2021 3:29:56 PM.565] LoadingScreenMsg: 
[10/21/2021 3:29:56 PM.816] LoadingScreenMsg: Loading Story Mode
[10/21/2021 3:29:59 PM.510] LoadingScreenMsg: Loading and Populating Game World
[10/21/2021 3:29:59 PM.761] LoadingScreenMsg: 
