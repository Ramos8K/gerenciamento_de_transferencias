# typescript_js
Uma Aplicação que realiza transações financeiras, com funcionalidades sendo programados com TypeScript, com intuito de se realizar um projeto profissional!




// Tipos Primitivos
let valor = 3000;
let nome = "";
let isPago = false;
let qualquer = "";
qualquer = 22;
// Arrays
const lista = [];
lista.push(22, 23);
// Enum
var TipoTransacao;
(function (TipoTransacao) {
    TipoTransacao["DEPOSITO"] = "Dep\u00F3sito";
    TipoTransacao["TRANSFERENCIA"] = "Transfer\u00EAncia";
    TipoTransacao["PAGAMENTO_BOLETO"] = "Pagamento de Boleto";
})(TipoTransacao || (TipoTransacao = {}));
const novaTransacao = {
    tipoTransacao: TipoTransacao.DEPOSITO,
    data: new Date(),
    valor: 0
};
console.log(novaTransacao);

= Pastas de Organização
    Components = Interagem com a Interface

    Utilis = Funções livres usadas dentro da Aplicação

    Types = Tipos usados na Aplicação, como enum, 

