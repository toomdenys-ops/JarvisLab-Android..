# BOBY LAB para Android

Aplicativo Android com inteligência artificial, voz e automações. A V3.9 mantém o painel circular aprovado, atualiza a cápsula flutuante com visual inspirado no Techi e muda o nome visível para **Boby**.

## Versões mantidas

| Versão | Projeto | Compilação |
| --- | --- | --- |
| **V3.9 — Boby com cápsula flutuante** (atual) | Arquivo Base64: BobyLab_Autonomo_V3_9_Capsula_Techi.zip.b64 | [Workflow BOBY V3.9](.github/workflows/build-boby-v39.yml) |
| **V3.8 — Jarvis com cápsula flutuante** | [ZIP do projeto](JarvisLab_Autonomo_V3_8_Capsula_Flutuante.zip) | [Workflow V3.8](.github/workflows/build-jarvis-v38.yml) |

## BOBY V3.9

A V3.9 renomeia a marca visível para Boby, troca o ícone da cápsula por microfone e deixa o controle compacto para abrir conversa por voz sobre outros aplicativos. Gemma 3, Qwen, DeepSeek, memória, voz e painel circular continuam no app. O identificador Android foi mantido para preservar os dados e permitir a atualização sobre a V3.8.

O arquivo do projeto está em Base64 porque a integração do GitHub só grava arquivos de texto; o workflow o decodifica automaticamente. Para compilar, abra **Actions → BOBY V3.9 Cápsula Flutuante → Run workflow**. Ao concluir, baixe **BobyLab-V3.9-Capsula-Flutuante-APK**.

## Cápsula flutuante

Abra **Configurações → Ativar cápsula**. Na primeira vez, autorize o Boby a aparecer sobre outros aplicativos. Arraste a cápsula para mudar sua posição; toque no microfone para abrir a conversa por voz.

## Voz

Nas configurações, escolha uma voz em português instalada no Android, toque em **Testar voz selecionada** e depois em **Usar esta voz**. O Android não informa o gênero de cada voz, então escolha pela amostra.

## Organização

- Os projetos V3.8 e V3.9 e seus workflows ficam no repositório.
- Versões mais antigas permanecem recuperáveis pelo histórico do GitHub.
