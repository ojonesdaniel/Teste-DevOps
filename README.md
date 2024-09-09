Teste estágio DevOps – IVORYIT
Parabéns! Você foi selecionado como um dos candidatos para realizar os testes e participar
de uma entrevista. Neste teste, vamos avaliar seus conhecimentos em Git, automações de
CI/CD com SonarCloud e publicações em nuvem
README:
• Objetivo: Além do que foi apresentado na descrição da vaga, queremos testar seus
conhecimentos na área de DevOps/Infraestrutura.

INFORMAÇÔES SOBRE O TESTE:
Cenário: Você foi convidado para fazer parte de uma squad de desenvolvimento, onde
atuará como DevOps, responsável por gerir a infraestrutura e promover boas práticas. Sua
responsabilidade inicial será provisionar um ambiente para a hospedagem de um site
estático.
Para esta estrutura, você também deverá elaborar uma esteira CI/CD, onde está deve ser
disparado desde o commit do código-fonte no Git, até este sendo "empurrado" para um
ambiente em nuvem, funcionando 100%.
Alguns requisitos devem ser atendidos:
1. Faça o download de um site estático gratuito da internet, ou crie um site próprio se
preferir
2. Crie uma conta no GitHub (caso ainda não tenha).
3. Crie uma conta no Sonarcloud (https://sonarcloud.io/login) (caso ainda não tenha).
4. Crie uma conta em um provedor de nuvem pública de sua escolha (AWS, Azure,
Digital Ocean, etc.) (caso ainda não tenha).
5. Use boas práticas de versionamento de código no Git. Avaliaremos o histórico de
commits no seu projeto do GitHub, por isso, utilize boas práticas na criação de
branchs e push, com descrições claras dos seus commits. O projeto deve ter três
branches principais: main, develop e homolog. Suba o código do site estático em
uma branch temporária e depois faça merge para a branch develop, em seguida
para homolog, e finalmente para main. Ao enviar para a branch main, o processo de
CI/CD deve ser automaticamente acionado, realizando as etapas de build (se
necessário), análise de qualidade no SonarCloud, e deploy da aplicação no ambiente
em nuvem. Certifique-se de que todo o processo esteja funcionando corretamente e
documente qualquer ajuste necessário. Inclua evidências dos primeiros commits
realizados localmente e depois enviados ao GitHub.
6. O teste deve conter uma pipeline que execute todo o fluxo CI/CD, desde a build do
projeto (se necessário), passando pela análise no SonarCloud, até o deploy da
aplicação na nuvem escolhida.
7. Envie um relatório com evidências de que a pipeline está funcionando. Inclua todas
as permissões necessárias para que possamos ver o que foi construído. Também
compartilhe o DNS (ou link) do site hospedado para avaliarmos o site em
funcionamento.
Considerações finais:
• As ferramentas Git e SonarCloud podem ser cadastradas gratuitamente, sendo que o
SonarCloud deve ter visibilidade pública para evitar cobranças."
• Caso escolha a AWS como provedor de nuvem, utilize os recursos S3 e CloudFront
para provisionamento. Aqui está um tutorial no YouTube para ajudar:
https://www.youtube.com/watch?v=QWGg1I1wido. Embora a AWS solicite um cartão
de crédito internacional, não haverá cobranças se você usar os recursos Free Tier.
Para o site estático, o custo será ZERO."