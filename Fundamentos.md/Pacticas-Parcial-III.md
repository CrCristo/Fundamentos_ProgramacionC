
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
	  int v1[3],f;
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n ingresa el vector escalar");
	  scanf("%d",&f);
	  printf("\n los valores del vector 1 son  :");
	  mult(v1,f);
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

	void mult(int v1[],int f)
	{
		int v3[3];
		for (p=0,e='i';p<3;p++,e++)
		{
			v3[p]=v1[p]*f;
		}
		imprime(v3);
	}

63 . Norma de un vector

	 #include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos (void);
	void captura(int[]);
	void norma(int[]);
	int p;
	char e;

	main ()
	{
	  printf ("Norma de un vector");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[2],f;
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n la norma del vector 1 es  :");
	  norma(v1);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=1;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}



	void norma(int v1[])
	{
		float v3=0;
		for (p=0,e='i';p<2;p++,e++)
		{
			v3=v3+(v1[p]*v1[p]);
		}
		v3=sqrt(v3);
		printf("\n %.2f \n",v3);
	}

64 . Angulo entre dos vectores s

	 #include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos (void);
	void captura(int[]);
	float norma(int[]);
	void angulo(int[],int[],float,float);
	int suma(int[],int[]);
	int p;
	char e;

	main ()
	{
	  printf ("Norma de un vector");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[2],v2[2];
	  float n1,n2;
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n ingresa los daots del vector 2 \n");
	  captura(v2);
	  n1=norma(v1);
	  n2=norma(v2);
	  angulo(v1,v2,n1,n2);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=1;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}



	float norma(int v[])
	{
		float v3=0;
		for (p=0,e='i';p<2;p++,e++)
		{
			v3=v3+(v[p]*v[p]);
		}
		v3=sqrt(v3);
		return v3;
	}
	
	void angulo(int v1[],int v2[],float n1,float n2)
	{
		int v;
		float ang;
		v=suma(v1,v2);
		ang= v/(n1*n2);
		ang= acos(ang);
		printf ("el angulo entre los vectores es : %.2f \n\n",ang);
	}
	
		int suma(int v1[],int v2[])
	{
		int v3[2],v;
		for (p=0,e='i';p<2;p++,e++)
		{
			v3[p]=v1[p]*v2[p];
		}
		for (p=0,e='i';p<2;p++,e++)
		{
			v=v+v3[p];
		}
		return v;
	}
	
	
65 . vector producto punto

	 #include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos (void);
	void captura(int[]);
	int suma(int[],int[]);
	int p;
	char e;

	main ()
	{
	  printf ("producto punto de un vector");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[2],v2[2];
	  float n1,n2;
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n ingresa los daots del vector 2 \n");
	  captura(v2);
	  suma(v1,v2);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=1;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}

	int suma(int v1[],int v2[])
	{
		int v3[2],v;
		for (p=0,e='i';p<3;p++,e++)
		{
			v3[p]=v1[p]*v2[p];
			}
		for (p=0,e='i';p<2;p++,e++)
		{
			v=v+v3[p];
		}
		printf("El producto punto de los dos vectores es = %d \n\n",v);
	}
	
66 . La distancia entre dos puntos


	 #include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos (void);
	void captura(int[]);
	int suma(int[],int[]);
	int p;
	char e;

	main ()
	{
	  printf ("la distancia ente dos puntos ");
	  datos();
	  system("pause");
	}

	void datos (void)
	{
	  int v1[2],v2[2];
	  float n1,n2;
	  printf("\n ingresa los daots del vector 1 \n");
	  captura(v1);
	  printf("\n ingresa los daots del vector 2 \n");
	  captura(v2);
	  suma(v1,v2);
	}

	void captura(int v[])
	{
		for (p=0,e='x';p<=1;p++,e++)
		{
			printf("v[%c]=",e);
			scanf("%d",&v[p]);
		}
	}

	int suma(int v1[],int v2[])
	{
		int v3[2];
		float v;
		for (p=0,e='i';p<3;p++,e++)
		{
			v3[p]=pow((v2[p]-v1[p]),2);
			}
		for (p=0,e='i';p<2;p++,e++)
		{
			v=v+v3[p];
		}
		v= sqrt(v);
		printf("La distancia entre los puntos = %.2f \n\n",v);
	}

