# Plano de implantação — PortfolioHUB

## 1. Objetivo

Implantar e manter o **Meu Study Hub TI** como um portfólio acadêmico centralizado, público e fácil de consultar. O repositório reúne materiais de disciplinas, entregas, projetos e certificados, enquanto o GitHub registra a evolução do trabalho e o GitHub Pages disponibiliza a versão publicada.

## 2. Escopo e ambientes

- **Repositório:** [FeMeNiKi/Meu_Study_Hub_TI](https://github.com/FeMeNiKi/Meu_Study_Hub_TI)
- **Publicação:** [GitHub Pages](https://femeniki.github.io/Meu_Study_Hub_TI/)
- **Branch principal:** `main`
- **Responsável pela administração:** proprietária do repositório

Este é um projeto individual. A leitura do conteúdo publicado é aberta ao público; alterações no repositório permanecem sob controle da proprietária.

## 3. Etapas de implantação

### 3.1 Planejamento

1. Manter uma estrutura de pastas por tema, disciplina e tipo de material.
2. Atualizar o `README.md` para explicar o propósito do Study Hub e orientar a navegação.
3. Registrar decisões, testes e procedimentos de segurança na pasta `docs/`.

**Evidência:** estrutura do repositório, README e documentação versionada.

### 3.2 Configuração e integração com GitHub

1. Manter o repositório no GitHub como fonte oficial das versões.
2. Trabalhar localmente e enviar alterações revisadas para a branch `main`.
3. Usar mensagens de commit claras, por exemplo: `docs: adiciona plano de implantação`.
4. Confirmar no painel do GitHub que o GitHub Pages publica o conteúdo esperado.

**Evidência:** histórico de commits, repositório público e endereço do GitHub Pages.

### 3.3 Gestão de usuários e segurança

1. Manter apenas a proprietária como administradora do projeto enquanto a atividade for individual.
2. Conceder acesso de escrita somente quando houver necessidade de colaboração.
3. Nunca versionar senhas, tokens, chaves de API ou arquivos `.env` com valores reais.
4. Manter arquivos locais e gerados fora do versionamento por meio do `.gitignore`.
5. Revisar arquivos antes de cada envio ao GitHub.

**Evidência:** [política de segurança](../SECURITY.md) e arquivo `.gitignore`.

### 3.4 Compartilhamento e controle de acesso

1. Manter o repositório público para que a banca possa consultar o conteúdo.
2. Compartilhar os links do repositório e do GitHub Pages na documentação de entrega.
3. Registrar contribuições pelo histórico de commits e, se houver colaboradores no futuro, por issues e pull requests.

**Evidência:** URLs públicas, histórico de versões e [guia de contribuição](../CONTRIBUTING.md).

### 3.5 Finalização e testes

Antes da entrega, executar a seguinte conferência:

- [ ] O `README.md` descreve o projeto e possui links corretos.
- [ ] O endereço do GitHub Pages abre sem erro 404.
- [ ] Os links internos apontam para arquivos existentes.
- [ ] Não há credenciais, arquivos `.env` ou materiais privados versionados.
- [ ] A branch `main` contém a versão revisada do projeto.
- [ ] Foi criada uma tag de entrega, como `v1.0.0-bootcamp-final`.

**Evidência:** checklist preenchida, tag criada e revisão final do repositório.

### 3.6 Apresentação final

Preparar um vídeo de até cinco minutos mostrando:

1. o objetivo e a organização do PortfolioHUB;
2. o repositório e o histórico de versões no GitHub;
3. o GitHub Pages em funcionamento;
4. as práticas de segurança e controle de acesso adotadas;
5. como a IA Gemini foi utilizada como apoio.

O vídeo e os links públicos devem ser reunidos no documento de entrega solicitado pela disciplina.

## 4. Uso de IA

O Gemini foi utilizado como apoio de planejamento e revisão. As interações e recomendações aproveitadas estão registradas em [uso-do-gemini.md](uso-do-gemini.md). A proprietária revisa cada sugestão antes de aplicá-la ao repositório.
