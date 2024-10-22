# -Identidade-na-Azure
Entendendo sobre Segurança e Identidade na Azure

Gerenciamento de Usuários, Personalização de Domínio e Segurança no Azure

O gerenciamento de usuários e permissões é essencial para a segurança e organização no Azure. Abaixo, vamos explorar como criar e convidar usuários para seu domínio, convites em massa, personalizar o nome do domínio e entender papéis administrativos. Além disso, falaremos sobre a proteção do ambiente com o Microsoft Defender for Cloud.

1. Criando um Usuário e Convidando para o Domínio Azure
Para adicionar um usuário ao seu domínio no Azure, você pode seguir os seguintes passos:

Vá até o Azure Active Directory (Azure AD) e selecione "Usuários".
Clique em Adicionar novo usuário e preencha os detalhes necessários, como nome, e-mail, e permissões.
Para convidar um usuário de fóruns de sua organização (por exemplo, exemplo@canaldacloud.com), você pode enviar um convite para o e-mail externo. Isso é feito através da função de Usuário Convidado .
2. Convite de Usuários em Massa com Template CSV
Se você precisar adicionar vários usuários uma vez, o Azure permite o upload em massa utilizando um arquivo CSV com o modelo fornecido pela plataforma. Para isso:

Acesse a seção de usuários no Azure AD e selecione "Usuários em Massa".
Faça o download do template CSV e preencha as informações dos usuários.
Suba o arquivo necessário, e o Azure cuidará do resto, enviando convites em massa para os usuários indicados.
3. Funções e Administradores: Permissões e Controle de Acesso
O Azure oferece uma série de papéis administrativos para facilitar o controle granular de quem pode fazer o quê no ambiente:

Administrador de Helpdesk : Pode redefinir senhas e ajudar com problemas básicos de usuário.
Administrador de senhas : Responsável apenas pela gestão de senhas de usuários.
Administrador de usuários : Pode gerenciar usuários e grupos, incluindo a criação de novos.
4. Personalização de Domínio de Nome
Uma das formas de personalizar o ambiente da sua organização no Azure é configurando um nome de domínio personalizado . Isso pode ser feito no Azure AD para melhorar a integração com o e-mail corporativo e outras ferramentas. Ao configurar seu domínio, por exemplo @canaldacloud.com, você terá uma identidade mais profissional e homologada ao seu negócio.

Além disso, vale lembrar que o Azure AD evoluiu para se tornar o Microsoft Entra ID , oferecendo uma abordagem ainda mais robusta para identidade e segurança.

5. Recuperação de Usuários Excluídos
Quando um usuário é excluído da nuvem, você tem até 30 dias para recuperá-lo antes que ele seja excluído permanentemente. Isso oferece uma camada adicional de segurança caso algum usuário seja removido acidentalmente.

6. RBAC e Grupos de Recursos
No Resource Group (Grupo de Recursos), você consegue validar seu acesso e ver as regras atribuídas. O Azure utiliza o RBAC (Role-Based Access Control) , que permite delegar instruções mais granulares, restringindo o que cada usuário pode acessar.

Você pode atribuir funções específicas a usuários, grupos, serviços principais ou identidades gerenciadas. Isso garante que cada pessoa ou sistema tenha apenas as permissões para executar suas funções.

7. Microsoft Defender para Nuvem: Escaneamento de Vulnerabilidades
O Microsoft Defender for Cloud é uma solução de segurança que identifica vulnerabilidades e oferece recomendações para corrigir problemas de segurança. Ele faz varreduras não apenas no Azure, mas também em outros provedores de nuvem, como AWS , Google Cloud Platform (GCP) , GitLab e Azure DevOps . Isso garante que sua organização esteja segura, independentemente de onde seus recursos estejam hospedados.
