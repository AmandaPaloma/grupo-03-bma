# Especificações do Projeto

## Estado da Arte

Nas pesquisas realizadas, foi possível notar uma expressiva quantidade de bancos de alimentos, sendo observado que grande parte deles, incluindo bancos de grandes cidades como Rio de Janeiro e São Paulo, não apresentam sistemas públicos e acessíveis via internet, específicos para o controle de doações de cestas básicas.

É importante frisar que existem iniciativas públicas e privadas para doação de alimentos, como o site Clique Alimentos,  vinculado ao Banco de Alimentos do Rio Grande do Sul, a plataforma Comida Invisível e o aplicativo VivaVida, vinculado à prefeitura de Campinas. Embora existam iniciativas vinculadas ao propósito de doação de alimentos, poucas propostas se adequam à necessidade específica do projeto em questão.

<table>
 <thead>
  <tr>
   <th>Imagens da Pesquisa</th>
   <th>Descrição</th>
  </tr>
 </thead>

 <tbody>
  <tr>
   <td><img src="https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2021-2-e1-proj-web-t1-grupo-7/blob/4b3d3255616e25d5082f4b3cf9297065c32b1cd1/docs/img/estadoarte1.png" width=500px></td>
   <td width=500px>O Clique Alimentos é uma iniciativa ligada à região do Rio Grande do Sul, onde o internauta escolhe uma "cidade" para destinar a doação de 1 kg de alimento para o Banco de Alimentos escolhido.

Fonte: https://www.cliquealimentos.com.br/Inicial.</td>
  </tr>

  <tr>
   <td><img src="https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2021-2-e1-proj-web-t1-grupo-7/blob/4b3d3255616e25d5082f4b3cf9297065c32b1cd1/docs/img/estadoarte2.png" width=500px></td>
   <td width=500px>A imagem refere-se a página inicial do site e app Comida Invisível, uma plataforma que tem como objetivo conectar pessoas para causar impacto social e ambiental, além de trazer conteúdos com objetivo de mudar o hábito de consumo de alimentos para que cada um possa fazer a sua parte.

Fonte: https://www.comidainvisivel.com.br/.</td>
  </tr>

  <tr>
   <td><img src="https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2021-2-e1-proj-web-t1-grupo-7/blob/bdd6ab740bb018ccd593ee55078450ccd1270a7f/docs/img/estadoarte3.png" width=500px></td>
   <td width=500px>A imagem em questão refere-se ao app VivaVida, da Prefeitura de Campinas, que tem como objetivo a captação de recursos para conversão e distribuição de cestas básicas através de sistema de Vouchers virtuais. 

Fonte: https://play.google.com/store/apps/details?id=br.com.vonbraunlabs.vivavida&hl=pt_BR&gl=US.</td>
  </tr>
 </tbody>

</table>

## Histórias de Usuários

No projeto são considerados dois principais tipos de usuários: funcionários vinculados ao BMA e ao CRAS que estejam envolvidos com o processo de distribuição de cestas básicas; e os beneficiários do programa de assistência social de doação de alimentos. 

No caso dos funcionários, é necessário que tais usuários tenham um perfil administrativo, pesquisador e estejam dispostos a promover o maior controle possível na distribuição de cestas básicas. São necessidades desses usuários: 

- Verificar o número de cestas básicas disponíveis para distribuição;
- Consultar o CPF dos beneficiários do programa de doação de alimentos a fim de verificar o registro da distribuição;
- Cadastrar um beneficiário do programa de doação de alimentos;
- Visualizar que tipo de cesta o beneficiário recebe, se ainda não recebeu no mês e saber a data do próximo recebimento.

No caso dos beneficiários as necessidades são: 

- Consultar a data do próximo recebimento de cesta básica/verde;;
- Consultar o local de retirada de cesta básica/verde;
- Consultar histórico de últimos recebimentos;

## Personas

