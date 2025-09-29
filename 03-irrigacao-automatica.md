# Algoritmo 03 - Irrigação Automática

Resumo: Aciona a bomba de água quando a umidade estiver abaixo do limite para a planta selecionada.

## Entradas
- `umidade_raw`  
- `umidade_minima`

## Saídas
- Acionamento da bomba de água

## Pseudocódigo
```
INÍCIO
   umidade = ler_sensor()
   se umidade < umidade_minima:
       ativar_bomba()
       aguardar TEMPO_IRRIGACAO
       desligar_bomba()
FIM
```

Autores:  
- Alice Coelho Pereira Leite  
- Alexssandro Gabriel de Almeida Silva  
- Erick Arruda Rodrigues  
- Arthur Scatena de Souza  
- Eduardo Gabriel Diniz Aiasi
