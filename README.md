Implements Win32 OutputDebugStringW in a DLL in such a way that it can be called like this:

```
rundll32 DebugOutput.dll,Debug Some message
```
