# 🚀 Projeto Prático – Dashboard com Flex Items

## 🎯 Objetivo
Construir uma **dashboard responsiva** usando **Flexbox**, aplicando as propriedades dos **Flex Items** para controlar crescimento, encolhimento, alinhamento e ordem dos elementos.  

---

## 📌 Orientações
Você deve criar um projeto com a seguinte estrutura:  

- Um **cabeçalho** (header).  
- Um **layout principal** dividido em **sidebar** (menu lateral) e **conteúdo principal**.  
- Dentro do conteúdo principal, crie **cards** que simulem informações da dashboard.  
- Um **rodapé** simples.  

Use **Flexbox** em todos os lugares necessários.  

---

## 🔧 Requisitos (passo a passo do desafio)

### 1. Estrutura
- Crie um arquivo `index.html` com a estrutura da página.  
- Crie um `style.css` para os estilos.  
- No **layout principal**, use `display: flex;` para posicionar a sidebar e o conteúdo lado a lado.  

### 2. Sidebar
- Sidebar deve ter **200px fixos** de largura.  
- Não deve crescer nem encolher.  
📌 Dica: use `flex: 0 0 200px;`.  

### 3. Conteúdo
- O conteúdo principal deve **ocupar todo o espaço restante**.  
📌 Dica: use `flex-grow: 1;`.  

### 4. Cards
- Dentro do conteúdo, crie pelo menos **5 cards**.  
- Os cards devem ter um **tamanho inicial de 200px** (`flex-basis`).  
- Devem **crescer igualmente** (`flex-grow: 1`).  
- Devem **encolher** quando não couberem na tela (`flex-shrink: 1`).  

### 5. Card de Destaque
- Escolha um card e aplique nele:  
  - `flex-grow: 2` → deve ocupar o dobro de espaço.  
  - `flex-basis: 300px` → deve começar maior que os outros.  
  - `order: -1` → deve aparecer primeiro.  
  - `align-self: center` → deve se alinhar diferente dos outros.  

### 6. Rodapé
- Crie um rodapé simples.  

---

## 🎯 Missões Extras
1. Crie um novo card que **não encolha nunca** (`flex-shrink: 0`).  
2. Reorganize os cards mudando apenas a propriedade `order`.  
3. Experimente diferentes valores de `align-self` em cada card.  
4. Transforme os cards em **botões interativos** (hover com cor diferente).  

---

## 📖 Dicas
- Comece com o HTML bem simples (header, sidebar, main, footer).  
- Só depois adicione os **cards**.  
- Vá aplicando as propriedades de Flexbox uma a uma para perceber a diferença.  

---

## ✅ Checklist de Entrega
- [ ] Header criado  
- [ ] Sidebar com largura fixa  
- [ ] Main ocupando espaço restante  
- [ ] Pelo menos 5 cards configurados com `flex-basis`, `flex-grow` e `flex-shrink`  
- [ ] Um card com destaque (`grow`, `basis`, `order`, `align-self`)  
- [ ] Footer criado  
- [ ] Missões extras (se feitas)  
