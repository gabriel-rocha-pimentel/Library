# NOTAS DO LIVRO

## INTRODUÇÃO
+ Construir um site é como construir uma cidade, você espera receber pessoas e trocar informações, pagamentos ou objetos, então devemos prestar atenção em alguns detalhes;
- [Transporte](As pessoas estão entrando no seu site através de qual navegador, e como o seu site esta em relação a eles.);
- [Responsividade](As pessoas acessam seu site através de varias plataformas, como seu site reage aos diferentes dispositivos.);
- [Acessibilidade](Esta é uma necessidade tanto para as pessoas na vida real quando na internet, então como o publico deficiente esta em relação ao seu site.);

### Primeiros Passos
+ Primeiro o usuário precisa estar conectado a internet, e para isso ele usa um ISP(Provedor de Serviço de Internet).
+ Então, quando o usuário quer ver um site no japão, o navegador contata o DNS(Sistema de Nomes de Domínio) através do ISP, o DNS envia a localização do servidor web que hospeda o endereço IP do site no japão.
+ E finalmente o navegador pede ao servidor web para acessar o site, e se for permitido uma copia da pagina do site é carregada no seu navegador.

## CAPITULO 1 e 2
+ Para a criação de um site devemos ficar atentos para alguns pontos principais
- [Documentação](HTML é um arquivo com uma estrutura definida, precisa seguir uma determinada ordem para funcionar.);
- [Estrutura](A estrutura do HTML em si, consiste em uma uma tag <html>, que inclui todas as tags posteriores, e duas tags, o <head> e a <body>, seu proposito é autodescritivo.);
- [Tags](A estrutura das tags consiste em uma tag de abertura "<" e uma tag de fechamento "/>" que tera uma barra para finalizar.);
- [Propridades](Valor e propriedade, algumas tags tem essas configurações especiais que podem ser acessadas através de um valor e propriedade, na tag <html> seria algo como <html lang="pt"></html>, isso define o idioma do documento como português);

## CAPITULO 3
### Listas
Existem dois tipos de listas
* Listas Ordenadas
    As ordenadas precisam seguir um padrão, seja ele númerico, alfabetica, etc. A lista ordenada precisa ter um forma em que cada elemento da lista possa ter um identificador unico.
    - Esta é criada com a tag <ol></ol>
    - E cada item na lista, é criada com a tag <li></li>

* Listas não ordenadas
    A lista não ordenada é definida de forma natural, todos os elementos estão em suas posições iniciais e podem ser reorganziados como bem entender.
    - Listas não ordenadas são criadas com a tag <ul></ul>
    - E assim como as ordenadas as tags de item correspondente são <li></li>


* Listas de Definição
    São listas em que cada item precisa ter uma definição em relação ao item de ligação
    - Listas de definição são criadas com <dl></dl>
    - E os seus items precisam ser identificados com a tag <dt></dt>

* Também é possivel criar listas aninhadas, basta fazer uma lista dentro de outra.

## CAPITULO 4