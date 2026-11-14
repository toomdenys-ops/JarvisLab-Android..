# JARVIS LAB para Android

Aplicativo Android do JARVIS LAB com inteligência artificial, voz e automações.

## Versões mantidas

Este repositório mantém somente as duas versões mais recentes do projeto:

| Versão | Projeto | Workflow |
| --- | --- | --- |
| **V3.7 — Interface aprovada** (atual) | [ZIP do projeto](JarvisLab_Autonomo_V3_7_Interface_Aprovada.zip) | [Compilar V3.7](.github/workflows/build-jarvis-v37.yml) |
| **V3.6 — Memória e voz** | [ZIP do projeto](JarvisLab_Autonomo_V3_6_Memoria_Voz.zip) | [Compilar V3.6](.github/workflows/build-jarvis-v36-REENVIO.yml) |

## Voz masculina

Na V3.7, abra **Configurações → Voz do Jarvis**. Escolha uma voz em português instalada no Android, toque em **Testar voz selecionada** e depois em **Usar esta voz** para salvar. O Android não informa o gênero de cada voz, então escolha pela amostra. A preferência fica salva neste aplicativo.

## Build V3.7

A compilação atualizada terminou com sucesso em 13 de novembro de 2026. [Abrir execução e baixar o APK](https://github.com/toomdenys-ops/JarvisLab-Android../actions/runs/43538384609). O artefato fica disponível por 14 dias.

Para gerar outro APK, abra **Actions → JARVIS V3.7 Interface Aprovada → Run workflow**.

## Organização

- Os ZIPs V3.6 e V3.7 ficam na raiz porque os workflows usam esses caminhos.
- Os workflows mantidos ficam na pasta .github/workflows.
- As versões anteriores foram removidas da lista de arquivos do repositório.
