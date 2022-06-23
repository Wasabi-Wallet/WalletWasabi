<br>

![](https://i.imgur.com/gI75EKu.png)

# Build From Source Code

### Get The Requirements

1. Get Git: https://git-scm.com/downloads
2. Get .NET 6.0 SDK: https://dotnet.microsoft.com/download
3. Optionally disable .NET's telemetry by executing in the terminal `export DOTNET_CLI_TELEMETRY_OPTOUT=1` on Linux and macOS or `setx DOTNET_CLI_TELEMETRY_OPTOUT 1` on Windows.

### Get Wasabi

Clone & Restore & Build

```sh
git clone https://github.com/Wasabi-Wallet/WalletWasabi.git
cd WalletWasabi/WalletWasabi.Fluent.Desktop
dotnet build
```

### Run Wasabi

Run Wasabi with `dotnet run` from the `WalletWasabi.Fluent.Desktop` folder.

### Update Wasabi

```sh
git pull
```