<table>
  <tr>
    <th>Foto</th>
    <th>Nome</th>
    <th>Descrição</th>
    <th>Aplicativos</th>
    <th>Motivações</th>
    <th>Frustrações</th>
    <th>Hobbies, História</th>
  </tr
        <tr>
    <td><img title="Maria Aparecida" src="https://images.unsplash.com/photo-1626668011687-8a114cf5a34c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"/></td>
    <td>Maria Aparecida</td>
    <td>
      <ul>
        <li>68 anos</li>
        <li>Aposentada</li>
        <li>Mora de aluguel em Poços de Caldas com a filha e dois netos</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Não usa redes sociais</li>
         </ul>
    </td>
    <td>
      <ul>
        <li>Cuidar da família</li>
        <li>Participar da missa</li>
        <li>Dançar forró</li>
      </ul>
    </td>
    <td>
      <li>Não terminou o ensino fundamental</li>
      <li>Não tem casa própria</li>
      <li>Nunca viu o mar</li>
    </td>
    <td>
      <li>Ver novelas</li>
      <li>Costurar</li>
       <li>Sua filha está desempregada desde meados de 2020 e, por isso, tornou-se a principal provedora do sustento da filha e dos dois netos</li>
          </td>
  </tr>
  <tr>
    <td><img title="Aline" src="https://images.unsplash.com/photo-1602184572201-89c7deeddf3c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=387&q=80"/></td>
    <td>Aline</td>
    <td>
      <ul>
        <li>36 anos</li>
        <li>Auditora da CGU</li>
        <li>Mora no Rio de Janeiro</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Twitter</li>
        <li>Instagram</li>
        <li>Youtube</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Emicida</li>
        <li>Angela Merkel</li>
        <li>Emmanuel Macron</li>
      </ul>
    </td>
    <td>
      <li>Não consegue executar a auditoria com facilidade por falta de disponibilidade da informação nos órgãos públicos</li>
      <li>Está sobrecarrega com as demandas de trabalho</li>
     </td>
    <td>
      <li>Música</li>
      <li>Cozinhar com o filho</li>
         <li>Foi nomeada presidente da comissão de acompanhamento da implementação da transparência ativa dos órgão públicos</li>
    </td>
  </tr>
    <tr>
    <td><img title="Jose Augusto" src="https://images.unsplash.com/photo-1545167622-3a6ac756afa4?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=412&q=80"/></td>
    <td>José Augusto</td>
    <td>
      <ul>
        <li>50 anos</li>
        <li>Padre</li>
        <li>Mora em Poços de Caldas</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Facebook</li>
        <li>Instagram</li>
        <li>Youtube</li>
        </ul>
    </td>
    <td>
      <ul>
        <li>Jornal O Globo</li>
        <li> Padre Júlio Lancellotti</li>
        <li>Papa Francisco</li>
      </ul>
    </td>
    <td>
      <li>Deseja que a sociedade se torne mais caridosa</li>
      <li>Não consegue ajudar a todos que estão em insegurança alimentar</li>
         </td>
    <td>
      <li>Ver jornal</li>
      <li>Ler a Bíblia</li>
      <li>No último ano, percebeu que os projetos sociais da igreja não tem conseguido contemplar todas as pessoas em situação de vulnerabilidade social</li>
    </td>
  </tr>
  <tr>
    <td><img title="Paulo" src="https://images.unsplash.com/photo-1552058544-f2b08422138a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=399&q=80"/></td>
    <td>Paulo</td>
    <td>
      <ul>
        <li>31 anos</li>
        <li>Assistente Social</li>
        <li>Mora em Poços de Caldas</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Twitter</li>
        <li>Instagram</li>
        <li>Youtube</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Carl Gustav Jung</li>
        <li>Josephina Albano</li>
        <li>Chico Buarque</li>
      </ul>
    </td>
    <td>
      <li>Acha o trabalho que executa extremamente burocrático</li>
        </td>
    <td>
      <li>Jogar Futebol</li>
      <li>Música</li>
      <li>Percebeu o aumento de demanda de benefícios sociais na pandemia, entretanto o processo de concessão é demorado uma vez que envolve dois equipamentos públicos diferentes</li>
    </td>
  </tr>
  <tr>
    <td><img title="Renato Luís" src="https://images.unsplash.com/photo-1599256621730-535171e28e50?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=371&q=80" /></td>
    <td>Renato Luís</td>
    <td>
      <ul>
        <li>28 anos</li>
        <li>Servidor Público</li>
        <li>Mora em Poços de Caldas</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Youtube</li>
        <li>Facebook</li>
        <li>Instagram</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Jão</li>
        <li>Mc Tha</li>
      </ul>
    </td>
    <td>
      <li>Não consegue fornecer os dados solicitados pela diretora do seu trabalho dentro dos prazos</li>
      <li>Tem dificuldade em consolidar dados</li>
    </td>
    <td>
      <li>Música</li>
      <li>Barzinho com os amigos</li>
           <li>Ele deseja ter mais facilidade em obter os dados do banco de alimentos com seus colegas de trabalho e elaborar relatórios com mais facilidade </li>
    </td>
  </tr>
  <tr>
    <td><img title="Roberta"
        src="https://images.unsplash.com/photo-1597223557154-721c1cecc4b0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=580&q=80"/></td>
    <td>Roberta</td>
    <td>
      <ul>
        <li>38 anos</li>
        <li>Servidora Pública (Diretora)</li>
        <li>Mora Poços de Caldas</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Facebook</li>
        <li>G1</li>
        <li>Instagram</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Jornais</li>
         <li>Josué de Castro</li>
         <li>Nina Simone</li>
       </ul>
    </td>
    <td>
      <li>Quer tornar o trabalho executado pelo Banco de Alimentos mais eficiente</li>
      <li>Quer aprender mais coisas</li>
    </td>
    <td>
      <li>Ler jornais</li>
      <li>Passar tempo com o marido</li>
      <li>Assistir séries</li>
      <li>Recebeu denúncias sobre beneficiários do Banco de Alimentos que teriam recebido o benefício em locais diferentes</li>
    </td>
  </tr>
