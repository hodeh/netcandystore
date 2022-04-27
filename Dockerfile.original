# The `FROM` instruction specifies the base image. You are
# extending the `microsoft/aspnet` image.

FROM  mcr.microsoft.com/dotnet/framework/aspnet:4.8

WORKDIR /inetpub/wwwroot
EXPOSE 80
EXPOSE 443
COPY . .
