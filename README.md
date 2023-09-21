# DeviceCodeHelper
Small C# library used in PSMALNET Powershell module to interact with EntraID with the device code OAuth flow.

# How to build it?

dotnet new classlib --name DeviceCodeHelper -f net6.0
dotnet add DeviceCodeHelper package Microsoft.Identity.Client
dotnet build -f net6.0 DeviceCodeHelper