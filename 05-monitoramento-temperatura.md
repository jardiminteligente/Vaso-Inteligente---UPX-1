# Algoritmo 05 - Monitoramento de Temperatura

Resumo: Monitora a temperatura ambiente e do solo e envia alerta caso esteja abaixo do limite definido para a planta selecionada.

## Entradas
- `temperatura_ambiente` (°C)  
- `temperatura_solo` (°C)  
- `temperatura_minima`

## Saídas
- `alerta_temperatura` (boolean)  
- Registro no histórico

## Pseudocódigo
```
INÍCIO
   temp_amb = ler_sensor_ambiente()
   temp_solo = ler_sensor_solo()
   se temp_amb < temperatura_minima:
       enviar_alerta("Temperatura ambiente abaixo do recomendado")
   se temp_solo < temperatura_minima:
       enviar_alerta("Temperatura do solo abaixo do recomendado")
FIM
```

Autores:  
- Alice Coelho Pereira Leite  
- Alexssandro Gabriel de Almeida Silva  
- Erick Arruda Rodrigues  
- Arthur Scatena de Souza  
- Eduardo Gabriel Diniz Aiasi
