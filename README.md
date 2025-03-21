#  __*Introdução ao Tema*__


- Os discos rígidos (HDDs) têm sido fundamentais no armazenamento de dados por décadas, oferecendo uma solução acessível e de alta capacidade. Mesmo com o avanço dos SSDs, os HDDs continuam amplamente usados, especialmente em ambientes corporativos. As interfaces SATA (Serial ATA) e SAS (Serial Attached SCSI) são essenciais para a comunicação entre os discos e o sistema, sendo a base do armazenamento tradicional em muitos servidores e estações de trabalho.



# __🔹 Funcionamento e Características__


- __HDD__ é a sigla, em inglês, para Hard Disk Drive, tipo de armazenamento (disco rígido)

 -O recurso tem uma função fundamental no computador: salvar e armazenar todos os seus arquivos.

__Como funciona__

  O HD (disco rígido) é um dos principais componentes do computador, responsável por armazenar todos os arquivos e programas. Ele funciona como uma biblioteca, onde cada dado tem um lugar específico para ser guardado e um índice que ajuda a encontrá-lo rapidamente.
Dentro do HD, há um prato que gira rapidamente e contém pequenos espaços onde os dados ficam armazenados. Para acessar essas informações, existe um braço de leitura, que se move sobre o prato para ler ou gravar os dados necessários. Como os arquivos podem ser armazenados em diferentes partes do disco (não em ordem contínua), um sistema de índice ajuda o braço de leitura a encontrar tudo de forma eficiente.

Por serem peças delicadas, o prato e o braço de leitura ficam protegidos dentro de uma caixa de metal, evitando danos no uso normal.

Todo computador precisa de um disco de armazenamento para guardar o sistema operacional, programas e arquivos, garantindo que tudo funcione corretamente.




```
```
- __SATA__ e __SAS__ são interfaces de conexão para esse tipo de armazenamento.

O SATA é uma interface de disco rígido que você usa para ler e gravar dados do e para o armazenamento, que pode ser SSD ou HDD. 

O SATA (Serial ATA) é uma interface usada para conectar dispositivos de armazenamento, como HDDs (discos rígidos) e SSDs (unidades de estado sólido), ao computador. Ele permite a leitura e gravação de dados de forma eficiente e rápida.

Nos SSDs SATA, os dados são armazenados em chips de memória flash, o que os torna muito mais rápidos do que os HDDs, que dependem de partes móveis para acessar as informações. Como não há necessidade de esperar um disco girar ou uma cabeça de leitura se mover, o acesso aos dados acontece de maneira quase instantânea.

A interface SATA também garante ampla compatibilidade, ou seja, é suportada pela maioria dos computadores e notebooks, facilitando a transição de um HDD para um SSD. Seu funcionamento resulta em inicializações mais rápidas e tempos de carregamento reduzidos para aplicativos e sistemas operacionais. Além disso, os dispositivos SATA consomem menos energia, o que é vantajoso para notebooks, prolongando a vida útil da bateria.

Já o SAS (Serial Attached SCSI) é um protocolo usado principalmente em servidores e sistemas corporativos para conectar dispositivos de armazenamento de alta performance, como HDDs e SSDs voltados para data centers.

Diferente do SATA, o SAS opera com um sistema ponto a ponto, onde cada dispositivo de armazenamento se comunica diretamente com o computador através de uma conexão dedicada. Isso significa que os dados são transferidos de forma mais eficiente e confiável. Além disso, a transmissão acontece de forma serial, ou seja, um bit por vez, garantindo precisão e estabilidade na comunicação.

O SAS é implementado em sistemas que utilizam HBAs (Host Bus Adapters), permitindo a conexão de múltiplos dispositivos de armazenamento de forma escalável. Essa tecnologia é muito utilizada em servidores porque oferece alta velocidade, confiabilidade e suporte para grandes volumes de dados, sendo essencial para empresas que precisam de armazenamento robusto e de alto desempenho.

```
```





## __HDD:__

###  __*Vantagens-*__
- Custo mais baixo por GB de armazenamento.
- Alta capacidade de armazenamento (ideal para grandes volumes de dados).
- Boa relação custo/GB, sendo econômico para armazenar grandes quantidades de dados.
- Longevidade de armazenamento para dados que não precisam ser acessados frequentemente.
- Facilidade de recuperação de dados em caso de falha.


