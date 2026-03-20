## Os primeiros passos para uma solução

O problema que você viveu naquela manhã de 1955 não era novo. Acontecia em laboratórios, universidades e empresas em todo o mundo, toda vez que um equipamento era trocado, atualizado ou simplesmente substituído por um modelo mais novo. E não era só isso.

Havia um segundo problema, igualmente frustrante, que acontecia todos os dias mesmo quando o hardware não mudava.

Imagine a rotina do laboratório. Você termina o seu programa, entrega os cartões perfurados para o operador, e entra numa fila. Porque o computador é um só, e há dezenas de pesquisadores querendo usá-lo. O operador pega o programa da fila, carrega os cartões na máquina, inicia a execução, espera o programa terminar, anota o resultado, descarrega os cartões, e só então pega o próximo programa da fila. Um de cada vez. Com pausa entre cada um. Com um ser humano no meio de cada etapa.

E durante essas pausas, o computador ficava completamente parado. Não executava nenhum cálculo, não fazia nada. Simplesmente esperava o operador terminar o que estava fazendo. Num equipamento que custava o equivalente a vários milhões de reais de hoje, ter o componente mais caro do sistema parado esperando um humano trocar um maço de cartões era um desperdício que ninguém conseguia ignorar.

Mas havia ainda algo pior do que as pausas entre programas. Mesmo durante a execução, o computador passava muito tempo sem fazer nada útil. Quando um programa precisava imprimir um resultado, enviava os dados para a impressora e então ficava esperando ela terminar. Impressoras mecânicas são lentas. O computador esperava. Quando precisava ler dados de um disco magnético, esperava o disco girar até a posição correta. O computador esperava. Para cada operação que envolvia um dispositivo físico, havia uma espera, e durante essa espera o computador não fazia absolutamente nada.

A percepção que foi surgindo em várias instituições ao mesmo tempo era inevitável: precisava existir alguma coisa entre o hardware e os programas. Algo que gerenciasse a fila. Algo que aproveitasse as esperas. Algo que poupasse cada programador de ter que aprender a falar com cada dispositivo do zero.

Em 1956, essa percepção se tornou realidade pela primeira vez.

A General Motors e a North American Aviation eram duas das maiores empresas dos Estados Unidos, e ambas usavam o mesmo computador: o IBM 704, um dos mais poderosos da época. As duas estavam cansadas do mesmo desperdício. Então, numa parceria que hoje pareceria improvável entre uma montadora de carros e uma fabricante de aviões, elas desenvolveram juntas um programa especial para o IBM 704. Um programa cujo único objetivo era gerenciar outros programas.

Ele se chamava **GM-NAA I/O**, nome formado pelas iniciais das duas empresas mais a sigla de Entrada e Saída em inglês. E o que ele fazia era simples: em vez de um operador humano carregando um programa por vez com pausa entre eles, o GM-NAA I/O lia um conjunto de programas de uma vez, os executava em sequência automaticamente, e passava para o próximo assim que um terminava. Se um programa dava erro, o sistema registrava o problema e avançava para o seguinte sem precisar de nenhuma intervenção humana.

Parece pouca coisa. Mas foi o primeiro momento na história em que um computador foi responsável por gerenciar a si mesmo.

O tempo ocioso entre programas caiu drasticamente. A IBM percebeu o potencial imediatamente, e começou a incluir sistemas semelhantes nos computadores que vendia. Esse modelo ficou conhecido como **processamento em lote**, do inglês _batch processing_: em vez de executar programas um por um com pausa entre eles, você preparava um lote inteiro e o computador os executava sem parar.

Mas o processamento em lote resolvia apenas uma parte do problema. Quando um programa começava a rodar, ele ainda tomava o computador inteiro para si. Todos os outros programas da fila precisavam esperar. Todos os outros pesquisadores precisavam esperar. E se um cálculo levasse horas, horas era o tempo que todo o resto ficava parado.

Havia uma pergunta que começava a incomodar cada vez mais pessoas: por que um computador capaz de executar bilhões de operações por segundo precisava ficar preso num único programa de cada vez?

---

Em 1959, um cientista da computação chamado **John McCarthy** publicou uma proposta que parecia impossível: e se um único computador pudesse atender vários pesquisadores ao mesmo tempo?

A ideia era a seguinte. Em vez de um programa ocupar o computador inteiro enquanto rodava, o sistema daria a cada programa uma fatia minúscula de tempo, algumas frações de segundo, e então passaria para o próximo, e para o próximo, e assim por diante em ciclo contínuo. Isso aconteceria tão rapidamente que cada pesquisador teria a sensação de estar usando o computador sozinho, quando na realidade dezenas de pessoas estariam compartilhando o mesmo hardware ao mesmo tempo.

Era uma ideia elegante. E era, também, extremamente difícil de implementar.

Em 1961, o MIT colocou essa ideia em prática com o **CTSS**, _Compatible Time-Sharing System_. Rodando num IBM 7094, o CTSS permitia que até 32 pesquisadores se conectassem ao computador ao mesmo tempo, cada um por um terminal remoto, e trabalhassem de forma completamente independente. Cada um digitava comandos, executava programas, recebia respostas, tudo parecendo imediato, como se o computador fosse só deles.

