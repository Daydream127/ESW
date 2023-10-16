Levantamento de requisitos + Diagrama(s) e especificação de casos-de-uso (texto estruturado e/ou Diagramas de Atividades).  

# POLYMORPH AI

## descrição informal

Pertende-se desenvolver um portal (POLYMORPH.AI) que, com recurso a inteligência artificial, permita criar programas a partir de diagramas.


## requisitos funcionais

RF--. O sistema deverá pedir um username ao utilizador.  
RF--. O sistema deverá pedir um display name ao utilizador.  
RF--. O sistema deverá pedir um email ao utilizador.  
RF--. O sistema deverá pedir uma password ao utilizador.  
RF--. O sistema deverá permitir o registo / login com email e password.  
RF--. O sistema deverá permitir o registo / login com redes sociais.  
RF--. O sistema deverá exigir que o utilizador leia e aceite os termos de serviço e política de privacidade da plataforma quando se registar.  
RF--. O sistema deverá permitir que o utilizador faça download dos seus dados (GDPR art.15 - Right of Access).  
RF--. O sistema deverá permitir que o utilizador apague a sua conta (GDPR art. 17/19 - Right to be forgotten).  
RF--. O sistema deverá suportar importar o display name e profile picture da rede social usada para registo para o perfil do sistema.  
RF--. O sistema deverá suportar 2FA TOTP ou SMS.  
RF--. O sistema deverá permitir ao utilizador editar o seu perfil (display name, foto).  
RF--. O sistema deverá permitir associar ao utilizador dados de faturação (nome completo, morada, número de identificação fiscal).  
RF--. O sistema deverá permitir associar ao utilizador métodos de pagamento.  
RF--. O sistema deverá permitir ao utilizador adquirir tokens.  
RF--. O sistema deverá permitir ao utilizador subscrever a um plano mensal ou anual.  
RF--. O sistema deverá permitir ao utilizador gerir (cancelar, alterar) o seu plano.  
RF--. O sistema deverá mostrar ao utilizador o seu plano.  
RF--. O sistema deverá mostrar ao utilizador a quantidade de tokens que possui.  
RF--. O sistema deverá permitir ao utilizador a consulta dos movimentos de tokens.  
RF--. O sistema deverá permitir ao utilizador a consulta do seu histórico de compras e faturas.  
RF--. O sistema deverá permitir a criação de contas empresariais.  
RF--. O sistema deverá permitir ao administrador da conta empresarial associar utilizadores existentes.  
RF--. O sistema deverá permitir ao administrador da conta empresarial criar utilizadores em massa no seu domínio.  
RF--. O sistema deverá permitir ao administrador da conta empresarial remover utilizadores no seu domínio.  
RF--. O sistema deverá permitir ao administrador da conta empresarial associar dados de faturação.  
RF--. O sistema deverá permitir ao administrador da conta gerir permissões dos utiliadores no seu domínio.  
RF--. O sistema deverá permitir ao administrador da conta empresarial escolher um plano mensal ou anual.  
RF--. O sistema deverá permitir aos utilizadores criar um projeto.  
RF--. O sistema deverá permitir aos utilizadores a consulta dos seus projetos.  
RF--. O sistema deverá permitir aos utilizadores convidar outros utilizadores para os seus projetos.  
RF--. O sistema deverá permitir aos utilizadores remover pessoas dos seus projetos.  
RF--. O sistema deverá permitir aos utilizadores editar os dados dos seus projetos (foto, nome).  
RF--. O sistema deverá permitir aos donos de projetos editar as permissões dos membros dos mesmos.  
RF--. O sistema deverá permitir aos donos de projetos apagar os mesmos.  
RF--. O sistema deverá permitir aos utilizadores com permissão para tal ligar o seu projeto a um projeto Git.  
RF--. O sistema deverá exigir aos utilizadores CAPTCHA e verificação 2FA para ações sensíveis (apagar um projeto, editar permissões).  
RF--. O sistema deverá permitir aos utilizadores fazer upload de diagramas.  
RF--. O sistema deverá permitir aos utilizadores fazer upload de ficheiros CASE.  
RF--. O sistema deverá permitir aos utilizadores visualisar e gerir os diagramas / ficheiros CASE submetidos.  
RF--. O sistema deverá permitir a repartição dos projetos.  
RF--. O sistema deverá permitir ao utilizador escolher as linguagens de programação e outros requisitos para cada parte do seu projeto.  
RF--. O sistema deverá fornecer ao utilizador uma estimativa de custos para o projeto como um todo e para cada uma das suas partes, com recurso a AI.  
RF--. O sistema deverá gerar código para o projeto de acordo com os diagramas, linguagem e outros requisitos submetidos, com recurso a AI.  
RF--. O sistema deverá testar o código de acordo com os requisitos do projeto.  
RF--. O sistema deverá permitir ao utilizador dar feedback ao código gerado.  
RF--. O sistema deverá permitir ao utilizador editar manualmente o código na plataforma ou num repositório Git.  
RF--. O sistema deverá permitir gerar código novamente com base no feedback do utilizador.  
RF--. O sistema deverá enviar notificações ao utilizador (PUSH/email) sempre que o seu input for necessário ou quando a geração de código estiver concluida.  
RF--. O sistema deverá permitir ativar ou desativar as notificações para cada projeto.  
RF--. O sistema deverá permitir que o utilizador consulte estatísticas relativas a si mesmo e aos seus projetos.  
RF--. O sistema deverá, antes de cada etapa de geração de código, apresentar a estimativa de custos ao utilizador e aguardar aprovação antes de começar.
RF--. O sistema deverá, em cada etapa de geração de código, descontar tokens ao utilizador.
