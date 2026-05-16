# Profil : `single-user`

> **Cible :** 1 utilisateur principal par appareil. Cas d'usage typique : PC personnel, portable cadre, station de developpeur.

## Vue d'ensemble

| Aspect             | Choix                                              |
|--------------------|----------------------------------------------------|
| Plateforme         | Windows 11 (25H2)                                  |
| Enrollment         | Autopilot **user-driven**, cloud-only              |
| Identite           | Entra ID join (pas d'AD on-prem, pas d'hybrid)     |
| Authentification   | Windows Hello for Business + Cloud Kerberos Trust  |
| Chiffrement disque | BitLocker XTS-AES 256 + TPM+PIN                    |
| App Control        | WDAC base policy (Microsoft + Store + ISG)         |
| Endpoint Protection| Defender + ASR 16 regles Block + CFA + EDR         |
| Mises a jour       | Windows Update for Business, rolling ring          |
