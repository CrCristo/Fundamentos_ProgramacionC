# Prácticas II Parcial
//22-Positivo Negativo

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t Positivo Y negativo");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese un valor: \n");
      scanf("%d",&n);
      imprime(n);
    }

    void imprime(int n)
    {
      if(n>0) {printf("\n\t El numero es positivo\n\n\t");}
      if(n==0){printf("\n\t El numero es neutro\n\n\t");}
      if(n<0) {printf("\n\t El numero es negativo\n\n\t");}
    }

23- Pendiente

24-

25-

