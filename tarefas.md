# EET-51 Comunicações II - 4º Laboratório: Multiplexação de Sinais Modulados Digitalmente

## Tarefas

### (a) Geração de Sequências de Bits

- Utilize a função `rand` para gerar quatro sequências de bits pseudo aleatórias contendo 10.000 bits cada uma.

### (b) Ilustração da Técnica FDM

- Gere quatro sinais 2-PAM com pulso retangular de energia unitária para cada sequência de bits.
- Utilize um pulso de largura `Ts` tal que 1/Ts = 4.000 Hz.
- Considere uma frequência de amostragem `Fa` = 224.000 Hz.

### (c) Geração do Sinal Multiplexado na Frequência

- Module os sinais 2-PAM utilizando portadoras com frequências:
  - `f1` = 44.000 Hz
  - `f2` = 52.000 Hz
  - `f3` = 60.000 Hz
  - `f4` = 68.000 Hz.

### (d) Visualização no Domínio do Tempo

- Visualize os três primeiros símbolos de cada sinal.
- Plote os sinais em uma mesma janela para observar a sobreposição.

### (e) Densidade Espectral de Potência

- Utilize a função `periodogram` para visualizar a Densidade Espectral de Potência dos quatro sinais.
- Plote os sinais em uma mesma janela para observar a separação.

### (f) Ilustração da Técnica TDM

- Utilize as quatro sequências de bits para gerar quatro sinais 2-PAM com pulso retangular de energia unitária.
- Os pulsos devem ter duração 4 vezes menor que o do FDM e não se sobreporem.
- Use a mesma frequência de amostragem do item (b).

### (g) Geração do Sinal Multiplexado no Tempo

- Module todos os sinais 2-PAM utilizando uma portadora com frequência `fc` = 56.000 Hz.

### (h) Visualização no Domínio do Tempo para TDM

- Visualize os três primeiros símbolos de cada sinal.
- Plote os sinais em uma mesma janela para observar a separação.

### (i) Densidade Espectral de Potência para TDM

- Utilize a função `periodogram` para visualizar a Densidade Espectral de Potência dos quatro sinais.
- Plote os sinais em uma mesma janela para observar a sobreposição.

### (j) Ilustração da Técnica CDM

- Utilize as quatro sequências de bits para gerar quatro sinais 2-PAM com pulso retangular de energia unitária.
- Utilize um pulso de largura `Ts` tal que 1/Ts = 4.000 Hz.
- Gere quatro sequências de espalhamento utilizando as sequências de bits: 0011101, 0111010, 1110100, 1101001.

### (k) Geração do Sinal Multiplexado no Tempo para CDM

- Module todos os sinais 2-PAM utilizando uma portadora com frequência `fc` = 56.000 Hz.
- Utilize as sequências de espalhamento para codificar os quatro sinais de forma diferente.

### (l) Visualização no Domínio do Tempo para CDM

- Visualize os três primeiros símbolos de cada sinal.
- Plote os sinais em uma mesma janela para observar a sobreposição.

### (m) Densidade Espectral de Potência para CDM

- Utilize a função `periodogram` para visualizar a Densidade Espectral de Potência dos quatro sinais.
- Plote os sinais em uma mesma janela para observar a sobreposição.

### (n) Experimento com Sequências de Espalhamento

- Multiplique uma das sequências de espalhamento pelos quatro sinais e observe o que ocorre no domínio da frequência.


### Tabela XOR

| XOR | 0 | 1 |
|-----|---|---|
| 0   | 0 | 1 |
| 1   | 1 | 0 |

### Tabela MULTIPLICAÇÃO 2-PAM


| PAM | 0 | 1 |
|-----|---|---|
| 0   | 1 | 0 |
| 1   | 0 | 1 |