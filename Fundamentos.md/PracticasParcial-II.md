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

//23-LaRecta

    #include<stdio.h>
    #include<stdlib.h>
    #include <math.h>
    #include <conio.h>

    void datos(void);
    float Pen(float,float,float,float);
    float PM(float,float);
    void imprime(float,float,float);

    main()
    {
        printf("\n\t\t Pendiente y punto medio");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float x1,x2,y1,y2,p,mx,my;
        printf("\n\t Ingresa loas coordenadas x,y de los puntos A y B, respectivamente:\n");
        scanf("%f%f%f%f",&x1,&y1,&x2,&y2);
        p= Pen(x1,x2,y1,y2);
        mx= PM(x1,x2);
        my= PM(y1,y2);
        imprime(p,mx,my);
    }

    float Pen(float x1,float y1,float x2,float y2)
    {
        float p;
        p=((y2-y1)/(x2-x1));
        return p;
    }


    float PM(float z1,float z2)
    {
        float pm;
        pm=((z2+z1)/(2));
        return pm;
    }


    void imprime(float p,float mx,float my)
    {
        printf("\n\t La pendiente de la recta AB es %.2f \n\t y las coordenadas del punto medio entre A y B es M(%.2f ; %.2f)\n\n",p,mx,my);
    }
    
24- Angúlos

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t Angulo");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese un angulo: \n");
      scanf("%d",&n);
      imprime(n);
    }

    void imprime(int n)
    {
      if(n>=0 & n<90) {printf("\n\t %d es angulo agudo\n\n\t",n);}
      if(n>90 & n<180){printf("\n\t %d es angulo obtuso\n\n\t",n);}
      if(n==90){printf("\n\t %d es angulo recto\n\n\t",n);}
      if(n==180){printf("\n\t %d es angulo llano\n\n\t",n);}
      if(n>180 & n<360){printf("\n\t %d es angulo concavo\n\n\t",n);}
      if(n==360){printf("\n\t %d es angulo completo\n\n\t",n);}

    }
    
    
//25-Etapa de Vida

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t Etapa de Vida");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese la edad: \n");
      scanf("%d",&n);
      imprime(n);
    }

    void imprime(int n)
    {
      if(n<=0) {printf("\n\t Periodo Prenatal\n\n\t",n);}
      if(0<n & n<=3){printf("\n\t Primera infancia\n\n\t",n);}
      if(3<n & n<=6){printf("\n\t Niñez temprana o preescolar\n\n\t",n);}
      if(6<n & n<=12) {printf("\n\t Niñez intermedio o escolar\n\n\t",n);}
      if(12<n & n<=18){printf("\n\t Adolescencia\n\n\t",n);}
      if(18<n & n<=35){printf("\n\t Juventud\n\n\t",n);}
      if(35<n & n<=50) {printf("\n\t Madurez\n\n\t",n);}
      if(50<n & n<=65){printf("\n\tAdultez\n\n\t",n);}
      if(65<n & n<=120){printf("\n\t Vejez o tercera edad\n\n\t",n);}
      if(120<n){printf("\n\t Fuera de rango\n\n\t",n);}
    }
26-MayorDe3

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t El amyor de los 3");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int n;
      printf("\n\t Ingrese los tres numeros: \n");
      scanf("%d%d%d",&n,&n2,&n3);
      imprime(n,n2,n3);
    }

    void imprime(int n,int n2,int n3)
    {
      if(n<=n2 & n2<n3 | n2<=n & n<n3) {printf("\n\t %d es angulo agudo\n\n\t",n);}
      if(n3<=n2 & n2<n | n2<=n3 & n3<n){printf("\n\t %d es angulo recto\n\n\t",n);}
      if(n3<=n & n<n2 | n<=n3 & n3<n2){printf("\n\t %d es angulo llano\n\n\t",n);}
      if(){printf("\n\t %d es angulo concavo\n\n\t",n);}
      if(----){printf("\n\t %d es angulo completo\n\n\t",n);}

    }