67 . proyeccion

68 . Matriz inicializada

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void imprime(int[][2]);
	int f,c;
	
	main()
	{
		  printf ("matriz inicializada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matriz [2][2]={1,2,3,4};
		int matris [2][2];
		matris[0][0]=4;
		matris[0][1]=3;
		matris[1][0]=2;
		matris[1][1]=1;
		imprime(matris);
		imprime(matriz);
	}

	void imprime(int matriz[][2])
	{
		for(f=0;f<2;f++)
		{
			for(c=0;c<2;c++)
			{
				printf("%d",matriz[f][c]);
				printf("\n");
			}
		}
	}
	
69 . Captura de una matriz

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[][2]);
	void imprime(int[][2]);
	int f,c;
	
	main()
	{
		  printf ("matriz capturada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matriz [2][2]={1,2,3,4};
		int matris [2][2];
		int matrix[2][2];
		matris[0][0]=4;
		matris[0][1]=3;
		matris[1][0]=2;
		matris[1][1]=1;
		captura(matrix);
		imprime(matris);
		imprime(matriz);
		imprime(matrix);
	}

	void captura (int M[][2])
	{
		for(f=0;f<2;f++)
		{
			for(c=0;c<2;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int matriz[][2])
	{
		for(f=0;f<2;f++)
		{
			for(c=0;c<2;c++)
			{
				printf("%d",matriz[f][c]);
				printf("\n");
			}
		}
		printf("\n");
	}
	
70 . 3X4

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[3][4]);
	void imprime(int[3][4]);
	int f,c;

	main()
	{
		  printf ("matriz 3X4 \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matrix[3][4];
		captura(matrix);
		imprime(matrix);
	}

	void captura (int M[3][4])
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<4;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[3][4])
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<4;c++)
			{
				printf("%d",M[f][c]);
				printf("\n");
			}
		}
		printf("\n");
	}

71 . 9X1

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[9][1]);
	void imprime(int[9][1]);
	int f,c;
	
	main()
	{
		  printf ("matriz inicializada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matrix[9][1];
		captura(matrix);
		imprime(matrix);
	}

	void captura (int M[9][1])
	{
		for(f=0;f<9;f++)
		{
			for(c=0;c<1;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[9][1])
	{
		for(f=0;f<9;f++)
		{
			for(c=0;c<1;c++)
			{
				printf("%d",M[f][c]);
				printf("\n");
			}
		}
		printf("\n");
	}

72 . 3X3

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[3][3]);
	void imprime(int[3][3]);
	int f,c;

	main()
	{
		  printf ("matriz inicializada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matrix[3][3];
		captura(matrix);
		imprime(matrix);
	}

	void captura (int M[3][3])
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<3;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[3][3])
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<3;c++)
			{
				printf("%d",M[f][c]);
				printf("\n");
			}
		}
		printf("\n");
	}

