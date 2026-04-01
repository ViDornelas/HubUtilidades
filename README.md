# Hub de Utilidades — Android

## Aluno
**Vinícius Silva Dornelas**

---

## Descrição

O **Hub de Utilidades** é um aplicativo Android desenvolvido em Java que centraliza quatro ferramentas distintas em um menu principal. O objetivo é exercitar navegação entre Activities via Intents, passagem de parâmetros, persistência de estado e lógica condicional.

---

## Funcionalidades

### 🎰 Mega-Sena
Gera números aleatórios únicos para apostas. O usuário escolhe entre 6, 7 ou 8 dezenas. Os números são ordenados e exibidos formatados.

### ⚖️ Calculadora de IMC
Calcula o Índice de Massa Corporal com base no peso (kg) e altura (m) informados. Exibe o valor numérico e a classificação (Abaixo do peso, Peso normal, Sobrepeso, Obesidade I/II/III).

### ✊ Jokenpô
Jogo de Pedra-Papel-Tesoura no formato melhor de 3. O PC escolhe aleatoriamente. O placar é mantido em tela e há botão de reinício.

### 😊 Questionário da Felicidade
Módulo exclusivo com cálculo ponderado:
- **Sono (S):** 0-3h = 1pt | 4-8h = 3pts | 9-12h = 2pts  
- **Estresse (E):** 0-3 = 3pts | 4-7 = 2pts | 8-10 = 1pt  
- **Fórmula:** `Felicidade = [(S + E) / 6] × 10`

**Classificações:**
| Pontuação | Classificação         |
|-----------|-----------------------|
| 0.0 – 2.0 | Muito Baixa (Alerta)  |
| 2.1 – 4.0 | Baixa (Precária)      |
| 4.1 – 6.0 | Moderada (Neutra)     |
| 6.1 – 8.0 | Alta (Bom equilíbrio) |
| 8.1 – 10.0| Plena (Ideal)         |

---

## Navegação

Todos os botões "Voltar" e o botão Back do Android retornam ao Menu Principal (`MainActivity`) usando `FLAG_ACTIVITY_CLEAR_TOP`, evitando acúmulo de Activities na pilha.

---

## Tecnologias

- **Linguagem:** Java  
- **SDK Mínimo:** Android 7.0 (API 24)  
- **Target SDK:** Android 14 (API 34)  
- **UI:** XML Layouts com Material Components  

---

## Como compilar

1. Abra o projeto no **Android Studio**
2. Aguarde a sincronização do Gradle
3. Clique em **Run** ou gere o APK em `Build > Build APK`
