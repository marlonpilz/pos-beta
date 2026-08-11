# PÓS — Beta Privada

Esta é uma beta visual e navegável do conceito PÓS.

## O que esta versão faz
- Funciona no navegador do celular e desktop.
- Simula a experiência principal do produto.
- Salva alguns registros apenas no navegador local usando localStorage.
- Não usa API da OpenAI.
- Não possui login real.
- Não envia dados para servidor.

## Publicar na Vercel — caminho mais simples

### Opção A — Sem GitHub, usando Vercel CLI
Requer Node.js instalado.

1. Abra uma conta em https://vercel.com
2. Instale a Vercel CLI:
   npm i -g vercel
3. Abra o terminal dentro desta pasta.
4. Rode:
   vercel
5. Faça login quando solicitado.
6. Aceite as opções padrão.
7. A Vercel vai gerar um endereço público.

Para publicar uma atualização depois:
   vercel --prod

### Opção B — GitHub + Vercel
1. Crie uma conta gratuita no GitHub.
2. Crie um repositório chamado pos-beta.
3. Envie os arquivos desta pasta para o repositório.
4. Entre na Vercel.
5. Clique em Add New > Project.
6. Importe o repositório pos-beta.
7. Clique em Deploy.
8. A Vercel gera o link público automaticamente.

## Importante
Esta beta NÃO é segura para receber relatos reais e sensíveis de usuários.
Ela serve apenas para visualizar e testar a experiência.
Não compartilhe com pessoas para inserir informações íntimas reais ainda.

## Próxima fase técnica
Para virar produto real será necessário:
1. Frontend próprio;
2. Backend protegido;
3. Banco de dados;
4. Autenticação/login;
5. Política de privacidade;
6. Integração com modelo de IA;
7. Camada de segurança clínica e de conteúdo;
8. Controle de exclusão dos dados do usuário.
