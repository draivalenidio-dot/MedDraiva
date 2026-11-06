# MediDraiva — Android MVP (base inicial)

Aplicação Android nativa em Kotlin + Jetpack Compose, com interface inicial bilingue (português/inglês), catálogo de módulos, pesquisa local e navegação básica.

## Requisitos
- Android Studio recente
- JDK 17
- Android SDK 36
- Gradle compatível com Android Gradle Plugin 8.13.2 (o Android Studio pode configurar o wrapper ao importar o projeto)

## Abrir
1. Descompacte a pasta `MediDraiva`.
2. Abra o Android Studio e escolha **Open**.
3. Selecione a pasta `MediDraiva`.
4. Aguarde a sincronização do Gradle.
5. Execute em emulador ou dispositivo Android com depuração USB ativada.

## O que já existe
- Ecrã inicial com identidade MediDraiva.
- Seis módulos apresentados em cartões.
- Pesquisa local pelo nome dos módulos.
- Ecrãs de detalhe demonstrativos.
- Recursos de texto em português e inglês (o idioma segue a configuração do Android).
- Navegação inferior.

## O que ainda não está implementado
- Conteúdo clínico validado.
- Persistência real com Room e favoritos.
- API, servidor e sincronização.
- Login e perfis.
- Calculadoras clínicas operacionais.
- Conteúdo descarregável para uso offline.
- Testes automatizados e geração/validação de APK.

## Segurança clínica
Esta versão é apenas um protótipo funcional de navegação. Não deve ser usada para decisões diagnósticas ou terapêuticas. Antes de publicação, cada conteúdo clínico deverá ter fontes identificadas, data de revisão, responsável editorial e processo de validação.
