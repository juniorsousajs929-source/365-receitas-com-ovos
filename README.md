# Clone da Página: Pacote Gelatina

A página ("pacote-gelatina-moun-prhv.bolt.host") foi clonada **exatamente como está** (incluindo todo o funcionamento da estrutura React/Vite, arquivos JS completos, estilos CSS, e imagens).

## Próximos passos para subir no GitHub

Como você não possuía o GitHub CLI configurado no terminal deste computador, eu deixei a pasta toda perfeitamente configurada com o Git local, e o primeiro "commit" (salvamento) já foi feito por mim.

Para publicar a página no seu GitHub, siga estes passos muito simples:

1. Acesse sua conta no [GitHub](https://github.com/new) e crie um **Novo Repositório** (não inicie com README, deixe tudo vazio).
2. O site mostrará alguns códigos. Você precisa apenas adicionar a conexão com o repositório que você acabou de criar. Abra o seu terminal (`cmd` ou `powershell`) dentro desta pasta `site` e role os comandos:

```bash
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPO.git
git push -u origin main
```

Após rodar esses 3 comandos, seu site já subiu para o ar!
Para ativá-lo como um site grátis, vá nas configurações do repositório no GitHub -> aba **Pages** -> Selecione a *branch* `main` e clique em Save. O link do seu site clonado ficará disponível em minutos!
