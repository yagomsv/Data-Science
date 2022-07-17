![image](https://user-images.githubusercontent.com/101029639/179421190-da45785a-52d2-4a23-946d-21fbcf138653.png)

## Projeto: Previsão de sucesso de campanha de Marketing (Banco)
As campanhas de <i>marketing</i> e venda constituem uma estratégia típica para potencializar negócios. As empresas utilizam dessas campanhas para atingir metas espefícicas, como por exemplo, a venda de um produto.

Nesse estudo de caso será utilizado dados de uma campanha de <i>telemarketing</i> feita para um banco Português para vender depósitos bancários de longo prazo. Os dados foram coletados entre os<b> anos de 2008 e 2013</b>. O banco de dados possui 16 variáveis independentes e uma variável dependente, descritas abaixo.

O estudo de caso consistiu primeiramente em realização uma análise exploratória dos dados, afim de extrair insights sobre o negócio e posteriomente foi realizada a criação de um modelo de classificação baseado na técnica de <b>Florestas Aleatórias</b>, que classifica quais os clientes farão ou não o depósito bancário. Este modelo poderá ser utilizado futuramente em campanhas de <i>marketing</i>, para que seja definido melhor o publico alvo das campanhas, otimizando assim os custos operacionais desse tipo de capitação de clientes.

<b>Descrição das variáveis:
  - <b>Variáveis de entrada</b>
    - Age: Idade do cliente
    - Job: Profissão do cliente
    - marital: Estado civil
    - education: Nível educacional
    - default: Inadimplência do cliente
    - housing: Empréstimo imobiliário
    - loan: Empréstimo pessoal
    - contact: Tipo de comunicação feita
    - month: Mês do último contato
    - day_of_week: Dia do último contato
    - duration: Duração do último contato
    - campaign: Número de ligações feitas ao cliente durante a campanha
    - pdays: Número de dias passado depois que o cliente foi contactado pela última vez em campanha anterior
    - previous: Número de contatos realizados antes desta campanha e para este cliente
    - poutcome: Resultado da campanha anterior
    - balance: Saldo em conta bancária
- <b>Variável de saída</b>
    - O cliente realizou o depósito bancário (Investimento)? sim/não

### Ferramentas e dados utilizados:
- <b> Manipulação, limpeza e análise exploratória dos dados:</b> Pandas, Numpy, missingno, scipy, imbalanced-learn;
- <b> Visualização dos dados:</b> matplotlib, seaborn;
- <b><i> Machine Learning:</b></i> Classificação (scikit-learn)
- <b> Fonte dos dados:</b> https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
