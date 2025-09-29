# Algoritmo 01 - Seleção de Planta

Resumo: Define os parâmetros de irrigação e temperatura mínima recomendada conforme a planta selecionada pelo usuário.

## Entradas
- `tipo_planta` (ex.: suculenta, rosa, cacto)

## Saídas
- `umidade_minima` (%)
- `temperatura_minima` (°C)

## Exemplo de Configuração
| Planta     | Umidade mínima | Temperatura mínima |
|------------|----------------|------------------|
| Suculenta  | 10%            | 20°C             |
| Cacto      | 5%             | 25°C             |
| Rosa       | 40%            | 18°C             |

## Pseudocódigo
```
INÍCIO
   tipo_planta = entrada_usuario()
   se tipo_planta = "Suculenta":
       umidade_minima = 10
       temperatura_minima = 20
   senão se tipo_planta = "Cacto":
       umidade_minima = 5
       temperatura_minima = 25
   senão se tipo_planta = "Rosa":
       umidade_minima = 40
       temperatura_minima = 18
   fim se
FIM
```

Autores:  
- Alice Coelho Pereira Leite  
- Alexssandro Gabriel de Almeida Silva  
- Erick Arruda Rodrigues  
- Arthur Scatena de Souza  
- Eduardo Gabriel Diniz Aiasi
