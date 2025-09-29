# Algoritmo 04 - Histórico de Dados

Resumo: Registra os valores de umidade e temperatura ao longo do tempo para análise no aplicativo.

## Entradas
- `umidade`  
- `temperatura`  
- `timestamp`

## Saídas
- Registro salvo (JSON/CSV)  
- Envio ao aplicativo

## Pseudocódigo
```
INÍCIO
   a cada INTERVALO:
       umidade = ler_sensor_umidade()
       temperatura = ler_sensor_temperatura()
       salvar(timestamp, umidade, temperatura)
       enviar_dados_para_app()
FIM
```

Autores:  
- Alice Coelho Pereira Leite  
- Alexssandro Gabriel de Almeida Silva  
- Erick Arruda Rodrigues  
- Arthur Scatena de Souza  
- Eduardo Gabriel Diniz Aiasi
