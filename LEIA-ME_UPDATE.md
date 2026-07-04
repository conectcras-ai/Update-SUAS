# Update SUAS 1.0.1

Conteúdo para o repositório público conectcras-ai/Update-SUAS.

Arquivos:
- manifest.xml: aponta para app.version 1.0.1.
- app/cras-gestao-suas-app-1.0.1-all.jar: pacote que o botão de atualização baixa.

Correção principal:
- Alerta de visitas domiciliares agora usa o mesmo percentual exibido no painel de indicadores, evitando alerta 0,0% quando o painel já calculou 100,0%.
