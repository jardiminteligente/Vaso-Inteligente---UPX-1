# Algoritmo 02 - Monitoramento de Umidade

Resumo: Monitora a umidade do solo e envia alerta caso esteja abaixo do limite definido para a planta.

## Entradas
- `umidade_raw` (valor do sensor)  
- `umidade_minima` (definida pelo tipo de planta)

## Saídas
- `alerta_umidade_baixa` (boolean)  
- Registro no histórico

## Pseudocódigo
```
INÍCIO
   umidade = ler_sensor()
   se umidade < umidade_minima:
       enviar_alerta("Solo seco - regar planta")
FIM
```

Autores:  
- Alice Coelho Pereira Leite  
- Alexssandro Gabriel de Almeida Silva  
- Erick Arruda Rodrigues  
- Arthur Scatena de Souza  
- Eduardo Gabriel Diniz Aiasi
