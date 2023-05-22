
1 .//inicializa el vector

    #include <stdio.h>
    #include<conio.h>
    void datos (void);

    main ()
    {
      printf ("\n Arreglos unidimensionales");
      datos();
      getch();
    }

    void datos (void)
    {
      int m,v1[4]={12,14,18,24};
      for (m=0;m<4;m++)
        {
          printf("\n V[%d] = %d,v1[m]");
        }
    }
2. Prgrama que agregue 10 valores a un arrelgo

3 . ingrese 10 elementos

    #include <stdio.h>
    #include<conio.h>
    void datos (void);
    void captura(int[]);
    void imprime(int[]);
    int p;

    main ()
    {
      printf ("\ningresa 10 valores");
      datos();
      system("pause");
    }

    void datos (void)
    {
      int v[10];
      printf("\n ingresa los daots \n");
      captura(v);
      printf("\n los valores son :");
      imprime(v);
    }
    void captura(int v[])
    {
    	for (p=0;p<10;p++)
    	{
    		printf("v[%d]=",p);
    		scanf("%d",&v[p]);
		}
	}
	    void imprime(int v[])
    {
    	for (p=0;p<10;p++)
    	{
    		printf("\n %d",v[p]);
		}
	}



4 .Ingresar 5 elementos

    #include <stdio.h>
    #include<conio.h>
    void datos (void);
    void captura(int[]);
    void imprime(int[]);
    int p;

    main ()
    {
      printf ("\ningresa 10 valores");
      datos();
      system("pause");
    }

    void datos (void)
    {
      int v[10];
      printf("\n ingresa los daots \n");
      captura(v);
      printf("\n los valores son :");
      imprime(v);
    }
    void captura(int v[])
    {
    	for (p=0;p<5;p++)
    	{
    		printf("v[%d]=",p);
    		scanf("%d",&v[p]);
		}
	}
	    void imprime(int v[])
    {
    	for (p=0;p<5;p++)
    	{
    		printf("\n %d",v[p]);
		}
	}
    
    
 57 . Vector XY

    #include <stdio.h>
    #include<conio.h>
    void datos (void);
    void captura(int[]);
    void imprime(int[]);
    int p;

    main ()
    {
      printf ("\ningresa 10 valores");
      datos();
      system("pause");
    }

    void datos (void)
    {
      int v[10];
      printf("\n ingresa los daots \n");
      captura(v);
      printf("\n los valores son :");
      imprime(v);
    }
    void captura(int v[])
    {
    	for (p=0;p<2;p++)
    	{
    		printf("v[%d]=",p);
    		scanf("%d",&v[p]);
		}
	}
	    void imprime(int v[])
    {
    	for (p=0;p<2;p++)
    	{
    		printf(" %d ",v[p]);
		}
	}
    
58 . Vector captura 2X

    #include <stdio.h>
    #include<conio.h>
    void datos (void);
    void captura(int[]);
    void imprime(int[]);
    int p;

    main ()
    {
      printf ("\dos vectores");
      datos();
      system("pause");
    }

    void datos (void)
    {
      int v1[2], v2[2];
      printf("\n ingresa los daots del vector 1 \n");
      captura(v1);
      printf("\n ingresa los daots \n");
      captura(v2);
      printf("\n los valores del vector 1 son  :");
      imprime(v1);
      printf("\n los valores del vector 2 son  :");
      imprime(v2);
    }
    void captura(int v[])
    {
    	for (p=0;p<2;p++)
    	{
    		printf("v[%d]=",p);
    		scanf("%d",&v[p]);
		}
	}
	    void imprime(int v[])
    {
    	for (p=0;p<2;p++)
    	{
    		printf(" %d ",v[p]);
		}
	}
    
 59 . Ingresa el vector XY
 
     #include <stdio.h>
    #include<conio.h>
    void datos (void);
    void captura(int[]);
    void imprime(int[]);
    int p;
    char e;

    main ()
    {
      printf ("\dos vectores");
      datos();
      system("pause");
    }

    void datos (void)
    {
      int v1[2];
      printf("\n ingresa los daots del vector 1 \n");
      captura(v1);
      printf("\n los valores del vector 1 son  :");
      imprime(v1);

    }
    void captura(int v[])
    {
    	for (p=0,e='x';p<=1;p++,e++)
    	{
    		printf("v[%c]=",e);
    		scanf("%d",&v[p]);
		}
	}
	    void imprime(int v[])
    {
    	for (p=0,e='i';p<2;p++,e++)
    	{
    		printf(" %d%c ",v[p],e);
		}
	}
    
60 .  Imoprime XYZ

	 #include <stdio.h>
	#include<conio.h>
	void datos (void);
	void captura(int[]);
	void imprime(int[]);
	int p;
	char e;

	main ()
	{
	  printf ("Imprime XYZ");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[3];
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n los valores del vector 1 son  :");
	  imprime(v1);

	}
	void captura(int v[])
	{
		for (p=0,e='x';p<=2;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}
	    void imprime(int v[])
	{
		for (p=0,e='i';p<3;p++,e++)
		{
			printf(" %d%c ",v[p],e);
		}
	}
	
	
61 . Vector Suma 

	 #include <stdio.h>
	#include<conio.h>
	void datos (void);
	void captura(int[]);
	void suma(int[],int[]);
	void imprime(int[]);
	int p;
	char e;

	main ()
	{
	  printf ("Suma de dos vectores");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[3],v2[3];
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n ingresa los daots del vector 2 \n");
	  captura(v2);
	  printf("\n los valores del vector 1 son  :");
	  suma(v1,v2);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=2;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}

	void imprime(int v[])
	{
		for (p=0,e='i';p<3;p++,e++)
		{
			printf(" %d%c ",v[p],e);
		}
	}

	void suma(int v1[],int v2[])
	{
		int v3[3];
		for (p=0,e='i';p<3;p++,e++)
		{
			v3[p]=v1[p]+v2[p];
		}
		imprime(v3);
	}


62 . Vector resta

	 #include <stdio.h>
	#include<conio.h>
	void datos (void);
	void captura(int[]);
	void suma(int[],int[]);
	void imprime(int[]);
	int p;
	char e;

	main ()
	{
	  printf ("Suma de dos vectores");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[3],v2[3];
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n ingresa los daots del vector 2 \n");
	  captura(v2);
	  printf("\n los valores del vector 1 son  :");
	  resta(v1,v2);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=2;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}

	void imprime(int v[])
	{
		for (p=0,e='i';p<3;p++,e++)
		{
			printf(" %d%c ",v[p],e);
		}
	}

	void resta(int v1[],int v2[])
	{
		int v3[3];
		for (p=0,e='i';p<3;p++,e++)
		{
			v3[p]=v1[p]-v2[p];
		}
		imprime(v3);
	}
	
62 multiplicacion de un vector por un numero escalar

	 #include <stdio.h>
	#include<conio.h>
	void datos (void);
	void captura(int[]);
	void suma(int[],int[]);
	void imprime(int[]);
	int p;
	char e;

	main ()
	{
	  printf ("multiplicacion por un valor escalar");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[3];
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n los valores del vector 1 son  :");
	  mult(v1);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=2;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}

	void imprime(int v[])
	{
		for (p=0,e='i';p<3;p++,e++)
		{
			printf(" %d%c ",v[p],e);
		}
	}

	void mult(int v1[])
	{
		int v3[3];
		for (p=0,e='i';p<3;p++,e++)
		{
			v3[p]=v1[p]*4;
		}
		imprime(v3);
	}

