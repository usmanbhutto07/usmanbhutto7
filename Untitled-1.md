2022-08-03 12:30:56> Program: Starting Squirrel Updater: --install . --noui --intentOverride=work --acquireSource=exe_store --exeName=81e82211-d247-4fa2-8c33-b01bbe1ee31b_30761298bbd02c88c013bec57794358731b9b4556b4927186e5e503c89d35a34.exe --bootstrapperMode
2022-08-03 12:30:56> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 12:30:56> RegistryService: TrySetRegKey: HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\AcquireSource created
2022-08-03 12:30:56> RegistryService: TrySetRegKey: HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\AcquireSource set successfully as exe_store
2022-08-03 12:30:56> Program: AcquireSource reg is set to exe_store
2022-08-03 12:30:56> LogHost: Write failed.
2022-08-03 12:30:56> LogHost: Message: MID does not exist
2022-08-03 12:30:57> LogHost: Stack trace: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Roaming\Microsoft\Teams\SquirrelTelemetry.log'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.StreamWriter.CreateFile(String path, Boolean append, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append)
   at Telemetry.AriaWrapper.LogToFile(String message)
2022-08-03 12:30:57> LogHost: Write failed.
2022-08-03 12:30:57> LogHost: Message: Scenario.Status: success, scenario: 3a109ffd-ddbb-4811-87bd-39e51bfefecd, Scenario.Name: desktop_squirrel_stubinstall, Scenario.Step: start, sequence: 0, appversion: , platformId: 27, DeviceInfo.OsName: Windows, DeviceInfo.CpuArchitecture: x64, DeviceInfo.OsVersion: 10.0.19044.0, AppInfo.ProcessArchitecture: x86, AppInfo.ClientType: desktop, dllSearchPathState: unset, clientType: desktop, source: exe, distSrc: default, breadcrumb: , SignedPackages: enabled, AcquireSource: exe_store, desktopSession: desktop-016ca9b4-aa86-43a7-8214-8063768a3a34, installSessionId: 9daf00a4aa4a990d5521bd6b3b550d8a0b4d863abe856ca61c25a5d27460a4f5, delta: 10, scenarioDelta: 10, elapsed: 1659555056659, stepDelta: 0, DeviceInfo.ComputerUuid: c9d0c522fb1911e6b6db41b8e6022045, DeviceInfo.OfficeMachineId: c9d0c522fb1911e6b6db41b8e6022045, InstallerVersion: 3.2.3.0, eventpdclevel: 1, userpdclevel: 0
2022-08-03 12:30:57> LogHost: Stack trace: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Roaming\Microsoft\Teams\SquirrelTelemetry.log'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.StreamWriter.CreateFile(String path, Boolean append, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append)
   at Telemetry.AriaWrapper.LogToFile(String message)
2022-08-03 12:30:57> Program: bootStrapperModeSettings: pdsEndpoint:https://teams.microsoft.com/desktopclient/installer/windows/
2022-08-03 12:30:57> Program: bootStrapperModeSettings: fallbackNextGenAppPayloadUrlX64:https://aka.ms/maglev-x64
2022-08-03 12:30:57> Program: bootStrapperModeSettings: fallbackNextGenAppPayloadUrlX86:https://aka.ms/maglev-x86
2022-08-03 12:30:57> Program: bootStrapperModeSettings: fallbackNextGenAppPayloadUrlARM64:https://aka.ms/maglev-arm64
2022-08-03 12:30:57> Program: bootStrapperModeSettings: getInstallerEndpointUrl:https://teams.live.com/downloads/getinstaller
2022-08-03 12:30:57> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentBuildNumber exists. Data - 19044
2022-08-03 12:30:57> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentMajorVersionNumber exists. Data - 10
2022-08-03 12:30:57> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentMinorVersionNumber exists. Data - 0
2022-08-03 12:30:57> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentBuildNumber exists. Data - 19044
2022-08-03 12:30:57> LogHost: Write failed.
2022-08-03 12:30:57> LogHost: Message: DownloadUrlRetry: 0, endpointUrl: https://teams.live.com/downloads/getinstaller?intent=Work&arch=x64&platVersion=10.0.19044, Scenario.Status: success, scenario: 3a109ffd-ddbb-4811-87bd-39e51bfefecd, Scenario.Name: desktop_squirrel_stubinstall, Scenario.Step: download_url_start, sequence: 1, appversion: , platformId: 27, DeviceInfo.OsName: Windows, DeviceInfo.CpuArchitecture: x64, DeviceInfo.OsVersion: 10.0.19044.0, AppInfo.ProcessArchitecture: x86, AppInfo.ClientType: desktop, dllSearchPathState: unset, clientType: desktop, source: exe, distSrc: default, breadcrumb: , SignedPackages: enabled, AcquireSource: exe_store, desktopSession: desktop-016ca9b4-aa86-43a7-8214-8063768a3a34, installSessionId: 9daf00a4aa4a990d5521bd6b3b550d8a0b4d863abe856ca61c25a5d27460a4f5, delta: 757, scenarioDelta: 757, elapsed: 1659555057406, stepDelta: 747, DeviceInfo.ComputerUuid: c9d0c522fb1911e6b6db41b8e6022045, DeviceInfo.OfficeMachineId: c9d0c522fb1911e6b6db41b8e6022045, InstallerVersion: 3.2.3.0, eventpdclevel: 1, userpdclevel: 0
2022-08-03 12:30:57> LogHost: Stack trace: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Roaming\Microsoft\Teams\SquirrelTelemetry.log'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.StreamWriter.CreateFile(String path, Boolean append, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append)
   at Telemetry.AriaWrapper.LogToFile(String message)
