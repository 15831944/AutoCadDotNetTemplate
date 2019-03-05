# AutoCad .NET Template

Use this code as a starter for creating a new AutoCad command/plugin.

## Configuration

1. Change targeted .NET Framework version if desired.
1. Update library references of `AcCoreMgd.dll`, `AcDbMgd.dll` and `AcMgd.dll` to the correct path.
  Those files should be in the `inc` folder where ObjectARX was installed/downloaded.
1. After changing project name, update the `netload` parameter in `start.scr` to `YOUR_DLL_NAME.dll`