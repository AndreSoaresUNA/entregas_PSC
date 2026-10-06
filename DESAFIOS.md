# HackTown — serviços para uma cidade digital
A prefeitura fictícia de HackTown precisa de pequenos programas de terminal. Você é a equipe de desenvolvimento.
**Obrigatório:** missão 1. Depois escolha ao menos uma entre 2 e 8. As demais são extras; não é necessário terminar todas hoje.

## Regras comuns
Cada missão deve ter uma classe executável com main, Scanner para os dados, ao menos um método de cálculo com parâmetros e retorno e mensagens compreensíveis.
Use ponto nos decimais; use Locale.US no Scanner. Mostre resultados decimais com duas casas quando indicado. Não coloque os dados dos exemplos fixos no código. Faça pelo menos dois testes e descreva-os no README.
Nesta aula, pode assumir entradas numéricas válidas nos intervalos descritos. Validação com if é bônus para quem já conhece. Não precisa usar laços, arrays, arquivos ou interface gráfica.

## 1 — Boletim da escola (essencial)
Leia o nome completo e três notas de 0 a 10. Implemente calcularMedia(double n1, double n2, double n3). Exiba nome e média com duas casas; não é preciso classificar aprovado/reprovado.
Teste A: Ana Souza; 7.5; 8.0; 9.5 → média 8.33.
Teste B: Bruno; 0; 5; 10 → média 5.00.
Pista: escolha um tipo que aceite frações e reveja o divisor.

## 2 — Lanchonete
Leia quantidade inteira positiva de lanches e preço unitário positivo. Implemente calcularTotal(int quantidade, double preco). Exiba total.
Teste A: 3; 12.50 → 37.50. Teste B: 2; 7.25 → 14.50.
Explique o tipo do resultado de int * double.

## 3 — Painel de temperatura
Leia temperatura em Celsius entre -100 e 100. Implemente converterParaFahrenheit(double celsius), usando F = C × 9/5 + 32. Exiba duas casas.
Teste A: 25 → 77.00. Teste B: -10 → 14.00.
Pista: verifique 9/5 antes de usar a fórmula.

## 4 — Entrega entre bairros
Leia distância positiva em km e velocidade média positiva em km/h. Implemente calcularMinutos(double distancia, double velocidade), com minutos = distância / velocidade × 60. Exiba tempo decimal e quantidade de minutos completos, obtida com cast para int.
Teste A: 10; 40 → 15.00 e 15. Teste B: 3; 25 → 7.20 e 7.
Explique por que minutos completos não são arredondados.

## 5 — Estacionamento
Leia duração inteira não negativa em minutos. Crie calcularHorasCompletas(int minutos) e calcularMinutosRestantes(int minutos), usando divisão e resto.
Teste A: 135 → 2 horas e 15 minutos. Teste B: 59 → 0 horas e 59 minutos.
Não precisa calcular valor a pagar.

## 6 — Loja com desconto
Leia preço positivo e desconto de 0 a 100. Implemente calcularPrecoFinal(double preco, double percentual). Exiba preço final.
Teste A: 150; 10 → 135.00. Teste B: 80; 12.5 → 70.00.
Explique a diferença entre percentual e valor de desconto. Estes são exercícios numéricos, não um sistema financeiro real.

## 7 — Cadastro de moradores
Leia idade inteira não negativa, depois nome completo e altura positiva em metros. Crie montarResumo(String nome, int idade, double altura), retornando uma String. Mostre o resumo.
Teste A: 19; Maria Clara; 1.65 → resumo contendo Maria Clara, 19 e 1.65.
Teste B: 22; João Pedro; 1.80 → resumo contendo João Pedro, 22 e 1.80.
Pista: atenção à troca de nextInt para nextLine. Não perca o sobrenome.

## 8 — Divisão da conta (chefão)
Leia total positivo da conta, número inteiro positivo de pessoas e percentual de serviço de 0 a 100. Crie calcularPorPessoa(double total, int pessoas, double percentual). Inclua o serviço antes de dividir e exiba duas casas.
Teste A: 120; 3; 10 → 44.00 por pessoa. Teste B: 99; 4; 0 → 24.75.
Explique por que converter o resultado de uma divisão inteira não recupera casas decimais.

## Entrega
Veja GUIA_ENTREGA.md. Entregue somente sua pasta com fontes .java e README. Não inclua .class, senhas, dados pessoais ou cópias de soluções de outras pessoas.
No README: usuário GitHub, missões feitas, instruções para rodar, dois testes por missão e respostas ao bilhete de saída.

