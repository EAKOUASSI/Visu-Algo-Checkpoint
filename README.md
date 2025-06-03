# Visu-Algo-Checkpoint
Ce checkpoint consistant à résoudre une série d'algo sur le site https://visualgo.net/ m'a permis de tester mes capacités en algorithmique et structures de données.
Dans l'ensemble j'ai réussi à résoudre la majeure partie des problèmes que j'ai eu  à testé, cependant ma principale difficulté à été de pouvoir résoudre les exercices quant à la "complexité globale" des algorithmes:
What is the time complexity of the following pseudocode?
int doSomethingCool(int n) {
  if (n < 3) return 0;
  int num = 7;
  for (int j = 1; j <= n; j++) ++num;
  for (int k = n; k >= 1; k--) ++num;
  return doSomethingCool(n-4) + num;
}

