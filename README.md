# Treinando-Dart

void main() {
  var nome = "Kleber"; //Essa variável assume o tipo da PRIMEIRA ATRIBUIÇÃO e NÃO pode mais receber outros tipos
  print(nome);

  nome = "Suiani";
  print(nome);

  //nome = 4; não posso trocar o tipo

  var x = 6; //aqui o x é um int
  x = 24;
  //x = "Bla"; //e por isso não posso atribuir uma String

  var bla = true; //quer dizer que "bla" será sempre do tipo bool
  bla = false;

  //bla = "true"; não pode pois " indicam String

  dynamic saldoEmConta = 30; //permite QUALQUER tipo em sua atribuição

  print("Você tem R\$$saldoEmConta");

  saldoEmConta = 30.5;
  print("Você tem R\$$saldoEmConta");
  
  saldoEmConta = "Zerado";
  print("Você está $saldoEmConta");
}
