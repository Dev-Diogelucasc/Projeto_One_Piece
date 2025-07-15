# 🏴‍☠️ One Piece - Site do Fã

Um site dedicado ao universo de One Piece, desenvolvido como projeto acadêmico para a disciplina de Programação para Internet.

## 📖 Sobre o Projeto

Este é um site temático sobre One Piece, o famoso mangá e anime criado por Eiichiro Oda. O projeto foi desenvolvido com o objetivo de criar uma experiência interativa e informativa para fãs da série, apresentando informações detalhadas sobre:

- **Personagens** principais e secundários da série
- **Arcos narrativos** e suas principais características  
- **Lutas** épicas e marcantes
- **Locais** importantes do mundo de One Piece
- **Akuma no Mi** (Frutas do Diabo) e seus poderes
- **Informações de contato** para feedback

O site foi criado como parte de um trabalho acadêmico, demonstrando conhecimentos em desenvolvimento web front-end e design responsivo.

## 🚀 Como Configurar o Ambiente

### Pré-requisitos

Para executar este projeto, você precisa apenas de:

- Um navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com a internet (para carregar ícones do Font Awesome)

### Opção 1: Execução Simples
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Dev-Diogelucasc/One-Piece.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd One-Piece
   ```

3. **Abra o arquivo `index.html` em seu navegador:**
   - Dê duplo clique no arquivo `index.html`, ou
   - Clique com o botão direito e selecione "Abrir com" → seu navegador preferido

### Opção 2: Servidor Local (Recomendado)
Para uma melhor experiência e evitar problemas com CORS:

**Usando Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Usando Node.js:**
```bash
# Instale o http-server globalmente
npm install -g http-server

# Execute o servidor
http-server
```

**Usando PHP:**
```bash
php -S localhost:8000
```

Após executar qualquer um dos comandos acima, acesse `http://localhost:8000` em seu navegador.

## 🎯 Como Usar o Site

### Navegação Principal

O site possui uma navegação intuitiva com as seguintes seções:

1. **Página Inicial** - Apresentação geral e curiosidades sobre a Família D.
2. **Arcos** - Informações sobre os principais arcos narrativos
3. **Personagens** - Galeria de personagens organizados por grupos
4. **Lutas** - Battles épicas e marcantes da série
5. **Locais** - Localizações importantes do mundo de One Piece
6. **Akuma no Mi** - Catálogo das Frutas do Diabo e seus poderes
7. **Contato** - Formulário para feedback e sugestões

### Funcionalidades

- **Design Responsivo:** O site se adapta a diferentes tamanhos de tela
- **Menu Mobile:** Menu hambúrguer para dispositivos móveis
- **Navegação Intuitiva:** Links entre páginas com botão de voltar
- **Layout Organizado:** Informações apresentadas de forma clara e estruturada
- **Imagens Otimizadas:** Galeria de imagens dos personagens e elementos da série

### Dicas de Uso

- Use a navegação superior para alternar entre as diferentes seções
- Em dispositivos móveis, clique no ícone de menu (☰) para acessar a navegação
- As imagens podem ser visualizadas em tamanho maior ao clicar nelas
- Use o botão "voltar" presente em cada página para retornar à página inicial

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Aqui estão algumas formas de colaborar:

### Tipos de Contribuições

- 🐛 **Reportar bugs** ou problemas encontrados
- 💡 **Sugerir melhorias** ou novas funcionalidades  
- 📝 **Melhorar documentação** ou corrigir informações
- 🎨 **Aprimorar design** e experiência do usuário
- ➕ **Adicionar conteúdo** sobre novos personagens, arcos ou locais

### Como Contribuir

1. **Fork o repositório**
2. **Crie uma branch para sua feature:**
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. **Faça suas alterações e commit:**
   ```bash
   git commit -m "Adiciona nova funcionalidade"
   ```
4. **Push para sua branch:**
   ```bash
   git push origin feature/nova-funcionalidade
   ```
5. **Abra um Pull Request**

### Diretrizes para Contribuição

- Mantenha o código limpo e bem comentado
- Teste suas alterações em diferentes navegadores
- Certifique-se de que o design responsivo continue funcionando
- Siga a estrutura de arquivos existente
- Adicione informações precisas sobre One Piece

### Reportar Problemas

Se encontrar bugs ou problemas, por favor:
1. Verifique se o problema já foi reportado nas Issues
2. Crie uma nova Issue com descrição detalhada
3. Inclua screenshots se aplicável
4. Mencione o navegador e sistema operacional usado

## 🛠️ Tecnologias Utilizadas

### Front-end
- **HTML5** - Estruturação semântica das páginas
- **CSS3** - Estilização e layout responsivo
- **JavaScript (ES6)** - Funcionalidade do menu mobile
- **Font Awesome 4.7.0** - Ícones e elementos visuais

### Estrutura de Arquivos
```
One-Piece/
├── index.html              # Página principal
├── arcos.html              # Página dos arcos
├── personagem.html         # Página dos personagens  
├── lutas.html              # Página das lutas
├── locais.html             # Página dos locais
├── akuma.html              # Página das Akuma no Mi
├── contato.html            # Página de contato
├── estilos/                # Arquivos CSS
│   ├── styles.css          # Estilos principais
│   ├── personagem.css      # Estilos da página de personagens
│   ├── arco.css            # Estilos da página de arcos
│   ├── lutas.css           # Estilos da página de lutas
│   ├── locais.css          # Estilos da página de locais
│   ├── akuma.css           # Estilos da página Akuma no Mi
│   ├── contato.css         # Estilos da página de contato
│   └── media-query.css     # Media queries para responsividade
├── imagens/                # Recursos visuais
│   ├── personagens/        # Imagens dos personagens
│   ├── logo2.jpg           # Logo do site
│   └── favicon.ico         # Ícone do site
└── icons/                  # Ícones diversos
    └── botao-voltar.png    # Ícone do botão voltar
```

### Recursos Externos
- **Font Awesome CDN** - Para ícones do menu mobile
- **Fontes do Sistema** - Arial, Helvetica, sans-serif

## 📋 Requisitos do Sistema

### Navegadores Suportados
- ✅ Google Chrome (versão 80+)
- ✅ Mozilla Firefox (versão 75+) 
- ✅ Safari (versão 13+)
- ✅ Microsoft Edge (versão 80+)

### Resolução de Tela
- 📱 **Mobile:** 320px - 768px
- 💻 **Tablet:** 768px - 1024px  
- 🖥️ **Desktop:** 1024px+

### Conectividade
- Conexão com internet necessária para carregar ícones do Font Awesome
- Site funciona offline após o primeiro carregamento (exceto ícones externos)

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE) - veja o arquivo LICENSE para detalhes.

## 📞 Contato

- **Desenvolvedor:** Dev-Diogelucasc
- **GitHub:** [Dev-Diogelucasc](https://github.com/Dev-Diogelucasc)
- **Projeto:** Programação para Internet

## 🙏 Agradecimentos

- **Eiichiro Oda** - Criador de One Piece
- **Comunidade One Piece** - Por inspirar este projeto
- **Font Awesome** - Pelos ícones utilizados
- **GitHub** - Por hospedar o projeto

---

⚓ *"Eu vou ser o Rei dos Piratas!"* - Monkey D. Luffy
