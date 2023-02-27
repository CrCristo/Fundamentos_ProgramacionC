// 00-Bienvenido

    #include<stdio.h>;
    #include<stdlib.h>;
    int nbro=2,edad=21;
    float hei=1.83,wei=78.5;
    char nom[7]="Cristo";

    main()
    {
        printf("\n \t Bienvenido \n \t");
        system("pause");
        printf("\n \t %s , tienes %d años, pesas %f kilos y mides %f metros. \n Además, tienes %d hermanos",nom,edad,wei,hei,nbro);
    }


// 01-Saludo

    #include<stdio.h>
    #include<stdlib.h>
    main()
    {
      printf("\n\t Esta es la clase de");
      printf("\n\t Fundamentos de Programaci%cn \n\n\n\t",162);
      system("pause");
    }

// 02-Carátula

    #include<stdio.h>
    #include<stdlib.h>

    void  caratula(void)
    {
        system ("color 5F");
        printf("\n\t Instituto Polit%ccnico Nacional",130);
        printf("\n\t ESIME TICOM%cN: \n \t Ingenier%ca Aeron%cutica  \n \t Fundamentos de Programaci%cn",160,161,160,162);
        printf("\n\t Cristopher R%cmulo S%cnchez \n\n\n\t",162,160);
    }

    main()
    {
        caratula();
        system("pause");
    }