73 . 5X2

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[5][2]);
	void imprime(int[5][2]);
	int f,c;
	
	main()
	{
		  printf ("matriz inicializada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matrix[5][2];
		captura(matrix);
		imprime(matrix);
	}

	void captura (int M[5][2])
	{
		for(f=0;f<5;f++)
		{
			for(c=0;c<2;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[5][2])
	{
		for(f=0;f<5;f++)
		{
			for(c=0;c<2;c++)
			{
				printf("%d",M[f][c]);
				printf("\n");
			}
		}
		printf("\n");
	}

74 . 1X6

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[1][6]);
	void imprime(int[1][6]);
	int f,c;
	
	main()
	{
		  printf ("matriz inicializada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matrix[5][2];
		captura(matrix);
		imprime(matrix);
	}

	void captura (int M[1][6])
	{
		for(f=0;f<1;f++)
		{
			for(c=0;c<6;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[1][6])
	{
		for(f=0;f<1;f++)
		{
			for(c=0;c<6;c++)
			{
				printf("%d",M[f][c]);
				printf("\n");
			}
		}
		printf("\n");
	}
	
75 . Escoger el número de filas y columnas de una matriz

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	#define T 10
	void datos(void);
	void captura(int[][T],int,int);
	void imprime(int[][T],int,int);
	int f,c;

	main()
	{
		  printf ("Escoger el número de filas y columna de una matriz \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int f1,c1;
		printf("Ingresa el número de filas y columnas de la matriz:  \n");
		scanf("%d%d",&f1,&c1);
		int matrix[f1][c1];
		captura(matrix,f1,c1);
		imprime(matrix,f1,c1);
	}

	void captura (int M[][T],int f1,int c1)
	{
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[][T],int f1,int c1)
	{
		system("cls");
		printf("\n");
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("\t");
				printf("%d",M[f][c]);
			}
			printf("\n");
		}
		printf("\n");
	}

76 . Promedio de un matriz

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	#define T 10
	float promedio(int[][T],int,int);
	void datos(void);
	void captura(int[][T],int,int);
	void imprime(int[][T],int,int);
	int f,c;

	main()
	{
		  printf ("matriz promedio \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int f1,c1;
		printf("Ingresa el número de filas y columnas de la matriz:  \n");
		scanf("%d%d",&f1,&c1);
		int matrix[f1][c1];
		captura(matrix,f1,c1);
		imprime(matrix,f1,c1);
		printf("el promedio de la matruiz es ; %.2f",promedio(matrix,f1,c1));
		printf("\n\n");
	}

	void captura (int M[][T],int f1,int c1)
	{
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[][T],int f1,int c1)
	{
		system("cls");
		printf("\n");
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("\t");
				printf("%d",M[f][c]);
			}
			printf("\n");
		}
		printf("\n");
	}

	float promedio(int matrix[][T],int c1,int f1)
	{
		float prom;
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				prom=(matrix[f][c])+prom;
			}
		}
		prom=(prom)/(f1*c1);
		return prom;
	}
	
77 . suma de dos matrices 

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	#define T 10
	void datos(void);
	void captura(int[][T],int,int);
	void imprime(int[][T],int,int);
	int suma(int[][T],int[][T],int[][T],int,int);
	int f,c;

	main()
	{
		  printf ("suma de matriz \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int f1,c1;
		int matrix[f1][c1],matriz[f1][c1],matris[f1][c1];

		printf("Ingresa el número de filas y columnas de la matriz:  \n");
		scanf("%d%d",&f1,&c1);
		printf("\n\n");

		captura(matrix,f1,c1);
		printf("\n\n");
		captura(matriz,f1,c1);

		suma(matriz,matrix,matris,f1,c1);
		imprime(matris,f1,c1);
		printf("\n\n");
	}

	void captura (int M[][T],int f1,int c1)
	{
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[][T],int f1,int c1)
	{
		system("cls");
		printf("\n");
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("\t");
				printf("%d",M[f][c]);
			}
			printf("\n");
		}
		printf("\n");
	}

	int suma(int matriz[][T],int matrix[][T],int matris[][T],int f1,int c1)
	{
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				matris[f][c]=(matriz[f][c])+(matrix[f][c]);
			}
		}
	}

