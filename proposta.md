---
layout: page
title: Programa
subtitle: Introdução à Programação de Computadores para Biologia
---


## 2o semestre de 2021

**Horário:**    Quinta-Feira – 19:00 às 21:00 horas          
                               
**Professora:** Tatiana Teixeira Torres, e-mail: tttorres(bio)ib.usp.br

OBS: substituir (bio) por @ 

## Proposta para novo programa:

| Aula | Data  | Tema                                            |
|------|-------|-------------------------------------------------|
| 1    | 19/08 | Apresentação da disciplina                      |
| 2    | 26/08 | Introdução à Programação / Bash                 |
| 3    | 02/09 | Bash (continuação) / Algoritmos                 |
| 4    | 09/09 | Introdução ao Perl / Variáveis e tipos de dados |
| 5    | 16/09 | Arrays e Hashes                                 |
| 6    | 23/09 | Estruturas de controle: condicionais            |
| 7    | 30/09 | Estruturas de controle: loops I                 |
| 8    | 07/10 | Estruturas de controle: loops II                |
| 9    | 14/10 | Manipulação de arquivos I                       |
| 10   | 21/10 | Manipulação de arquivos II                      |
| :x:  | 28/10 | Dia do servidor público. Não haverá aula        |
| 11   | 04/11 | Manipulação de strings e expressões regulares   |
| 12   | 11/11 | Subrotinas I                                    |
| 13   | 18/11 | Subrotinas II                                   |
| 14   | 25/11 | <span style="color:red">Módulos I: introdução e CPAN (opcional)</span>|
| 15   | 02/12 | <span style="color:red">Módulos II: BioPerl (opcional)</span>         |

  

## Proposta de nova forma de avaliação:

Exercícios semanais: a cada novo tema de aula, será disponibilizado um exercício que deverá ser entregue no prazo de sete dias. A entrega dos exercícios será realizada via moodle (https://edisciplinas.usp.br/). O atraso na entrega implica na <span style="color:red">redução da nota em 10%</span>. Serão <span style="color:red">oito</span> exercícios ao longo do semestre, com pesos <span style="color:red">iguais</span>. 

## Proposta de novo critério para aprovação e pesos das avaliações:

{% highlight perl linenos %}  
#!/usr/bin/perl

my ($E1, $E2, $E3, $E4, $E5, $E6, $E7, $E8, $nota_final);
($E, $M, $H) = @ARGV; 

$nota_final = ($E1+$E2+$E3+$E4+$E5+$E6+$E7+$E8)/8;

if ($nota_final >= 5) {
  print "Aluno aprovado\n";
} else {
  print "Aluno reprovado\n";
}

#conversao de nota para conceitos, apenas para a Pos-graduacao
if ($nota_final < 5) {
  print "R, Reprovado, sem direito a credito\n";
} elsif ($nota_final <= 7.0) {
  print "C, Regular, com direito a credito\n";
} elsif ($nota_final <= 8.5) {
  print "B, Bom, com direito a credito\n";
} else {
  print "A, Excelente, com direito a credito\n";
}
exit;

{% endhighlight %}
  

## Bibliografia:

- Curtis Jamison, D. “Perl Programming for Biologists”, John Wiley & Sons, Inc., 2003.
- Wall, L.; Christiansen, T.; Orwant, J. “Programming Perl”, O'Reilly Media, 2000.
- Tisdall, J. “Beginning Perl for Bioinformatics”, O'Reilly Media, 2001.
- Setubal J. C.; Meidanis J. "Introduction to Computational Molecular Biology", Brooks/Cole Pub Co, 1997.
