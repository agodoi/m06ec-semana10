# Aula: Engenharia de Áudio Aplicada ao Amplificador Montado em Laboratório

## 1. O que é um sistema de áudio?

### Fluxo completo

Fonte sonora → Microfone → Pré-amplificador → Amplificador de potência → Alto-falante → Ouvido

> O circuito montado por vocês representa apenas uma parte da cadeia.

### Tópicos

* Onde o sinal nasce?
* Onde ele é amplificado?
* Onde a energia elétrica vira som?
* Por que há fontes de áudio melhores que outras (Zin / Zout)?


# 2. O que significa "som de qualidade"?

> Por que duas caixas de som podem tocar a mesma música e soar completamente diferentes?


### Fidelidade

Capacidade de reproduzir o som original.

### Distorção

O amplificador altera o sinal.

### Ruído

Sons indesejados adicionados ao sinal.

### Resposta em frequência

Capacidade de reproduzir graves, médios e agudos.

# 3. Frequência e percepção humana

### Faixa auditiva

20 Hz a 20 kHz

<img src="https://images.openai.com/static-rsc-4/_A-IVoGjmmNAxaq-bui_iDxzUz94jpDEHGMtzYPHP1YvpJgqO4RxgC3qechnHwH8mwHt6dBmM5TXhl-HI_RMZHKvUyCpPWVk7a9yg7Dkg8Zy0zwhsyHveNfAZQMOlOOQDBidoSA0QXRxwO7WFq1jU4ccMi12z1S35DgLzjgIv4odcd-w0rHc2FTGCNK3oF9R" width="400">


<img src="https://images.openai.com/static-rsc-4/F6wwlGptEjPV4NTyoHc_gcY0SS9NeUtLDsMEP0xV77CeN2ICSJKOnhInTD3XBbWl5clQc1L2VB0Omnq0Kn8gnWI08bS46Th0YF8O07Qmvow8QUdAzruV_FVhAoa6DvVDwkmnZsVZA-jx4z-aD4DPSwr-vKhKZKyPi1fhKAtkHgOCAEHS3047BgNvjUEuwCSu" width="400">

<img src="https://images.openai.com/static-rsc-4/ZjPbR9J2eGIv_i3Almny4Z-UVF_aQnuGyAUxTfNcktlWBxuhAqVXEj7zLE6qfJRy2jOLlGdEqm2k6Ex8Nh7B1w4s1kzgSiqO_oe-9ChIIm5IXp4U6Oya1BeoGqerM2ylAppDWo0P1-SuhZGRP2M0UKuj7C5f6pzCYAwmBG2gTt-Pbast0LXSbB7KZtUGFmc-" width="400">

<img src="https://images.openai.com/static-rsc-4/nESK4HP9MmLHlXYV5CFWl-MyEg6zPL2amjkw_JqTBGnKN6nxMqNXOwGi2rTqtEfIZbGUtoH4NpgNFr1QiK1YRilDm58vGlRVJWyHrIbtzHaSAHtRW3gxj-ZO3DmhliTvlguLtMZj6NZjLj8PCES2A2rCVcnE-k89UJuxvzCArb60IGNpwwSBAcsBTi0oaZ-J" width="400">

<img src="https://images.openai.com/static-rsc-4/d03gNLEPvOWq6LAZc6nGx-0PwSUv_izVjZBALHttcRwqvynTiiPo1IPGEzmfTRYhijqLFUXwYZkSgUzKQ_qzmyXbCpq-fYWCjew7aQDjNcR-Lzx5DInQkbaCWPNrEfRNgWGPqwQPDmPRb-R8NbaoR6azHoLl5F-XzdcLGIYx_Gz9OCUchzwBMA2Gt1AEGdDl" width="400">

### Relação

* Grave → 20 Hz a 250 Hz
* Médio → 250 Hz a 4 kHz
* Agudo → acima de 4 kHz

### Experimento

Gerador de funções:

* 50 Hz
* 500 Hz
* 5 kHz
* 15 kHz

> Como o som muda?


# 4. O amplificador realmente amplifica?

