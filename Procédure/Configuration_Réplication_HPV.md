# Mettre en Place la Réplication HPV

La réplication Hyper-V fait partie intégrante du rôle Hyper-V. Il contribue à votre stratégie de récupération d’urgence en répliquant une machine virtuelle à partir d’un serveur hôte Hyper-V vers un autre pour maintenir vos charges de travail disponibles. Hyper-V Réplique crée une copie d’une machine virtuelle en cours d'exécution vers une machine virtuelle hors ligne répliquée.

## Étape 1 : Activer la règle de trafic entrant HTTPS

  ```powershell
  Enable-NetFirewallRule -DisplayName 'Hyper-V Replica HTTPS Listener (TCP-In)'
```
## Étape 2 : Activer la règle de trafic entrant HTTPS
