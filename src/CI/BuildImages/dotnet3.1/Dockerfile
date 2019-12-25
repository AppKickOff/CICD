FROM mcr.microsoft.com/dotnet/core/sdk:3.1-alpine

RUN mkdir /root/.dotnet/tools
ENV PATH="/root/.dotnet/tools:${PATH}"
RUN dotnet tool install --global GitVersion.Tool