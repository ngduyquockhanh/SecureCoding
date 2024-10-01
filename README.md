Use github codespace

Setup .NET 5.0:
```
wget https://dot.net/v1/dotnet-install.sh -O dotnet-install.sh
chmod +x dotnet-install.sh 
./dotnet-install.sh --channel 5.0
```

Build and run lab:
```
cd .\1.InputValidation\sql-injection\razor\ef\before\OnlineBankingApp\
dotnet build .
dotnet run
```