Aproveitar a medição feita no roteiro.

### Fórmula

Av = Vout / Vin

Observe que:

* Se Av = 1 → não amplifica
* Se Av = 10 → amplifica 10 vezes

### Exemplo

Vin = 0,2V

Vout = 2V

Av = 10



# 5. Ganho em decibéis

Unidade utilizada na indústria.

### Fórmula

G(dB) = 20·log(Vout/Vin)

### Exemplo

Vout/Vin = 10

G = 20 dB

Mostrar:

| Ganho        |
| ------------ |
| 2x = 6 dB    |
| 10x = 20 dB  |
| 100x = 40 dB |


# 6. Potência de áudio

Conexão direta com o item 3 do relatório prático.

### Fórmula

P = V × I

### Exemplo do roteiro

Sem áudio:

P = 12 × 0,02

P = 0,24W

Com áudio:

P = 12 × 0,2

P = 2,4W

> Para onde foi essa potência?

Resposta:

* Alto-falante
* Aquecimento
* Perdas nos transistores

# 7. Por que um amplificador esquenta?

### Potência dissipada

P = VCE × IC

Aplica-se em um transistor do circuito.

Parte da energia vira:

* Som
* Calor


# 8. O que é clipping?

Observe as formas de onda do osciloscópio do roteiro. 

<img src="https://images.openai.com/static-rsc-4/g_yksmZxPkQpkKtVFLilYH5OmhpE05msFUCwKGRRdMI_BOGvgfCelyDj2gq6uD5oFRjbyVYDgwiiYT9XfOyKAF1yWd8KabmQxe3IILm5EbKlLbvg7AMkHvRRkCiCpM_BTGQb2mrk8VbAfA74nVMQL4yRDTqg41Ft6qGPVG7HJIe0x0mLXbtQDByput9pqCuB" width="400">

<img src="https://images.openai.com/static-rsc-4/PPYXAVpd-zcjaiLLnAozzU1sGettnTuNybLXAobaMgELLeVf4vpJhxWzLygLW85xKnSYvrXNUhIMe418gv14QAFTX9UAu00F5t9zKCrK_hylDQZVfczz6W2G22eGRLJMmENXDz8krcoWK7p0qXNXpfRaCUmgItpIzSWn0uMyl0QNeIF1WjVYQ7oo_b-IogPO" width="400">

<img src="https://images.openai.com/static-rsc-4/6DPF7ywHMAmiMCaySDKiA7DeIM28I0wYsWRoR79LzJW1tG-T0mVjp9I-TttDRJT6wb7AKB1KKfDtoTug5yaeRI32d6kUxItYzLzUt9LqopStN6tL4CMdBrHgb7lbN6QOQIPS9NcuaIdrS0xJiI2XHln-eHtiOIVP4_OBJ9KBUkSiUBE2vsI8X4hvecVOis_h" width="400">

<img src="https://images.openai.com/static-rsc-4/HqXpVs2HQhfr_-Yxi_FilGOR1ZWCp0svXFbzz6vfUO3JIrymy3qzREiNp_BBsx27te9NstumgkKh4C_IuTMbQhUiFjkM0I3VwSe1PGQw0G59qqhgWPDRx9vWcqcNq5sk49iZjUBsAR0mI6NDl_ml0IU-sKqMbflWYG9AYNHK-pJpvY8QefIQSD1DXZzTYT4V" width="400">

<img src="https://images.openai.com/static-rsc-4/r30eIpm-wmH5zJEgV7deh5WYP0pYL_t8G-2a0RRIDnrZNQ-9M_lDTFHkHu_NVX2bOILriM2vqZ_PNSrwQZA_3Gijo2U-Le8xALBj_waYNqlY6YVKEV8pmZr2NA3RntZ8fwzVu9nKxsmCx9_N6gAiJe_pJfI9ehRjALdsXA6HHKgAWHeEF7b5-Q8FYbE5XniF"  width="400">


### Observe

Senoide normal

↓

Volume excessivo

↓

Topo achatado

↓

Clipping

### Consequências

* Som desagradável
* Distorção
* Aquecimento do alto-falante