2022-08-03 12:30:57> FileDownloader: Downloading url: https://teams.live.com/downloads/getinstaller?intent=Work&arch=x64&platVersion=10.0.19044
2022-08-03 12:30:58> LogHost: Write failed.
2022-08-03 12:30:58> LogHost: Message: DownloadUrlRetry: 0, endpointUrl: https://teams.live.com/downloads/getinstaller?intent=Work&arch=x64&platVersion=10.0.19044, sizeInBytes: 134, Scenario.Status: success, scenario: 3a109ffd-ddbb-4811-87bd-39e51bfefecd, Scenario.Name: desktop_squirrel_stubinstall, Scenario.Step: download_url_end, sequence: 2, appversion: , platformId: 27, DeviceInfo.OsName: Windows, DeviceInfo.CpuArchitecture: x64, DeviceInfo.OsVersion: 10.0.19044.0, AppInfo.ProcessArchitecture: x86, AppInfo.ClientType: desktop, dllSearchPathState: unset, clientType: desktop, source: exe, distSrc: default, breadcrumb: , SignedPackages: enabled, AcquireSource: exe_store, desktopSession: desktop-016ca9b4-aa86-43a7-8214-8063768a3a34, installSessionId: 9daf00a4aa4a990d5521bd6b3b550d8a0b4d863abe856ca61c25a5d27460a4f5, delta: 1399, scenarioDelta: 1399, elapsed: 1659555058048, stepDelta: 642, DeviceInfo.ComputerUuid: c9d0c522fb1911e6b6db41b8e6022045, DeviceInfo.OfficeMachineId: c9d0c522fb1911e6b6db41b8e6022045, InstallerVersion: 3.2.3.0, eventpdclevel: 1, userpdclevel: 0
2022-08-03 12:30:58> LogHost: Stack trace: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Roaming\Microsoft\Teams\SquirrelTelemetry.log'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.StreamWriter.CreateFile(String path, Boolean append, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append)
   at Telemetry.AriaWrapper.LogToFile(String message)
2022-08-03 12:30:58> BootstrapperInstallManager: getinstaller endpoint returned installer path https://statics.teams.cdn.office.net/production-windows-x64/1.5.00.17656/
2022-08-03 12:30:58> BootstrapperInstallManager: No decoded deep link is returned from get installer endpoint. Continue install without deep link
2022-08-03 12:30:58> Program: setup.json does not exist
2022-08-03 12:30:58> Program: File does not contain contextual info: 81e82211-d247-4fa2-8c33-b01bbe1ee31b_30761298bbd02c88c013bec57794358731b9b4556b4927186e5e503c89d35a34.exe
2022-08-03 12:30:58> UpdateManager: using rootAppDirectory: C:\Users\Hp\AppData\Local\Microsoft\Teams
2022-08-03 12:30:58> Program: About to install to: C:\Users\Hp\AppData\Local\Microsoft\Teams
2022-08-03 12:30:58> Program: Setup.json exist, copying over
2022-08-03 12:30:58> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Run does not have TeamsMachineInstaller
2022-08-03 12:30:58> Program: CheckMsiAndTryAddInstallSource: Not MSI, no need to add HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\InstallSource
2022-08-03 12:30:58> CheckForUpdateImpl: Couldn't write out staging user ID, this user probably shouldn't get beta anything: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Local\Microsoft\Teams\packages\.betaId'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.StreamWriter.CreateFile(String path, Boolean append, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize, Boolean checkHost)
   at System.IO.File.InternalWriteAllText(String path, String contents, Encoding encoding, Boolean checkHost)
   at System.IO.File.WriteAllText(String path, String contents, Encoding encoding)
   at Squirrel.UpdateManager.CheckForUpdateImpl.getOrCreateStagedUserId()
