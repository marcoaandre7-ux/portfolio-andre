# Portfólio de Andre

Portfólio pessoal de Andre, criado para apresentar projetos digitais em uma estante interativa de livros. O site inclui um retrato interativo, navegação em inglês, português e espanhol e links de contato por WhatsApp e e-mail.

A estante consulta os repositórios públicos do GitHub, exclui nomes que contenham `app` e apresenta projetos selecionados em destaque. Projetos sem repositório público também podem ser cadastrados manualmente em `fitas.html`.

## Executar localmente

Abra `index.html` em um navegador. A consulta aos projetos requer acesso à internet e pode estar sujeita aos limites da API pública do GitHub. Para servir os arquivos localmente, execute `python -m http.server` nesta pasta.

## Arquivos

- `index.html`: apresentação, idiomas e contato.
- `fitas.html`: estante interativa e integração com GitHub.
- `adriano-3d.png`: retrato estilizado usado na página inicial.

O portfólio é um site estático, sem dependências de compilação ou credenciais no navegador.
