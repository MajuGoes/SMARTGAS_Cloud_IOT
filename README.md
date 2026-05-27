# SMARTGÁS: Sistema Controlador de Vazamento de Gás

> Projeto de Extensão 2026.1 — Aplicação de Cloud, IoT e Indústria 4.0 em Python
> **Instituição:** UNIRUY Wyden
> **Orientador:** Prof. Heleno

---

## 👥 Componentes da Equipe
* **Maria Julia Sousa de Aquino Goes - 202402961063**
* **Fagner Amado Lima - 202212050264**
* **Arthur Miranda de Oliveira - 202402408224**

---

## 📝 Contextualização e Justificativa do Projeto

O envelhecimento da população brasileira aponta para uma transformação estrutural profunda na composição da nossa sociedade. Segundo dados consolidados do Censo Demográfico de 2022 e as atualizações trazidas pela Pesquisa Nacional por Amostra de Domicílios Contínua (PNAD Contínua) do IBGE, o Brasil possui hoje mais de **5,6 milhões de idosos residindo em lares unipessoais**. Esse contingente representa o maior grupo demográfico entre todas as pessoas que vivem sozinhas no país, totalizando quase 29% dessas residências.

Esse fenômeno social evidencia uma mudança comportamental louvável: a busca ativa pela autonomia e independência na terceira idade. No entanto, o isolamento residencial traz consigo riscos invisíveis. Estudos epidemiológicos publicados na plataforma SciELO acendem um alerta crítico sobre a alta letalidade das intoxicações por gases em ambientes domésticos. 

Para o idoso que vive só, o perigo iminente é potencializado pela ausência de redes de apoio imediatas e, principalmente, pelo declínio sensorial biológico decorrente do envelhecimento, como a perda natural das percepções olfativa e auditiva. Sem a capacidade plena de sentir o odor característico do gás ou de ouvir pequenos escapes, esses cidadãos tornam-se severamente vulneráveis a exposições tóxicas prolongadas.

O **SMARTGÁS** surge como uma resposta tecnológica para mitigar as lacunas de segurança geradas pelas limitações sensoriais e pelo isolamento dos idosos, atuando como uma barreira técnica de proteção ativa nos exatos momentos em que os sentidos humanos falham, garantindo que a vida independente seja vivenciada com total liberdade e segurança.

## 🛠️ Lista de Componentes Utilizados

| Identificador | Qtd | Componente | Função Principal no Ecossistema |
| :---: | :---: | :--- | :--- |
| **U1** | 1 | Arduino Uno R3 | Processamento central da lógica e comandos do sistema. |
| **GAS1** | 1 | Sensor de Gás | Monitoramento contínuo da concentração de gás no ar ambiente. |
| **SERVO1** | 1 | Posicional Micro Servo | Atuador mecânico para fechamento automatizado do registro. |
| **PIEZO1** | 1 | Piezo (Buzzer) | Alarme acústico de alta intensidade para aviso de emergência. |
| **D1** | 1 | LED Vermelho | Sinalização visual complementar de estado de atenção. |
| **S1** | 1 | Botão (Push-Button) | Mecanismo manual de reset e rearme seguro do sistema. |
| **R1-R3** | 3 | Resistores (10kΩ, 1kΩ, 200Ω) | Proteção elétrica e estabilização de sinal dos pinos digitais. |

## 💻 Simulação Virtual do Circuito
O circuito elétrico e toda a engenharia de arquitetura de hardware foram validados e simulados virtualmente na plataforma Tinkercad.

* 🔗 **Link da Simulação Interativa:** [Acessar Projeto no Tinkercad](https://www.tinkercad.com/things/7GDlxybwOON-spectacular-blorr/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=qpL7NQGQss3GHhnVN6XvzKXSvgP7-TFcaSZU9Ni3MmE)

* 🔗 **Link da Apresentação no Canva:** [Acessar Apresentação SMARTGAS](https://canva.link/o3i51dbqhbenask)