</table>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Administrador       | Alterar permissões e cadastrar novos usuários do BMA e CRAS | Permitir a administração de contas e o controle de usuários |
|Usuário BMA/CRAS | Cadastrar beneficiários |Inserir no sistema pessoas aptas ao recebimento do benefício  |
|Usuário BMA/CRAS | Alterar cadastro de beneficiários| Permitir a atualização/correção de dados do beneficiário |
|Usuário BMA/CRAS | Registrar cestas básicas/verdes e pontos para os quais as cestas foram enviadas | Registrar nº de cestas básicas e local de distribuição para prestação de contas |
|Usuário BMA/CRAS | Consultar se beneficiário já recebeu auxílio durante o período de referência | Evitar concessão de cesta básica em duplicidade |
|Usuário BMA/CRAS | Registrar o benefício entregue ao beneficiário | Deduzir saldo e deixar registrado que o beneficiário já recebeu o benefício |
|Beneficiário | Consultar data de recebimento do próximo benefício | Evitar deslocamento desnecessário para recebimento de benefício |
|Beneficiário | Consultar locais com cestas disponíveis | Localizar o endereço mais próximo com cestas em estoque |
|Cidadão| Quantidade de cestas doadas e quantidade de família atendidas| 	Dar transparência ao trabalho do BMA| 
|Cidadão|	Quantidade de alimentos doados por fonte|	Dar transparência ao trabalho do BMA |

O quadro abaixo apresenta uma breve definição de cada perfil: 

|Perfil| Descrição
|--------------------|------------------------------------|
|Administrador|	Servidor do BMA/CRAS com grau máximo de visualização e controle do sistema|
|Usuário BMA/CRAS |	Servidor/colaborador vinculado ao BMA/CRAS que recebe, separa e prepara as cestas básicas e cestas verdes, cadastra beneficiários|
|Beneficiário| 	Pessoa que recebe a cesta básica ou a cesta verde|
|Cidadão |	Qualquer pessoa que acesse o site para buscar infomações sobre o Banco de Alimentos|


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre. |
|02| O front end deve ser desenvolvido com a linguagem de programação Javascript e para isso deve ser utilizado o framework React na versão mais recente. |
|03| Deve ser utilizado o framework Bootstrap para padronização de interface do usuário. |
|04| Como linguagem de folha de estilos deverá ser utilizado o CSS. |
|05| O sistema deve fazer uso de Media Queries e do sistema de Grid do Bootstrap para ajustar de forma responsiva em aparelhos de diferentes resoluções. |
|06| O sistema deverá expor funcionalidades e interoperar com  outras aplicação legadas através do protocolo HTTP por meio de APIs RESTful. |
|07| O transporte de informações se dará por meio do formato JSON. |
|08| O mecanismo de autorização entre as APIs deverá ser feiro por meio do JWT. |
|09| O sistema de ser construido de forma modular para faciliatr a implantação. |
|10| Os módulos que compõem os microsserviços no back end devem ser desenvolvidos na linguagem de programação C# utilizando .Net como ambiente de execução do lado do servidor. |
|11| Deve ser utilizado como ferramenta de versionamento o GIT e cada módulo deve possuir repositório distinto para melhor controle das modificações do código. |
|12| O sistema deve possuir características de aplização distribuída: abertura, portabiliadde, uso de recursos de rede. |


## Mecanismos Arquiteturais

|Ambiente | Design  | Implementação |
|------|-----------------------------------------|----|
|Persistência| Framework ORM | - | 
|Persistência| Banco de dados relacional | - |
|Front end| Framework de desenvolvimento | React |
|Front end| Linguagem de programação | JavaScript |
|Front end| Framework de folhas de estilos | Bootstrap |
|Folhas de estilo| Linguagem de folha de estilos | CSS |
|Deploy| Plataforma de automatização de deploy | - |
|Back end| Linguagem de programação | C# |
|Back end| Ambiente de execução | .Net |
|Back end| Serviço de execução de código | - |
|Back end| Gerenciador de tráfego | - |
|Autenticação| Padrão de formato para autenticação | JWT |
|Autenticação| Serviço de autenticação | - |
|Integração| Formato de transporte de informações | JSON |
|Integração| Protocolo de comunicação | HTTP |
|Integração| Estilo de arquitetura | REST |
|Versionamento| Controle e armazenamento de código fonte | GitHub |
|Versionamento| Versionamento de código fonte | Git |
|Automação| Ferramenta de workflow | - |
|Build| Ferramenta de build de componenetes do software | NPM |




## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