//27-IMC

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    float IMC(float,float);
    void imprime(float);

    main()
    {
      system("color 1F");
      printf("\n\n\t Etapa de Vida");
      datos();
      system("pause");
    }

    void datos(void)
    {
      float e,p,n;
      printf("\n\t Ingese su estatura en m y su peso en kg: \n");
      scanf("%f%f",&e,&p);
      n= IMC(e,p);
      imprime(n);
    }

	float IMC(float e,float p)
	{
	    float n;
		n=(p)/(e*e);
	    return n;
	}
    void imprime(float n)
    {

      if(0<n & n<18){printf("\n\t Peso bajo\n\n\t",n);}
      if(18<=n & n<=24.9){printf("\n\t Normal\n\n\t",n);}
      if(24.9<n & n<=26.9) {printf("\n\t Sobrepeso \n\n\t",n);}
      if(26.9<n & n<=29.9){printf("\n\t Obesidad grado I\n\n\t",n);}
      if(29.9<n & n<=40){printf("\n\t Obesidad grado II muy alto\n\n\t",n);}
      if(40<n) {printf("\n\t Obesidad grado III Extrema\n\n\t",n);}
    }

//28Ejemplo Switch case

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void elige(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t ejemplo\n");
      datos();
      system("pause");
    }

    void datos(void)
    {
    	int n;
    	printf("Elige la opcion 1 o 2: \n");
    	scanf("%d",&n);
    	elige (n);
	}
	
	void elige(int n)
	{
		switch(n)
		{
			case 1: printf("\n\t Elegiste 1 \n\n");
			break;
			case 2: printf("\n\t Elegiste 2 \n\n");
			break;
			default: printf("Fuera de rango");	
		}
	}
    

//29-Alfabeto fonético

    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    void elige(char);

    main()
    {
      system("color 1F");
      printf("\n\n\t Alfabeto fonetico \n");
      datos();
      system("pause");
    }

    void datos(void)
    {
    	char n;
    	printf(" Inserta la letra: \n");
    	scanf("%c",&n);
    	elige (n);
	}
	
	void elige(char n)
	{
		switch(n)
		{
			case 'a':
			case 'A': printf("\n\t Alfa \n\n");
			break;
			case 'b': 
			case 'B': printf("\n\t Bravo \n\n");
			break;
			case 'c': 
			case 'C': printf("\n\t Charly \n\n");
			break;
			case 'd':
			case 'D': printf("\n\t Delta \n\n");
			break;
			case 'E':
			case 'e': printf("\n\t Eco \n\n");
			break;
			case 'f':
			case 'F': printf("\n\t Foxtrot \n\n");
			break;
			case 'g':
			case 'G': printf("\n\t Golf \n\n");
			break;
			case 'h':
			case 'H': printf("\n\t Hotel \n\n");
			break;
			case 'i':
			case 'I': printf("\n\t India \n\n");
			break;
			case 'j':
			case 'J': printf("\n\t Juliette \n\n");
			break;
			case 'k':
			case 'K': printf("\n\t Kilo \n\n");
			break;
			case 'l':
			case 'L': printf("\n\t Lima \n\n");
			break;
			case 'm':
			case 'M': printf("\n\t Metro \n\n");
			break;
			case 'n':
			case 'N': printf("\n\t Nectar \n\n");
			break;
			case 'o':
			case 'O': printf("\n\t Oscar \n\n");
			break;
			case 'p':
			case 'P': printf("\n\t Papa \n\n");
			break;
			case 'q':
			case 'Q': printf("\n\t Quebec \n\n");
			break;
			case 'r':
			case 'R': printf("\n\t Romeo \n\n");
			break;
			case 's':
			case 'S': printf("\n\t Sierra \n\n");
			break;
			case 't':
			case 'T': printf("\n\t Tango \n\n");
			break;
			case 'U':
			case 'u': printf("\n\t Union \n\n");
			break;
			case 'v':
			case 'V': printf("\n\t Victor \n\n");
			break;
			case 'w':
			case 'W': printf("\n\t Whiskey \n\n");
			break;
			case 'x':
			case 'X': printf("\n\t X-ray \n\n");
			break;
			case 'y':
			case 'Y': printf("\n\t Yankee \n\n");
			break;
			case 'Z':
			case 'z': printf("\n\t Zulu \n\n");
			break;
			default: printf("\n\n Fuera de rango \n\n");	
		}
	}


