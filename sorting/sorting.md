1. Bubble Sort

   for (int i = 0; i < n; i++) {
    int numberOfSwaps = 0;
    for (int j = 0; j < n - 1; j++) {
      if (a[j] > a[j + 1]) {
        swap(a[j], a[j + 1]);
        numberOfSwaps++;
      }
    }
    if (numberOfSwaps == 0) {
      break;
    }
  }