# 9. Por que existem caixas de som diferentes?

Esse é um tema que chama a atenção.

### Compare

<img src="https://images.openai.com/static-rsc-4/kOhm-UXHhXWxgUVdc5FVa6HYQE_nhErshIgZH5yEhgY3jCKaRilNk8UIkzmtxdghSITdyzdcloWTV23IazFn0dzCXRhy44SvAAOGxWygXSQhQgLTvgwra4jUWPxd_R5a4vLfcRBL1JnrbkQYGFwezSLY5-6Df-gMlXpBDEisPwdG_3AitPLXwDqslQ7RO7fV" width="400">

<img src="https://images.openai.com/static-rsc-4/Xj-pqveP3fGswA5UvbtxV1QrG9iyegI-RGKFmDojAcYjCtn_3pl70r1oc7klqOioiJ-Do8hpAsr6zXA5Tc3Ze-cUWuJDis1_XWN2OuAg-BVqhZ700HDNe_-_t4hn6-vqKvx_ZU7dp3tbBRabkMjJUz7Rs5-XB2vhwZZOfWNyUzoc1j0c4B3yekJnjLd2Iwem" width="400">

<img src="https://images.openai.com/static-rsc-4/PTnuFfmm_HYIPbrRdKH5GIpMDzoiWY3jCv2_GWZLakijAeB3vTVVnQOf1JHs7c3HjgKKSWUW9rI0gQOkA5KoNEvNVIpS76-6aDhLwtFYr9-C-ySzszzkn5YbuTfm6XptzAFYO90FaNxRObLltNUgmeKe4_-tlfGNvBC5u74lkfoNqWUES4Sj6GpWF1MHj5i2" width="400">

<img src="https://images.openai.com/static-rsc-4/I2dE0arIc72DJ4_qA6-8vN8KGbk2EbijZcNhmIN2PAEj_ae_2TmKBB2s5W4niWhvdkfYFnDeAhQBEF9p2oAdS58N3VtfbQ98oPponyNcrkS5Ivg93VlZBrYOvSQ-THGcmiyJJ0UBMUqEJtXsNfeKUJRCsqp1QddHG0niAiTg38QAc_L2m2yejti5kIy09rQI" width="400">

### Woofer

Graves

### Tweeter

Agudos

### Subwoofer

Subgraves

### Caixa 3 vias (nosso caso)

Cada alto-falante trabalha em uma faixa.

<img src="https://github.com/agodoi/m06ec-semana10/blob/main/assets/altofalante.png" width="400">


# 10. Por que a caixa influencia tanto?

Conceito muito importante.

### Sem caixa

As ondas frontal e traseira se cancelam.

### Com caixa

A energia sonora é direcionada.

### Tópicos para discussão

* Caixa selada
* Bass reflex
* Caixa acústica profissional


# 11. Eficiência do alto-falante

Pergunta:

> Dois alto-falantes de 10 W tocam igual?

### Sensibilidade

Exemplo:

* 85 dB/W/m
* 92 dB/W/m

A diferença percebida é enorme.


# 12. Impedância do alto-falante

### 4 Ω

### 8 Ω

Lei de Ohm:

I = V/R

Menor impedância:

* maior corrente
* maior potência
* maior aquecimento


# 13. Matemática do som

### Comprimento de onda

λ = v/f

Exemplo:

f = 100 Hz

v = 343 m/s

λ = 3,43 m

Note que:

* Graves possuem ondas gigantes
* Agudos possuem ondas curtas

Isso explica o tamanho dos subwoofers.


# 14. Engenharia reversa do próprio circuito

Perguntas:

* Onde está o pré-amplificador?
* Onde está o ganho?
* Onde está o estágio de potência?
* Qual transistor fornece corrente ao alto-falante?
* Onde ocorre maior dissipação?


# Encerramento

### Grande pergunta

> Por que um amplificador de áudio de qualidade custa muito mais caro que apenas um circuito que amplifica?

* Eletrônica analógica
* Potência
* Acústica
* Psicoacústica
* Processamento de sinais
* Projeto mecânico de caixas acústicas