78 . resta de dos matrices

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	#define T 10
	void datos(void);
	void captura(int[][T],int,int);
	void imprime(int[][T],int,int);
	int suma(int[][T],int[][T],int[][T],int,int);
	int f,c;

	main()
	{
		  printf ("suma de matriz \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int f1,c1;
		int matrix[f1][c1],matriz[f1][c1],matris[f1][c1];

		printf("Ingresa el número de filas y columnas de la matriz:  \n");
		scanf("%d%d",&f1,&c1);
		printf("\n\n");

		captura(matrix,f1,c1);
		printf("\n\n");
		captura(matriz,f1,c1);

		suma(matriz,matrix,matris,f1,c1);
		imprime(matris,f1,c1);
		printf("\n\n");
	}

	void captura (int M[][T],int f1,int c1)
	{
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	void imprime(int M[][T],int f1,int c1)
	{
		system("cls");
		printf("\n");
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				printf("\t");
				printf("%d",M[f][c]);
			}
			printf("\n");
		}
		printf("\n");
	}

	int suma(int matriz[][T],int matrix[][T],int matris[][T],int f1,int c1)
	{
		for(f=0;f<f1;f++)
		{
			for(c=0;c<c1;c++)
			{
				matris[f][c]=(matriz[f][c])-(matrix[f][c]);
			}
		}
	}

79 . Matriz identidad
/*
* C Program to check if a given matrix is an identity matrix
*/

	#include <stdio.h>

	int main (void)
	{
		int a[10][10];
		int i = 0, j = 0, row = 0, col = 0;

		printf ("Enter the order of the matrix (mxn):\n");
		printf ("where m = number of rows; and\n");
		printf ("      n = number of columns\n");
		scanf ("%d %d", &row, &col);

		int flag = 0;

		printf ("Enter the elements of the matrix\n");
		for (i = 0; i < row; i++)
		{
			for (j = 0; j < col; j++)
			{
				scanf ("%d", &a[i][j]);
			}
		}

		for (i = 0; i < row; i++)
		{
			for (j = 0; j < col; j++)
			{
				if (i == j && a[i][j] != 1)
				{
					flag = -1;
					break;
				}
				else if (i != j && a[i][j] != 0)
				{
					flag = -1;
					break;
				}
			}
		}

		if (flag == 0)
		{
			printf ("It is a IDENTITY MATRIX\n");
		}
		else
		{
			printf ("It is NOT an identity matrix\n");
		}

		return 0;
	}

80 . Matriz simetrica 

	// saber si una matriz es simetrica

	/*
	* C Program to check if a given matrix is an identity matrix
	*/
	#include <stdio.h>

	int main (void)
	{
		int a[10][10];
		int i = 0, j = 0, row = 0, col = 0;

		printf ("Enter the order of the matrix (mxn):\n");
		scanf ("%d %d", &row, &col);

		int flag = 0;

	 //captura
		printf ("Enter the elements of the matrix\n");
		for (i = 0; i < row; i++)
		{
			for (j = 0; j < col; j++)
			{
				scanf ("%d", &a[i][j]);
			}
		}
	 //saer sui es simetrica 
		for (i = 0; i < row; i++)
		{
			for (j = 0; j < col; j++)
			{
				if (i == j)
				{
					break;
				}
				else if (i != j && a[i][j] != a[j][i])
				{
					flag = -1;
					break;
				}
			}
		}

		if (flag == 0)
		{
			printf ("es una matriz simetrica \n");
		}
		else
		{
			printf ("No es una matriz simetrica \n");
		}

		return 0;
	}