O impacto foi imediato e profundo. Pesquisadores que antes precisavam agendar tempo de máquina com dias de antecedência agora simplesmente sentavam num terminal e começavam a trabalhar. A produtividade explodiu. E com ela, surgiu algo que ninguém tinha antecipado completamente: uma série de problemas novos que o processamento em lote nunca precisou resolver.

Quando um único pesquisador usava o computador por vez, não havia nada para proteger: era ele e a máquina. Mas quando trinta pesquisadores usavam o mesmo computador ao mesmo tempo, cada um com seus próprios arquivos e seus próprios programas, as perguntas se multiplicavam. Como garantir que o programa de um pesquisador não acesse ou apague os arquivos de outro? Como evitar que um programa com erro derrube o sistema inteiro e interrompa o trabalho de todos? Como organizar os arquivos de dezenas de pessoas no mesmo disco sem que virem uma bagunça impossível de gerenciar?

Responder a essas perguntas exigia algo muito mais completo do que uma fila inteligente de execução. Exigia um sistema inteiro de coordenação. E foi para construir esse sistema que surgiu, em 1964, o projeto mais ambicioso da história da computação até aquele momento.

---

O MIT, os Bell Labs da AT&T e a General Electric se uniram com um objetivo declarado: construir o sistema operacional definitivo, que resolvesse de uma vez por todas todos esses problemas. O projeto se chamou **Multics**, de _Multiplexed Information and Computing Service_. A ideia era criar algo tão completo e robusto que durasse décadas.

O Multics foi pioneiro em ideias que usamos até hoje. Ele introduziu as pastas dentro de pastas que você usa toda vez que organiza arquivos no computador. Introduziu as permissões de acesso, a capacidade de definir quem pode ler ou modificar cada arquivo. Introduziu formas de dar a cada programa a ilusão de ter mais memória disponível do que fisicamente existia.

Era extraordinariamente ambicioso. E era, também, extraordinariamente difícil de construir.

O projeto atrasou anos. Custou muito mais do que o previsto. Quando ficou pronto, era considerado por muitos excessivamente complexo e lento para o hardware da época. Em 1969, os Bell Labs desistiram e se retiraram.

Dois dos engenheiros que tinham trabalhado no Multics ficaram sem um sistema operacional para usar. Um deles, **Ken Thompson**, estava no meio do desenvolvimento de um jogo que rodava no Multics, e precisava de alguma máquina onde pudesse continuar. Havia um computador pequeno acumulando poeira num canto dos Bell Labs, praticamente ninguém usava. Thompson e seu colega **Dennis Ritchie** começaram a escrever um sistema operacional simplificado para ele. Sem reuniões de comitê. Sem a burocracia que havia engessado o Multics. Dois engenheiros, um computador ocioso, e um problema prático para resolver.

Em 1969, Thompson escreveu o núcleo do sistema em três semanas. Em 1970, o sistema ganhou um nome: **Unix**. Uma brincadeira com o nome Multics, trocando o prefixo _Multi_ pelo prefixo _Uni_, sugerindo algo mais simples e focado.

---

O Unix não era o mais poderoso nem o mais rápido sistema da época. Mas tinha algo que os outros não tinham: uma filosofia clara.

Thompson e Ritchie construíram o Unix em torno de uma ideia que parece simples mas tem consequências profundas: os programas não deveriam precisar saber como o hardware funciona por dentro. Eles deveriam simplesmente pedir ao sistema operacional o que precisam, e o sistema operacional se encarregaria de todos os detalhes.

Essa ideia resolveu, de uma vez, o problema que você viveu naquela sala de 1955. Num mundo com o Unix, quando o hardware muda, apenas o sistema operacional precisa ser atualizado. Os programas continuam funcionando exatamente como antes, porque eles nunca falaram diretamente com o hardware para começo de conversa. Falavam com o Unix. E o Unix se entendia com o hardware no lugar deles.

O Unix se espalhou pelas universidades americanas ao longo dos anos 1970. A AT&T, impedida por lei de comercializar software na época, distribuía o código-fonte livremente para fins acadêmicos. Uma geração inteira de cientistas da computação aprendeu como sistemas operacionais funcionam estudando o Unix por dentro. As ideias de Thompson e Ritchie moldaram toda a área.

Quando as restrições legais mudaram e a AT&T tentou comercializar o Unix, as universidades não queriam voltar para um sistema fechado que não podiam mais estudar e modificar. Em 1991, um estudante finlandês de 21 anos chamado **Linus Torvalds** começou a escrever do zero o seu próprio sistema inspirado no Unix, completamente livre e aberto para qualquer pessoa usar, estudar e modificar. Ele o chamou de **Linux**.

Hoje, o Linux roda nos servidores que hospedam boa parte da internet, nos supercomputadores mais poderosos do mundo, e em praticamente todos os smartphones do planeta, sob o nome Android. O macOS da Apple e o iOS dos iPhones têm raízes diretas no Unix. Décadas de computação moderna foram construídas sobre as ideias que dois engenheiros colocaram num computador empoeirado num laboratório de pesquisa em 1969, porque precisavam de um lugar para rodar um jogo.