# 📱 Kotlin e Java Mobile 01

> Projeto de estudos de desenvolvimento Android com Java e Kotlin

## 📋 Sobre o Projeto

Este é um projeto educacional desenvolvido durante o curso de **Desenvolvimento Mobile com Java e Kotlin**. O aplicativo demonstra conceitos fundamentais de desenvolvimento Android, incluindo criação de interfaces, manipulação de eventos e navegação entre telas.

## 🚀 Tecnologias Utilizadas

- **Java** - Linguagem principal de desenvolvimento
- **Kotlin** - Linguagem moderna para Android
- **Android SDK** - API 36.1 (Android 16.0)
- **ConstraintLayout** - Layout responsivo
- **Android Studio** - IDE de desenvolvimento

## 📂 Estrutura do Projeto

```
MOBILE_JAVA_KOTLIN/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com.example.appaula01/
│   │   │   │       └── MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   └── activity_login.xml
│   │   │   │   ├── drawable/
│   │   │   │   ├── values/
│   │   │   │   └── mipmap/
│   │   │   └── AndroidManifest.xml
│   │   └── androidTest/
│   └── build.gradle
├── gradle/
└── settings.gradle
```

## 🎯 Funcionalidades

- ✅ Tela de login com campos de usuário e senha
- ✅ Interface responsiva com ConstraintLayout
- ✅ Botão de ação principal
- ✅ Navegação entre Activities
- ✅ Tratamento de eventos de clique

## 🛠️ Como Executar

### Pré-requisitos

- Android Studio Arctic Fox ou superior
- JDK 11 ou superior
- Android SDK com API 36 ou superior
- Emulador Android ou dispositivo físico

### Passos para Execução

1. **Clone o repositório**
   ```bash
   git clone https://github.com/LucNath/Kotlin-e-Java-Mobile-01.git
   cd Kotlin-e-Java-Mobile-01
   ```

2. **Abra o projeto no Android Studio**
   - File → Open
   - Selecione a pasta do projeto
   - Aguarde o Gradle sincronizar

3. **Configure o emulador**
   - Tools → Device Manager
   - Crie um dispositivo virtual (recomendado: Pixel 6, API 33+)

4. **Execute o aplicativo**
   - Clique no botão Run (▶️) ou pressione `Shift + F10`
   - Selecione o dispositivo/emulador
   - Aguarde a instalação

## 📱 Capturas de Tela

<!-- Adicione screenshots do app aqui -->
_Screenshots serão adicionados em breve_

## 📚 Aprendizados

Este projeto cobre os seguintes conceitos:

- 📐 **Layouts XML**: Criação de interfaces com ConstraintLayout
- 🎨 **Estilização**: Uso de cores, margens e espaçamentos
- 🔗 **Activities**: Navegação e ciclo de vida
- 🖱️ **Event Listeners**: Tratamento de eventos de clique
- 📦 **Recursos**: Organização de strings, cores e drawables

## 🐛 Resolução de Problemas

### Erro de Build
Se encontrar erros de build:
```bash
Build → Clean Project
Build → Rebuild Project
```

### Problema com OneDrive
**⚠️ Importante**: Evite manter o projeto em pastas sincronizadas (OneDrive, Dropbox, etc.)
- Mova o projeto para: `C:\Users\[seu-usuario]\AndroidStudioProjects\`

### Emulador não conecta
```bash
adb kill-server
adb start-server
```

## 👤 Autor

**Lucas Nath**

- GitHub: [@LucNath](https://github.com/LucNath)
- Projeto: [Kotlin-e-Java-Mobile-01](https://github.com/LucNath/Kotlin-e-Java-Mobile-01)

## 📄 Licença

Este projeto é destinado para fins educacionais.

## 🤝 Contribuições

Contribuições, issues e sugestões são bem-vindas! Sinta-se à vontade para abrir uma issue ou pull request.

---

⭐ Se este projeto te ajudou, considere dar uma estrela!

**Desenvolvido com ❤️ durante o curso de Desenvolvimento Mobile**
