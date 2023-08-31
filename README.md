# ProjetoHeuristica
Arcabouço Python para codificação de algoritmos heurísticos para solução de problemas de PO.

Este projeto está baseado no problema do caixeiro viajante (PCV).

O programa aqui apresentado NÃO resolve o problema PCV, mas deixa definido um arcabouço de Entrada->Processamento->Saída em python.

- No diretório raiz encontram-se:
(1) Esse arquivo `README.md`
(2) Diretório `bin` com o arquivo executável acompanhado de diretórios e arquivos de configuração necessários à sua execução
(3) Diretório `src` com todos os arquivos fontes (sources) do programa organizados em subdiretórios

- Para executar o programa deve-se ter o Python 3 instalado em sua máquina e seguir os comentários a seguir.

Ir ao diretório `bin` e executar o arquivo `executavel.py`

$ python executavel.py

junto com o arquivo `executar.config` e a estrutura de diretórios `INPUT` e `OUTPUT`.

O arquivo `executar.config` contém os parâmetros que definem uma rodada de execução como, por exemplo, critérios de parada (tempo máximo, ou número máximo de iterações), algoritmos a serem executados, etc.

O diretório VINPUT" deve conter o arquivo `input.config` que lista as instâncias a serem resolvidas na rodada (nome dos arquivos `.dat`) de execução e os arquivos `.dat` com as informações que definem a instância.

O diretório `OUTPUT` é criado pelo próprio programa caso ele não exista. Nele aparecerão todas as soluções e saídas do programa após, ou durante, a sua execução.
