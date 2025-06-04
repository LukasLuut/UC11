# 📋 PLANO DE TESTE - [Fossas da Desgraça. “Não enterramos só corpos, enterramos histórias.”]

---

## 1. 🎯 Objetivo dos Testes


### Garantir que o sistema consiga: 
- Cadastrar corpos no necrotério
- Consultar corpos armazenados
- Controle de liberação de corpos
- Notificar prazo de permanencia
  

Validando a experiência do usuário e a precisão do sistema.

---

## 2. 📦 Escopo dos Testes

### ✔️ O que será testado

Liste aqui todas as funcionalidades que serão testadas:

| Funcionalidade                  | Descrição                                                     |
|---------------------------------|---------------------------------------------------------------|
| Cadastrar corpos no necrotério  | Usuário poderá registrar a entrada de um corpo                |
| Consultar corpos armazenados    | Mostrar quantos corpos estão no necrotério em determinado dia |
| Controle de liberação de corpos | Registrar a liberação de um corpo para a família              |
| Notificar prazo de permanencia  | Notificar quando um corpo ultrapassa o prazo máximo permitido |

### ❌ O que **não** será testado

Liste funcionalidades que estão fora do escopo deste plano de teste:

| Funcionalidade fora do escopo  | Justificativa                                         |
|--------------------------------|-------------------------------------------------------|
| Edição de registro             | necessário verificar a segurança dessa funcionalidade |
| Teste de carga                 | Fora do escopo por falta de ferramentas               |

---

## 3. ✅ Critérios de Sucesso

Especifique os critérios para considerar o teste como **bem-sucedido**:

| Funcionalidade                  | Descrição                                                                   |
|---------------------------------|-----------------------------------------------------------------------------|
| Cadastrar corpos no necrotério  | Usuário registra com sucesso a entrada de um corpo                          |
| Consultar corpos armazenados    | Deve apresentar os corpos que estavam no necrotério na data x               |
| Controle de liberação de corpos | Realizar o arquivamento do registro e emitir a liberação do corpo           |
| Notificar prazo de permanencia  | Apresentar uma notificação quando o prazo máximo estiver próximo ou vencido |

---

## 4. 🧪 Estratégia de Teste

Descreva a abordagem dos testes que serão realizados:

### Tipos de Testes Utilizados:

- [x] Testes Funcionais
- [ ] Testes de Interface (UI)
- [ ] Testes de Usabilidade

### Método de Execução:

- [ ] Manual
- [x] Automatizado
- [ ] Híbrido

---

## 5. 🧰 Recursos Necessários

### Equipamentos:

| Equipamento        | Especificações mínimas                     |
|--------------------|--------------------------------------------|
|  Celular Android   | Versão 10 ou superior                         |
|  Computador        | Navegador Chrome/Firefox atualizado           |

### Ferramentas:

| Ferramenta             | Finalidade                             |
|------------------------|----------------------------------------|
| Ex: JUnit              | Testes automatizados                   |
| Ex: TestRail           | Planejamento e execução dos testes     |

### Equipe Envolvida:

| Função                 | Quantidade | Nome(s) (opcional)       |
|------------------------|------------|--------------------------|
| Testador               |    1       |      Luut                |
| Desenvolvedor          |    1       |      Luut                |


---

## 6. 🛠️ Plano de Execução

Descreva como os testes serão realizados na prática.

### Etapas de Execução:

1. Preparação dos ambientes de teste.
2. Instalação da versão de teste do sistema.
3. Execução dos casos de teste manuais.
4. Registro de defeitos encontrados.
5. Análise de resultados.

### Ambiente de Teste:

| Ambiente               | Descrição                                     |
|------------------------|-----------------------------------------------|
| Ex: Desenvolvimento    | Versão com novas funcionalidades              |
| Ex: Homologação        | Ambiente próximo ao ambiente de produção      |

---

## 7. 📆 Cronograma

Organize o tempo das etapas do teste.

| Atividade                  | Data de Início | Data de Término |
|---------------------------|----------------|-----------------|
| Planejamento do Teste     |                |                 |
| Preparação do Ambiente    |                |                 |
| Execução dos Testes       |                |                 |
| Documentação dos Resultados|               |                 |

---

## 8. ⚠️ Riscos e Mitigações

Liste possíveis problemas que podem afetar os testes, com planos de ação.

| Risco Identificado                      | Possível Impacto                   | Estratégia de Mitigação                     |
|----------------------------------------|-----------------------------------|---------------------------------------------|
| Ex: Incompatibilidade com iOS antigo   | Aplicativo não abre em alguns aparelhos | Testar em diferentes versões do iOS      |
| Ex: Falta de dispositivos de teste     | Atraso nos testes manuais         | Uso de emuladores                           |

---
