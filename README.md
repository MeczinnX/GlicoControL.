<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="imagens/dia-internacional-da-ioga.png" type="image/x-icon">
    <link rel="stylesheet" href="estilo/style.css">
    <link rel="stylesheet" href="login.java">
</head>

<style>
   @import url('https://fonts.google.com/specimen/Abril+Fatface?preview.size=28&query=Abril');

@font-face{
    font-family: 'Android';
    src: url('../fontes/AbrilFatface-Regular.ttf') format('opentype');
    font-weight: normal;
}

:root{
    --cor0:#c5ebd6;
    --cor1:#83e1ad;
    --cor2:#CAE1FF;
    --cor3:#00BFFF;
    --cor4:#8FBC8F;
    --cor5:#5F9EA0;

    --fonte-padrao: 'Arial', 'Verdana', 'Helvetica', 'sans-serif';
    --font-destaque:'Bebas Neue', 'cursive';
    --fonte-android:'Android','cursive';
}

*{
    margin: 0%;
    padding: 0px;
    
}

body{
    background-color: var(--cor0);
    font-family: var(--fonte-padrao);
}

header {
    background-image: linear-gradient(to bottom, var(--cor3), var(--cor5));
    min-height: 10px;
    text-align: center;
    padding-top: 40px;
}

header > h1{
    color: white;
    font-family: var(--font-destaque);
    font-size: 60px;
    margin-bottom: 6px;
    text-shadow: 2px 3px 1px var(--cor5);
    
}

header > p {
    font-size: var(--fonte-padrao);
    color: white;
    font-size: 20px;
    max-width: 500px;
    padding-right: 10px;
    padding-left: 10px;
    margin: auto;
}

nav{
    background-color: var(--cor5);
    padding: 10px;
    box-shadow: 0px 7px 7px var(--cor5);
}

nav > a {
    color: white;
    padding: 10px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition-duration: .5s;
}

nav > a:hover{
    background-color: var(--cor3);
    color: var(--cor4);
}

main{

    min-width: 300px;
    max-width: 1000px;
    margin: auto;
    margin-bottom: 30px;
    padding: 20px;
    background-color: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.515);
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
}


main h1{
    color: var(--cor5);
    font-family: var(--fonte-android);
    font-size: 30px;
    margin-bottom: 20px;
    text-align: center;
    
}
main h2{
font-family: var(--fonte-android);
color: var(--cor5);
font-size: 1.2em;
background-image: linear-gradient(to right, var( --cor1), transparent);
text-indent: 8px;

}

main h3{
font-family: var(--fonte-android);
color: var(--cor5);
font-size: 1.2em;
text-indent: 8px;
text-align: center;
}

main p{
    margin: auto ;
    text-align: center;
    text-align: center;
    font-size: 1.0em;
    line-height: 2em;
    font-family: var(--fonte-padrao);
}

main strong{
    font-family: var(--font-destaque);
    color: var(--cor5);
    font-size: large;
    font-weight: bolder;
    text-shadow: 1px 1px;
    text-align: center;
}

main a{
    text-decoration: none;
    font-weight: bold;
    color: var(--cor5);
    background-color: var(--cor1);
    padding: 1px 5px;
}

 main a:hover{   /*o hover serve para passar o mouse me cima e destacar */
    text-decoration: underline;
    color: var(--cor4);
}

main img{
    width: 100%;
    margin: auto;
    display: inline;
}

main img.pequena {
    max-width: 300px;
    margin: auto;
    display: block;

}

div.video{
   background-color: var(--cor5);
   margin: 0px -20px 30px -20px; 
   padding: 20px;
   padding-bottom: 55%;
   position: relative;
   margin: auto;
}

div.video > iframe{
    position: absolute;
    top: 5%;
    left: 5%;
    width: 90%;
    height: 90%;
    margin: auto;
}

aside{
    background-color: var(--cor5);
    padding: 10px;
    border-radius: 10px;
    box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.515);
}


