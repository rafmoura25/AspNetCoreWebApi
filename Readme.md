![Logo of the project](https://static.gunnarpeipman.com/wp-content/uploads/2019/12/dotnet-core-featured.png.webp)

# SmartSchool
> Web Api - .net core 3.1 / EF Core 3.1

Projeto criado a partir da Curso:
https://www.udemy.com/course/criando-web-api-com-aspnet-core-31-ef-core-31/

## Instalação / Primeiros Passos

Guia rápido para subir a api localmente.

### Executando o Migration e Data base
```shell
# Dentro da pasta SmartSchool.WebAPI
> dotnet tool install --global dotnet-ef --version 3.1.0 # Rodar caso não tenha o EF instalado
> dotnet ef migrations script
> dotnet ef migrations add init
> dotnet ef database update # Será criado o arquivo SmartSchool.db
```

### Rodando a Api localmente
```shell
> dotnet watch run # http://localhost:5000/
```