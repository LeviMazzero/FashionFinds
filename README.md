<h1> Nome da Empresa/Software: FashionFinds </h1>
- Missão:
    Capacitar microempreendedores locais através de soluções digitais acessíveis,
promovendo crescimento econômico e inclusão social.
- Visão:
    Ser a principal plataforma de apoio para microempreendedores locais,
impulsionando o desenvolvimento sustentável das comunidades.
- Valores:
1. Inovação: Na FashionFinds, valorizamos a inovação como uma força motriz para o
progresso. Estamos constantemente buscando novas maneiras de melhorar e criar
soluções tecnológicas que atendam às necessidades em constante evolução de
nossos clientes.
2. Colaboração/Comunicação: Reconhecemos que o trabalho em equipe é
fundamental para alcançar o sucesso. Promovemos um ambiente de colaboração
onde as ideias são compartilhadas livremente, e todos são incentivados a contribuir
com suas habilidades e conhecimentos para alcançar objetivos comuns.
3. Integridade: Agimos com honestidade e transparência em todas as nossas
interações. Mantemos altos padrões éticos em nossos negócios e nos
comprometemos a cumprir nossas promessas e obrigações, garantindo a confiança
e o respeito de nossos clientes e parceiros mantendo assim um laço de confiança.
4. Empatia: Valorizamos a empatia como uma ferramenta essencial para entender as
necessidades e preocupações de nossos clientes e colegas de trabalho.
Demonstramos compreensão e consideração pelos outros, buscando sempre
encontrar soluções que atendam às suas necessidades.
5. Responsabilidade Social: Estamos comprometidos com o bem-estar das
comunidades em que atuamos e reconhecemos nossa responsabilidade em
contribuir para um mundo melhor. Apoiamos iniciativas sociais e ambientais e nos
esforçamos para ser um agente de mudança positiva na sociedade.
6. Qualidade: Buscamos a excelência em tudo o que fazemos, desde o
desenvolvimento de produtos até o atendimento ao cliente. Estabelecemos altos
padrões de qualidade e nos esforçamos para superar as expectativas de nossos
clientes.
7. Respeito à Diversidade: Valorizamos e respeitamos a diversidade em todas as
suas formas. Reconhecemos a importância da inclusão e estamos comprometidos
em criar um ambiente de trabalho onde todas as pessoas se sintam valorizadas e
respeitadas, independentemente de sua origem, identidade ou crenças.
8. Sustentabilidade: Reconhecemos nossa responsabilidade em proteger o meio
ambiente e promover práticas sustentáveis em nossos negócios. Nos esforçamos
para minimizar nosso impacto ambiental, adotando práticas ecológicas em todas as
nossas operações, exemplo: valorizando a reutilização de roupas e a divulgação das
lojas que promovem o uso das mesmas através do aplicativo (lojas de brechós).
9. Foco no Cliente: Colocamos as necessidades e interesses de nossos clientes no
centro de todas as nossas decisões e ações. Estamos empenhados em oferecer um
atendimento excepcional e em fornecer soluções que agreguem valor e contribuam
para o sucesso de nossos clientes sejam eles consumidores ou varejistas.
10. Crescimento Pessoal e Profissional: Valorizamos o desenvolvimento pessoal e
profissional dos nossos comerciantes e varejistas parceiros. Oferecemos suporte e
recursos para que possam aprimorar suas habilidades de gestão, marketing e
atendimento ao cliente, capacitando-os a alcançar seu máximo potencial e sucesso
em seus negócios.

- Definição do Projeto de Software:
● Resumo:
   FashionFinds é uma plataforma de e-commerce personalizada para
microempreendedores locais, oferecendo ferramentas de marketing digital e
suporte ao cliente.
● Como o software funcionará?
   O software permitirá que os microempreendedores locais criem suas próprias lojas
online de forma intuitiva, gerenciando produtos, pedidos e pagamentos. Os usuários
terão acesso a ferramentas de SEO, marketing por e-mail e análises de dados. O
diferencial está no suporte ao cliente e na comunidade, além da facilidade de uso.
Nossos usuários:
Usuário Varejista:
    Microempreendedores locais, como proprietários de lojas de bairro e brechós.
Usuário Cliente:
    O cliente inicia o aplicativo e fornece a localização.
    O aplicativo exibe os comércios varejistas próximos ao usuário, mostrando
promoções e benefícios como frete grátis.
    Se o cliente se interessar por algum item de roupa, será redirecionado para a página
de cadastro do app.
    Após o cadastro, o usuário seleciona se deseja retirar na loja para evitar o
pagamento do frete ou aguardar a entrega em casa.
    O cliente seleciona a opção desejada e finaliza a compra, efetuando o pagamento e
aguardando a entrega ou dirigindo-se à loja para retirar o pedido.
- Diferencial e Relevância:
    O software oferece uma solução completa e acessível para microempreendedores
competirem no mercado online, promovendo o crescimento de seus negócios.
- Quais Plataformas:
    Será lançado como aplicativo para ios e android, e no futuro para melhor administração contará com interface web.
