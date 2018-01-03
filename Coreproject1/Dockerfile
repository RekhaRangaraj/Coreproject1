FROM microsoft/aspnetcore:1.1

WORKDIR /app
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "Coreproject1.dll"]