![image](https://user-images.githubusercontent.com/111446231/217905115-848d9a3d-6206-42eb-9ca8-c8a292c634eb.png)

// 03-Personaje

    #include<stdio.h>
    #include<stdlib.h>

    void  personaje(void)
    {
        printf("\n\t Nombre: \t\t\t Augusta Ada King o Ada Byron ");
        printf("\n\t Fecha de nacimiento: \t\t 10 de diciembre de 1815, Londres, Reino Unido ");
        printf("\n\t Hechos Relevantes: \t\t Es considerada la primer programadora al crear un algoritmo in%cdito en ese entonces pensado para ser procesado por una m%cquina",130,160);
        printf("\n\t Fecha de Fallecimiento: \t 27 de noviembre de 1852, Marylebone, Londres, Reino Unido");
        printf("\n\t ¿Porque te agrada?: \t\t Honestamente, siempre me ha parecido atractiva la est%ctica steampunk y al conocer su historia y aportes Ada Byron me da esa sensaci%cn de innovaci%cn en un mundo del pasado y de una forma m%cs realista",130,162,162,160);

    }

    main()
    {
        personaje();
        system("pause");
    }


//04-Mis_Datos

    #include<stdio.h>;
    #include<stdlib.h>;
    int nbro=2,edad=21;
    float hei=1.83,wei=78.5;
    char nom[7]="Cristo";

    void misdatos(void)
    {
        system("color 5F");
        printf("\n \t Bienvenido, \n \t %s  tienes %d a%cos, pesas %.2f kilos y mides %.2f metros. \n\t Adem%cs, tienes %d hermanos \n\t",nom,edad,164,wei,hei,160,nbro);
    }

    main()
    {
        misdatos();
        system("pause");
    }
    
//05-Datos

    #include <stdio.h>

    void datos(void)
    {
        int age;
        printf("\n Cu%cntos a%cos tienes?\n",160,164);
        scanf("%d",&age);
        printf("\n Tienes %d a%cos",age,164);
    }

    main()
    {
        datos();
    }


//06-Captura

    #include <stdio.h>

    void captura(void)
    {
        char name[30];
        float prom, gasto_men, sueldo_men;
        printf("\n Ingrese su nombre: \n");
        //scanf("%s",&name);
        gets(name); // para que se le pueda poner un espacio
        printf("\n C%cal es tu promedio escolar?\n",163);
        scanf("%f",&prom);
        printf("\n Cu%cntos gastas al mes?\n",160);
        scanf("%f",&gasto_men);
        printf("\n C%cal es tu sueldo mensual?\n",163);
        scanf("%f",&sueldo_men);
        system("cls");
        printf("\n\t %s \n\t promedio = \t\t %.2f \n\t gasto mensual = \t %.2f pesos \n\t sueldo mensual = \t %.2f pesos \n",name,prom, gasto_men, sueldo_men);
    }

    main()
    {
        captura();
    }


//07-FichaAeronave


    #include<stdio.h>;
    #include<stdlib.h>;

    char avion[15]="Boeing 787", carro[20]="Ferrari 458";
    int npas_avion=217,npas_carro=2,vel_avion=954, vel_car=325,gas_car=86, gas_avion=101330;
    float hei_avion=16.9,lenght_avion=56.7,hei_car=1.213,lenght_car=4.527;

    void fichatecnica(void)
    {
        printf("\n\t\t\t\t Ficha T%ccnica: %s",130,avion);
        printf("\n\t Capacidad de pasajeros \t\t %d  pasajeros  \n\t Dimensiones \t\t\t\t %.3f m altura \n\t\t\t\t\t\t %.3f m longitud \n\t Capacidad de combustible \t\t  %d litros \n\t Velocidad m%cxima \t\t\t %d km*h \n\n",npas_avion,hei_avion,lenght_avion,gas_avion,160,vel_avion);
        printf("\n\n\t\t ----------------------------------------------------------- \n");
        printf("\n\t\t\t\t Ficha T%ccnica: %s",130,carro);
        printf("\n\t Capacidad de pasajeros \t\t %d  pasajeros  \n\t Dimensiones \t\t\t\t %.3f m altura \n\t\t\t\t\t\t %.3f m longitud \n\t Capacidad de combustible \t\t  %d litros \n\t Velocidad m%cxima \t\t\t %d km*h \n\n",npas_carro,hei_car,lenght_car,gas_car,160,vel_car);
    }

    void fichatecnica(void);
    main()
    {
        fichatecnica();
        system ("pause");
    }
    
    
 //08-DatosDeClase

    #include<stdio.h>;
    #include<stdlib.h>;

    void datos(void);
    void imprime(int,float);

    main()
    {
        printf ("\n\t Datos del alumno");
        datos();
        system("pause");
    }

    void datos(void)
    {
        int mat;
        float prom;
        printf("\n\t ingresa el nuero de las materias que cursas:\t");
        scanf("%d",&mat);
        printf("\n\t ingresa tu promedio:\t");
        scanf("%f",&prom);
        imprime(mat,prom);//Lama a la funcion
    }

    void imprime(int mat,float prom)
    {
        system("cls");
        printf("\n\t Para las materias que tienes: %d",mat);
        printf("\n\t Tu promedio es de: %.2f \n", prom);
    }


//09-Boleto

    #include<stdio.h>;
    #include<stdlib.h>;

    void boleto(void);
    void imprime(int,int,float);

    main()
    {
        printf ("\n\t Datos del boleto de avión");
        boleto();
        system("pause");
    }

    void boleto(void)
    {
        int sal,n_vuelo;
        float hora;
        printf("\n\t Ingresa el nuemero de sala:\t");
        scanf("%d",&sal);
        printf("\n\t ingresa El numero de vuelo:\t");
        scanf("%d",&n_vuelo);
        printf("\n\t ingresala hora del vuelo:\t");
        scanf("%f",&hora);
        imprime(sal,n_vuelo,hora);
    }

    void imprime(int sal,int n_vuelo,float hora)
    {
        system("cls");
        printf("\n\t Tu vuelo es el: %d \n\t Espera en la sala %d \n\t El avion parte a las %.2f \n",sal,n_vuelo,hora);
    }
    
//10-AreaTrian

    #include<stdio.h>;
    #include<stdlib.h>;


    void datos(void);
    float areatrian(float b,float h);
    void imprime(float A);
    main()
    {
        printf("\n\t\t Area de un Triangulo");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float b,h,A;
        printf("\n\t Ingresa la base y la altura:\n");
        scanf("%f",&b);
        scanf("%f",&h);
        A=areatrian(b,h);
        imprime(A);
    }

    float areatrian(float b,float h)
    {
        float a;
        a=(b*h)/(2);
        return a;
    }

    void imprime(float A)
    {
        printf("Area = %.2f \n\n",A);
    }
    
 //11-Factura
 
    #include<stdio.h>
    #include<stdlib.h>


    void factura(void);
    void imprime(char[], int ,int, float, float);

    main()
    {
        printf("\n\t\t\t Factura");
        factura();
        system("pause");
    }

    void factura(void)
    {
        char n_est[6]="E012";
        int n_fol=967, w_ID=7396;
        float precio=22.15, monto=1107.5;
        imprime(n_est,n_fol,w_ID,precio,monto);
    }

    void imprime(char n_est[], int n_fol,int w_ID, float precio,float monto)
    {
        printf("\n\t Numero de estacion \t\t %s  \n\t Folio \t\t\t\t %d \n\t Identificacion \t\t  %d \n\t Precio \t\t\t %.2f \n\t Monto \t\t\t %.2f  \n\n",n_est,n_fol,w_ID,precio,monto);
    }
        
 //12-Cuadrado

    #include<stdio.h>;
    #include<stdlib.h>;
    #include<math.h>;


    void datos(void);
    float areacuad(float l);
    float percuad(float l);
    void imprime(float A,float P);
    main()
    {
        printf("\n\t\t Area de un Cuadrado");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float l,A,P;
        printf("\n\t Ingresa la base:\n");
        scanf("%f",&l);
        A=areacuad(l);
        P=percuad(l);
        imprime(A,P);
    }

    float areacuad(float l)
    {
        float a;
        a=pow(l,2);
        return a;
    }
    
	float percuad(float l)
	{
    	float p;
    	p=(4*l);
    	return p;
    }
    void imprime(float A,float P)
    {
        printf("Area = %.2f unidades cuadradas\nPerimetro = %.2f unidades\n\n",A,P);
    }
    
 //13-Rectangulo

    #include<stdio.h>;
    #include<stdlib.h>;
    #include<math.h>;


    void datos(void);
    float arearec(float b,float h);
    float perrec(float b,float h);
    float diagrec(float b,float h);
    void imprime(float A,float P,float D);
    main()
    {
        printf("\n\t\t Area de un Rectangulo");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float b,h,A,P,D;
        printf("\n\t Ingresa la base y la altura:\n");
        scanf("%f%f",&b,&h);
        A=arearec(b,h);
        P=perrec(b,h);;
        D=diagrec(b,h);
        imprime(A,P,D);
    }

    float arearec(float b,float h)
    {
        float a;
        a=(b*h);
        return a;
    }
    
    float perrec(float b,float h)
	{
    	float p;
    	p=(2*b+2*h);
    	return p;
    }
    
    float diagrec(float b,float h)
    {
        float d;
        d=sqrt((pow(b,2))+(pow(h,2)));
        return d;
    }

    void imprime(float A,float P,float D)
    {
        printf("Area = %.2f unidades cuadradas\nPerimetro = %.2f unidades\nDiagonal = %.2f unidades\n\n",A,P,D);
    }
    
    
 //14-Suma de 3 valores
 
    #include<stdio.h>;
    #include<stdlib.h>;
    #include<math.h>;


    void datos(void);
    float sum(float a,float b,float c);
    void imprime(float S);
    main()
    {
        printf("\n\t\t Suma de tras valores");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float a,b,c,S;
        printf("\n\t Ingresa los tres valores:\n");
        scanf("%f%f%f",&a,&b,&c);
		S=sum(a,b,c);
        imprime(S);
    }

    float sum(float a,float b,float c)
    {
        float S;
        S=(a+b+c);
        return S;
    }

    void imprime(float S)
    {
        printf("El resultado de la suma es = %.2f unidades\n\n",S);
    }
 
 //15-Division y resta

    #include<stdio.h>;
    #include<stdlib.h>;
    #include<math.h>;


    void datos(void);
    float res(float a,float b);
    float divs(float a,float b);
    void imprime(float R,float D);
    main()
    {
        printf("\n\t\t Resta y division");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float a,b,R,D;
        printf("\n\t Ingresa los valores:\n");
        scanf("%f%f",&a,&b);
		R=res(a,b);
		D=divs(a,b);
        imprime(R,D);
    }

    float res(float a,float b)
    {
        float R;
        R=(a-b);
        return R;
    }

    
    float divs(float a,float b)
	{
    	float D;
    	D=(a/b);
    	return D;
    }

    void imprime(float R,float D)
    {
        printf("\n El resultado de\nla resta es = %.2f unidades\nla division es = %.2f unidades\n\n",R,D);
    }


//16-Raíz

    #include<stdio.h>
    #include<stdlib.h>
    #include<math.h>


    void datos(void);
    float raiz(float a);
    void imprime(float R);
    main()
    {
        printf("\n\t\t Raiz");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float a,R;
        printf("\n\t Ingresa los valores:\n");
        scanf("%f",&a);
		R=raiz(a);
        imprime(R);
    }

    float raiz(float a)
    {
        float R;
        R=pow(a,0.5);
        return R;
    }


    void imprime(float R)
    {
        printf("\n El resultado de la raiz cuadrada es = %.2f unidades\n",R);
    }

//17-Potencia

    #include<stdio.h>
    #include<stdlib.h>
    #include<math.h>


    void datos(void);
    float pot(float a, int b);
    void imprime(float R);
    main()
    {
        printf("\n\t\t Potencia");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float a,b,P;
        printf("\n\t Ingresa los valores del numero y de la potencia:\n");
        scanf("%f%f",&a,&b);
		P=pot(a,b);
        imprime(P);
    }

    float pot(float a,int b)
    {
        float P;
        P=pow(a,b);
        return P;
    }


    void imprime(float P)
    {
        printf("\n El resultado de la potencia es = %.2f unidades\n",P);
    }


//18-seno,coseno y tangente

    #include<stdio.h>
    #include<stdlib.h>
	#include <math.h>
	#include <conio.h>
	
    void datos(void);
    float seno(float a);
    float cose(float a);
    float tang(float a);
    void imprime(float S,float C,float T);
    main()
    {
        printf("\n\t\t Seno , Coseno y Tangente");
        datos();
        system("pause");
    }

    void datos(void)
    {
        float a,S,C,T;
        printf("\n\t Ingresa el valor del angulo que deseas calcular:\n");
        scanf("%f",&a);
		S=seno(a);
		C=cose(a);
		T=tang(a);
        imprime(S,C,T);
    }

    float seno(float a)
    {
        float S;
		S=(((sen(a))*180)/M_PI);
        return S;
    }

    
    float cose(float a)
    {
        float C;
		C=(((cos(a))*180)/M_PI);
        return C;
    }

    float tang(float a)
    {
        float T;
		T=(((tan(a))*180)/M_PI);
        return T;
    }


    void imprime(float S,float C,float T)
    {
        printf("\n El resultado de\nSeno es = %.2f grados\nCoseno es = %.2f grados \nTangente es = %.2f grados\n\n",S,C,T);
    }
