# libft

A *libft* é uma biblioteca personalizada desenvolvida como parte do currículo da [Escola 42](https://www.42network.org/). Ela contém implementações de funções fundamentais em C, que são utilizadas para manipulação de strings, alocação de memória, e manipulação de arquivos, entre outras.

## Objetivo

O objetivo do projeto é criar uma biblioteca com várias funções úteis que podem ser usadas em projetos futuros. Durante o desenvolvimento, o foco é entender como as funções padrão do C funcionam e como elas podem ser implementadas manualmente de maneira eficiente e segura.

## Funcionalidades Implementadas

A *libft* inclui funções de diferentes áreas, tais como:

### Manipulação de Strings
- `ft_strlen`: Calcula o comprimento de uma string.
- `ft_strcpy`: Copia uma string de origem para uma string de destino.
- `ft_strncpy`: Copia até um número específico de caracteres de uma string de origem para uma de destino.
- `ft_strcmp`: Compara duas strings.
- `ft_strchr`: Localiza a primeira ocorrência de um caractere em uma string.
- `ft_strstr`: Localiza a primeira ocorrência de uma substring dentro de uma string.

### Manipulação de Memória
- `ft_memset`: Preenche uma área de memória com um valor específico.
- `ft_bzero`: Preenche uma área de memória com zero.
- `ft_memcpy`: Copia uma área de memória de origem para destino.
- `ft_memmove`: Move uma área de memória de origem para destino de maneira segura.
- `ft_memcmp`: Compara duas áreas de memória.

### Conversões e Auxiliares
- `ft_atoi`: Converte uma string para um inteiro.
- `ft_isdigit`: Verifica se um caractere é um dígito.
- `ft_isalpha`: Verifica se um caractere é uma letra.
- `ft_isalnum`: Verifica se um caractere é alfanumérico.
- `ft_toupper`: Converte um caractere para maiúsculo.
- `ft_tolower`: Converte um caractere para minúsculo.

### Funções Adicionais
- `ft_putnbr`: Imprime um número inteiro na saída padrão.
- `ft_putchar`: Imprime um caractere na saída padrão.
- `ft_putstr`: Imprime uma string na saída padrão.
- `ft_putendl`: Imprime uma string seguida de uma nova linha.

## Como Compilar

1. Clone o repositório:
   ```bash
   git clone https://github.com/eliandrosergio/libft.git
   cd libft
   cd libft
   make
