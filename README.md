# Teste de Usabilidade — Cadastro de Recurso

**1. Telas analisadas**
 1. [Tela inicial com botão "Cadastrar Recursos](assets/tela_geral.png)

Tela inicial do painel com ações rápidas e acesso ao cadastro de recursos.

2. [Página de cadastro de recursos ](assets/tela_equip.png)

Lista e opções de gerenciamento de recursos com botão "Novo Recurso".

3. [Popup "Novo Recurso" (formulário)](assets/tela_infos.png)

Modal para inserir dados do equipamento (nome, tipo, localização) com "Cancelar" e "Continuar".

4. [Lista mostrando o recurso criado](assets/tela_finalizada.png)

Visão que confirma o cadastro e exibe a localização do recurso.

- Contexto: fluxo de cadastro de um novo equipamento para uso em alocações de combate a incêndio.

**2. Tipo de teste**

**Tipo:** Tarefa

**O que será testado:** simular a tarefa que um usuário real executaria para cadastrar um novo equipamento: localizar a ação, abrir o formulário, preencher os campos obrigatórios, usar as ações "Cancelar" ou "Continuar" e confirmar que o recurso foi criado com localização.

**3. Conjunto de perguntas (fluxo/funil)**
1. Descoberta: Onde você clicaria para iniciar o cadastro de um recurso na tela inicial?
2. Navegação: Ao acessar a página de cadastro, você encontrou o botão "Novo Recurso" rapidamente?
3. Compreensão do formulário: As labels e placeholders do popup deixam claro quais informações são obrigatórias e o formato esperado (ex.: coordenadas)?
4. Decisão: Se você quiser desistir, o botão "Cancelar" está aparente e claro; se quiser prosseguir, o botão "Continuar" transmite a ação esperada, ficou natural para você escolher?
5. Confirmação: Após confirmar, você localizou o recurso na lista/tela de confirmação e consegue ver a indicação de localização?

**4. Objetivo do teste**
Verificar que um usuário consegue cadastrar um novo recurso e que o sistema registra sua localização, permitindo identificar posteriormente qual equipamento está mais próximo de uma ocorrência.

**5. Ação ou entendimento esperado**
O usuário deve saber onde acessar a página de cadastro, entender quais campos são obrigatórios e completar o cadastro. Ao finalizar, deve ver claramente que o recurso foi criado e onde sua localização foi registrada.