//30-No circula

	#include <stdio.h>
	#include <stdlib.h>
	void datos(void);
	void elige(int);

	main()
	{
	  system("color 1F");
	  printf("\n\n\t No circula \n");
	  datos();
	  system("pause");
	}

	void datos(void)
	{
		int n;
		printf(" Inserta el ultimo nuemero de tu matricula: \n");
		scanf("%d",&n);
		elige (n);
	}

	void elige(int n)
	{
		switch(n)
		{
			case 5:
			case 6: printf("\n\t Lunes No circula - Placa Amarillo \n\n");
			break;
			case 7: 
			case 8: printf("\n\t Martes No circula - Placa Rosa \n\n");
			break;
			case 3: 
			case 4: printf("\n\t Miercoles No circula - Placa Rojo \n\n");
			break;
			case 1:
			case 2: printf("\n\t Jueves No circula - Placa Verde \n\n");
			break;
			case 9:
			case 0: printf("\n\t Viernes No circula - Placa Azul \n\n");
			break;
			default: printf("\n\n Fuera de rango \n\n");	
		}
	}
	
	
//31- Multiplo de 5
 
    #include <stdio.h>
    #include <stdlib.h>
    void datos(void);
    int Mult(int);
    void imprime(int);

    main()
    {
      system("color 1F");
      printf("\n\n\t Multiplo de 5");
      datos();
      system("pause");
    }

    void datos(void)
    {
      int e,n;
      printf("\n\t Ingrese el numero: \n");
      scanf("%d",&e);
      n= Mult(e);
      imprime(n);
    }

	int Mult(int e)
	{
	    int n;
		n=(e%5);
	    return n;
	}
    void imprime(int n)
    {

      if(n==0){printf("\n\t Es multiplo de 5 \n\n\t",n);}
      if(n!=0){printf("\n\t No es multiplo de 5\n\n\t",n);}
    }


//32- Ciclo for 0 al 9
 
    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclofor(void);

    main()
    {
      system("color 1F");
      printf("\n\n\t Incremento");
      ciclofor();
      system("pause"); 
    }

    void ciclofor(void)
    {
        int n;
        printf("\n\t Imprime 0 al 9 incrementos en uno: \n");
		for(n=0;n<10;n++)
		{
			printf("\n %d",n);
			//getch();
		}
    }

//33- Ciclo for 9 al 0
 
    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclofor(void);

    main()
    {
      system("color 1F");
      printf("\n\n\t Decremento");
      ciclofor();
      system("pause"); 
    }

    void ciclofor(void)
    {
        int n;
        printf("\n\t Imprime 0 al 9 incrementos en uno: \n");
		for(n=9;n>=0;n--)
		{
			printf("\n %d",n);
			//getch();
		}
    }

//34- Ciclo for 10 al 30 con imcremento en dos
 
    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclofor(void);

    main()
    {
      system("color 1F");
      printf("\n\n\t Incremento de dos en dos");
      ciclofor();
      system("pause"); 
    }

    void ciclofor(void)
    {
        int n;
        printf("\n\t Imprime 0 al 9 incrementos en uno: \n");
		for(n=10;n<=30;n+=2)
		{
			printf("\n %d",n);
			getch();
		}
    }
//35- Ciclo for300 al 270 con decremento en tres
 
    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclofor(void);

    main()
    {
      system("color 1F");
      printf("\n\n\t decremento de tres ");
      ciclofor();
      system("pause"); 
    }

    void ciclofor(void)
    {
        int n;
        printf("\n\t Imprime 300 al 270 decrementos en tres: \n");
		for(n=300;n>=270;n-=3)
		{
			printf("\n %d",n);
			//getch();
		}
    }
    
