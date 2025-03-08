# .NET


Odonto Vision

Visão Geral do Projeto
Odonto Vision é uma solução desenvolvida para o setor odontológico, com o objetivo de incentivar a saúde bucal preventiva através de um aplicativo gamificado. 
O foco do projeto é reduzir os custos para a OdontoPrev, promovendo boas práticas de saúde dental que ajudam a evitar a necessidade de procedimentos mais caros no futuro. 
O sistema está sendo desenvolvido com a arquitetura Clean Architecture, organizada em camadas de Presentation, Application, Domain, e Infrastructure, 
utilizando .NET para oferecer uma interface robusta e responsiva.

Principais Funcionalidades
- Aplicativo Gamificado para Saúde Preventiva: Incentiva os usuários a adotarem boas práticas de saúde bucal.
- Implementação de Views e ViewModels: Desenvolvemos uma interface de usuário dinâmica, incluindo views e viewmodels, além de estruturação HTML para aprimorar a experiência e usabilidade.
- Arquitetura Limpa (Clean Architecture): Organização do código em camadas para garantir separação de responsabilidades, testabilidade e fácil manutenção.

Instruções de Instalação e Configuração

Pré-requisitos
- .NET SDK: Certifique-se de ter o .NET SDK instalado. Você pode baixá-lo [aqui](https://dotnet.microsoft.com/download).
- Banco de Dados Oracle: Conexão configurada com o Oracle Database.
  - Hostname: oracle.fiap.com.br
  - Porta: 1521
  - Service name: orcl
  - Username: rm554199
  - Password: 160103
- Ferramenta de Gerenciamento de Pacotes: Certifique-se de ter o NuGet configurado para baixar dependências adicionais, se necessário.

Passo a Passo para Instalação
1
   cd OdontoVision

2. Restaurar Dependências
   dotnet restore

3. Compilar o Projeto
   dotnet build

4. Executar a Aplicação
   ```bash
   dotnet run
   ```

5. Acessar o Servidor
   - Acesse o servidor local no navegador através de http://localhost:<porta>, onde <porta> será especificada no terminal após a execução do projeto.

Configuração das Views e ViewModels
- As views e viewmodels foram implementadas para oferecer uma experiência visual interativa, utilizando HTML para estruturação das páginas. 
As views podem ser encontradas na pasta /Views, e os viewmodels correspondentes estão na pasta /ViewModels.
- A organização e o desenvolvimento das views seguem o padrão MVVM (Model-View-ViewModel) para garantir a separação de lógica e apresentação.

