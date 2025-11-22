# Hallazgos Principales – TryHackMe: Ice

## 1. Icecast CVE‑2004‑1561 – RCE
- **Severidad:** Crítica
- Permite ejecución remota de código vía HTTP (puerto 8000).

## 2. Robo de credenciales
- Uso de Kiwi (`creds_all`) para extracción de credenciales locales.

## 3. Habilitación de RDP
- Persistencia remota usando `enable_rdp`.

## 4. Riesgo adicional
- Potencial pivoting si existiesen otras máquinas accesibles.

## Recomendaciones
- Parchear/actualizar Icecast.
- Deshabilitar servicios no necesarios.
- Monitorizar cambios críticos como activación de RDP.
- Segmentar la red para limitar exposición.