//36- Ciclo for raiz cuadrada con decremento en 2
 
    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>
	#include<math.h>
	
    void ciclofor(void);
	float raiz(float n);
	
    main()
    {
      system("color 1F");
      printf("\n\n\t Ciclo for raiz cuadrada ");
      ciclofor();
      system("pause"); 
    }

    void ciclofor(void)
    {
        int n;
        printf("\n\t  Imprime raiz cuadrada con decremento en 2: \n");
		for(n=20;n<=40;n+=2)
		{
			printf("%f \n",raiz(n));
			//getch();
		}
    }

	float raiz(float n)
	{
	    return sqrt(n);
	}
	
//37- Potencia cubica con inc en 6
 
    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>
	#include<math.h>
	
    void ciclofor(void);
	float raiz(float n);
	
    main()
    {
      system("color 1F");
      printf("\n\n\t Ciclo for potencia cubica  ");
      ciclofor();
      system("pause"); 
    }

    void ciclofor(void)
    {
        int n;
        printf("\n\t  Imprime potencia cubica con incremento en 6: \n");
		for(n=6;n<=60;n+=6)
		{
			printf("%f \n",raiz(n));
			//getch();
		}
    }

	float raiz(float n)
	{
	    return pow(n,3);
	}

//38 - while0a9

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclowhile(void);

    main()
    {
      printf("\n\n\t Incremento con while");
      ciclowhile();
      system("pause"); 
    }

    void ciclowhile(void)
    {
        int n=0;
        printf("\n\t Imprime 0 al 9 incrementos en uno: \n");
		while(n<=9)
		{
			printf("\n %d",n);
			n++;
			//getch();
		}
    }


//39 - dowhile0a9

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclodowhile(void);

    main()
    {
      printf("\n\n\t Incremento con do-while");
      ciclodowhile();
      system("pause"); 
    }

    void ciclodowhile(void)
    {
        int n=0;
        printf("\n\t Imprime 0 al 9 incrementos en uno: \n");
		do
	    	{
				printf("\n %d",n);
				n++;
				//getch();
			} while(n<10);
    }


//40 - 20 al 52 con incr en 4

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclowhile(void);

    main()
    {
      printf("\n\n\t while 20 a 52");
      ciclowhile();
      system("pause"); 
    }

    void ciclowhile(void)
    {
        int n=20;
        printf("\n\t Imprime 20 al 52 incrementos en 4: \n");
		while(n<=52)
		{
			printf("\n %d",n);
			n+=4;
			//getch();
		}
    }


//41 - 1000 al 500 con decr en 10

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclowhile(void);

    main()
    {
      printf("\n\n\t while 1000 a 500");
      ciclowhile();
      system("pause"); 
    }

    void ciclowhile(void)
    {
        int n=1000;
        printf("\n\t Imprime 1000 al 500 incrementos en 10: \n");
		while(n>=500)
		{
			printf("\n %d",n);
			n-=10;
			//getch();
		}
    }


//42 - 70 al 7 con decr en 7

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclowhile(void);

    main()
    {
      printf("\n\n\t while 70 a 7");
      ciclowhile();
      system("pause"); 
    }

    void ciclowhile(void)
    {
        int n=70;
        printf("\n\t Imprime 70 al 7 incrementos en 7: \n");
		while(n>=7)
		{
			printf("\n %d",n);
			n-=7;
			//getch();
		}
    }


//43 - 3000 al 9000 con incr en 1000

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclodowhile(void);

    main()
    {
      printf("\n\n\t Incremento con do-while en 1000");
      ciclodowhile();
      system("pause"); 
    }

    void ciclodowhile(void)
    {
        int n=3000;
        printf("\n\t Imprime 3000 al 9000 incrementos en mil: \n");
		do
	    	{
				printf("\n %d",n);
				n+=1000;
				//getch();
			} while(n<=9000);
    }

// 44 -  Do while de 5 a 50 multiplicando con n

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclodowhile(void);

    main()
    {
      printf("\n\n\t Tabla del 5");
      ciclodowhile();
      system("pause"); 
    }

    void ciclodowhile(void)
    {
        int n=1;
		do
	    	{
	    		int m;
	    		m=5*n;
			printf("\n 5 X %d = %d",n,m);
			n++;
			//getch();
		} while(n<=10);
    }