81 . triangular de una matriz

    #include <stdio.h>
    void main()
    {
 
        int i, j, r, c, array[10][10];
        printf("Enter the r and c value:");
 
        scanf("%d%d", &r, &c);
        for (i = 1; i <= r; i++)
        {
            for (j = 1; j <= c; j++)
            {
                printf("array[%d][%d] = ", i, j);
                scanf("%d", &array[i][j]);
            }
        }
 
        printf("matrix is");
        for (i = 1; i <= r; i++)
        {
            for (j = 1; j <= c; j++)
            {
                printf("%d", array[i][j]);
            }
            printf("\n");
        }
 
        for (i = 1; i <= r; i++)
        {
            printf("\n");
            for (j = 1; j <= c; j++)
            {
                if (i >= j)
                {
                    printf("%d", array[i][j]);
                }
                else
                {
                    printf("\t");
                }
            }
 
        }
 
        printf("\n\n");
        for (i = 1; i <= r; i++)
        {
            printf("\n");
            for (j = 1; j <= c; j++)
            {
	            if (j >= i)
                    {
                	printf("%d", array[i][j]);
            	    }
            	    else 
                    {
                	//printf("\t");
	            }
            // printf("\n");
 
        }
 
    }

82 . MAtriz inversa 

	#include<stdio.h>
	#include<math.h>
	float determinant(float [][25], float);
	void cofactor(float [][25], float);
	void transpose(float [][25], float [][25], float);
	int main()
	{
	  float a[25][25], k, d;
	  int i, j;
	  printf("Enter the order of the Matrix : ");
	  scanf("%f", &k);
	  printf("Enter the elements of %.0fX%.0f Matrix : \n", k, k);
	  for (i = 0;i < k; i++)
	    {
	     for (j = 0;j < k; j++)
	       {
		scanf("%f", &a[i][j]);
		}
	    }
	  d = determinant(a, k);
	  if (d == 0)
	   printf("\nInverse of Entered Matrix is not possible\n");
	  else
	   cofactor(a, k);
	}

	/*For calculating Determinant of the Matrix */
	float determinant(float a[25][25], float k)
	{
	  float s = 1, det = 0, b[25][25];
	  int i, j, m, n, c;
	  if (k == 1)
	    {
	     return (a[0][0]);
	    }
	  else
	    {
	     det = 0;
	     for (c = 0; c < k; c++)
	       {
		m = 0;
		n = 0;
		for (i = 0;i < k; i++)
		  {
		    for (j = 0 ;j < k; j++)
		      {
			b[i][j] = 0;
			if (i != 0 && j != c)
			 {
			   b[m][n] = a[i][j];
			   if (n < (k - 2))
			    n++;
			   else
			    {
			     n = 0;
			     m++;
			     }
			   }
		       }
		     }
		  det = det + s * (a[0][c] * determinant(b, k - 1));
		  s = -1 * s;
		  }
	    }

	    return (det);
	}

	void cofactor(float num[25][25], float f)
	{
	 float b[25][25], fac[25][25];
	 int p, q, m, n, i, j;
	 for (q = 0;q < f; q++)
	 {
	   for (p = 0;p < f; p++)
	    {
	     m = 0;
	     n = 0;
	     for (i = 0;i < f; i++)
	     {
	       for (j = 0;j < f; j++)
		{
		  if (i != q && j != p)
		  {
		    b[m][n] = num[i][j];
		    if (n < (f - 2))
		     n++;
		    else
		     {
		       n = 0;
		       m++;
		       }
		    }
		}
	      }
	      fac[q][p] = pow(-1, q + p) * determinant(b, f - 1);
	    }
	  }
	  transpose(num, fac, f);
	}
	/*Finding transpose of matrix*/ 
	void transpose(float num[25][25], float fac[25][25], float r)
	{
	  int i, j;
	  float b[25][25], inverse[25][25], d;

	  for (i = 0;i < r; i++)
	    {
	     for (j = 0;j < r; j++)
	       {
		 b[i][j] = fac[j][i];
		}
	    }
	  d = determinant(num, r);
	  for (i = 0;i < r; i++)
	    {
	     for (j = 0;j < r; j++)
	       {
		inverse[i][j] = b[i][j] / d;
		}
	    }
	   printf("\n\n\nThe inverse of matrix is : \n");

	   for (i = 0;i < r; i++)
	    {
	     for (j = 0;j < r; j++)
	       {
		 printf("\t%f", inverse[i][j]);
		}
	    printf("\n");
	     }
	}
PROYECTO Prototipo

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[3][3]);
	int det(int[3][3]);
	int d2x2(int[3][3],int);
	void imprime(int[3][3]);
	int f,c;

	main()
	{
		  printf ("matriz inicializada \n\n");
		  datos();
		  system("pause");
	}
	void datos (void)
	{
		int matrix[3][3],D1;
		captura(matrix);
		D1=det(matrix);
		printf("%d",D1);
	}

	void captura (int M[3][3])
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<3;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
		}
	}

	int det(int M[3][3])
	{
		int f1,Res1=0,d;
		for(c=0;c<3;c++)
		{
			for(f=0;f<1;f++)
			{
				f1=c;
				d=d2x2(M,f1);
				Res1=(Res1)+(-1*M[f][c]*d);
			}
		}
		return Res1;
	}

	int d2x2(int M[3][3],int f1)
	{
		int M1[2][2],d2;
		for(f=1;f<3;f++)
		{
			for(c=0;c<3;c++)
			{
				if (c==f1){
					break;
				}
				else{
					for(f=0;f<2;f++)
					{
						for(c=0;c<2;c++)
						{
							M1[f][c]=M[f][c];
						}
					}	
				}
			}
		}
		d2=M1[0][0]*M1[1][1] - M1[1][0]*M1[0][1];
		printf("%d",d2);
		return d2;
	}