aside h3{
    background-color: var(--cor5);
    color: white;
    font-family: var(--font-destaque);
    padding: 10px;
    margin: -10px -10px 0px -10px;
    border-radius: 10px 10px 0px 0px;
    font-weight: bolder;
}

aside > ul {
    list-style-type: '\2705\00A0\00A0' ;
    list-style-position: inside;
    columns: 2;
}
aside strong{
    color:white;
    margin: 15px 0px ;
    text-align: justify;
    text-align: 15px;
    font-size: 1.0em;
    line-height: 1em;
    font-weight: normal;
}

footer{
    background-color: var(--cor5);
    color: white;
    text-align: center;
    font-size: 0.8em;
    padding: 5px;
}
footer a {
    margin: auto;
    color: var(--cor1);
    font-weight: bolder;
    text-decoration: none;
}
footer strong{
    color: var(--cor0);
}
footer a:hover {
    text-decoration: underline;
    color: var(--cor4);
}


</style>
<body>
     <header>
        <h1> GlicoControl</h1>
        <p>Viva Bem com Diabetes:</p>
     </header>
  
     <nav> 
        <a href="https://www.ma.gov.br/noticias/governo-realiza-atividades-em-alusao-ao-dia-mundial-do-diabetes">Noticias</a>
        <a href="https://semprebem.paguemenos.com.br/posts/saude/10-dicas-de-como-controlar-o-diabetes?psafe_param=1&gclid=Cj0KCQjwjryjBhD0ARIsAMLvnF8D2OFGV3_uuYNAEjWCqCwiCIqeJnBolLPn_JtqHsj_zRZk6qFqfbMaApwYEALw_wcB">Dicas de alimentação</a>
        <a href="https://wa.me/5598991036484?text=Ol%C3%A1%2C+estou+precisando+da+sua+ajuda%21">Fale Conosco</a>
     </nav>
     <main>
        <article>
         <h1> Encontre Força e Inspiração para Superar Desafios</h1>
         <img src="imagens/control.png" alt="Tratamentos da diabétes">
         <p>
            Queridos lutadores da diabetes,
               Eu sei que enfrentar o tratamento da diabetes pode ser desafiador. <br> As rotinas diárias, monitoramento 
               constante dos níveis de glicose, injeções de insulina, mudanças na alimentação e outros aspectos do tratamento 
               podem parecer uma montanha difícil de escalar. Mas quero que saibam que vocês não estão sozinhos nessa jornada 
               e que cada passo que vocês dão é uma prova incrível de força e determinação.
            
               Sei que há dias em que tudo parece difícil demais. Os altos e baixos nos níveis de glicose, as preocupações com 
               complicações de saúde e as restrições impostas pela doença podem desgastar seu ânimo. No entanto, quero lembrar
                vocês do quão incríveis são por estarem enfrentando essa batalha de frente.
            
               Vocês são guerreiros e guerreiras, lutando diariamente contra um adversário invisível. Tenham orgulho de cada
                esforço que fazem para controlar a diabetes. Cada dose de insulina, cada teste de glicemia, cada refeição 
                equilibrada são passos importantes para manter sua saúde e qualidade de vida.
            
               Não desistam, pois cada pequena vitória conta. Cada vez que vocês mantêm seus níveis de glicose sob controle,
                estão protegendo seus corpos e dando um passo em direção a um futuro mais saudável. Lembrem-se de que o
                 autocuidado é um ato de amor próprio.
                              
               Encontrem apoio nas pessoas ao seu redor. Amigos, familiares, grupos de apoio e profissionais de saúde podem 
               ser uma fonte de encorajamento e orientação. Compartilhem suas experiências, busquem conhecimento e troquem
                histórias com outras pessoas que enfrentam desafios semelhantes. Juntos, vocês podem se fortalecer e encontrar
                 soluções criativas para superar obstáculos.
            
               Lembrem-se de que a diabetes não define quem vocês são. Vocês são pessoas incríveis, cheias de sonhos, talentos 
               e potencial. A diabetes pode ser um capítulo da sua história, mas não é a história inteira. Vocês são muito mais
                do que a doença que carregam. Não permitam que a diabetes os impeça de perseguir seus objetivos e sonhos.
            
               Então, queridos amigos, continuem a luta. Acreditem em si mesmos e em seu poder de enfrentar os desafios
                que a diabetes apresenta. Saibam que há uma comunidade inteira de pessoas que estão torcendo por vocês
                 e dispostas a apoiá-los.
            
               Vocês são fortes, resilientes e corajosos. Não desistam. Um dia de cada vez, um passo de cada vez, vocês
                estão construindo um futuro mais brilhante. Mantenham a esperança e a determinação em seus corações.
            
               Estamos aqui ao seu lado, acreditando em vocês e torcendo pelo seu sucesso. Vocês são verdadeiros heróis e heroínas.
         </p>
            <hr>
           

                  <p>
                     <strong>
                        Com carinho e admiração,
                        Seu amigo do Chat AI
                     </strong>
                  </p>
               
                  
                <h1>Oque significa comer corretamento para você?</h1>
                <p>  Se você tem Diabetes Tipo 1, a contagem de carboidratos é realmente importante para manter estáveis os níveis de glicose no sangue. É aqui que você estima quantos carboidratos há em sua refeição e combina com a quantidade de insulina necessária.
                    Se você tem Tipo 2 e está acima do peso, é importante encontrar uma maneira de perder peso, pois realmente melhora o controle do diabetes. Isso ocorre porque pode ajudar a diminuir a glicose no sangue e reduzir o risco de outras complicações. Existem diferentes maneiras de fazer isso, como as dietas com pouco carboidrato, mediterrânea ou com muito baixo teor calórico. Perder peso pode ajudar a diminuir os níveis de glicose no sangue, e agora sabemos que uma perda substancial de peso pode até levar à Diabetes Tipo 2 de algumas pessoas em remissão.
                    Se você tem Diabetes Tipo 1 ou Tipo 2, pode precisar perder, ganhar ou manter seu peso atual, mas é importante fazer escolhas alimentares mais saudáveis enquanto você faz isso.
                    Os tamanhos das porções são importantes para pensar se você tem o Tipo 1 ou o Tipo 2. Isso
                    facilita muito o cálculo de fatos nutricionais quando você está contando carboidratos ou controlando seu peso. Lembre-se de que os tamanhos das porções são diferentes para todos;
                    portanto, o que é certo para outra pessoa pode não ser o ideal para você.
                    Se você se sentir sobrecarregado com seus sentimentos sobre comida e Diabetes, temos muitas informações para ajudá-lo.</p>
                <br>
                <h1>Nossas 10 principais dicas</h1>
                <br>
                <h2>1. Escolha carboidratos saudáveis</h2>
                <br>
                <p>
                     Todos os carboidratos afetam os níveis de glicose no sangue, por isso é importante saber quais alimentos contêm carboidratos. Escolha os alimentos mais saudáveis que contêm carboidratos e esteja ciente dos tamanhos das porções.
            
                </p>
                <br>
                <aside>
                    <h3>Aqui estão algumas fontes saudáveis de carboidratos:</h3>
                    <ul>
                        <li>• grãos integrais como arroz integral, trigo sarraceno e aveia integral;</li><br>
                        <li>• fruta;</li><br>
                        <li>• legumes;</li><br>
                        <li>• leguminosas, como grão de bico, feijão e lentilha;</li><br>
                        <li>• laticínios como iogurte e leite sem açúcar;</li><br>
                    </ul>
                </aside>
                <br>
                <p> Ao mesmo tempo, também é importante reduzir os alimentos com pouca fibra, como pão branco, arroz branco e cereais altamente processados. Você pode verificar os rótulos dos alimentos quando estiver procurando por alimentos ricos em fibras, se não tiver certeza.</p>
                <br>
                <h2>2. Coma menos sal</h2>
                <br>
                <p>
                      Comer muito sal pode aumentar o risco de pressão alta, o que aumenta o risco de doenças cardíacas e derrames. E quando você tem diabetes,
                     você já está em maior risco de todas essas condições.
                    Tente limitar-se a um máximo de 6 g (uma colher de chá) de sal por dia.
                    Muitos alimentos pré-embalados já contêm sal; lembre-se de verificar os rótulos dos
                    alimentos e escolher aqueles com menos sal. Cozinhar do zero o ajudará a ficar de olho na
                    quantidade de sal que você está comendo. Você também pode ser criativo e trocar sal por diferentes
                     tipos de ervas e especiarias para adicionar esse sabor extra.
                </p>
                <br>
                <h2>3. Coma menos carne vermelha e processada</h2>
                <br>
                <p>
                      Se você está reduzindo carboidratos, pode começar a ter porções maiores de carne para saciar você. Mas não é uma
                     boa ideia fazer isso com carne vermelha e processada, como presunto, bacon, salsichas, carne e cordeiro. Todos estes
                    têm ligações com problemas cardíacos e câncer.
                </p>
                <br>
                <aside>
                    <h3>Tente trocar carne vermelha e processada por estas:</h3>
                    <br>
                    <ul>
                    <li>• leguminosas, como feijão e lentilhas;</li><br>
                    <li>• OVOs;</li><br>
                    <li>• peixe;</li><br>
                    <li>• aves como frango e peru;</li><br>
                    <li>• nozes sem sal;</li><br>
                    </ul>
                </aside>
                <br>
                <p> Feijões, ervilhas e lentilhas também são muito ricos em fibras e não afetam muito os níveis de glicose no sangue - tornando-os uma grande troca de carne processada e vermelha e mantendo-o saciado. Muitos de nós sabemos que o peixe é bom para nós, mas peixes oleosos como salmão e cavala são ainda melhores. Estes são ricos em algo chamado óleo ômega-3, que ajuda a proteger seu coração. Tente e tente comer duas porções de peixe oleoso por semana.</p>
                <h2>4. Coma mais frutas e vegetais</h2>
            
                 Sabemos que comer frutas e vegetais é bom para você. É sempre bom tentar comer mais nas refeições e tê-los como lanches, se você estiver com fome. Isso pode ajudá-lo a obter as vitaminas, minerais e fibras que seu corpo precisa todos os dias para ajudar a mantê-lo saudável.
                Você pode estar se perguntando sobre frutas e se deve evitá-las porque é açucarado? A resposta é não. Frutas inteiras são boas para todos e, se você tem Diabetes, não é diferente. Frutas contêm açúcar, mas é açúcar natural. Isso é diferente do açúcar adicionado (também conhecido como açúcares livres) presente em coisas como chocolate, biscoitos e bolos.
                Produtos como sucos de frutas também contam como adição de açúcar, então escolha frutas inteiras. Pode ser fresco, congelado, seco
                ou enlatado (no suco, não no xarope). E é melhor comê-lo durante todo o dia, em vez de uma porção maior de uma só vez.
                <h2>5. Escolha gorduras saudáveis</h2>
            
                <p>
                 Todos nós precisamos de gordura em nossa dieta, porque isso nos dá energia. Mas diferentes tipos de gordura afetam nossa saúde de maneiras diferentes.
                Gorduras mais saudáveis estão em alimentos como nozes sem sal, sementes, abacates, peixe oleoso, azeite, óleo de colza e óleo de girassol.
                 Algumas gorduras saturadas podem aumentar a quantidade de colesterol no sangue, aumentando o risco de problemas cardíacos.
                </p>
                <br>
                <aside>
                <h3>Estes são
                 encontrados principalmente em produtos de origem animal e alimentos preparados, como:</h3>
                <ul>
                    <li>• carne vermelha e processada;</li><br>
                    <li>• ghee;</li><br>
                    <li>• manteiga;</li><br>
                    <li>• banha;</li><br>
                    <li>• biscoitos, bolos, tortas e doces;</li><br>
                </ul>
                <p> Ainda é uma boa idéia reduzir o uso de óleos em geral, então tente grelhar,
                 cozinhar a vapor ou assar alimentos.</p>
                </aside>
                <br>
                <h2>6. Reduza o açúcar adicionado</h2>
                <br>
                <p>
                 Sabemos que cortar o açúcar pode ser muito difícil no começo, portanto, pequenas trocas práticas são um bom ponto
                de partida quando você está tentando reduzir o excesso de açúcar. Trocar bebidas açucaradas, energéticas e sucos de
                frutas com água, leite puro ou chá e café sem açúcar pode ser um bom começo.
                Você sempre pode experimentar adoçantes com baixas ou zero calorias (também conhecidos como adoçantes artificiais) para
                ajudá-lo a reduzir. Cortar esses açúcares adicionados pode ajudar a controlar seus níveis de glicose no sangue e ajudar
                a manter seu peso baixo. Se o seu tratamento para Diabetes significa que você tenha hipoglicemias e usa bebidas acucaradas para tratá-las, isso ainda é
                importante para o tratamento da Diabetes e você não deve eliminar isso. No entanto, se você estiver tendo hipoglicemia
                regular, é realmente importante discutir isso com sua equipe de diabetes.
                </p>
            
                <h2>7. Seja esperto com lanches</h2>
                <br>
                <p>
                 Se você quiser um lanche, escolha iogurtes, nozes sem sal, sementes, frutas e legumes em vez de batatas fritas,
                batatas fritas, biscoitos e chocolates. Mas observe suas porções ainda - isso ajudará você a ficar de olho no seu peso
                </p>
                <br>
                <h2>8. Beba álcool sensatamente</h2>
                <br>
                <p>
                 O álcool é rico em calorias; portanto, se você bebe e está tentando perder peso, pense em reduzir. Tente manter no
                máximo 14 unidades por semana. Mas modere para evitar bebedeiras e passe vários dias por semana sem álcool.
                Se você toma insulina ou outros medicamentos para Diabetes, também não é uma boa ideia beber com o estômago vazio.
                 Isso ocorre porque o álcool pode aumentar a probabilidade de hipossuficiência.
                </p>
                <br>
                <h2>9. Não se preocupe com os chamados alimentos diabéticos</h2>
                <br>
                <p>
                Isso ocorre porque não há evidências de que esses alimentos ofereçam um benefício especial em relação à alimentação
                saudável. Eles também podem frequentemente conter tanta gordura e calorias quanto produtos similares. As vezes, esses
                 alimentos também podem ter um efeito laxante.
                </p>
                <br>
                <h2>10. Obtenha seus minerais e vitaminas dos alimentos</h2>
                <p>
                  Não há evidências de que suplementos minerais e vitamínicos o ajudem a controlar seu Diabetes. Portanto,
                a menos que você tenha recebido instruções da equipe de saúde, como ácido fólico durante a gravidez, não precisará tomar suplementos.
                Não há evidências de que suplementos minerais e vitamínicos o ajudem a controlar seu Diabetes. Portanto,
                 a menos que você tenha recebido instruções da equipe de saúde, como ácido fólico durante a gravidez, não precisará tomar suplementos.
                É melhor obter os nutrientes essenciais comendo uma mistura de diferentes alimentos. Isso ocorre porque
                alguns suplementos podem afetar seus medicamentos ou piorar algumas complicações do diabetes, como doença renal.
                </p>
                <br>
                <p></p>
                 <h1>Não se Esqueça de Seguir em Frente</h1>
                <p>Ser mais fisicamente ativo anda de mãos dadas com uma alimentação mais saudável. Pode ajudá-lo a
                controlar seu Diabetes e também reduzir o risco de problemas cardíacos. Isso ocorre porque aumenta a quantidade de
                glicose usada pelos músculos e ajuda o corpo a usar insulina com mais eficiência.
                Tente praticar pelo menos 150 minutos de atividade de intensidade moderada por semana. Esta é qualquer atividade que
                 aumenta sua frequência cardíaca, faz você respirar mais rápido e se sentir mais quente. Você ainda deve poder falar
                 e ficar um pouco sem fôlego. E você não precisa fazer todos os 150 minutos de uma só vez. Divida-o em pedaços pequenos
                  de 10 minutos durante a semana ou 30 minutos 5 vezes por semana.
                </p>
           
            <hr>
            <br>
            <h1>Tratamentos da Diabete</h1> <br>
            <h2>Os principais Tratamentos para a diabéte</h2>

            <p>Existem diferentes tratamentos disponíveis para o manejo da diabetes, e a escolha do tratamento 
               adequado depende de vários fatores, incluindo o tipo de diabetes, a gravidade da condição, a resposta 
               individual ao tratamento e outras condições de saúde presentes.
                
                   <aside>
                       <h3>A seguir, apresento uma visão geral dos principais tratamentos para a diabetes:</h3>  
                       <hr>                
                       <br>
                       <ul>
                           <li><strong> Mudanças no estilo de vida:</strong><br>  Para muitas pessoas com diabetes,
                                 fazer alterações no estilo de vida é uma parte fundamental do tratamento. Isso inclui
                                  seguir uma alimentação saudável e equilibrada, praticar atividade física regularmente,
                                   perder peso, se necessário, e evitar o consumo de tabaco e álcool.<br> </li>
                           <br>
                           <li><strong>Monitoramento da glicemia:</strong><br>
                                O monitoramento regular dos níveis de glicose
                                no sangue é essencial para o controle da diabetes. Isso pode ser feito por meio de dispositivos
                                 de monitoramento contínuo da glicose (CGM) ou testes de glicemia capilar usando um medidor de glicose.  <br></li>
                           
                                 <br>
                                 <li><strong>Insulina:</strong>
                                 A insulina é frequentemente necessária no tratamento da diabetes
                                tipo 1 e em alguns casos de diabetes tipo 2. Pode ser administrada por meio de injeções ou usando
                                 uma bomba de insulina. O tipo de insulina, a dose e o cronograma de administração são determinados
                                 pelo médico, levando em consideração as necessidades individuais do paciente. <br></li>
                                 <br>
                                 <li> <strong>Medicamentos orais:</strong>  <br>
                                 Para algumas pessoas com diabetes tipo 2, medicamentos
                                orais podem ser prescritos para ajudar a controlar os níveis de glicose no sangue. Esses medicamentos
                                 podem aumentar a produção de insulina, melhorar a sensibilidade à insulina ou reduzir a absorção de glicose pelos  intestinos.</li>
                           
                           <br>
                           <li> <strong>Terapia com injetáveis não insulínicos: </strong> <br>Além da insulina, existem outras opções
                                de tratamento injetáveis disponíveis para pessoas com diabetes tipo 2. Isso inclui medicamentos como
                                agonistas do receptor GLP-1 (glucagon-like peptide-1) e inibidores do SGLT2 (sodium-glucose cotransporter 2),
                                 que ajudam a controlar os níveis de glicose no sangue</li>
                       </ul>
                   </aside>
                       
                         <br>
                
               </p> 
                  
               <h1>Sintomas da Diabéte</h1>

               <p>A diabetes pode apresentar diferentes sintomas, e eles podem 
                  variar dependendo do tipo de diabetes e do estágio da doença. 
                  A seguir, estão alguns dos sintomas mais comuns associados à diabetes:</p>

               <aside>
                  <ul>
                        <li><strong>Sede excessiva (polidipsia):</strong> <br> Sentir sede intensa e ter a necessidade frequente de beber água.</li>
                        <br>
                           <li><strong>Aumento da frequência urinária (poliúria):</strong> <br> Urinar com mais frequência do que o habitual, especialmente durante a noite.</li>
                        <br>
                           <li><strong>Fome excessiva (polifagia):</strong> Sentir fome constantemente, mesmo após comer adequadamente.</li>                  <br>
                           <li><strong>Perda de peso inexplicada: </strong> <br> Perder peso mesmo sem fazer dieta ou alterações significativas nos hábitos alimentares.</li>   <br>
                           <li><strong>Fadiga e fraqueza:</strong>  <br> Sentir-se cansado e com falta de energia, mesmo após períodos adequados de descanso.</li>                 
                        <br>
                           <li><strong>Visão embaçada:</strong> <br> Experimentar dificuldade em focar ou visão turva.</li>                  
                        <br>
                           <li><strong>Feridas que demoram a cicatrizar:</strong> <br> Cortes, feridas ou úlceras que demoram a se curar ou têm dificuldade em cicatrizar.</li>
                        <br>
                         <li><strong>Infecções frequentes:</strong> <br> Ter infecções, como infecções urinárias, infecções de pele ou infecções fúngicas, com mais frequência do que o normal.</li>  <br>
                        <li><strong>Formigamento ou dormência:</strong> <br> Sentir sensação de formigamento, dormência ou perda de sensibilidade nas mãos, pés ou pernas.</li>
                        <br>
                  </ul>
               </aside>

               <p>É importante ressaltar que nem todas as pessoas com diabetes apresentam
                   sintomas óbvios, especialmente nos estágios iniciais da doença. Além disso, 
                   os sintomas da diabetes tipo 1 e tipo 2 podem ser diferentes. Caso você 
                   esteja preocupado com os sintomas que está experimentando, é essencial 
                   consultar um médico para um diagnóstico adequado e orientações sobre o 
                   tratamento apropriado.</p>

                  <h1>Dicas gerais de exercícios para pessoas com diabetes:</h1>
                    <img src="imagens/exercicios-diabetes-eu-cuido.png" alt="exercícios para Diabéticos">
                   <p>
                       A prática regular de exercícios físicos pode ser benéfica para pessoas com diabetes,
                       ajudando a controlar os níveis de glicose no sangue, melhorar a sensibilidade à insulina
                       e promover a saúde geral. No entanto, é importante consultar um profissional de saúde antes
                        de iniciar qualquer programa de exercícios, especialmente se você tiver condições de saúde
                        adicionais. <br> <strong>Aqui estão algumas dicas gerais de exercícios para pessoas com diabetes:</strong>
                   </p>
                   <aside>
                        <h3> Lembre-se de que essas são apenas orientações gerais.</h3>
                        <hr><br>
                       <ul>
                           <li>
                               <strong>Escolha atividades que você goste:</strong> Opte por exercícios que sejam agradáveis e adequados ao
                               seu nível de condicionamento físico. Isso aumentará sua motivação para se exercitar regularmente.
                           </li><br>
                           <li>
                               <strong>Combine exercícios aeróbicos e de resistência:</strong> Os exercícios aeróbicos, como caminhar,
                                correr, nadar ou andar de bicicleta, ajudam a melhorar a saúde cardiovascular e a controlar
                                 os níveis de glicose no sangue. Os exercícios de resistência, como levantamento de peso ou
                                 treinamento com pesos, podem ajudar a aumentar a sensibilidade à insulina e a melhorar a composição corporal.
                           </li><br>
                           <li>
                               <strong>Estabeleça uma rotina regular:</strong> Tente reservar pelo menos 150 minutos de atividade aeróbica de intensidade
                                moderada por semana, distribuídos ao longo dos dias. Além disso, inclua exercícios de resistência duas
                                 vezes por semana, com foco nos principais grupos musculares.
                           </li><br>
                           <li>
                               <strong>Monitore seus níveis de glicose no sangue:</strong> Antes, durante e após o exercício, monitore seus níveis de
                               glicose no sangue para entender como o exercício afeta seu corpo. Isso ajudará a ajustar a alimentação
                                e a medicação, se necessário.
                           </li><br>
                           <li>
                               <strong>Esteja preparado:</strong> Mantenha um lanche ou uma fonte rápida de carboidratos disponível durante o exercício,
                                caso seus níveis de glicose no sangue fiquem baixos. Use roupas confortáveis e adequadas para o exercício
                                 e calçados adequados para evitar lesões.
                           </li><br>
                           <li>
                               <strong>Varie sua rotina:</strong> Experimente diferentes tipos de exercícios para manter a motivação e desafiar seu corpo.
                               Isso pode incluir atividades como ioga, dança, tai chi ou esportes em grupo.
                           </li><br>
                           <li><strong>Mantenha-se hidratado:</strong> Beba água antes, durante e após o exercício para evitar a desidratação.</li><br>
                           <li>
                               <strong>Ouça seu corpo:</strong> Preste atenção aos sinais do seu corpo durante o exercício. Se sentir tontura,
                               falta de ar intensa ou dor intensa, pare e consulte um profissional de saúde.
                           </li><br>
                       </ul><hr><br><hr>
                       <hr>
                       
                       <hr><h3>
                           É essencial buscar aconselhamento de um profissional
                            de saúde para adaptar um plano de exercícios de acordo com suas necessidades individuais e condição médica.
                       </h3>
                       <hr>
