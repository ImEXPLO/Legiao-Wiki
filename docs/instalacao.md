# 🚀 Guia de Instalação

Siga estes passos rigorosamente para evitar travamentos e garantir a melhor performance.

## 1. Requisitos
* **Minecraft:** 1.21.1
* **Loader:** NeoForge
* **RAM Mínima:** 6GB
* **RAM Recomendada:** 8GB (Não aloque mais que 10GB!)

## 2. Java Arguments (CRUCIAL) ☕
O argumento padrão do Minecraft causa travamentos com mods pesados.
**Copie e cole** os argumentos abaixo nas configurações do seu Perfil no Launcher (CurseForge/Prism/ATLauncher):

# É OPCIONAL - PORÉM AJUDARÁ MUITO NO PROCESSO DE OTIMIZAÇÃO COM O DISTANT HORIZONS!

```text
-Xms4G -Xmx8G -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1

---

# 🚀 Installation Guide

Follow these steps strictly to prevent crashes and ensure the best performance.

## 1. Requirements
* **Minecraft:** 1.21.1
* **Loader:** NeoForge
* **Minimum RAM:** 6GB
* **Recommended RAM:** 8GB (Do not allocate more than 10GB!)

## 2. Java Arguments (CRUCIAL) ☕
The default Minecraft arguments cause stutters with heavy modpacks.
**Copy and paste** the arguments below into your Launcher Profile settings (CurseForge/Prism/ATLauncher):

```text
-Xms4G -Xmx8G -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1