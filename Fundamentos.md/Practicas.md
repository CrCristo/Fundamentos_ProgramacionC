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
    
    
 //07-DatosDeClase

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
