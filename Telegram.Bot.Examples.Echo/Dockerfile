FROM microsoft/windowsservercore
ARG source
WORKDIR /app
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["C:\app\Telegram.Bot.Examples.Echo.exe"]
