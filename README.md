# 🌤️ Weather App

Uma aplicação web moderna e responsiva para consultar informações do clima em tempo real.

## ✨ Funcionalidades

- 🔍 Busca por cidade
- 🌡️ Temperatura atual
- 🌤️ Condições climáticas
- 🌅 Imagens dinâmicas (dia/noite)
- 📱 Design responsivo
- 🎨 Interface moderna e intuitiva

## 🚀 Como usar

### **Para usuários (após clonar o repositório):**

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/weather-app.git
   cd weather-app
   ```

2. **Configure sua API Key (ÚNICO passo necessário!)**
   - Obtenha uma chave gratuita em [AccuWeather API](https://developer.accuweather.com/)
   - Abra o arquivo `config.js`
   - Substitua `add_your_api_key_here` pela sua chave real
   - **Pronto!** 🎉

3. **Execute o projeto**
   - Abra o arquivo `index.html` em seu navegador
   - **Não precisa instalar nada!** É vanilla JavaScript

### **✨ Isso é tudo!** 
O projeto funciona imediatamente após configurar a API key. Não há dependências, build steps ou configurações complexas.

## 🛠️ Tecnologias utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com flexbox e grid
- **JavaScript (ES6+)** - Lógica da aplicação
- **AccuWeather API** - Dados meteorológicos

## 📁 Estrutura do projeto

```
weather-app/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos da aplicação
├── js/
│   ├── app.js          # Lógica principal
│   └── weather.js      # Integração com API
├── src/
│   ├── icons/          # Ícones do clima
│   ├── day.jpg         # Imagem de fundo (dia)
│   └── night.jpg       # Imagem de fundo (noite)
├── config.js           # Configurações (não versionado)
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Este arquivo
```

## 🔧 Configuração da API

1. Acesse [AccuWeather Developer Portal](https://developer.accuweather.com/)
2. Crie uma conta gratuita
3. Gere uma API Key
4. Substitua `DEMO_KEY_REPLACE_WITH_REAL_KEY` no arquivo `js/weather.js` pela sua chave real

## 📱 Responsividade

O app foi desenvolvido com foco na responsividade, funcionando perfeitamente em:
- 📱 Dispositivos móveis
- 💻 Tablets
- 🖥️ Desktops

## 🎨 Design

- Interface moderna com tema escuro
- Animações suaves
- Ícones SVG otimizados
- Imagens de fundo dinâmicas baseadas no horário

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🖼️ Imagem do projeto
<img width="2000" height="1200" alt="Design sem nome" src="https://github.com/user-attachments/assets/5bb26668-3a48-4421-89c8-a5eaab5bfc87" />

