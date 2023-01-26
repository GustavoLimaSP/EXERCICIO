1 - O que é clone?

2 - O que é commit?

3 - O que é repositório?

4 - O que é pull?

5 - O que é um VCS?

--------------------------------------
R:

1 - Git clone é um dos muitos comandos do Git. Ele tem como principal proposta clonartodos os arquivos de repositório remoto para um repositório local. Por padrão, todo o histórico de commits, branches e menges são copiados também. Esse comando é muito útil para quando precisamos de uma nova cópia do projeto ou simplesmente porque queremos conferir alguns arquivos.

2 - Um commit é um conjunto de alterações que você fez em um projeto. Ele marca uma versão do seu código. Um commit guarda as alterações feitas nos arquivos, quem fez essas alterações e uma mensagem que resume essa alteração.

3 - Um repositório, ou repo, é um diretório onde você armazena os arquivos do seu projeto, que podem ser códigos, imagens, áudios, vídeos ou qualquer coisa relacionada a esse projeto. Ele pode ficar armazenado no seu computador, um repositório local, ou também ser armazenado em alguns serviços como GitHub, BitBucket ou GitLab, ou seja, um repositório remoto.

4 - O comando git pull é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. Fazer o merge de alterações upstream remotas no repositório local é algo comum em fluxos de trabalho de colaboração baseados em Git. O comando git pull é a combinação de dois outros comandos, o git fetch, seguido do git merge. No primeiro estágio da operação, o git pull executa o comando git fetch, que abrange a ramificação local para qual a HEAD aponta. Quando o conteúdo é baixado, o git pull insere o fluxo de trabalho de merge. O commit de merge é criado e a HEAD é atualizada para apontar o novo commit.

5 - Os VCS às vezes são conhecidos como ferramentas SCM (Gerenciamento de código-fonte) ou RCS (Sistema de controle de revisão). Uma das ferramentas VCS mais populares em uso hoje é chamada de Git. Ela é um VCS Distribuído, uma categoria conhecida como DVCS, que a gente vai ver mais adiante.
