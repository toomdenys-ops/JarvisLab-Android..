# JARVIS LAB para Android

Aplicativo Android do JARVIS LAB com inteligência artificial, voz e automações.

## Versões mantidas

Este repositório mantém somente as duas versões mais recentes do projeto:

| Versão | Projeto | Workflow |
| --- | --- | --- |
| **V3.8 — Cápsula flutuante** (atual) | [ZIP do projeto](JarvisLab_Autonomo_V3_8_Capsula_Flutuante.zip) | [Compilar V3.8](.github/workflows/build-jarvis-v38.yml) |
| **V3.7 — Interface aprovada** | [ZIP do projeto](JarvisLab_Autonomo_V3_7_Interface_Aprovada.zip) | [Compilar V3.7](.github/workflows/build-jarvis-v37.yml) |

## V3.8

A V3.8 adiciona a cápsula flutuante do Jarvis e mantém a seleção de voz nas configurações do Android. O APK é compilado pelo GitHub Actions; quando a execução terminar, baixe o artefato **JarvisLab-V3.8-Capsula-Flutuante-APK**.

Para compilar, abra **Actions → JARVIS V3.8 Cápsula Flutuante → Run workflow**.

## Voz masculina

Nas configurações do app, escolha uma voz em português instalada no Android, toque em **Testar voz selecionada** e depois em **Usar esta voz** para salvar. O Android não informa o gênero de cada voz, então escolha pela amostra. A preferência fica salva neste aplicativo.

## Build V3.7

A compilação da V3.7 terminou com sucesso em 13 de novembro de 2026. [Abrir execução e baixar o APK](https://github.com/toomdenys-ops/JarvisLab-Android../actions/runs/43538384609). O artefato fica disponível por 14 dias.

## Organização

- Os ZIPs das versões V3.7 e V3.8 ficam na raiz porque os workflows usam esses caminhos.
- Os workflows mantidos ficam na pasta .github/workflows.
- Versões anteriores podem ser recuperadas pelo histórico do GitHub.
