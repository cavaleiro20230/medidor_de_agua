# medidor_de_agua
Sistema de Monitoramento de Água




## Explicações sobre a Configuração de Caixas d'Água

Adicionei um sistema completo para configuração de diferentes capacidades de caixas d'água, permitindo maior flexibilidade e precisão no monitoramento do seu sistema.

### Principais Melhorias Implementadas

#### 1. Seleção de Modelos Padrão

- **Modelos pré-configurados**: Adicionei uma lista de tamanhos comuns de caixas d'água (500L, 1.000L, 1.500L, 2.000L, 3.000L, 5.000L, 10.000L)
- **Opção personalizada**: Possibilidade de definir capacidades específicas para atender qualquer necessidade
- **Interface intuitiva**: Menu dropdown para seleção rápida do modelo desejado


#### 2. Suporte para Múltiplas Caixas

- **Configuração de caixas secundárias**: Monitoramento de mais de uma caixa d'água simultaneamente
- **Visualização independente**: Cada caixa tem seu próprio indicador de nível e alertas
- **Detecção de transferência**: O sistema pode identificar quando água está sendo transferida entre caixas


#### 3. Calibração Avançada

- **Calibração automática**: Função para medir a altura real da caixa e ajustar o sensor
- **Diferentes tipos de sensores**: Suporte para sensores ultrassônicos, boias elétricas e sensores de pressão
- **Ajuste de altura**: Configuração da altura física da caixa para cálculos mais precisos


#### 4. Armazenamento Persistente

- **Salvamento na EEPROM**: Todas as configurações são armazenadas na memória não-volátil
- **Múltiplos perfis**: Cada caixa tem suas próprias configurações salvas
- **Recuperação automática**: O sistema carrega as configurações ao iniciar


### Como Utilizar

1. **Configurar Capacidade da Caixa**:

1. Acesse a aba "Configurações"
2. Selecione um modelo padrão ou escolha "Personalizado"
3. Se personalizado, insira a capacidade exata em litros



2. **Configurar Múltiplas Caixas**:

1. Ative a opção "Configurar múltiplas caixas"
2. Defina a capacidade da caixa secundária
3. Monitore os níveis de ambas as caixas na aba "Caixa d'Água"



3. **Calibrar Sensores**:

1. No programa Arduino, use a função de calibração automática
2. O sistema fará múltiplas leituras para determinar a altura correta
3. Confirme a calibração para salvar os valores





### Benefícios Práticos

1. **Maior Precisão**:

1. Cálculos de volume baseados na capacidade real da caixa
2. Alertas personalizados para cada tamanho de reservatório
3. Monitoramento mais preciso do consumo



2. **Versatilidade**:

1. Adaptável a qualquer configuração de caixas d'água
2. Ideal para residências, comércios e indústrias
3. Suporte para sistemas com caixas de diferentes tamanhos



3. **Facilidade de Uso**:

1. Interface intuitiva para configuração
2. Seleção rápida de modelos comuns
3. Visualização clara dos níveis e volumes





Esta implementação torna o sistema muito mais versátil, permitindo que você configure exatamente o tipo e tamanho de caixa d'água que possui, garantindo medições precisas e alertas adequados para sua instalação específica.
