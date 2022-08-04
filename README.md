# algoritmo-insertion-sort
1 void BubbleSort(int∗ v, int n) { //n é tamanho do veto
2 int i, fim, aux;
3 for (fim = n−1; fim > 0; −−fim) {
4 for (i = 0; i < fim; ++i) {
5 if (v[i] > v[i+1]) {
6 aux = v[i];
7 v[i] = v[i+1];
8 v[i+1] = aux;

