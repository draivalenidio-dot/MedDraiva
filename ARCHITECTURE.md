# Arquitetura planeada

## Estratégia offline-first
- Room como fonte local de leitura para conteúdos publicados e favoritos.
- Retrofit para obter atualizações do serviço remoto.
- Repositórios como camada única de acesso aos dados.
- WorkManager para sincronização quando houver conectividade e condições adequadas.
- PostgreSQL no backend, atrás de uma API autenticada.

## Camadas
- UI: Jetpack Compose e ViewModels.
- Domain: modelos e casos de uso independentes da interface.
- Data: Room, Retrofit, DTOs, mapeadores e repositórios.

## Segurança e governança clínica
- Não recolher dados identificáveis de pacientes no MVP.
- Não incluir diagnóstico automático ou prescrição automática.
- Conteúdo clínico versionado, com referências, data de revisão e responsável.
- Doses e calculadoras exigem validação clínica, testes de limites e unidades, e alertas de segurança antes da disponibilização.
- Avaliar requisitos legais e regulatórios aplicáveis em Moçambique e nos mercados de publicação.
