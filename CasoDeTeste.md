## 🧪 ID: 001

### ✅ Nome do Teste: Cadastro de cadáver 


### 🎯 Descrição:
  Verificar se o sistema permite cadastrar um corpo com os dados necessários válidos


### 🧰 Pré-requisitos:
-  Usuário deve estar na tela de cadastro
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com dados válidos
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | Lucas William          |
| Idade            | 31                     |
| Data chegada     | 01/06/2025             |
| Causa da morte   | Inanição emocional     |

### 💡 Resultado Esperado:
O cadáver deve ser cadastrado e o usuário redirecionado para a página inicial com a mensagem "Cadastro realizado com sucesso".)

### 📌 Resultado Obtido:


### ✅ Status do Teste:
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 002

### ✅ Nome do Teste: Consulta de corpos armazenados 


### 🎯 Descrição:
  Verificar se o sistema permite buscar os corpos armazenados no necrotério na data específica


### 🧰 Pré-requisitos:
-  Usuário deve estar na tela de busca
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de busca
2. Preencher os campos obrigatórios com dados válidos
3. Clicar no botão "Buscar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste        |
|------------------|-----------------------|
| Data             |   01/02/1998          |
| Hora             |   15:00:00            |

### 💡 Resultado Esperado:
Deve apresentar uma lista com os cadáveres que estavam no necrotério até esta data e hora específica 

### 📌 Resultado Obtido:


### ✅ Status do Teste:
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 003

### ✅ Nome do Teste: Controle de liberação de corpos


### 🎯 Descrição:
  Verificar se o sistema permite arquivar cadastro de um corpo com os dados necessários válidos


### 🧰 Pré-requisitos:
-  Usuário deve estar na tela de cadastro
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com dados válidos
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste        |
|------------------|------------------------|
| Nome             | Lucas William          |
| Idade            | 31                     |
| Data chegada     | 01/06/2025             |
| Causa da morte   | Inanição emocional     |

### 💡 Resultado Esperado:
O cadáver deve ser cadastrado e o usuário redirecionado para a página inicial com a mensagem "Cadastro realizado com sucesso".)

### 📌 Resultado Obtido:
O cadáver foi cadastrado com sucesso e redirecionado corretamente

### ✅ Status do Teste:
- [ ] Aprovado
- [ ] Reprovado

---

