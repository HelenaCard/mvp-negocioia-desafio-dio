# EletroAprende

> **Aprenda Engenharia Elétrica de um jeito mais simples.**

O **EletroAprende** é uma proposta de plataforma educacional que busca
reunir e organizar conteúdos de Engenharia Elétrica em um único
ambiente. A ideia é facilitar o acesso a materiais de estudo,
aproximando conceitos teóricos de aplicações práticas e apoiando
estudantes e pessoas interessadas no setor elétrico.

> **Status do projeto:** MVP em desenvolvimento. Este repositório deve
> ser atualizado conforme as funcionalidades forem implementadas,
> testadas e publicadas.

------------------------------------------------------------------------

## Sumário

-   [Sobre o projeto](#sobre-o-projeto)
-   [Problema identificado](#problema-identificado)
-   [Solução proposta](#solução-proposta)
-   [Público-alvo](#público-alvo)
-   [Objetivos](#objetivos)
-   [Funcionalidades do MVP](#funcionalidades-do-mvp)
-   [Organização dos conteúdos](#organização-dos-conteúdos)
-   [Identidade visual](#identidade-visual)
-   [Tecnologias e ferramentas](#tecnologias-e-ferramentas)
-   [Modelo de negócio](#modelo-de-negócio)
-   [Desenvolvimento com apoio de IA](#desenvolvimento-com-apoio-de-ia)
-   [Testes e validação](#testes-e-validação)
-   [Estrutura do repositório](#estrutura-do-repositório)
-   [Como executar o projeto](#como-executar-o-projeto)
-   [Evoluções futuras](#evoluções-futuras)
-   [Links](#links)
-   [Referências](#referências)

------------------------------------------------------------------------

## Sobre o projeto

O EletroAprende surge da percepção de que estudantes e interessados em
Engenharia Elétrica frequentemente precisam procurar materiais em
diferentes sites, plataformas e documentos. Essa dispersão pode
dificultar a continuidade dos estudos e a compreensão de assuntos que
exigem uma conexão entre teoria e prática.

A plataforma pretende funcionar como um portal de apoio à aprendizagem,
com conteúdos organizados por área, nível de dificuldade e formato. O
objetivo é tornar a busca por materiais mais simples e oferecer um ponto
de partida para revisão e aprofundamento.

## Problema identificado

Entre as dificuldades que motivam a proposta estão:

-   Materiais de estudo distribuídos em diferentes plataformas;
-   Dificuldade para encontrar conteúdos organizados por assunto;
-   Distância entre explicações teóricas e exemplos de aplicação;
-   Necessidade de materiais complementares para revisão e exercícios;
-   Falta de um espaço único para localizar conteúdos introdutórios e
    técnicos.

## Solução proposta

O EletroAprende propõe centralizar materiais educacionais relacionados à
Engenharia Elétrica em uma biblioteca digital. Os usuários poderão
pesquisar conteúdos, aplicar filtros e acessar páginas com informações
sobre cada material.

A proposta também prevê uma área administrativa para cadastrar, editar,
publicar e organizar os materiais, permitindo que o portal seja
atualizado sem a necessidade de alterar manualmente o código da
aplicação.

## Público-alvo

-   Estudantes de cursos técnicos em Eletrotécnica;
-   Estudantes de Engenharia Elétrica;
-   Alunos de cursos profissionalizantes;
-   Pessoas interessadas em eletricidade e energia;
-   Profissionais que desejam revisar ou atualizar conhecimentos.

## Objetivos

1.  Facilitar a localização de materiais de estudo;
2.  Organizar conteúdos por categorias e níveis de dificuldade;
3.  Aproximar conceitos técnicos de exemplos práticos;
4.  Oferecer uma experiência de navegação simples e responsiva;
5.  Permitir a atualização dos materiais por meio de uma área
    administrativa.

## Funcionalidades do MVP

### Área pública

-   Página inicial com apresentação do projeto;
-   Navegação por categorias de conteúdo;
-   Biblioteca de materiais educacionais;
-   Busca por título e descrição;
-   Filtros por categoria, nível e tipo de material;
-   Página individual para cada material;
-   Links ou arquivos para acesso aos conteúdos;
-   Formulário de contato ou interesse;
-   Atalho de contato via WhatsApp, quando configurado.

### Área administrativa

-   Acesso administrativo protegido por autenticação;
-   Painel com indicadores gerais;
-   Cadastro, edição e exclusão de materiais;
-   Controle de publicação (rascunho ou publicado);
-   Destaque de materiais na página inicial;
-   Organização das categorias;
-   Consulta e gerenciamento dos contatos recebidos.

### Segurança e privacidade

-   Visitantes podem visualizar somente materiais publicados;
-   Visitantes não podem consultar a lista de contatos cadastrados;
-   A gestão de materiais e contatos deve ser restrita a administradores
    autorizados;
-   Dados sensíveis e credenciais não devem ser inseridos no
    código-fonte;
-   Formulários devem validar os campos e informar claramente eventuais
    erros;
-   A coleta de dados deve apresentar informação de privacidade e
    solicitar consentimento quando aplicável.

> As funcionalidades descritas representam o escopo planejado. Atualize
> esta seção para refletir somente o que estiver efetivamente
> implementado e validado na versão publicada.

## Organização dos conteúdos

A biblioteca foi planejada para reunir materiais em seis categorias
principais:

  -----------------------------------------------------------------------
  Categoria                           Exemplos de assuntos
  ----------------------------------- -----------------------------------
  Eletricidade Básica                 Tensão, corrente, resistência,
                                      potência e Lei de Ohm

  Sistemas Elétricos                  Geração, transmissão, distribuição,
                                      transformadores e subestações

  Instalações Elétricas               Circuitos, diagramas, condutores,
                                      proteção e dimensionamento

  Energias Renováveis                 Energia solar, eólica,
                                      hidrelétrica, sustentabilidade e
                                      eficiência energética

  Automação e Controle                Comandos, sensores, controladores e
                                      automação industrial

  Cálculos e Exercícios               Fórmulas, exemplos resolvidos,
                                      questões e desafios
  -----------------------------------------------------------------------

Os materiais também poderão ser classificados por nível de dificuldade
--- iniciante, intermediário ou avançado --- e por formato, como
apostila, PDF, resumo, exercício, artigo, vídeo ou link externo.

## Identidade visual

A identidade visual proposta busca transmitir tecnologia, confiança,
inovação e conexão com o setor elétrico.

  Elemento        Cor                  Código
  --------------- -------------------- -----------
  Azul-marinho    Cor principal        `#092D50`
  Azul elétrico   Cor de destaque      `#168AC4`
  Azul-claro      Apoio visual         `#65C7F2`
  Branco          Fundo e contraste    `#FFFFFF`
  Cinza-claro     Fundo secundário     `#F3F6F9`
  Amarelo         Destaques pontuais   `#FFC928`

A interface deve priorizar legibilidade, contraste, organização dos
elementos e adaptação a computadores, tablets e celulares. Como
referência tipográfica, foram consideradas fontes sem serifa, como Inter
ou Poppins.

## Tecnologias e ferramentas

A seleção final deve corresponder às tecnologias realmente utilizadas no
código do projeto. A proposta inicial considera:

-   **Lovable:** criação e implementação da interface da aplicação;
-   **Lovable Cloud:** recursos de backend, autenticação, banco de dados
    e armazenamento, conforme os recursos habilitados no projeto;
-   **React:** construção da interface, caso confirmado na configuração
    gerada;
-   **TypeScript:** tipagem do código, caso utilizado;
-   **Git e GitHub:** versionamento e hospedagem do repositório;
-   **ChatGPT:** apoio à definição do problema, planejamento, elaboração
    de requisitos, criação de prompts e revisão do projeto.

> Confira o arquivo `package.json` e a configuração do projeto antes de
> manter esta lista. Remova ferramentas que não tenham sido utilizadas.

## Modelo de negócio

O EletroAprende foi concebido inicialmente como um portal de conteúdo
educacional. Nesta etapa, a prioridade é validar a utilidade da
plataforma, a organização dos materiais e a experiência de navegação.

### Business Model Canvas --- hipótese inicial

  -----------------------------------------------------------------------
  Bloco                               Proposta inicial
  ----------------------------------- -----------------------------------
  Proposta de valor                   Reunir materiais de Engenharia
                                      Elétrica em um ambiente organizado
                                      e acessível

  Segmentos de clientes               Estudantes, pessoas em formação
                                      técnica e interessados no setor
                                      elétrico

  Canais                              Plataforma web, redes sociais e
                                      divulgação em instituições de
                                      ensino

  Relacionamento                      Conteúdos organizados, formulário
                                      de contato e canais de comunicação

  Fontes de receita                   Não definidas para o MVP; avaliar
                                      possibilidades após validação

  Recursos principais                 Plataforma, materiais educacionais,
                                      equipe responsável e infraestrutura
                                      digital

  Atividades principais               Curadoria, organização, atualização
                                      e divulgação dos conteúdos

  Parcerias principais                Instituições de ensino,
                                      profissionais e produtores de
                                      conteúdo técnico

  Estrutura de custos                 Hospedagem, ferramentas digitais,
                                      produção e revisão de conteúdo
  -----------------------------------------------------------------------

Este Canvas representa hipóteses iniciais, não resultados de pesquisa de
mercado. Os segmentos, canais, parcerias e possíveis fontes de receita
devem ser validados com usuários reais.

### TAM, SAM e SOM

As estimativas de TAM (mercado total), SAM (mercado atendível) e SOM
(parcela de mercado que se pretende alcançar) ainda precisam ser
construídas com dados confiáveis.

Não foram incluídos valores numéricos para evitar estimativas sem fonte.
Para completar esta análise, pesquise dados atuais sobre estudantes de
cursos técnicos e superiores relacionados à área elétrica, alcance
geográfico pretendido e capacidade real de atendimento do projeto.
Registre a fonte, o ano e o método de cálculo de cada estimativa.

## Desenvolvimento com apoio de IA

O ChatGPT foi proposto como apoio ao planejamento e à estruturação do
produto, auxiliando na identificação do problema, definição do
público-alvo, organização das funcionalidades e elaboração do prompt de
implementação.

O Lovable foi escolhido como ferramenta de apoio à construção da
aplicação. O processo de desenvolvimento deve ocorrer de forma
iterativa:

1.  Definir o problema e a proposta de valor;
2.  Delimitar o escopo do MVP;
3.  Planejar as páginas, funcionalidades e estrutura de dados;
4.  Implementar a aplicação;
5.  Testar os fluxos principais;
6.  Registrar problemas encontrados e correções realizadas;
7.  Publicar a versão validada e documentar os resultados.

### Prompt de desenvolvimento

O prompt completo utilizado no Lovable deve ser disponibilizado junto ao
projeto ou registrado nesta documentação. Recomenda-se incluir:

-   O contexto e o problema que o produto busca resolver;
-   O público-alvo e a proposta de valor;
-   As páginas e funcionalidades esperadas;
-   A identidade visual;
-   Os requisitos de banco de dados e autenticação;
-   As regras de segurança e privacidade;
-   Os critérios de aceitação e os testes necessários.

### Registro de ajustes realizados

Preencha esta tabela durante o desenvolvimento. Registre somente
alterações que realmente foram solicitadas e realizadas.

  Problema identificado        Ajuste solicitado   Resultado após o ajuste
  ---------------------------- ------------------- -------------------------
  A preencher após os testes   A preencher         A preencher
  A preencher após os testes   A preencher         A preencher
  A preencher após os testes   A preencher         A preencher

## Testes e validação

Antes da publicação, recomenda-se testar os principais fluxos da
aplicação.

-   [ ] A página inicial carrega corretamente;
-   [ ] O menu direciona para as seções esperadas;
-   [ ] A biblioteca exibe os materiais publicados;
-   [ ] A busca retorna resultados coerentes;
-   [ ] Os filtros funcionam em conjunto e individualmente;
-   [ ] As páginas individuais dos materiais exibem as informações
    corretas;
-   [ ] Links e arquivos dos materiais podem ser acessados;
-   [ ] O formulário valida os campos obrigatórios;
-   [ ] O envio do formulário registra os dados corretamente;
-   [ ] Visitantes não conseguem acessar dados privados;
-   [ ] O login administrativo funciona;
-   [ ] Usuários não autorizados não conseguem gerenciar conteúdos;
-   [ ] O cadastro, a edição e a exclusão de materiais funcionam;
-   [ ] A publicação e o rascunho respeitam as permissões;
-   [ ] A interface funciona em celular, tablet e computador;
-   [ ] Contraste, textos, rótulos e navegação por teclado foram
    revisados.

### Resultados dos testes

Após executar os testes, descreva aqui:

-   Quais funcionalidades foram validadas;
-   Quais problemas foram encontrados;
-   Quais correções foram realizadas;
-   O que ainda não está funcionando ou precisa ser melhorado.

Não declare que uma funcionalidade foi testada ou aprovada sem realizar
a verificação.

## Estrutura do repositório

A estrutura abaixo é uma sugestão. Ajuste os diretórios e nomes para
refletir os arquivos reais do projeto.

``` text
eletroaprende/
├── README.md
├── src/
├── public/
├── docs/
│   └── images/
│       ├── home.png
│       ├── biblioteca.png
│       ├── material.png
│       └── dashboard.png
├── package.json
└── .gitignore
```

### Capturas de tela

Adicione imagens reais da aplicação para documentar as telas principais.
Salve os arquivos na pasta `docs/images/` e mantenha os nomes abaixo ou
atualize os caminhos.

**Página inicial**

![Página inicial do EletroAprende](docs/images/home.png)

**Biblioteca de materiais**

![Biblioteca de materiais do EletroAprende](docs/images/biblioteca.png)

**Página de um material**

![Página de material do EletroAprende](docs/images/material.png)

**Painel administrativo**

![Painel administrativo do EletroAprende](docs/images/dashboard.png)

> Substitua as imagens de exemplo pelos screenshots reais. Se alguma
> tela ainda não estiver implementada, remova temporariamente a imagem
> correspondente.

## Como executar o projeto

As instruções abaixo são um modelo para projetos baseados em Node.js.
Confirme os comandos e requisitos no `package.json` e na configuração
real do projeto.

### Pré-requisitos

-   Git instalado;
-   Node.js em versão compatível com o projeto;
-   Gerenciador de pacotes utilizado pelo repositório (npm, pnpm ou
    yarn);
-   Configurações necessárias para conectar aos serviços do Lovable
    Cloud, caso aplicável.

### Instalação

``` bash
# Clone o repositório
git clone URL_DO_REPOSITORIO

# Entre na pasta do projeto
cd eletroaprende

# Instale as dependências (se o projeto utilizar npm)
npm install

# Inicie o ambiente de desenvolvimento
npm run dev
```

Substitua `URL_DO_REPOSITORIO` pelo endereço real do repositório. Se o
projeto utilizar outro gerenciador de pacotes ou comandos diferentes,
siga as instruções existentes nos arquivos de configuração.

Não publique chaves privadas, tokens, senhas ou outras credenciais no
GitHub. Utilize as variáveis de ambiente e os mecanismos de configuração
apropriados para o ambiente de desenvolvimento e produção.

## Evoluções futuras

Depois da validação do MVP, algumas possibilidades de evolução poderão
ser avaliadas:

-   Ampliação da biblioteca de conteúdos;
-   Inclusão de trilhas de aprendizagem;
-   Exercícios interativos e simulados;
-   Favoritos e histórico de materiais;
-   Recursos de acompanhamento do progresso;
-   Parcerias com instituições de ensino e profissionais;
-   Novos formatos de conteúdo e recursos de acessibilidade.

Essas ideias não fazem parte do escopo inicial e devem ser priorizadas
conforme o retorno dos usuários e a viabilidade técnica.

## Links

-   **Aplicação publicada:** `INSERIR_LINK_DA_APLICACAO`
-   **Repositório GitHub:** `INSERIR_LINK_DO_REPOSITORIO``

Atualize os campos acima antes de entregar ou divulgar o projeto.

## Referências

Inclua nesta seção as fontes efetivamente utilizadas na elaboração dos
conteúdos técnicos, na pesquisa de mercado e na fundamentação do
projeto.

Para cada referência, informe os dados necessários para que outra pessoa
consiga localizar a fonte, como autor ou instituição, título, ano e
endereço eletrônico, além da data de acesso quando aplicável.

Evite publicar materiais protegidos por direitos autorais sem
autorização. Sempre que possível, utilize conteúdos próprios, fontes
abertas ou materiais cuja licença permita o compartilhamento, mantendo
os créditos e links de origem.
