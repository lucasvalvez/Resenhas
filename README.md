# Resenhas

# Capítulo 5:

Neste capítulo, o autor busca trazer uma abordagem dos aspectos mais fundamentais no desenvolvimento de software, o "projeto de software", é uma leitura essencial para quem deseja entender como projetar software de maneira eficiente e sustentável. No princípio do capítulo, destaca-se a importância de um bom design, explicando que um código bem estruturado facilita a manutenção, a evolução do sistema e evita o famoso "código espaguete", onde tudo está interligado de forma confusa e difícil de modificar.

Para isso, ele introduz alguns princípios fundamentais que ajudam a guiar um bom projeto. A ideia principal é manter o código organizado, modular e de fácil extensão. Um dos conceitos mais enfatizados é a relação entre coesão e acoplamento. Coesão diz respeito a quão bem as partes de um módulo estão relacionadas entre si – quanto maior a coesão, mais focada e eficiente é uma classe ou um módulo. Já o acoplamento trata do nível de dependência entre diferentes partes do sistema – um software bem projetado deve ter baixo acoplamento, permitindo que suas partes sejam alteradas sem impactar todo o sistema.

O autor então apresenta os famosos princípios SOLID, que são diretrizes fundamentais para escrever código de qualidade. Ele explica como cada um deles contribui para criar um software mais flexível e fácil de manter. O princípio da responsabilidade única, por exemplo, mostra como é importante que cada classe tenha um propósito bem definido, evitando que uma única parte do código tente fazer tudo ao mesmo tempo. Já o princípio do aberto/fechado ensina que o código deve ser projetado para permitir novas funcionalidades sem que seja necessário modificar o que já está pronto, garantindo maior estabilidade ao sistema.

Ao longo do capítulo, Valente também discute padrões de projeto, como Singleton, Factory Method e Observer, que são soluções reutilizáveis para problemas comuns no desenvolvimento de software. Ele não apenas explica o que são esses padrões, mas também ilustra seu uso com exemplos práticos, tornando o aprendizado mais intuitivo.

A grande sacada desse capítulo é que ele não se limita à teoria; ele mostra na prática como esses conceitos podem ser aplicados no dia a dia de um desenvolvedor. Além disso, o autor apresenta exemplos de boas e más práticas, ajudando o leitor a identificar e evitar erros comuns no design de software.

No fim das contas, esse capítulo é um verdadeiro guia para quem deseja escrever código de forma mais estruturada e inteligente. Ele ensina que projetar software não é apenas sobre fazê-lo funcionar, mas sim sobre fazê-lo funcionar de um jeito que permita futuras melhorias sem grandes dores de cabeça.

# Capítulo 6:

O autor começa explicando a diferença entre arquitetura e design de software, destacando que a arquitetura está em um nível mais alto de abstração, lidando com decisões que impactam a estrutura global do sistema, enquanto o design foca em aspectos mais detalhados da implementação.

Ao longo do capítulo, são apresentados diferentes estilos arquiteturais, mostrando como cada um possui vantagens e desafios específicos. Um dos mais clássicos é o modelo em camadas, amplamente utilizado em sistemas corporativos, onde cada camada tem um papel bem definido, como a camada de apresentação, a de lógica de negócio e a de acesso a dados. Esse modelo é vantajoso por sua organização e separação de responsabilidades, mas pode se tornar engessado conforme o sistema cresce.

Outro estilo muito discutido é o MVC (Model-View-Controller), bastante popular no desenvolvimento de aplicações web e desktop. Ele divide a aplicação em três partes: o Modelo, que representa os dados e regras de negócio; a Visão, que cuida da interface com o usuário; e o Controlador, que gerencia a comunicação entre modelo e visão. Esse padrão ajuda a manter um código mais modular e facilita a manutenção.

Além dos modelos mais tradicionais, o autor também aborda arquiteturas mais modernas, como microsserviços. Esse estilo tem ganhado cada vez mais espaço, principalmente em sistemas distribuídos e escaláveis. Diferente de uma arquitetura monolítica, onde toda a aplicação é um grande bloco único, os microsserviços dividem o sistema em serviços menores, independentes e que podem ser desenvolvidos, implantados e escalados separadamente. Isso traz diversas vantagens, como maior flexibilidade e resiliência, mas também aumenta a complexidade na comunicação entre os serviços.

Outro conceito importante discutido no capítulo é a arquitetura orientada a eventos, usada em sistemas que precisam responder rapidamente a mudanças, como aplicações de streaming e sistemas financeiros. Nesse modelo, componentes do sistema se comunicam através de eventos, tornando a aplicação mais desacoplada e escalável.

O autor não se limita apenas a descrever essas arquiteturas, mas também traz exemplos práticos e discute os desafios reais enfrentados ao aplicá-las. Ele mostra, por exemplo, como escolher a arquitetura adequada dependendo do tipo de sistema que está sendo desenvolvido.

No final, o grande aprendizado desse capítulo é que não existe uma única arquitetura perfeita para todos os casos. Cada escolha envolve trade-offs, e um bom arquiteto de software deve avaliar bem os requisitos do sistema antes de decidir qual abordagem seguir. É um capítulo essencial para quem quer entender como estruturar software de forma eficiente, garantindo tanto a escalabilidade quanto a facilidade de manutenção no longo prazo.