//45 Tabla de n

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>

    void ciclodowhile(void);

    main()
    {
      printf("\n\n\t Tabla de n");
      ciclodowhile();
      system("pause"); 
    }

    void ciclodowhile(void)
    {
        int n=1, m;
        printf("\n\t Ingresa el numero de la tabla que quierae: \n");
        scanf("%d",&m);
		do
	    	{
	    		int r;
	    		r=m*n;
				printf("\n %d X %d = %d",n,m,r);
				n++;
				//getch();
			} while(n<=10);
    }


46 divisa.c

47 temperatura.c

48 longitudes.c

    #include <stdio.h>
    #include <stdlib.h>
	#include <conio.h>
	void datos(void);
	int elige(int,int);
	
	main()
	{

        int m;
        do{ 
            system ("cls");
            system("color 4f");
            printf("\n\n Longitudes\n");
            datos();
            printf("\n\n\n\t\t");
            system("pause");
            printf ("\n Presiona 1 si quieres continuar o cualquier otra tecla para salir");
            scanf("%d",&m);
        } while (m == 1);

    }
    
    void datos(void)
    {
        int num,sel;
        printf ("\n\t Selecciona la opcion que desees \n\t 1. km. a millas \n\t 2.millas a km. \n\t 3.metros a pies  \n\t 4.pies a metros \n\t 5.Salir \n\n\t");
        scanf("%d",&sel);
        printf ("\n\t ingresa la cantidad que deseas convertir \n\n\t");
        scanf("%d",&num);
		elige(sel,num);
	}

	int elige(int sel,int num)
	{
		switch(sel)
		{
			case 1: printf("\n\t %d km equivalen a %.2f millas  \n\n",num,num/1.609);
			break;
			case 2: printf("\n\t %d millas  equivalen a %.2f km \n\n",num,num*1.609);
			break;
			case 3: printf("\n\t %d km equivalen a %.2d pies \n\n",num,num*3281);
			break;
			case 4: printf("\n\t %d pies equivalen a %.2d km \n\n",num,num/3281);
			break;
			case 5: printf("\n\t Vuelva pronto \n\n");
			break;
			default: printf("\n\n Opcion Fuera de rango \n\n");	
		}
	}

Longitudes.c  V1.2

	#include <stdio.h>
	#include <stdlib.h>
	#include <conio.h>
	void datos(void);
	int elige(int,int);
	float mult(int,float);

	main()
	{

	    char m;
	    do{ 
		system ("cls");
		system("color 4f");
		printf("\n\n Longitudes\n");
		datos();
		printf("\n\n\n\t\t");
		system("pause");
		printf ("\n Presiona enter si quieres continuar o cualquier otra tecla para salir");
		m=getch();
	    } while (m == 13);
	}

	void datos(void)
	{
	    int num,sel;
	    printf ("\n\t Selecciona la opcion que desees \n\t 1. km. a millas \n\t 2.millas a km. \n\t 3.metros a pies  \n\t 4.pies a metros \n\t 5.Salir \n\n\t");
	    scanf("%d",&sel);
	    printf ("\n\t ingresa la cantidad que deseas convertir \n\n\t");
	    scanf("%d",&num);
	    system ("cls");
		elige(sel,num);
	} 

	int elige(int sel,int num)
	{
		switch(sel)
		{
			case 1: printf("\n\t %d km equivalen a %.2f millas  \n\n",num,mult(num,9.87));
			break;
			case 2: printf("\n\t %d millas  equivalen a %.2f km \n\n",num,mult(num,9.87));
			break;
			case 3: printf("\n\t %d km equivalen a %.2d pies \n\n",num,mult(num,9.87));
			break;
			case 4: printf("\n\t %d pies equivalen a %.2d km \n\n",num,mult(num,9.87));
			break;
			case 5: printf("\n\t Vuelva pronto \n\n");exit(0);
			break;
			default: printf("\n\n Opcion Fuera de rango \n\n");	
		}
	}

	float mult (int num,float c)
	{
		float C;
		C=num*c;
		return C;
	}

