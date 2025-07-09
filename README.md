# video-semantic-qna
Trilha React + Node com IA da NLW 20 da Rocketseat
## Inicializando o Projeto

### Instalação de Dependências

- `typescript @types/node -D`  
    (Necessário apenas se a versão do Node for 22)
- `fastify`  
    Framework principal para gerenciamento HTTP.
- `@fastify/cors`  
    Permite selecionar os endereços do frontend que poderão se comunicar com a API interna.
- `zod`  
    Biblioteca para validação de dados.
- `fastify-type-provider-zod`  
    Integração do Zod com o Fastify para validação tipada.
- `@biomejs/biome -D` - Linter especializado
- `npx ultracite init` -> Superset de configurações construída sobre o Biome

### Configuração

`npx tssc --init`
    Inicializa o projeto typescript

Acessar `https://github.com/tsconfig/bases?tab=readme-ov-file` e escolher o template tsx desejado

Após isso, adicionar: 


```typescript
 "noEmit": true, // Usa o typescript apenas para verificação de tipos, sem gerar código JavaScript (sem bundling)
    "allowImportingTsExtensions": true, // Permite importar arquivos .ts diretamente
```





















## Tecnologias

Biomejs com Ultracite - Linter com um superset de configurações (Ultracite)

