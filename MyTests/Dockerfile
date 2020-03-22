FROM mcr.microsoft.com/dotnet/core/sdk:2.2
COPY . src/
WORKDIR /src
RUN dotnet restore
RUN dotnet test MyTests\MyTests.csproj
ENTRYPOINT ["cmd"]