2022-08-03 12:30:58> CheckForUpdateImpl: Failed to load local releases, starting from scratch: System.IO.DirectoryNotFoundException: Cou2022-08-03 15:44:42> Program: Starting Squirrel Updater: --install . --noui --intentOverride=work --acquireSource=exe_store --exeName=81e82211-d247-4fa2-8c33-b01bbe1ee31b_30761298bbd02c88c013bec57794358731b9b4556b4927186e5e503c89d35a34.exe --bootstrapperMode
2022-08-03 15:44:42> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:44:42> RegistryService: TrySetRegKey: HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\AcquireSource set successfully as exe_store
2022-08-03 15:44:42> Program: AcquireSource reg is set to exe_store
2022-08-03 15:44:42> Program: bootStrapperModeSettings: pdsEndpoint:https://teams.microsoft.com/desktopclient/installer/windows/
2022-08-03 15:44:42> Program: bootStrapperModeSettings: fallbackNextGenAppPayloadUrlX64:https://aka.ms/maglev-x64
2022-08-03 15:44:42> Program: bootStrapperModeSettings: fallbackNextGenAppPayloadUrlX86:https://aka.ms/maglev-x86
2022-08-03 15:44:42> Program: bootStrapperModeSettings: fallbackNextGenAppPayloadUrlARM64:https://aka.ms/maglev-arm64
2022-08-03 15:44:42> Program: bootStrapperModeSettings: getInstallerEndpointUrl:https://teams.live.com/downloads/getinstaller
2022-08-03 15:44:42> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentBuildNumber exists. Data - 19044
2022-08-03 15:44:42> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentMajorVersionNumber exists. Data - 10
2022-08-03 15:44:42> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentMinorVersionNumber exists. Data - 0
2022-08-03 15:44:42> RegistryService: TryGetRegKey: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\CurrentBuildNumber exists. Data - 19044
2022-08-03 15:44:43> FileDownloader: Downloading url: https://teams.live.com/downloads/getinstaller?intent=Work&arch=x64&platVersion=10.0.19044
2022-08-03 15:44:45> BootstrapperInstallManager: getinstaller endpoint returned installer path https://statics.teams.cdn.office.net/production-windows-x64/1.5.00.17656/
2022-08-03 15:44:45> BootstrapperInstallManager: No decoded deep link is returned from get installer endpoint. Continue install without deep link
2022-08-03 15:44:45> Program: Config already exists. Deleting first.
2022-08-03 15:44:45> Program: File does not contain contextual info: 81e82211-d247-4fa2-8c33-b01bbe1ee31b_30761298bbd02c88c013bec57794358731b9b4556b4927186e5e503c89d35a34.exe
2022-08-03 15:44:45> UpdateManager: using rootAppDirectory: C:\Users\Hp\AppData\Local\Microsoft\Teams
2022-08-03 15:44:45> Program: About to install to: C:\Users\Hp\AppData\Local\Microsoft\Teams
2022-08-03 15:44:45> Program: Install path C:\Users\Hp\AppData\Local\Microsoft\Teams already exists, burning it to the ground
2022-08-03 15:44:45> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:44:46> Program: Setup.json exist, copying over
2022-08-03 15:44:46> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Run does not have TeamsMachineInstaller
2022-08-03 15:44:46> Program: CheckMsiAndTryAddInstallSource: Not MSI, no need to add HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\InstallSource
2022-08-03 15:44:46> CheckForUpdateImpl: Couldn't write out staging user ID, this user probably shouldn't get beta anything: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Local\Microsoft\Teams\packages\.betaId'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.StreamWriter.CreateFile(String path, Boolean append, Boolean checkHost)
   at System.IO.StreamWriter..ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize, Boolean checkHost)
   at System.IO.File.InternalWriteAllText(String path, String contents, Encoding encoding, Boolean checkHost)
   at System.IO.File.WriteAllText(String path, String contents, Encoding encoding)
   at Squirrel.UpdateManager.CheckForUpdateImpl.getOrCreateStagedUserId()
