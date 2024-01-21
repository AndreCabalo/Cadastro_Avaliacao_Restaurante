<p align="center">
  
<img src=https://github.com/AndreCabalo/Cadastro_Avaliacao_Restaurante/assets/103711127/cbb2432c-1e50-415a-972c-a249000d57d5> 
</p>

# Restaurante Manager
Este é um simples projeto Python chamado "Restaurante Manager" que gerencia uma lista de restaurantes, seus estados (aberto ou fechado), categorias, e avaliações atribuídas pelos clientes.

# Estrutura do Projeto
O projeto possui duas classes principais:

- Restaurante
- Avaliacao

# Classe Restaurante

# Atributos de Restaurante:

_nome: Nome do restaurante.

_categoria: Categoria do restaurante.

_status: Estado do restaurante (aberto ou fechado).

_avaliacao: Lista de avaliações atribuídas ao restaurante.

# Métodos de Restaurante:

__init__(self, nome, categoria): Método construtor que inicializa o restaurante e o adiciona à lista de restaurantes.

__str__(self): Método que imprime os dados do restaurante formatados.

listar_restaurantes(cls): Método de classe que lista todos os restaurantes.

status(self): Método de propriedade que retorna o status formatado do restaurante.

alterar_estado(self): Método que altera o estado do restaurante entre aberto e fechado.

receber_avaliacao(self, cliente, nota): Método que atribui uma avaliação a um restaurante.

media_avaliacoes(self): Método de propriedade que calcula a média das avaliações do restaurante.

# Classe  Avaliacao:

# Atributos de Avaliação:

_cliente: Nome do cliente que atribui a avaliação.

_nota: Nota atribuída pelo cliente.

# Métodos de Avaliação:

__init__(self, cliente, nota): Método construtor que inicializa uma avaliação.

# Execução do Projeto

O script principal (app.py) demonstra a utilização das classes, criando instâncias de restaurantes, alterando seus estados, recebendo avaliações e listando todos os restaurantes com suas informações.

# Como Executar
Certifique-se de ter o Python instalado em seu sistema.

Clone este repositório.

Navegue até o diretório do projeto.

Execute o arquivo app.py para ver a saída do programa.

Sinta-se à vontade para expandir este projeto adicionando mais funcionalidades, melhorando a interface do usuário ou implementando recursos adicionais. 

Divirta-se codificando!
