# Exercício 02

Um animal contém um nome, comprimento, número de patas (o padrão é 4), uma cor,
ambiente e uma velocidade (em m/s).
<br>Um peixe é um animal, tem 0 patas, o seu ambiente é o mar (padrão), cor cinzenta (padrão).
Além disso, o peixe tem como característica: barbatanas e cauda;
<br>Um mamífero é um animal, o seu ambiente é a terra (padrão);
Um urso é um mamífero, cor castanho e o seu alimento preferido é o mel.
<br>Codifique as classes animal, peixe e mamífero.
<br><br>Para a classe Animal, codifique os métodos:
<br>+Animal();
<br>+void alteraNome(String nome);
<br>+void alteraComprimento(int comprimento);
<br>+void alteraPatas(int patas);
<br>+void alteraCor(String cor);
<br>+void alteraAmbiente(String ambiente);
<br>+void alteraVelocidade(float velocidade);
<br>+void dados(); //imprime os dados RELEVANTES do animal
<br>E os seus atributos (Com geters e seters básicos) são:
<br>-String nome
<br>-int comprimento( );
<br>-int patas( );
<br>-String cor( );
<br>-String ambiente( );
<br>-float velocidade( );
<br><br>Para a classe Peixe, codifique:
<br>+Peixe();
<br>+void alteraCaracteristica(String caracteristica);
<br>+String caracteristica( ); // retorna a características de um determinado peixe;
<br>+void dados( ); // imprimir na tela os dados RELEVANTES de PEIXE
<br><br>Para a classe Mamifero, codifique:
<br>+Mamifero ();
<br>+void alteraAlimento(String alimento);
<br>+String alimento( ); // retorna o alimento de um determinado
<br>+void dados( ); // imprimir na tela os dados RELEVANTES de MAMÍFERO
<br><br>Por último, crie um arquivo de teste (por exemplo TesteAnimais.java) de forma a ter um
jardim zoológico (Lista de animais), com os seguintes animais: camelo, tubarão, urso-do-
canadá.

Exemplo de dados:
Zoo:
<br>
<br>Animal: Camelo
<br>Comprimento: 150 cm
<br>Patas: 4
<br>Cor: Amarelo
<br>Ambiente: Terra
<br>Velocidade: 2.0 m/s
<br><br>
<br>Animal: Tubarão
<br>Comprimento: 300 cm
<br>Patas: 0
<br>Cor: Cinzento
<br>Ambiente: Mar
<br>Velocidade: 1.5 m/s
<br>Caracteristica: Barbatanas e cauda.
<br><br>
<br>Animal: Urso-do-canadá
<br>Comprimento: 180 cm
<br>Patas: 4
<br>Cor: Vermelho
<br>Ambiente: Terra
<br>Velocidade: 0.5 m/s
<br>Alimento: Mel
