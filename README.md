# Binodata.Utility.Component.Standard
Binodata.Utility.Component for .net standare

# How to use
```C#

ApiResult<string> apiOKResult = ApiResult<string>.OK("Success");

ApiResult<string> apiFailResult = ApiResult<string>.Error("Fail");

ApiResult<string> apiFailNumberResult = ApiResult<string>.Error("Fail", 101);


```
