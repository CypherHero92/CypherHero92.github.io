---
layout: post
title: "Simulación de ataque con PowerShell y detección con Wazuh"
date: 2025-07-30
categories: malware siem detección
---

Hoy vamos a simular un ataque de persistencia en Windows y ver cómo se detecta con Wazuh.

## 🔥 Ataque

Ejecutamos el siguiente script:

```powershell
Set-ItemProperty -Path 'HKCU:\Software\Microsoft\Windows\CurrentVersion\Run' -Name 'backdoor' -Value 'powershell.exe -WindowStyle Hidden -EncodedCommand ...'
🛡️ Detección con Wazuh
El agente genera la siguiente alerta:

yaml
Copiar
Editar
Rule: 1005 fired (level 10) - Registry Persistence Modification
✅ Conclusión
Hemos visto cómo detectar una técnica de persistencia simple con PowerShell usando Wazuh como SIEM.

Próximamente: detección de Cobalt Strike, DNS tunneling y beaconing.

yaml
Copiar
Editar

4. Elige **Commit directly to the `main` branch**
5. Haz clic en **“Commit new file”**

---

## ✅ Ver tu blog

Abre:

https://cypherhero92.github.io/

yaml
Copiar
Editar

- Verás el título del post como entrada
- Si haces clic, te lleva al post completo

---