2022-08-03 15:44:46> CheckForUpdateImpl: Failed to load local releases, starting from scratch: System.IO.DirectoryNotFoundException: Could not find a part of the path 'C:\Users\Hp\AppData\Local\Microsoft\Teams\packages\RELEASES'.
   at System.IO.__Error.WinIOError(Int32 errorCode, String maybeFullPath)
   at System.IO.FileStream.Init(String path, FileMode mode, FileAccess access, Int32 rights, Boolean useRights, FileShare share, Int32 bufferSize, FileOptions options, SECURITY_ATTRIBUTES secAttrs, String msgPath, Boolean bFromProxy, Boolean useLongPath, Boolean checkHost)
   at System.IO.FileStream..ctor(String path, FileMode mode, FileAccess access, FileShare share)
   at Squirrel.Utility.LoadLocalReleases(String localReleaseFile)
   at Squirrel.UpdateManager.CheckForUpdateImpl.<CheckForUpdate>d__8.MoveNext()
2022-08-03 15:44:46> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:44:46> CheckForUpdateImpl: Downloading RELEASES.exe file from https://statics.teams.cdn.office.net/production-windows-x64/1.5.00.17656
2022-08-03 15:44:46> FileDownloader: Downloading file: https://statics.teams.cdn.office.net/production-windows-x64/1.5.00.17656/RELEASES.exe
2022-08-03 15:44:48> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:44:49> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:44:49> CheckForUpdateImpl: Manifest Raw Length: 130 Length: 127 Content: 018712996CE7306E82EFFB0B231E47667D8A958153CE2CE4DBC92EB2D55FB30A
2022-08-03 15:44:49> CheckForUpdateImpl: First run or local directory is corrupt, starting from scratch
2022-08-03 15:44:49> FileDownloader: Downloading file: https://statics.teams.cdn.office.net/production-windows-x64/1.5.00.17656/Teams-1.5.00.17656-full.nupkg
2022-08-03 15:45:26> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:45:28> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:45:28> ApplyReleasesImpl: No delta packages found. Applying current release package.
2022-08-03 15:45:28> ApplyReleasesImpl: getting squirrel aware apps failed with exception Could not find a part of the path 'C:\Users\Hp\AppData\Local\Microsoft\Teams\current'.
2022-08-03 15:45:28> ApplyReleasesImpl: Writing files to app directory: C:\Users\Hp\AppData\Local\Microsoft\Teams\current
2022-08-03 15:45:34> RegistryService: RegKeyExists: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Teams\ does not exist
2022-08-03 15:45:34> ApplyReleasesImpl: Squirrel Enabled Apps: [C:\Users\Hp\AppData\Local\Microsoft\Teams\current\Teams.exe]
2022-08-03 15:45:39> ApplyReleasesImpl: About to RemoveOldShorcuts for Teams.exe, rootAppDir C:\Users\Hp\AppData\Local\Microsoft\Teams
2022-08-03 15:45:39> RegistryService: RegKeyExists: HKEY_CURRENT_USER\Software\Policies\Microsoft\Cloud\Office\16.0\Teams does not exist
2022-08-03 15:45:39> ApplyReleasesImpl: Registry value Software\Policies\Microsoft\Cloud\Office\16.0\Teams\PreventFirstLaunchAfterInstall does not exist
2022-08-03 15:45:39> RegistryService: RegKeyExists: HKEY_CURRENT_USER\Software\Policies\Microsoft\Office\16.0\Teams does not exist
2022-08-03 15:45:39> ApplyReleasesImpl: Registry value Software\Policies\Microsoft\Office\16.0\Teams\PreventFirstLaunchAfterInstall does not exist
2022-08-03 15:45:39> RegistryService: RegKeyExists: HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Teams does not exist
2022-08-03 15:45:39> ApplyReleasesImpl: Registry value Software\Microsoft\Office\16.0\Teams\PreventFirstLaunchAfterInstall does not exist
2022-08-03 15:45:39> ApplyReleasesImpl: Registry flags are not set: proceed with default value NotConfigured
2022-08-03 15:45:40> ApplyReleasesImpl: Starting fixPinnedExecutables
2022-08-03 15:45:40> ApplyReleasesImpl: Examining Pin: Facebook.lnk
2022-08-03 15:45:40> ApplyReleasesImpl: Examining Pin: File Explorer.lnk
2022-08-03 15:45:40> ApplyReleasesImpl: Examining Pin: Microsoft Edge.lnk
2022-08-03 15:45:40> ApplyReleasesImpl: Fixing up tray icons
2022-08-03 15:45:40> ApplyReleasesImpl: Couldn't rewrite shim RegKey, most likely no apps are shimmed: System.NullReferenceException: Object reference not set to an instance of an object.
   at Squirrel.UpdateManager.ApplyReleasesImpl.<unshimOurselves>b__34_0(RegistryView view)
