README

- Este projeto foi construído desta maneira para servir, não somente como a entrega do nosso primeiro sprint, como também para servir como um cartão de visita do nosso projeto.
- Esperamos que goste.

- Para a sua melhor experiência, logo abaixo você encontrará algumas informações importantes.

=========================================
===== O QUE ENTENDEMOS DO BRIEFING ======
=========================================

- DESCREVER BRIEFING ORIGINAL DA PORTO

=========================================
======== O QUE ESTAMOS PROPONDO =========
=========================================

- 1. Entendemos que nosso trabalho inicia com a chegada de um possível novo cliente.
    - 1.a. Este cliente já se cadastrou na base de dados da Porto.
    - 1.b. A interface do perfil do usuário e do interesse do usuário chegam para nós através de uma API (no caso de uma aplicação prática).
    - 1.c. Nosso projeto é substituir o vistoriador que hoje, de maneira parcial vistoria as bicicletas dos possíveis segurados por amostragem e valor da bicileta.

- 2. Entedemos também da necessidade de levar o produto para bicicletas a partir de R$ 2.000,00.
    - 2.a. Tendo isso em mente, nosso projeto substitui a interface humana por uma interface de inteligência artificial.

- 3. Sobre a nossa proposta, de forma resumida e topicular:
    - 3.a. Nossa interface é aplicada em possíveis candidatos à segurados Porto.
    - 3.b. Os dados iniciais, tais como, Nome, CPF, RG, Endereço, etc (Dados sensíveis protegidos pela LGPD), já estarão previamente preenchidos e não teremos acesso a estes dados inicialmente.
    - 3.c. Nossa interface inicialmente vai analisar documentos como nota fiscal do produto ou recibo de compra e venda e identificar automaticamente dados como:
            - 3.c.1. Número da NF;
            - 3.c.2. Empresa responsável pela venda;
            - 3.c.3. Data da venda;
            - 3.c.4. Descrição do produto;
            - 3.c.5. Valor pago (sem frete);
    - 3.d. Se permitido pelos orgãos reguladores, vamos validar o número da NF através de API's (Tópico em discussão - TBC)

- 4. Identificar o modelo da bicicleta e validar com foto em tempo real (sem upload) do número de série no produto.

- 5. Identificar as peças mais importantes do modelo da bicicleta para fazer a análise visual.

- 6. Através de um scanner de inteligência artificial, vamos tentar identificar se as peças correspondem as originais de fábrica.

- 7. Na etapa 2 do scanner, vamos solicitar 8 fotos de peças e componentes da bicicleta para validar se a evidência corresponde ao produto e a NF.

- 8. Enviamos para o banco de dados essas informações e o computador analisa através de uma acuracidade entre 70% e 100% de precisão.

- 9. Na tomada de decisão de aprovado, pendente e rejeitado, o sistema vai interpretar as informações transmitidas pelo usuário e as evidências coletadas.

- !. Resultados:
        - Caso aprovado, o cliente será transmitido através de API's para a base de dados da porto e será integrado ao status de aprovação.
        - Caso pendente, o chatbot fará um ativo no telefone do cliente, informado a pendência de novas evidências e realizando um call to action para retorno ao APP.
        - Caso reprovado, o cliente será encaminhado automaticamente com ticket para a central de atendimento da Porto, para tratativas de erros.

Enjoy =)