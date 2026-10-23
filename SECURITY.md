# Política de Segurança

## Escopo

O Meu Study Hub TI é um repositório acadêmico individual, composto principalmente por documentação, materiais de estudo, projetos e referências de portfólio. Esta política orienta a proteção dos arquivos e das credenciais eventualmente utilizadas por projetos futuros.

## Boas práticas adotadas

- Não versionar senhas, tokens, chaves de API, dados pessoais sensíveis ou arquivos `.env` com valores reais.
- Usar o `.gitignore` para excluir arquivos locais, caches, pastas de dependências e configurações específicas de IDE.
- Revisar a lista de arquivos antes de cada commit e envio ao repositório remoto.
- Utilizar autenticação em dois fatores na conta GitHub da proprietária.
- Manter o acesso de escrita restrito à proprietária enquanto o projeto for individual.

Quando um projeto exigir variáveis de ambiente, deve ser disponibilizado apenas um arquivo de exemplo, como `.env.example`, sem dados reais.

## Como relatar uma vulnerabilidade

Não publique senhas, tokens ou detalhes que permitam exploração em uma issue pública.

Para relatar uma possível vulnerabilidade, entre em contato com a proprietária pelo [perfil no GitHub](https://github.com/FeMeNiKi), descrevendo o problema sem compartilhar credenciais. O relato será analisado e, quando necessário, a correção será registrada em um commit.

## Em caso de exposição de credenciais

1. Revogar ou trocar imediatamente a credencial exposta no serviço de origem.
2. Remover o valor dos arquivos atuais e adicioná-los ao `.gitignore`, quando aplicável.
3. Revisar o histórico do Git antes de considerar o incidente resolvido.
4. Registrar a correção sem publicar o segredo nem detalhes sensíveis.
