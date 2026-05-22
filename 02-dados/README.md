# 02 - Dados

## Decisão: dados não foram incluídos neste repositório

Apesar dos CSVs serem essenciais pra reprodução completa da análise, optei 
por não incluí-los neste repositório público pelos seguintes motivos:

### 1. Confidencialidade dos dados
Os dados, mesmo anonimizados (IDs como "USER_123" e "Loja 001"), são 
propriedade da Méliuz e contêm informações de negócio sensíveis: volumes 
de transação, comportamento de saída de usuários e performance por parceiro. 
Expor isso publicamente seria inadequado independente de autorização explícita.

### 2. Princípio de menor privilégio
Como o avaliador da Méliuz já possui os arquivos originais, não há benefício 
em duplicar a exposição. A análise deste repositório pode ser auditada sem 
acesso aos CSVs aqui.

### Caso seja necessário rodar localmente
Coloque os 6 CSVs nesta pasta, com nomes originais, e os scripts da pasta 
`04-analise/` funcionarão normalmente.

## Alternativas que considerei e descartei

| Opção | Por que descartei |
|---|---|
| ZIP com senha | Tamanho continua excedendo limite (430MB) |
| Git LFS | Complexidade técnica sem retorno proporcional |
| Repositório privado | Quebra a auditabilidade rápida pelo avaliador |
| Storage externo | Adiciona infraestrutura sem necessidade |

A decisão de manter o repositório enxuto e público, com dados confidenciais 
fora dele, foi consciente.
