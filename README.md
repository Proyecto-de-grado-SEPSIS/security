# security
Repo de manejo de version de keycloak como control de acceso al artefacto 
# Version
keycloak 21.1.1 
# Comandos de despliegue en producción 
El despliegue se hace bajo el protocolo HTTP, para el HTTPS seguir la documentación de Keycloack para añadir el certificado
## Windows 
1. ingresar a la carpeta /keycloak 21.1.1 
2.  igresar el comando 

```bash
./bin kc.sh start --hostname-strict=false --http-enabled=true
```
## Linux o unix based systems 
1. ingresar a la carpeta /keycloak 21.1.1 
2.  igresar el comando 

```bash
./bin kc.bat start --hostname-strict=false --http-enabled=true
```