2022-08-03 15:45:40> ApplyReleasesImpl: Couldn't rewrite shim RegKey, most likely no apps are shimmed: System.NullReferenceException: Object reference not set to an instance of an object.
   at Squirrel.UpdateManager.ApplyReleasesImpl.<unshimOurselves>b__34_0(RegistryView view)
2022-08-03 15:45:40> MeetingAddinInstaller: System.ArgumentException: Cannot delete a subkey tree because the subkey does not exist.
   at System.ThrowHelper.ThrowArgumentException(ExceptionResource resource)
   at Microsoft.Win32.RegistryKey.DeleteSubKeyTree(String subkey, Boolean throwOnMissingSubKey)
   at Microsoft.Win32.RegistryKey.DeleteSubKeyTree(String subkey)
   at Squirrel.MeetingAddinInstaller.<InstallMeetingAddinAsync>d__15.MoveNext()
2022-08-03 15:45:40> MeetingAddinInstaller: StagedAppDirectory does not exist. Using Current
2022-08-03 15:45:40> MeetingAddinInstaller: There is no version.txt. Falling back to getting version from folder name
2022-08-03 15:45:40> MeetingAddinInstaller: Version: 1.0.22147.1; addinPackageDirectory: 1.0.22147.1
2022-08-03 15:45:40> MeetingAddinInstaller: .dead exists: False
2022-08-03 15:45:40> MeetingAddinInstaller: path to .dead: C:\Users\Hp\AppData\Local\Microsoft\TeamsMeetingAddin\1.0.22147.1\.dead
2022-08-03 15:45:40> MeetingAddinInstaller: before cleanup unused versions
2022-08-03 15:45:40> MeetingAddinInstaller: Addin directory exists. Copy was successful
2022-08-03 15:45:40> MeetingAddinInstaller: Version 1.0.22147.1 of the meeting add-in is now installed
2022-08-03 15:45:40> PresenceAddinInstaller: Installing Teams Presence addin for Outlook...
2022-08-03 15:45:40> PresenceAddinInstaller: Copying C:\Users\Hp\AppData\Local\Microsoft\Teams\current\resources\assets\tlb\Uc.tlb to C:\Users\Hp\AppData\Local\Microsoft\TeamsPresenceAddin
2022-08-03 15:45:40> PresenceAddinInstaller: Copying C:\Users\Hp\AppData\Local\Microsoft\Teams\current\resources\assets\tlb\Uc.win32.tlb to C:\Users\Hp\AppData\Local\Microsoft\TeamsPresenceAddin
2022-08-03 15:45:40> PresenceAddinInstaller: check if UC TypeLib points to current\resources\assets\tlb\Uc.tlb
2022-08-03 15:45:40> PresenceAddinInstaller: Registering UC Typelib WIN32 under HKCU...
2022-08-03 15:45:41> PresenceAddinInstaller: UC Typelib WIN32 successfully registered to C:\Users\Hp\AppData\Local\Microsoft\TeamsPresenceAddin\Uc.win32.tlb under HKCU!
2022-08-03 15:45:41> PresenceAddinInstaller: Registering UC Typelib WIN64 under HKCU...
2022-08-03 15:45:41> PresenceAddinInstaller: UC Typelib WIN64 successfully registered to C:\Users\Hp\AppData\Local\Microsoft\TeamsPresenceAddin\Uc.tlb under HKCU!
2022-08-03 15:45:41> PresenceAddinInstaller: IM Provider registry key has been created!
2022-08-03 15:45:41> ApplyReleasesImpl: cleanDeadVersions: for original version of  and current version of 1.5.00.17656
2022-08-03 15:45:41> ApplyReleasesImpl: cleanDeadVersions: exclude current folder stage
2022-08-03 15:45:42> RegistryService: TryDeleteRegKey: HKEY_CURRENT_USER\Software\Microsoft\Office\Teams\PreventInstallationFromMsi not found