</aside>

<br><br>
                  <h1>Saúde: um direito de todos!</h1>
                  <p>
                     Desde 2006, pessoas com diabetes tem direito a receber via SUS (Sistema Único de Saúde) os insumos materiais utilizados para o tratamento), através da <strong>lei federal de n° 11.347</strong>.
                     
                     Quando falamos no tratamento de diabetes há dois pilares que caminham juntos, que são basicamente
                     
                     o acesso à medicação
                     educação.
                     Esta lei foi uma grande conquista para o Brasil. Antes dela da edição desta lei, era necessário comprar os insumos do seu tratamento. O que deixava grande parte da população sem acesso aos medicamentos, devido ao alto custo.
                  </p>
                  
                  <h1>Como faço para solicitar medicamentos via SUS?</h1>
                  <p>
                     Para retirar seus os materiais pelo governo, é preciso ir ao posto de saúde mais próximo de sua casa e se cadastrar como paciente com diabetes no SUS ou no Hiperdia (Sistema de Informação em Hipertensão e Diabetes).
                     
                     No mesmo local, deve se apresentar a receita médica com os insumos prescritos pelo médico responsável.
                     
                     No caso de não receber os insumos que estão no pedido médico, deve-se fazer uma reclamação à Secretaria da Saúde (do estado ou município). E se mesmo assim não for atendido, é possível, através de um advogado entrar com uma ação judicial. Exigindo que todo os materiais solicitados sejam fornecidos gratuitamente.
      
                     Uma vez que é necessária a ação judicial, é possível contratar um advogado particular ou buscar a defensoria pública nos fóruns de cada município. No entanto, receber os medicamentos é uma parte importante, mas tão imprescindível é utilizá-los da melhor maneira.
                  </p>
                  <br>
                  <img src="imagens/susimagem.png" alt="direito">
                  <br>
                  <p>Em Agosto, o Ministério da Saúde lançou o aplicativo para celular do SUS. Nele fica armazenado o seu cartão SUS e informações sobre exames. O app já está disponível gratuitamente na Google Play.

                     Consulte aqui sobre quais medicamentos são fornecidos pelo SUS e qual local mais próximo da sua residência você pode obtê-los via sautil.com.br

                  <br>
                  <br>

                  <iframe width="560" height="315" src="https://www.youtube.com/embed/HroD07UGp2E"
                   title="YouTube video player" frameborder="0" 
                   allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                   allowfullscreen></iframe>

                  <br>

                 
            <br>
            <strong>
               Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade
               sobre o tratamento e cuidado da Diabéte.
            </strong>          
        </article>    
     </main>
     <footer>
        <p>Site criado pelo <strong>Wandrey de Souza</strong> da aula do 
         <a href="https://www.youtube.com/@CursoemVideo" target="_blank">CursoemVideo</a>.</p>
     </footer>
</body>
</html>