### __*Desvantagens-*__
- Desempenho mais lento em comparação com SSDs.
- Partes móveis tornam o HDD mais vulnerável a danos físicos.
- Maior consumo de energia.
- Ruído e aquecimento devido às partes móveis.
- Menor resistência a impactos em comparação com SSDs.
- Maior tamanho físico e peso


## __SATA:__

 ### __*Vantagens-*__
- Baixo custo
- Fácil instalação
- Boa compatibilidade
- Adequado para uso pessoal e de escritório
- Menor consumo de energia

### __*Desvantagens-*__
- Desempenho limitado
- Menor escalabilidade e recursos avançados em comparação com SAS
- Menos confiável em ambientes de alta demanda



# __SAS:__

### __*Vantagens-*__
- Desempenho muito superior ao SATA (até 12 Gb/s)
- Alta confiabilidade, com características de detecção e recuperação de falhas
- Escalabilidade, ideal para servidores e datacenters
- Maior durabilidade e resistência, ideal para uso em ambientes empresariais
- Melhor desempenho em configurações RAID
- Suporta discos de maior capacidade


### __*Desvantagens-*__
- Custo mais alto, o que pode não justificar para uso doméstico
- Complexidade maior na configuração e manutenção
- Menor compatibilidade com hardware doméstico
- Maior consumo de energia em comparação com o SATA
- Necessita de controladores especiais para operação





# __Aplicações e Exemplos Práticos__
### HDD -   Aplicações práticas comuns incluem:

__1. Armazenamento em Servidores de Baixo Custo:__

Exemplo Prático: Pequenos servidores ou servidores domésticos, como um NAS (Network Attached Storage), frequentemente usam HDDs por causa do seu custo por gigabyte mais baixo em comparação com os SSDs. Esses servidores podem ser usados para armazenar grandes quantidades de dados, como backups, mídia de vídeo e arquivos compartilhados.
Aplicação: Armazenamento em servidores e sistemas NAS para backup de dados, mídia e arquivos compartilhados.

__2. Sistemas de Videomonitoramento (CFTV):__

Exemplo Prático: Os sistemas de câmeras de segurança e videomonitoramento frequentemente utilizam HDDs para gravar vídeos de câmeras em alta definição (HD ou 4K). Como esses sistemas geralmente gravam continuamente por longos períodos de tempo, os HDDs oferecem uma solução econômica para armazenar grandes volumes de vídeo.
Aplicação: Armazenamento de gravações de câmeras de segurança (CFTV) em empresas ou residências.

__3. Data Centers e Armazenamento em Nuvem:__

Exemplo Prático: Muitos data centers de empresas de hospedagem e provedores de armazenamento em nuvem, especialmente em soluções de armazém de dados de longo prazo (cold storage), utilizam HDDs devido ao baixo custo de aquisição em comparação com SSDs. Embora os SSDs sejam usados para armazenamento de dados ativos (com acesso frequente), os HDDs são uma escolha popular para armazenamento de dados que não precisam de acesso rápido.
Aplicação: Armazenamento de dados em larga escala em data centers e soluções de armazenamento em nuvem.

```
```

### SATA - Principais aplicações incluem:

__1. Armazenamento de Dados em Servidores de Pequeno Porte:__

Exemplo Prático: Servidores de pequeno porte ou NAS (Network Attached Storage) usam dispositivos de armazenamento conectados via SATA para armazenar e compartilhar dados entre múltiplos usuários em redes locais (LAN).
Aplicação: Armazenamento em servidores e sistemas NAS para backup de dados, compartilhamento de arquivos e armazenamento de mídia.

__2. Armazenamento em Datacenters (Cold Storage):__ 

Exemplo Prático: Em datacenters, onde grandes volumes de dados precisam ser armazenados a um custo acessível, os discos SATA podem ser usados para cold storage (armazenamento de longo prazo para dados pouco acessados).
Aplicação: Armazenamento de dados em larga escala que não requerem acesso frequente, como backups de longo prazo ou dados arquivados.

__3. Sistemas de Vídeo Vigilância (CFTV):__ 

Exemplo Prático: Sistemas de câmeras de segurança que armazenam longas gravações de vídeo, como câmeras IP e sistemas de CFTV, usam HDDs SATA para gravar imagens de vídeo por longos períodos.
Aplicação: Armazenamento de gravações de câmeras de segurança em sistemas de videomonitoramento, onde a quantidade de armazenamento é essencial para gravar grandes volumes de dados de vídeo.
```
```