ProyectoVFinal 

	#include <stdio.h>
	#include<conio.h>
	#include<math.h>
	void datos(void);
	void captura(int[3][3],int[3][1]);
	int det(int[3][3]);
	void cambcol(int[3][3], int[3][1],int[3][3],int);
	void imprime(int[3][3]);
	void incognita(int,int);
	int f,c;

	main()
	{
		int num;
		do{
			system("cls");
			printf("Resolucion de un sistema de ecuaciones 3x3\n\n");
			datos();
			printf("Presione 1 para repetir o cualquier otro numero para finalizar:\n");
			scanf("%d", &num);
		}while(num==1);
	}
	void datos (void)
	{
		int matrix[3][3],MatRES[3][1], M[3][3],D1,d1,d2,d3, cont =0;
		captura(matrix,MatRES);
		D1=det(matrix);
		//ahora guardamos ese valors y hacemos una mtraiz que va acambiar la columna por la de los resultados
		cambcol(matrix,MatRES,M,cont);
		d1=det(M);
		cont=1;
		cambcol(matrix,MatRES,M,cont);
		d2=det(M);
		cont=2;
		cambcol(matrix,MatRES,M,cont);
		d3=det(M);

		printf("Los valores de las incognitas son: \nx=");
		incognita(D1,d1);
		printf("y=");
		incognita(D1,d2);
		printf("z=");
		incognita(D1,d3);
	}

	void incognita (int D,int d)
	{
		float x;
		x=(d/D);
		printf("%.2f \n",x);
	}
	void captura (int M[3][3],int MatRES[3][1])
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<3;c++)
			{
				printf("%d,%d=",f,c);
				scanf("%d",&M[f][c]);
				printf("\n");
			}
			printf(" RES %d=",f);
			scanf("%d",&MatRES[f][1]);
			printf("\n");
		}
	}

	int det(int a[3][3])
	{
		int d;
		d = a[0][0] * ((a[1][1]*a[2][2]) - (a[2][1]*a[1][2])) -a[0][1] * (a[1][0]* a[2][2] - a[2][0] * a[1][2]) + a[0][2] * (a[1][0] * a[2][1] - a[2][0] * a[1][1]);
		printf(" det=  %d \n",d);
		return(d);
	}

	void cambcol(int matrix[3][3], int MatRES[3][1],int M[3][3],int cont)
	{
		for(f=0;f<3;f++)
		{
			for(c=0;c<3;c++)
			{
				M[f][c]=matrix[f][c];
			}
		}
		for(f=0;f<3;f++)
		{
			M[f][cont]=MatRES[f][1];
		}
	}
