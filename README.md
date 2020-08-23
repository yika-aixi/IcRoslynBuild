# IcRoslynBuild

### Version:
1. Code Analysis Version 3.7.0
2. MSBuild Version:16.6.0
3. SQLitePCLRaw:2.0.3


### Unity `com.unity.collections` using -> System.Runtime.CompilerServices.Unsafe The version is lower

#### Handling method
	
1. Copy only the folder com.unity.collections from Library/PackageCache/
2. Paste it under Packages (optionally rename it to com.unity.collections so it has the same name as in its package.json file)
3. Delete or Disable System.Runtime.CompilerServices.Unsafe.dll from the Packages/com.unity.collections/