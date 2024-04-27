&nbsp;&nbsp;&nbsp;&nbsp; Usuário: Representa a pessoa que interage com a aplicação através do cliente (navegador ou aplicativo).

&nbsp;&nbsp;&nbsp;&nbsp; Cliente: É a interface através da qual o usuário interage com a aplicação.

&nbsp;&nbsp;&nbsp;&nbsp; Servidor:

&nbsp;&nbsp;&nbsp;&nbsp; Views: Correspondem às várias interfaces de usuário que o cliente pode solicitar, como listas, cabeçalhos, carrossel de imagens, cards com histórias, visualização de perfil e formulários de login. Estes são os elementos que o usuário vê e com os quais interage.

&nbsp;&nbsp;&nbsp;&nbsp; Controllers: Incluem funcionalidades como "Cadastrar Perfil" e "Deletar Perfil" para usuários, e "Cadastrar" e "Visualizar" para feedbacks. Estes controladores recebem as ações do usuário, interagem com os modelos para processar essas ações e, em seguida, determinam qual view deve ser apresentada ao usuário.

&nbsp;&nbsp;&nbsp;&nbsp; Models: Contêm a estrutura de dados e a lógica de negócios. Por exemplo, o modelo "Users" contém campos como ID, Usuário e Tipo de usuário, enquanto o modelo "Feedbacks" contém Título, Descrição, Área do voluntariado e Autor. Esses modelos interagem com o banco de dados para buscar, salvar ou atualizar dados conforme necessário.

&nbsp;&nbsp;&nbsp;&nbsp; Servidor Banco de Dados: Armazena os dados que são manipulados pelos modelos. Quando um modelo precisa de dados, ele faz uma consulta ao banco de dados, que então retorna os dados solicitados para que o modelo possa processá-los.


- Explique os elementos chave do diagrama e como eles se relacionam.
- Explique as decisões de design e as implicações de cada componente na arquitetura.
- Explique como a arquitetura atende aos objetivos e requisitos do projeto.