### SAS -  Principais aplicações incluem:

__1. Armazenamento em Servidores Empresariais:__

Exemplo Prático: Servidores de alto desempenho em empresas e datacenters utilizam SAS para conectar discos rígidos e SSDs devido à sua alta velocidade e confiabilidade. O SAS é utilizado para armazenar dados críticos e garantir uma rápida resposta em ambientes de missão crítica, como servidores de banco de dados ou servidores web.
Aplicação: Armazenamento em servidores de missão crítica, como bancos de dados, servidores de arquivos e servidores de aplicativos empresariais.

__2. Armazenamento de Dados Críticos em Ambientes Empresariais:__

Exemplo Prático: Empresas que lidam com dados críticos, como registros financeiros, dados médicos ou informações confidenciais, usam SAS para garantir a alta confiabilidade e desempenho nas operações diárias. O SAS é ideal para esses ambientes devido à sua capacidade de fornecer uma alta taxa de transferência e suporte para longas sessões de gravação e leitura.
Aplicação: Armazenamento de dados sensíveis, como em sistemas bancários, médicos, governamentais e outras aplicações que exigem alta disponibilidade e desempenho.

__3. Armazenamento para Backup Empresarial:__

Exemplo Prático: Empresas utilizam SAS para configurar sistemas de backup com múltiplos discos rígidos em configurações RAID. A alta confiabilidade e a taxa de transferência rápida garantem que os dados sejam copiados e recuperados rapidamente em caso de falhas.
Aplicação: Armazenamento e backup de dados empresariais críticos, com alta disponibilidade e segurança.


```
```

# __Diferenças entre SATA e SAS.__


- A principal diferença entre os dois é a velocidade de transferência de dados. 

O SAS é uma interface de comunicação ponto a ponto (p2p) que faz a transferência de dados serialmente. O SATA é um padrão de comunicação desenvolvido para conectar e transferir dados entre os discos e as motherboards. 
O SAS é a evolução do SATA, mantendo a comunicação em paralelo, mas entregando um padrão totalmente novo de SCSI. 
O SAS pode ser uma boa opção para empresas que precisam de múltiplas unidades de armazenamento de alta performance. O SATA é uma boa opção para necessidades mais comuns como o armazenamento de alta




# __Velocidade, confiabilidade e aplicações típicas.__

__HDDs (Hard Disk Drive)__

Velocidade:
A velocidade dos HDDs é determinada pela rotação dos discos (medida em RPM, rotações por minuto). Os modelos mais comuns têm 5400 ou 7200 RPM, com velocidades de leitura e gravação geralmente entre 80 e 160 MB/s.

Confiabilidade:
Os HDDs são confiáveis para armazenar grandes volumes de dados a longo prazo, mas sua confiabilidade pode ser comprometida por fatores como desgaste mecânico ou quedas físicas. Eles possuem uma vida útil média de cerca de 3 a 5 anos em uso intenso, dependendo do modelo e dos cuidados.

	Aplicações típicas:
Armazenamento de longo prazo: usados para backups, arquivamento de documentos e armazenar grandes arquivos, como vídeos e imagens.
Computadores pessoais e servidores: especialmente onde o custo-benefício é prioritário.
Data Centers e empresas: para armazenar grandes volumes de dados que não precisam ser acessados frequentemente.


__SATA (Serial ATA)__


	Velocidade:
Existem diferentes versões do SATA, cada uma com sua taxa de transferência máxima:
SATA I: até 1,5 Gbps (~150 MB/s)
SATA II: até 3 Gbps (~300 MB/s)
SATA III: até 6 Gbps (~600 MB/s)
A velocidade também depende do dispositivo conectado, como HDDs ou SSDs. SSDs SATA, por exemplo, conseguem alcançar taxas próximas ao limite da interface SATA III.

	Confiabilidade:
O padrão SATA é confiável para a maioria dos dispositivos de armazenamento, sendo amplamente utilizado há décadas. (introduzido no início dos anos 2000)
Embora os SSDs SATA tenham maior durabilidade por não possuírem partes móveis, HDDs SATA podem ser mais suscetíveis a falhas mecânicas.
A confiabilidade varia com a qualidade dos dispositivos e o uso; o padrão em si é bastante estável.

	Aplicações típicas:
HDDs e SSDs em computadores pessoais: O SATA é a interface mais comum para discos rígidos e SSDs em desktops e laptops, oferecendo boa relação custo-benefício.
Servidores de médio porte: Usado em cenários onde a velocidade extrema do NVMe não é necessária. (NVMe (Non-Volatile Memory Express) é um protocolo de comunicação projetado para dispositivos de armazenamento que utilizam memória não volátil)
Armazenamento externo: Muitos discos rígidos e SSDs externos usam interfaces SATA, conectados via adaptadores ou gabinetes USB.

__SAS (Serial Attached SCSI)__
	
	Velocidade:
O SAS oferece velocidades superiores em comparação ao SATA, com diferentes versões:
SAS-1: até 3 Gbps (~375 MB/s)
SAS-2: até 6 Gbps (~750 MB/s)
SAS-3: até 12 Gbps (~1,5 GB/s)
SAS-4: até 22,5 Gbps (~2,8 GB/s)
Além disso, os discos SAS geralmente têm velocidades de rotação mais altas (10.000 ou 15.000 RPM), o que melhora o desempenho em comparação com discos SATA.

	Confiabilidade:
Os discos SAS são projetados para uso intensivo em servidores e data centers, oferecendo maior durabilidade e confiabilidade.
Eles possuem um MTBF (Mean Time Between Failures) mais alto, geralmente em torno de 1,6 milhão de horas, o que os torna ideais para ambientes críticos. (O MTBF (Mean Time Between Failures) é uma métrica utilizada para avaliar a confiabilidade de um equipamento ou sistema. Ele representa o tempo médio esperado entre falhas consecutivas)
Suportam recursos como redundância e detecção de erros avançada, aumentando a segurança dos dados.

	Aplicações típicas:
Servidores e data centers: usados em ambientes corporativos que exigem alta performance e confiabilidade.
Armazenamento de dados críticos: ideal para bancos de dados, sistemas de transações financeiras e outras aplicações que demandam acesso rápido e constante.
Sistemas de virtualização: devido à sua capacidade de lidar com cargas de trabalho intensivas.


# __🔹 Curiosidades e Tendências Futuras__


### __Curiosidades SATA__

- Substituiu o PATA – O SATA substituiu o antigo PATA (Parallel ATA), que usava cabos largos e mais lentos.

- Velocidades Crescentes – As versões do SATA foram evoluindo:

- SATA I (1,5 Gb/s)

- SATA II (3,0 Gb/s)

- SATA III (6,0 Gb/s)


### __SAS (Serial Attached SCSI)__

- Mais Rápido que SATA – O SAS pode atingir velocidades de 12 Gb/s ou mais, ideal para servidores e data centers.

### __Curiosidades HD__

- O Primeiro HD Tinha 5MB – O IBM 305 RAMAC (1956) pesava mais de uma tonelada e tinha apenas 5 MB de capacidade.

- Partículas de Poeira Podem Danificar o HD – O espaço entre o cabeçote e os pratos do HD é menor que um fio de cabelo! Uma única partícula de poeira pode resultar em uma falha catastrófica do disco.



## Tendencias futuras

- O SATA tem sido amplamente utilizado em SSDs e HDDs de baixo custo, mas seu futuro é incerto devido ao avanço das interfaces mais rápidas, como o NVMe (PCIe), que já estão no mercado e oferecem desempenho muito superior. 

- O SAS é amplamente utilizado em servidores e armazenamento empresarial, oferecendo maior confiabilidade e velocidade em comparação com o SATA. No entanto, com o avanço e o o crescimento do NVMe em infraestrutura corporativa, o SAS pode perder relevância nos próximos anos. 

- Apesar da ascensão dos SSDs, os HDDs continuam sendo a principal opção para armazenamento de grande volume. A indústria está focada no aumento da capacidade, utilizando novas tecnologias para maximizar a densidade dos discos. Embora os HDDs não possam competir em velocidade com os SSDs, eles continuarão sendo essenciais para armazenamento em massa e backups.


# __FONTES:__


https://recoverit.wondershare.com.br/hard-drive/what-is-sata.html

https://www.techtudo.com.br/noticias/2015/12/o-que-e-hdd-conheca-tecnologia-que-guarda-seus-dados-para-sempre.ghtml

https://www.controle.net/faq/sata-vs-sas-qual-a-diferenca-desses-hard-disks

https://blog.hostone.com.br/armazenamento-ssd-sas-sata/

