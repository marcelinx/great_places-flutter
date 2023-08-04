# Locaimage - Armazenamento de Imagens e Locais

O Locaimage é um aplicativo Flutter que permite aos usuários armazenar imagens juntamente com informações de localização. Ele utiliza recursos nativos do dispositivo, como a câmera e a localização, para proporcionar uma experiência completa de armazenamento e visualização de imagens associadas a locais específicos. O aplicativo utiliza a biblioteca SQLite para gerenciar o armazenamento local dos dados.

## Recursos e Dependências

O aplicativo Locaimage utiliza os seguintes recursos nativos e dependências:

### Recursos Nativos

#### Câmera
A funcionalidade de câmera permite que os usuários capturem imagens diretamente dentro do aplicativo. Isso é feito por meio do plugin `image_picker`, que facilita a integração com a câmera do dispositivo e a seleção de imagens da galeria.

#### Localização
O recurso de localização é utilizado para associar informações de latitude e longitude às imagens capturadas. Isso possibilita que os usuários saibam onde cada imagem foi registrada. A obtenção das coordenadas de localização é realizada utilizando recursos nativos do dispositivo.

### Dependências

O Locaimage utiliza as seguintes dependências para facilitar o desenvolvimento:

#### image_picker: ^1.0.2
O pacote `image_picker` é utilizado para acessar a câmera do dispositivo e a galeria de fotos, permitindo que os usuários capturem novas imagens ou selecionem imagens existentes. Ele simplifica a interação com os recursos nativos de captura de imagem e escolha de arquivos.

#### path_provider: ^2.0.15
A dependência `path_provider` fornece métodos simples para acessar os diretórios de armazenamento específicos da plataforma em que o aplicativo está sendo executado. Isso é essencial para salvar e recuperar as imagens capturadas e outros dados importantes, como o banco de dados SQLite.

#### path: ^1.8.3
O pacote `path` fornece utilitários para trabalhar com caminhos de arquivo e diretório de maneira eficiente. Ele é frequentemente usado em conjunto com outras dependências, como o `path_provider`, para manipular arquivos de forma confiável.

## Funcionalidades

- Captura de imagens usando a câmera do dispositivo.
- Escolha de imagens da galeria.
- Associação automática de coordenadas de localização às imagens.
- Armazenamento seguro das imagens e informações relacionadas no banco de dados SQLite.
- Visualização das imagens em uma interface de usuário intuitiva juntamente com detalhes de localização.

## Como Executar o Aplicativo

Para executar o aplicativo Locaimage em seu ambiente de desenvolvimento local, siga estas etapas:

1. Certifique-se de ter o Flutter e o Dart instalados em sua máquina.
2. Clone este repositório e navegue até o diretório do projeto.
3. Execute o comando `flutter pub get` para instalar as dependências listadas no arquivo `pubspec.yaml`.
4. Conecte um dispositivo físico ou configure um emulador.
5. Execute o comando `flutter run` no diretório do projeto para iniciar o aplicativo.

Agora você pode explorar as funcionalidades do Locaimage diretamente em seu dispositivo ou emulador.

**Nota:** Certifique-se de que as permissões relevantes, como acesso à câmera e à localização, estejam habilitadas no dispositivo ou emulador para garantir o funcionamento adequado do aplicativo.

## Contribuição

Se você deseja contribuir para o desenvolvimento do Locaimage, sinta-se à vontade para enviar pull requests ou relatar problemas no repositório oficial do projeto. Sua contribuição é muito apreciada!

---

Esperamos que o Locaimage ofereça a você uma maneira conveniente de armazenar suas imagens com informações de localização. Aproveite o uso do aplicativo e não hesite em entrar em contato conosco em caso de dúvidas ou sugestões!