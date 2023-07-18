<h1 align="center">
📄<br>Readme Template
</h1>

## 📚 Criando um exemplo de aplicativo com integração fastlane.

> Fastlane é uma ferramenta de automação de código aberto que simplifica o processo de desenvolvimento e distribuição de aplicativos iOS. Ele oferece um conjunto de ferramentas que ajudam os desenvolvedores a automatizar tarefas repetitivas, como compilar, testar, assinar e enviar o aplicativo para a App Store.


---

## Comandos 

- gem install fastlane -NV
- fastlane init
- Escolhi a opção "4. 🛠  Manual setup - manually setup your project to automate your tasks"

- Edit o arquivo Fastfile
<div>
platform :ios do
  lane :build do
    build_app(scheme: "ios-fastlane", configuration: "Release")
  end
end
</div>
- fastlane build


 
<div align="center">
  <br/>
  <br/>
  <br/>
    <div>
      <h1>Open Source</h1>
      <sub>Copyright © 2023 - <a href="https://github.com/leocompiler">iuricode</sub></a>
    </div>
    <br/>
    💖
</div>
