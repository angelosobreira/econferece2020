FROM mcr.microsoft.com/windows/servercore:ltsc2019 

LABEL version="1.0.0" description="Docker da Embarcadero conference" manitainer="Angelo Sobreira"

COPY prjAPI.exe C:/api/prjAPI.exe
COPY libpq.dll C:/api/libpq.dll

WORKDIR "C:/api"

EXPOSE 80

CMD ["C:\\api\\prjAPI.exe"]