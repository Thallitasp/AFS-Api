# AFS-Api.CleanArchitecture
Uso do Clean-Arquitecture

## <a name="Migration"></a> Migration
### Powershell
Criando a variavel de ambiente para habilitar a migração
e Adicionando uma migração
```
$env:DEMOCLEAN_CONN = "Host=localhost;Port=5432;Database=DemoClean;User Id=postgres;Password=postgres;"
Add-Migration InitialCreate -OutputDir PostgresDataAccess/Entities/Migrations
```