Pontuações sobre a empresa

● Fluxograma AS IS/TO BE:
![FluxogramaFashionFinds](https://github.com/LeviMazzero/HolySoftware/assets/91742210/b3e36e55-9dbe-414a-8852-81917e497f88)

- Historias de Usuario
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>História de Usuário</th>
            <th>Critério de Aceitação</th>
            <th>Prioridade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>US1</td>
            <td>Como cliente, quero navegar facilmente pelo aplicativo para encontrar os produtos que procuro.</td>
            <td>
                <ol>
                    <li>O aplicativo deve ter uma interface intuitiva e amigável.</li>
                    <li>Os produtos devem ser categorizados e filtrados de forma clara, por tipos de produtos, cores, marca e tamanhos disponiveis.</li>
                    <li>A busca por produtos deve ser rápida e precisa no máximo 5 segundos.</li>
                </ol>
            </td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>US2</td>
            <td>Como cliente, quero poder visualizar fotos e informações detalhadas dos produtos antes de comprá-los.</td>
            <td>
                <ol>
                    <li>As fotos dos produtos devem ser de alta qualidade e mostrar o produto em diferentes ângulos.</li>
                    <li>As informações dos produtos devem ser completas e precisas, incluindo descrição, tamanho, cor, material, etc.</li>
                    <li>O cliente pode alterar o tamanho e cor desejado do produto de acordo com as opções oferecidas pela loja.</li>
                </ol>
            </td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>US3</td>
            <td>Como cliente, quero poder adicionar produtos ao carrinho de compras e finalizar a compra em ate quatro telas(Carrinho, endereço e metodo de entrega, forma de pagamento e confirmação dos dados).</td>
            <td>
                <ol>
                    <li>O processo de checkout deve ser simples e direcional, com um fluxo sem retornos naturais a telas anteriores</li>
                    <li>O cliente deve poder escolher entre diferentes formas de pagamento mantendo a segurança de suas informações.</li>
                    <li>O cliente deve receber um e-mail/sms de confirmação de compra após finalizar o pedido contendo o recibo/codigo de sua compra.</li>
                </ol>
            </td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>US4</td>
            <td>Como comerciante local, quero poder cadastrar meus produtos no aplicativo de forma rápida e fácil, onde todo processo ocorra em até tres telas (descrição, fotos, formas de pagamento do cliente).</td>
            <td>
                <ol>
                    <li>O comerciante deve poder fornecer todas as informações relevantes sobre seus produtos e suas opções disponiveis.</li>
                    <li>O processo de cadastro do produto inclui fotos com variação de tamanho e cor do produto facilitando assim a identificação do mesmo de acordo com as diretrizes do aplicativo.</li>
                    <li>O comerciante deve poder selecionar formas de pagamento e parcelamento para seus produtos, além de descontos aplicados aos mesmos.</li>
                </ol>
            </td>
            <td>Média</td>
        </tr>
        <tr>
            <td>US5</td>
            <td>Como comerciante local, quero poder gerenciar meus pedidos e entregas de forma eficiente.</td>
            <td>
                <ol>
                    <li>O comerciante deve poder visualizar todos os seus pedidos em um único lugar.</li>
                    <li>O comerciante deve poder acompanhar o status de cada pedido.</li>
                    <li>O comerciante deve poder imprimir etiquetas de envio e rastrear as entregas.</li>
                </ol>
            </td>
            <td>Média</td>
        </tr>
        <tr>
            <td>US6</td>
            <td>Como cliente, quero poder me comunicar com o comerciante local para tirar dúvidas e fazer solicitações.</td>
            <td>
                <ol>
                    <li>O aplicativo deve fornecer um canal de comunicação direto entre o cliente e o comerciante.</li>
                    <li>O cliente deve poder enviar mensagens e fotos para o comerciante.</li>
                    <li>O comerciante deve responder às mensagens do cliente em tempo hábil(o tempo depende do comerciante porem o aplicativo incentiva respostas rapidas via push notifications).</li>
                </ol>
            </td>
            <td>Baixa</td>
        </tr>
        <tr>
            <td>US7</td>
            <td>Como cliente, quero poder avaliar os produtos que comprei e compartilhar minha opinião com outros clientes.</td>
            <td>
                <ol>
                    <li>O aplicativo deve permitir que os clientes avaliem os produtos com estrelas de um a cinco.</li>
                    <li>O aplicativo deve permitir que os clientes escrevam comentários e fotos sobre os produtos junto de sua avaliação.</li>
                    <li>Os comentários dos clientes devem ser visíveis para outros clientes porem sendo moderados pelas diretrizes do aplicativo.</li>
                </ol>
            </td>
            <td>Baixa</td>
        </tr>
    </tbody>
</table>
  
 - Requisitos Funcionais:

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Requisito Funcional</th>
            <th>Detalhes</th>
            <th>Prioridade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>RF1</td>
            <td>O aplicativo deve permitir que os clientes procurem produtos por nome, categoria e localização.</td>
            <td>
                <ol>
                    <li>A busca deve ser rápida e precisa, utilizando indices em nome e categoria para melhor otimização de informações no banco de dados.</li>
                    <li>Os resultados da busca devem ser relevantes para a consulta do cliente, tambem aparecendo produtos correlacionados de acordo com localização, categoria de outras lojas ou comprados em conjunto na mesma loja.</li>
                </ol>
            </td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>RF2</td>
            <td>O aplicativo deve permitir que os clientes comprem produtos online e paguem com segurança.</td>
            <td>
                <ol>
                    <li>O processo de checkout deve ser simples e intuitivo onde todo processo ocorra em ate quatro telas(Carrinho, endereço e metodo de entrega, forma de pagamento e confirmação dos dados).</li>
                    <li>O cliente deve poder escolher entre diferentes formas de pagamento tais quais pix, cartão de credito, debito, boleto e a opção de compras parceladas.</li>
                    <li>Os dados de pagamento do cliente precisam ser enviados de forma segura atraves de uma encriptação via JWT e caso disponivel TOPT se disponbilizado pelo banco de pagamento</li>
                    <li>O cliente deve receber um e-mail/sms de confirmação de compra após finalizar o pedido contendo o recibo.</li>
                </ol>
            </td>
            <td>Alta</td>
        </tr>
    </tbody>
</table>

- Requisitos Não Funcionais


<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Requisito Não Funcional</th>
            <th>Detalhes</th>
            <th>Prioridade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>RNF1</td>
            <td>Segurança</td>
            <td>O aplicativo deve proteger os dados dos usuários contra acesso não autorizado, uso indevido e divulgação de acordo com a LGPD.</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>RNF2</td>
            <td>Desempenho</td>
            <td>O sistema deve ser capaz de processar ate mil transações por segundo</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>RNF3</td>
            <td>Escalabilidade</td>
            <td>O aplicativo deve ser capaz de lidar com um grande número de usuários e transações, utilizando containers escalaveis hospedados na nuvem (AWS).</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>RNF4</td>
            <td>Disponibilidade</td>
            <td>O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, caso ele caia devera ser reiniciado automaticamente via pipeline.</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>RNF5</td>
            <td>Usabilidade</td>
            <td>Todas as caixas de dialogo e botões tem a mesma aparencia e comportamento retirando alguns lugares chaves como a finalização da compra para gerar mais atenção do consumidor.</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>RNF6</td>
            <td>Acessibilidade</td>
            <td>O aplicativo deve ser acessível a pessoas com deficiência visual trabalhando em conjunto de empresas como EqualWeb, BeMyEyes e Assistive alem de funções nativas do smartphone.</td>
            <td>Média</td>
        </tr>
        <tr>
            <td>RNF7</td>
            <td>Manutenabilidade</td>
            <td>O aplicativo deve ser fácil de manter e atualizar utilizando ciclos de GMUD para lançamentos de releases com novas versões e com cronogramas diarios para hotfix.</td>
            <td>Média</td>
        </tr>
    </tbody>
</table>

- Requisitos Funcionais Detalhados:


<table>
    <thead>
        <tr>
            <th>Função</th>
            <th>Descrição</th>
            <th>Entradas</th>
            <th>Origem</th>
            <th>Saídas</th>
            <th>Destino</th>
            <th>Ação</th>
            <th>Requer Pré-Condição</th>
            <th>Pós-Condição</th>
            <th>Efeitos Colaterais</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cadastrar Produto</td>
            <td>Permite que o comerciante local cadastre seus produtos no aplicativo.</td>
            <td>Nome do produto, Descrição do produto, Categoria do produto, Preço do produto, Quantidade em estoque, Fotos do produto</td>
            <td>Interface do aplicativo para o comerciante local</td>
            <td>Produto cadastrado no sistema, Mensagem de confirmação de cadastro</td>
            <td>Banco de dados do aplicativo</td>
            <td>Inserir os dados do produto no banco de dados</td>
            <td>O comerciante local deve estar logado no aplicativo.</td>
            <td>O produto estará disponível para venda no aplicativo.</td>
            <td>O estoque do produto será atualizado.</td>
        </tr>
        <tr>
            <td>Buscar Produtos</td>
            <td>Permite que o cliente procure produtos no aplicativo.</td>
            <td>Termo de busca, Categoria do produto, Localização</td>
            <td>Interface do aplicativo para o cliente</td>
            <td>Lista de produtos que correspondem ao termo de busca, e produtos correlacionados</td>
            <td>Interface do aplicativo para o cliente</td>
            <td>Pesquisar no banco de dados os produtos que correspondem ao termo de busca</td>
            <td>O cliente deve ter o aplicativo baixado e atualizado.</td>
            <td>O cliente terá acesso a uma lista de produtos que correspondem ao termo de busca. O cliente poderá visualizar a localização dos produtos</td>
            <td>Nenhum.</td>
        </tr>
    </tbody>
</table>

![image](https://github.com/LeviMazzero/FashionFinds/assets/91742210/cc4ddd12-1452-48df-a7cf-d8e4076a9073)

*"Empoderando microempreendedores, conectando comunidades."*
