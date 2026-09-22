# 📱 QR Code Studio — Gerador & Leitor de QR Code

**QR Code Studio** é uma aplicação web completa, moderna e totalmente *client-side* (100% executada no navegador) para geração, personalização e leitura de códigos QR.

O projeto aceita diversos formatos de entrada (Links, Wi-Fi, Cartões de Visita vCard e PIX) e oferece suporte a leitura de arquivos e escaneamento em tempo real via câmera.

## ✨ Funcionalidades

### 🎨 Gerador de QR Code

* **Múltiplos Formatos:**

  * **Texto / URL:** Links diretos ou textos genéricos.

  * **Wi-Fi:** Gera QR Code de conexão rápida com SSID, senha e protocolo de criptografia (WPA/WPA2/WEP).

  * **vCard:** Cartão de visitas digital completo (Nome, Telefone, E-mail, Empresa).

  * **PIX:** Formatação estática rápida para recebimento de pagamentos via PIX.

* **Customização Visual Avançada:**

  * Escolha de cores personalizadas para os módulos (foreground) e fundo (background).

  * Ajuste dinâmico de dimensões em pixels.

  * Inserção de **Logotipo central** customizado com ajuste de contraste e tolerância a erros (`CorrectLevel.H`).

* **Exportação:**

  * Download em **PNG** de alta resolução.

  * Download em **SVG** vetorial.

  * Copiar a imagem diretamente para a área de transferência.

### 📷 Leitor / Scanner

* **Upload de Arquivo:** Arraste e solte ou selecione imagens nos formatos PNG, JPG, WEBP e GIF para decodificação instantânea.

* **Leitura via Câmera:** Leitor em tempo real utilizando a webcam ou câmera do smartphone (com alternância entre câmera frontal e traseira).

* **Ações Rápidas:** Copiar texto decodificado ou abrir URLs diretamente em nova aba.

### 🛠️ Recursos de Experiência do Usuário (UX)

* **Tema Claro / Escuro (Dark Mode):** Alternância manual de tema com persistência local.

* **Histórico Local (LocalStorage):** Grava os QR Codes gerados e escaneados sem armazenar nada em servidores externos.

* **Notificações Toast:** Sistema de feedback visual responsivo e não intrusivo.

* **Privacidade Total:** 100% do processamento ocorre no próprio navegador.

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3**

* [**Tailwind CSS**](https://tailwindcss.com/?utm_source=gemini) (Interface responsiva e moderna)

* **JavaScript (ES6+)**

* [**QRCode.js**](https://github.com/davidshimjs/qrcodejs?utm_source=gemini) (Renderização do QR Code)

* [**jsQR**](https://github.com/cozmo/jsQR?utm_source=gemini) (Leitura e decodificação de imagem/vídeo)

* [**FontAwesome**](https://fontawesome.com/?utm_source=gemini) (Ícones da interface)

## 🚀 Como Executar o Projeto

Como o projeto foi desenvolvido em arquitetura de arquivo único (*Single File Application*), não é necessário instalar dependências com Node.js ou gerenciadores de pacote.

1. **Clone o repositório:**

   ```
   git clone https://github.com/seu-usuario/qr-code-studio.git
   
   
   ```

2. **Navegue até a pasta:**

   ```
   cd qr-code-studio
   
   
   ```

3. **Abra no seu navegador:**

   * Basta dar um duplo clique no arquivo `index.html`, ou abri-lo diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

## 🌐 Publicação (GitHub Pages)

Para disponibilizar seu projeto online via **GitHub Pages**:

1. Faça o push do código para o GitHub.

2. No seu repositório, vá em **Settings** > **Pages**.

3. Em **Build and deployment** > **Branch**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.

4. Clique em **Save**. Em instantes, seu projeto estará acessível publicamente!
