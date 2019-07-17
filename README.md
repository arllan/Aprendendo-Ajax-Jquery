# Aprendendo-Ajax-Jquery
Diretorio para fins educacionais


* async: Por padrão, todas as requisições são enviadas de forma assíncrona, definido com true. Se você precisar de solicitações síncronas, defina esta opção como false . Requisições cross-domain e dataType: "jsonp" não suportam a operação síncrona. Observe que solicitações síncronas podem bloquear temporariamente o navegador, desativando quaisquer ações enquanto a solicitação estiver ativa.

* beforeSend: Para alterar o cabeçalho da requisição ou realizar operações antes do envio da requisição, utilize esta função.

* cache: Se definido como false, ele vai forçar páginas não devem ser armazenados em cache pelo navegador solicitado.

* complete: A função a ser chamada quando os acabamentos de solicitação (depois success e error retornos de chamada são executados).

* contents: Um objeto de pares string/expressão regular que determinam como o jQuery irá analisar a resposta, dado o seu tipo de conteúdo.

* contentType: Ao enviar dados para o servidor, use esse tipo de conteúdo. O padrão é "application/x-www-form-urlencoded; charset=UTF-8", o que é bom para a maioria dos casos. Se você passar explicitamente em um tipo de conteúdo para $.ajax(), então é sempre enviado para o servidor (mesmo que nenhum dado é enviado).

* context: Este objeto será o contexto de todos os retornos de chamada relacionados ao Ajax. Por padrão, o contexto é um objeto que representa as configurações Ajax utilizadas na chamada ($.ajaxSettings fundiu-se com as definições passadas para $.ajax).

* converters: Um objeto que contém os conversores dataType-to-dataType. O valor de cada conversor é uma função que retorna o valor transformado da resposta.

* crossDomain: Se você deseja forçar um pedido crossdomain (como JSONP) no mesmo domínio, defina o valor de crossdomain a true. Isso permite, por exemplo, redirecionamento do servidor para outro domínio.

* data: Dados a serem enviados para o servidor. O formato deve ser variável/valor e se você não deixar nesta formatação a função formatará automaticamente.

* dataFilter: Uma função a ser usada para manipular os dados de resposta brutos de XMLHttpRequest. Esta é uma função de pré-filtragem para sanitizar a resposta. Você deve devolver os dados higienizados. A função aceita dois argumentos: Os dados brutos retornados do servidor e o parâmetro dataType.

* dataType: Você define qual o tipo de dado a ser retornado pela requisição. Os valores possíveis são: xml, html, json, jsonp, script e text. Configurando esta opção você permite uma avaliação dos dados que são retornados. Se esta opção for omitida a função identifica o tipo de dado, mas não avalia.

* error: Uma função a ser chamada se a solicitação falhar. A função recebe três argumentos: O objeto jqXHR (em jQuery 1.4.x, XMLHttpRequest), uma string que descreve o tipo de erro que ocorreu e um objeto de exceção opcional, se ocorreu.

* global: Indica se os eventos manipuladores definidos em .ajaxSend() e .ajaxError() valerão na requisição atual. Por padrão está setado para true.

* headers: Um objeto de cabeçalho adicional para enviar junto com solicitações usando o transporte XMLHttpRequest.

* ifModified: Permitir que a solicitação seja bem-sucedida somente se a resposta tiver sido alterada desde a última solicitação. Isso é feito verificando o cabeçalho Last-Modified. O valor padrão é false , ignorando o cabeçalho.

* isLocal: Permite que o ambiente atual seja reconhecido como "local" (por exemplo, o sistema de arquivos), mesmo que o jQuery não o reconheça como tal por padrão. Os seguintes protocolos são reconhecidos atualmente como locais: file , *-extension e widget . Se o isLocal definição precisa de modificação, recomenda-se a fazê-lo uma vez no $.ajaxSetup() método.

* jsonp: Substitui o nome da função callback em uma solicitação JSONP.

* jsonpCallback: Especifica o nome da função callback para uma solicitação JSONP. Este valor será usado em vez do nome aleatório gerado automaticamente pelo jQuery.

* method: O método HTTP a ser usado para o pedido (por exemplo, POST, GET, PUT).

* mimeType: Um tipo mime para substituir o tipo XHR mime.

* password: Uma senha para ser usada com XMLHttpRequest em resposta a uma solicitação de autenticação de acesso HTTP.

* processData: Esta variável é configurada para processar e transformar as informações passadas para o padrão application/x-www-form-urlencoded. Se por algum motivo você não quer esta formatação, como mandar no formato xml para o servidor, atribua false para esta variável.

* scriptCharset: Aplica-se somente quando o transporte "script" é usado (por exemplo, solicitações entre domínios com tipo de dados jsonp ou script e tipo GET). Define o charset atributo na tag script usado no pedido. Usado quando o conjunto de caracteres na página local não é o mesmo do script remoto.

* statusCode: Um objeto de códigos e funções numéricas HTTP a ser chamado quando a resposta tem o código correspondente.

* success: Se a requisição finalizar com sucesso, é executada esta função, que recebe os dados recebidos do servidor.

* timeout: Se você quer limitar o tempo para a execução da requisição, defina um valor em milissegundos. Não retornando sucesso dentro do tempo definido, uma mensagem de erro, configurada por você na função error, será mostrada.

* traditional: Defina esta opção como true se você quiser usar o estilo tradicional de serialização de parâmetro.

* type: O método usado para a requisição. Aceita GET ou POST. O padrão é GET.

* url: Endereço no servidor que receberá a requisição.

* username: Um nome de usuário a ser usado com XMLHttpRequest em resposta a uma solicitação de autenticação de acesso HTTP.

* xhr: Callback para criar o objeto XMLHttpRequest.

* xhrFields: Um objeto de pares fieldName-fieldValue para definir sobre o nativo XHR objeto.
