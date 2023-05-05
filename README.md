
# Getting Started with APIMATIC Calculator

## Introduction

Simple calculator API hosted on APIMATIC

## Install the Package

If you are building with .NET CLI tools then you can also use the following command:

```bash
dotnet add package myUniqueCSharpPackage29 --version 1.2.999
```

You can also view the package at:
https://www.nuget.org/packages/myUniqueCSharpPackage29/1.2.999

## Test the SDK

The generated SDK also contain one or more Tests, which are contained in the Tests project. In order to invoke these test cases, you will need `NUnit 3.0 Test Adapter Extension` for Visual Studio. Once the SDK is complied, the test cases should appear in the Test Explorer window. Here, you can click `Run All` to execute these test cases.

## Initialize the API Client

**_Note:_** Documentation for the client can be found [here.](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/client.md)

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| `Environment` | Environment | The API environment. <br> **Default: `Environment.Production`** |
| `Timeout` | `TimeSpan` | Http client timeout.<br>*Default*: `TimeSpan.FromSeconds(100)` |

The API client can be initialized as follows:

```csharp
APIMATICCalculator.Standard.APIMATICCalculatorClient client = new APIMATICCalculator.Standard.APIMATICCalculatorClient.Builder()
    .Environment(APIMATICCalculator.Standard.Environment.Production)
    .Build();
```

## List of APIs

* [Simple Calculator](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/controllers/simple-calculator.md)

## Classes Documentation

* [Utility Classes](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/utility-classes.md)
* [HttpRequest](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/http-request.md)
* [HttpResponse](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/http-response.md)
* [HttpStringResponse](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/http-string-response.md)
* [HttpContext](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/http-context.md)
* [HttpClientConfiguration](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/http-client-configuration.md)
* [HttpClientConfiguration Builder](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/http-client-configuration-builder.md)
* [IAuthManager](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/i-auth-manager.md)
* [ApiException](https://github.com/git-fudge/cSharpSourceCode/blob/1.2.999/doc/api-exception.md)

