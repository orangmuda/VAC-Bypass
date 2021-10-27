# VAC-Bypass
 AboutValve Anti-Cheat bypass (27-10-21)

### Compiling from source

When you have equiped a copy of source code, next step is opening **VAC-Bypass.sln** in Microsoft Visual Studio 2019.

Then change build configuration to `Release | x86` and simply press **Build solution**.

If everything went right you should receive `VAC-Bypass.dll`  binary file.

### Loading

It is mandatory to strictly follow each step of loading in order to make bypass work.

**Method 1**:

1. Close Steam client if open.

1. Disconnect from the internet.

1. Run Steam as Administrator.

1. Inject `VAC-Bypass.dll` into `Steam.exe` process.

1. After successful injection messagebox saying `Initialization was successful!` should appear.

1. Reconnect to the internet.

1. Press `Retry` in steam window saying 'Could not connect to Steam servers'.
