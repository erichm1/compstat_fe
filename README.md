# 🚀 CompStat FE (compstat_fe/frontend)

Este repositório contém o frontend do projeto CompStat, desenvolvido para visualização e interação com dados geoespaciais. 🌍📊

## 🛠️ Tecnologias Utilizadas

- **⚛️ React** - Biblioteca para construção de interfaces web dinâmicas.
- **📱 React Native** - Framework para desenvolvimento de aplicativos móveis.
- **🟨 JavaScript** - Linguagem de programação base do projeto.
- **🔵 TypeScript** - Superset do JavaScript que adiciona tipagem estática.

## ⚙️ Instalação e Configuração

### 📌 Requisitos
Antes de iniciar, certifique-se de ter instalado:
- Node.js (versão recomendada: LTS)
- Gerenciador de pacotes (npm ou yarn)

### 📥 Passos para Configuração
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/compstat_fe.git
   cd compstat_fe
   ```

2. Instale as dependências:
   ```sh
   npm install  # ou yarn install
   ```

3. Inicie o servidor de desenvolvimento:
   ```sh
   npm start  # ou yarn start
   ```

## 📂 Estrutura do Projeto
```
compstat_fe/
│── src/               # 📂 Código-fonte do projeto
│   ├── components/    # 🏗️ Componentes reutilizáveis
│   ├── screens/       # 📺 Telas principais da aplicação
│   ├── services/      # 🔌 Conexão com a API
│   ├── styles/        # 🎨 Estilização global e temas
│   ├── utils/         # 🔧 Funções auxiliares
│── public/            # 🌍 Arquivos estáticos e index.html
│── package.json       # 📦 Configuração do projeto
│── tsconfig.json      # 🛠️ Configuração do TypeScript
```

## 🧪 Executando os Testes
Para rodar os testes automatizados:
```sh
npm test  # ou yarn test
```

## 🔗 Endpoints Principais (Consumo da API)
- `GET /api/data/` - 📊 Obtém os dados processados.
- `POST /api/upload/` - 📤 Faz upload de arquivos para análise.
- `GET /api/statistics/` - 📈 Obtém estatísticas geoespaciais.

## 🤝 Contribuição
Contribuições são bem-vindas! Para contribuir:
1. Fork o repositório.
2. Crie uma branch (`feature-minha-mudanca`).
3. Commit suas alterações (`git commit -m "Minha contribuição"`).
4. Push para a branch (`git push origin feature-minha-mudanca`).
5. Abra um Pull Request.

## 📜 Licença
Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

