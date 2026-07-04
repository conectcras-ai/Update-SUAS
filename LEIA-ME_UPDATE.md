# Update SUAS 1.0.0

Conteúdo publicado para o repositório público conectcras-ai/Update-SUAS.

Arquivos principais:
- manifest.xml: app.version 1.0.0.
- app/cras-gestao-suas-app-1.0.0-all.jar.

Correção:
- O cliente SUAS passa a priorizar a configuração compartilhada do ConectCRAS para usuario/senha/banco.
- URLs antigas do SUAS (db.url/cras.db.url) não sobrescrevem mais o IP digitado no card do cliente.
- Se a senha salva for recusada pelo MySQL, o SUAS pede a senha do usuário da aplicação e testa novamente.
- Recursos internos do SUAS mantêm o novo ícone do desktop.
- Correção de alerta de visitas domiciliares mantida.

Observação:
- O update por JAR atualiza a aplicação. Para corrigir o ícone do atalho do Windows, use o instalador ConectSUAS-1.0.0.exe.
